# macapture_support

Support website for [macapture](https://apps.apple.com), a screen capture utility for macOS.
Lightweight macOS screen capture tool with video recording, image annotation, and clipboard history.

## Features

### Screenshot Capture
- Area selection via on-screen overlay with multi-monitor support
- Saved as PNG to `~/Pictures/Macapture/`
- Auto-copied to clipboard

### Video Recording
- Configurable frame rate (5–60 fps)
- Pause, resume, restart, and discard controls
- Export as **MP4** (H.264) or **GIF**
- Click ripple overlay — animated circles drawn at click positions during recording

### Image Editor
Open any captured image to annotate with:
- **Freehand draw** — pencil strokes with adjustable width and color
- **Arrow** — draggable endpoints with arrowhead
- **Rectangle** — colored outline
- **Text** — inline editable labels with configurable font size
- **Pixelate** — block-pixel redaction for hiding sensitive content
- Select, move, undo, and delete annotations
- Save in-place or as a copy

### History Panel
- Slide-out panel with search/filter
- Thumbnails for images and videos
- Quick actions: open, reveal in Finder, edit, copy to clipboard
- Up to 200 items, persisted across launches

### Clipboard History
- Optional text clipboard monitoring (off by default)
- Captured text items appear in the history panel

### Global Keyboard Shortcuts
| Default | Action |
|---------|--------|
| `⇧⌘6` | Open main window |
| `⇧⌘C` | Capture area |
| `⇧⌘V` | Capture video |
| `⇧⌘H` | Toggle history |

All shortcuts are configurable in Settings. Conflicts are auto-resolved.

### Menu Bar
- Status item with camera icon
- Quick access to main window, settings, 
