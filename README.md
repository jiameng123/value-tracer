# Value Tracer

Value Tracer is a VS Code extension that helps you track, manage, and switch between different values in your code. It provides an intuitive way to manage value changes during development and debugging.

![Demo GIF](https://github.com/saga7878/value-tracer/blob/main/demo.gif)

## Features

### 📍 Value Tracking

- Automatically tracks value changes in your code
- Shows value history through CodeLens
- Quick switch between historical values
- Restore to original values easily

### 🔄 Quick Actions

- Edit values with quick picker
- View value history in side panel
- Switch to previous values instantly
- Restore single or multiple values
- Add current value to history manually

### ⌨️ Keyboard Shortcuts

- `Alt+Shift+E` (`Cmd+Shift+E` on Mac): Edit value
- `Alt+Shift+V` (`Cmd+Shift+V` on Mac): Show value history
- `Alt+Shift+B` (`Cmd+Shift+B` on Mac): Back to previous value
- `Alt+Shift+R` (`Cmd+Shift+R` on Mac): Restore all values
- `Alt+Shift+H` (`Cmd+Shift+H` on Mac): Add current value to history
- `Alt+Shift+Delete` (`Cmd+Shift+Delete` on Mac): Clear current value history
- `Alt+Delete` (`Cmd+Delete` on Mac): Clean up all history

### 🖱️ Context Menu

Right-click to access Value Tracer features:

- View Value History
- Restore to Previous Value
- Restore All Values

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "Value Tracer"
4. Click Install

## Usage

1. **Track Values**
   - Values are tracked when modified through commands or CodeLens
   - Manual tracking available via `Alt+Shift+H` or CodeLens
   - CodeLens indicators appear above tracked values

2. **Edit Values**
   - Click on CodeLens "Edit Value" or use `Alt+Shift+E`
   - Select from history or enter new value

3. **View History**
   - Click on CodeLens "Show History" or use `Alt+Shift+V`
   - View all previous values with timestamps

4. **Restore Values**
   - Restore single value: Use CodeLens or `Alt+Shift+B`
   - Restore all values: Use `Alt+Shift+R` or context menu

### Example Usage

```javascript
// Before
const primaryColor = '#FF0000';

// After editing with Value Tracer
const primaryColor = '#0000FF';  // CodeLens shows history: #FF0000 → #00FF00 → #0000FF
```

## Extension Settings

This extension contributes the following settings:

- `value-tracer.autoRestore`: Enable/disable automatic value restoration when opening files

- `value-tracer.historyRetentionDays`:  Number of days to keep value history (default: 30)


## Requirements

- VS Code version 1.95.0 or higher

## Known Issues

[Link to issues](https://github.com/saga7878/value-tracer/issues)

## Release Notes

### 0.0.1

- Initial release
- Smart value tracking system
- CodeLens integration with history display
- Manual value history addition
- Comprehensive keyboard shortcuts
- Context menu integration
- History cleanup features

## Feedback and Contributions

- File bugs, feature requests in [Issues](https://github.com/saga7878/value-tracer/issues)
- Contribute via [Pull Requests](https://github.com/saga7878/value-tracer/pulls)

---
Enjoyed the extension? Give it a ⭐️ on [GitHub](https://github.com/saga7878/value-tracer)!
