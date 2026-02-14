# Live HTML, CSS & JS Editor

A browser-based code editor for writing HTML, CSS, and JavaScript with a real-time live preview. Built as a single `index.html` file with no build tools or server required.

## Features

- **Live Preview** - See changes instantly in a side-by-side preview pane as you type
- **Multi-file Projects** - Create and manage multiple files and folders within a project
- **Project Management** - Create, rename, delete, and switch between projects stored in localStorage
- **Syntax Highlighting** - Built-in highlighting for HTML, CSS, and JavaScript
- **Emmet Expansion** - Tab-triggered Emmet abbreviation expansion in HTML and CSS
- **Auto-close** - Automatic closing of brackets, quotes, and HTML tags
- **File Manager** - Tree-based file explorer with drag-and-drop, copy/cut/paste, and context menus
- **Tabbed Editing** - Open multiple files as tabs with close buttons
- **Download ZIP** - Export the entire project as a `.zip` file
- **Copy Output** - Copy the combined HTML output to clipboard
- **Auto-save** - Drafts are periodically saved to localStorage
- **Console Output** - Inline JavaScript console captures `console.log`, errors, and warnings
- **Themes** - Switch between Mocha (default), Latte, Dracula, and Nord color themes
- **Resizable Panels** - Drag the divider between the editor and preview to resize

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/barkhai-ux/lab5.git
   ```
2. Open `index.html` in any modern browser.

No dependencies, no build step, no server needed.

## Usage

- **New Project** - Click "+ New" in the sidebar to create a project
- **Add Files** - Use "+ File" or "+ Folder" buttons in the Files section
- **Edit** - Click a file in the tree or tabs to open it in the editor
- **Save** - Click "Save" or rely on auto-save to persist changes to localStorage
- **Reset** - Restore default file contents with the "Reset" button
- **Download** - Click "Download ZIP" to export the project
- **Theme** - Select a theme from the dropdown in the header

## Tech Stack

- Vanilla HTML, CSS, and JavaScript (no frameworks)
- [JSZip](https://stuk.github.io/jszip/) for ZIP file generation (loaded via CDN)
- localStorage for persistence

## License

This project is for educational purposes.
