# Sandbox Configuration

## Server Settings
- **Default Port:** 3000
- **Live Reload:** Enabled with `npm run preview`
- **Auto Open:** Enabled

## Folder Structure
- `docs/` - Final documents
- `examples/` - Reference materials  
- `drafts/` - Work in progress
- `assets/` - Media files

## Customization Options

### Change Default Port
Edit `package.json` scripts section:
```json
"preview": "live-server --port=YOUR_PORT --mount=/docs:docs"
```

### Add New Folders
1. Create folder: `mkdir new-folder`
2. Add to `.gitignore` if needed
3. Update `index.html` navigation

### Custom Styling
Edit `index.html` CSS section for custom appearance.

## Markdown Extensions
Supported features:
- Tables
- Code syntax highlighting  
- Task lists
- Blockquotes
- Math expressions (if preview supports)

---
*Modify this file to document your personal sandbox setup.*