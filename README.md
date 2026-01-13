# Zed Editor Configuration

Personal configuration for Zed editor.

## Theme

**VS Code Dark+** - Custom theme in `themes/dark-plus.json`

## Key Settings

- **Font**: Monaco (weight: 550, size: 12pt)
- **UI Font**: Size 15pt
- **Keymap**: VSCode base
- **Tab Size**: 2 spaces
- **Soft Wrap**: Editor width
- **Format on Save**: Off
- **Cursor**: Bar shape with blink
- **Terminal**: Docked right

## UI Configuration

- Snippets sorted at top of autocomplete
- File icons enabled
- Git status indicators enabled
- Quick actions and breadcrumbs hidden
- Sticky scroll disabled
- Inline git blame disabled
- Telemetry disabled

## Custom Keybindings

- `Alt+Shift+F` - Format document
- `Cmd+Y` - Redo
- `Cmd+G` - Agent allow once (in agent panel)
- `Cmd+G` - Agent keep (in editor diff)
- `Shift+Enter` - Send text in terminal

## Snippets

Custom snippets for fast coding. See `snippets/README.md` for details.

## File Type Associations

- `*.stub` → Handlebars
- `bin/**/*` → Shell script
- `bin/**/*.ts` → TypeScript
- `.eslintrc`, `tsconfig.json`, `.prettierrc` → JSONC
