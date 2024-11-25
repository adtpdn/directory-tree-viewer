# 🌳 Directory Tree Viewer

A modern, browser-based directory tree generator with a clean interface and powerful configuration options. Generate visual directory structures easily without installing any software.

## 🚀 Live Demo
[View Live Demo](https://adtpdn.github.io/directory-tree-viewer/)

## ✨ Features

- 🎨 **Dark/Light Mode** - Easy on the eyes with theme persistence
- 📁 **Local Directory Processing** - Works entirely in your browser
- 🔍 **Powerful Filtering**
  - Ignore patterns support
  - File extension filtering
  - Hidden files toggle
  - Adjustable depth levels
- 📋 **One-Click Copy** - Easily copy the generated tree
- 🔒 **Privacy First** - All processing happens locally, no file uploads
- 📱 **Responsive Design** - Works on desktop and mobile devices

## 🛠️ Configuration Options

### Ignore Patterns
Default patterns (customizable):

```
.git

node_modules

*.log

*.tmp

.DS_Store

*.cfg

*.import

.godot/
```


### Display Options
- Show/Hide Files
- Show/Hide Folders
- Show/Hide Hidden Files
- File Extension Filtering
- Maximum Depth Control

## 📖 Usage

1. Visit the [Directory Tree Viewer](https://adtpdn.github.io/directory-tree-viewer/)
2. Click "Select Directory" to choose a folder
3. Adjust configuration options as needed:
   - Set ignore patterns
   - Configure display options
   - Specify file extensions
   - Set maximum depth
4. Click "Copy Tree" to copy the generated structure

## 🔨 Built With

- [Tailwind CSS](https://tailwindcss.com/) - For styling and responsive design
- [Font Awesome](https://fontawesome.com/) - For icons and visual elements
- Vanilla JavaScript - For core functionality and file processing
- HTML5 File API - For directory reading capabilities