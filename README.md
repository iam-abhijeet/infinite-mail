# Halo Mail

A clickable mailbox UI/UX concept. It's a static demo built to pitch the design: there's no backend, and nothing is really sent.

**Live demo:** https://iam-abhijeet.github.io/halo-mail/

## What you can try

- **Folders:** Inbox, Starred, Important, Sent, Drafts, All mail, Promotions, Transactions, Social, Updates, Spam and Trash
- **Labels:** colour-coded labels. You can create new ones and add or remove them on any message.
- **Inbox tabs:** All, Primary, Promotions, Social, Updates and Transactions, with a sliding highlight
- **Reading pane:** full message view, sender details, smart-reply chips, reply, reply all and forward, plus a close button (Esc or X) to clear it
- **Resizable panes:** drag the divider between the list and the message. Drag far left to hide the list (focus view) or far right to hide the reader. Double-click the divider to reset.
- **Collapsible sidebar:** shrinks to icons with count badges (button at the bottom, or press `[`)
- **Attachment previews:** images (zoom and pan), PDFs rendered page by page, CSV and text files, plus file cards for Word, Excel and zip files
- **Compose:** recipient chips with contact suggestions, Cc and Bcc, a formatting toolbar, links, emoji and "Help me write"
- **Attachments in compose:** browse, drag and drop, or paste files, with live thumbnails and upload progress
- **Drafts:** saved automatically. Sending plays a send animation and offers Undo.
- **Actions:** archive, delete, restore, delete forever, spam / not spam, move, mark read or unread, bulk select and empty trash
- **Star = Important:** starring a message also marks it important, and unstarring removes it from both
- **AI Summarize:** a canned summary shown with a typing effect
- **Refresh:** delivers a new message the first time
- **Motion and UI:** frosted-glass panels, drifting background, ripple buttons, staggered list animations, swipe actions on touch, toasts with Undo
- **Themes:** light and dark mode with a circular reveal
- **Layout:** works on desktop, tablet and phone
- **Keyboard shortcuts:** `C` compose, `/` search, `J`/`K` move, `E` archive, `#` delete, `S` star, `R` reply, `F` forward, `?` help

## Tech

A single `index.html` in plain HTML, CSS and JavaScript. Icons come from [Lucide](https://lucide.dev), PDF rendering from [PDF.js](https://mozilla.github.io/pdf.js/), and fonts from Google Fonts (Instrument Serif, Plus Jakarta Sans and JetBrains Mono). All mail, people, images and PDFs are sample data generated in the browser.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```
