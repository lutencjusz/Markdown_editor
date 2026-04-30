# Markdown Browser SPA

A simple SPA application (HTML + CSS + JS) for browsing and editing Markdown files.

## Features

- `.md` file tree (recursively from subdirectories) with folder collapsing and expanding,
- raw Markdown editor,
- live preview,
- save via the `Save` button and `Ctrl+S` shortcut,
- adjustable panel widths,
- remembers the last file and tree expansion state (localStorage, per folder name),
- no file/folder creation functionality.

## Running the Application

1. Open `code.html` in the current Chrome or Edge.
2. Click `Select Directory` and choose a working directory.
3. Select a `.md` file, edit, and save.

## Technical Notes

- File system access is implemented using the `showDirectoryPicker` API (requires a supported browser).
- Preview uses `marked` + `DOMPurify` from a CDN.
- Styling is based on the Neumorphism specification from the `Specyfikacja_Neumorphism.md` file.

## Repository Information

The repository history has been simplified: the remote repository has been replaced with a single commit containing only `index.html`, `styles.css`, and `README.md`. The operation was performed locally: additional files remained on disk but are no longer tracked by Git. Operation date: Thu Apr 30 2026.
