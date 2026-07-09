# Appraisal Statement Library

A lightweight, client-side React app for cataloguing and quickly copying your go-to appraisal statements to the clipboard.

## Features

- **Click to Copy** — click any statement card to copy it to your clipboard
- **Search** — find statements by title or content (press `/` to focus the search)
- **Tags** — organize and filter by custom, editable tags
- **Pin to Top** — favorite statements bubble up first
- **Hover Controls** — compact, intuitive UI with controls revealed on hover
  - ★ pin / unpin
  - ▾ expand full text
  - ✎ edit title, tags, and text
  - ✕ delete
- **Dracula Theme** — dark, easy on the eyes
- **Offline-First** — all data lives in your browser's localStorage
- **Export/Import** — backup and restore as JSON

## Usage

1. Open `index.html` in your browser
2. Click a card to copy the statement text
3. Use the search bar (`/` to focus) to filter quickly
4. Click tag chips to filter by category
5. Hover a card to reveal the control buttons

## Data

- All statements are stored in your browser's localStorage automatically
- Use the **Export** button to download a backup as JSON
- Use the **Import** button to restore from a backup
- Use the **Reset** button to restore the original built-in statements

## Customization

Edit the `SEED` array in the HTML file to add or modify default statements, or manage them entirely through the app UI.

---

Built with React, Dracula theme.
