# 📋 Copy Paste Debug

A developer tool for inspecting and debugging clipboard data. Paste content to see all available clipboard formats and their data.

## 🚀 Live Demo

The tool is available online at: `https://ignu.github.io/copy-paste-debug`

## Features

- **View all clipboard types** - See every format available in your clipboard (text/html, text/plain, application-specific formats, etc.)
- **Syntax highlighting** - HTML content is displayed with proper syntax highlighting for easy reading
- **HTML structure extraction** - Automatically generates a clean HTML structure view with styling removed and text truncated
- **Export/Import** - Download clipboard data as JSON or upload previously saved clipboard data

## Usage

### Online (GitHub Pages)

1. Visit the [live demo](https://ignu.github.io/copy-paste-debug)
2. Paste any content (Ctrl/Cmd+V) to see all available clipboard formats
3. Use individual copy buttons to copy specific formats
4. For HTML content, view both the original and cleaned structure versions

### Local Development

1. Open `docs/index.html` in your browser
2. Paste any content (Ctrl/Cmd+V) to see all available clipboard formats

## 🔧 Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. The workflow:

1. Triggers on pushes to the main branch
2. Deploys the `docs/` folder to GitHub Pages
3. Makes the tool available at `https://ignu.github.io/copy-paste-debug`

To enable GitHub Pages for your fork:

1. Go to your repository settings
2. Navigate to "Pages" in the sidebar
3. Under "Source", select "GitHub Actions"
4. The site will be automatically deployed on the next push
