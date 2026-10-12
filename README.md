# Kernel Notes

A lightweight, local-first notes app built as a single-page HTML application. It lets you create, search, pin, organize, preview, and export notes directly in the browser without requiring a backend.

## Features

- Create and manage multiple notes
- Search notes by title or content
- Pin important notes to the top
- Move notes to trash and restore them later
- Toggle between editor and markdown preview
- Focus mode for distraction-free writing
- Markdown formatting toolbar for bold, italic, headings, lists, quotes, code blocks, and links
- Dark mode and light mode support
- Local autosave using browser storage
- Export a note as Markdown (.md)
- Backup all notes as a JSON file
- Mobile-friendly layout

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript

## Project Structure

- `notepad1.html` — complete app UI and logic in one file

## Run Locally

Because this project is a static app, you can run it by opening the file directly in a browser:

1. Download or clone the repository.
2. Open `notepad1.html` in your browser.
3. Start creating notes.

You can also serve it locally with a simple static server if preferred:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/notepad1.html
```

## Notes Storage

Notes are stored in the browser's localStorage, so they remain available on the same browser/device unless cleared manually.

## Backup and Export

- Use the app's backup option to download a JSON backup of all notes.
- Use the export option to save the currently selected note as a Markdown file.

## Example Use Cases

- Quick daily journal entries
- Personal task tracking
- Meeting notes
- Idea capture
- Lightweight documentation

## License

This project is provided as-is for personal and educational use.
