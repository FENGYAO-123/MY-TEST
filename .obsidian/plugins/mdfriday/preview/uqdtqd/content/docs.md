---
title: "Documentation"
description: "Complete documentation for Notebook Navigator - Modern File Explorer for Obsidian"
---

# Notebook Navigator Documentation

Welcome to the complete documentation for Notebook Navigator, the modern file explorer for Obsidian.

## Getting Started

### Installation

1. Open Settings → Community plugins in Obsidian
2. Search for "Notebook Navigator"
3. Click Install, then Enable
4. The plugin will appear in your left sidebar

### First Steps

Once installed, Notebook Navigator will replace your default file explorer with a powerful dual-pane interface featuring:

- **Navigation tree** on the left
- **File list** on the right
- **Resizable divider** between panes
- **Rich preview text** for each note

## Key Features

### Keyboard Navigation

Navigate your vault with full keyboard support:

- **Arrow keys** - Move up/down in lists
- **Tab** - Switch between panes
- **Page Up/Down** - Jump by pages
- **Home/End** - Jump to start/end
- **Shift + ↑/↓** - Extend selection

### Dual-Pane Layout

The interface is split into two main areas:

1. **Navigation Pane** (left)
   - Folder tree structure
   - Tag hierarchy
   - Pinned notes section

2. **File List Pane** (right)
   - Files in selected folder/tag
   - Rich previews with thumbnails
   - Date grouping options

### Rich Previews

Each note shows:

- **Preview text** (1-5 lines configurable)
- **Feature images** from frontmatter
- **Creation/modification dates**
- **Clickable tags** with colors
- **File size** and word count

## Developer API

Notebook Navigator provides a TypeScript API for plugin developers:

### Basic Usage

```typescript
// Get the plugin instance
const nbNav = this.app.plugins.plugins['notebook-navigator'];

// Access the API
const api = nbNav.api;

// Navigate to a folder
api.navigateToFolder('path/to/folder');

// Get selected files
const selected = api.getSelectedFiles();

// Subscribe to events
api.on('selection-changed', (files) => {
    console.log('Selected files:', files);
});
```

### Available Methods

- `navigateToFolder(path: string)` - Navigate to folder
- `navigateToTag(tag: string)` - Navigate to tag
- `getSelectedFiles()` - Get currently selected files
- `selectFiles(paths: string[])` - Select specific files
- `refreshView()` - Refresh the current view

### Events

- `selection-changed` - Fired when selection changes
- `navigation-changed` - Fired when navigation changes
- `view-refreshed` - Fired after view refresh

## License

Notebook Navigator is released under the MIT License. See the [LICENSE](https://github.com/johansan/notebook-navigator/blob/main/LICENSE) file for details.

---

**Need more help?** Check out our [GitHub repository](https://github.com/johansan/notebook-navigator) or join the discussion in the Obsidian Discord server.
