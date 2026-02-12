# PAT - AI-Powered Pattern Analysis

A web-based tool for logistics pattern analysis, conversion, and management.

## Features

- **Pattern Converter**: Import patterns from Excel/CSV files or extract from PDFs/images using AI
- **Pattern Analysis**: PMK uniqueness calculation, duplicate detection, field suggestions
- **Pattern Management**: Build and manage your pattern library
- **Project System**: Organize patterns into projects with localStorage persistence

## Quick Start (Local)

1. Download `index.html`
2. Open it directly in your browser, OR
3. Use VS Code with Live Server extension for a better experience

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the repository
3. Go to Settings → Pages → Select "main" branch → Save
4. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

## AI Image Extraction Setup

To enable PDF/image extraction:

1. Get an API key from [console.anthropic.com](https://console.anthropic.com)
2. In PAT, click on PDF/Image upload
3. Enter your API key when prompted (stored locally in your browser)

## Data Storage

All data is stored in your browser's localStorage:
- Projects and patterns persist across sessions
- Data stays on your machine - nothing is sent to external servers (except AI extraction which uses Anthropic's API)
- Clear browser data to reset

## Tech Stack

- React 18
- Tailwind CSS
- PapaParse (CSV parsing)
- SheetJS (Excel read/write)
- PDF.js (PDF processing)
- Anthropic Claude API (AI extraction)

## License

MIT
