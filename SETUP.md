# Portfolio Project Setup

## Project Structure
```
sena-portfolio/
├── index.html              # Home page
├── about.html              # About page
├── services.html           # Services page
├── how-it-works.html      # How it works page
├── contact.html           # Contact page
├── styles.css             # Global styles
├── scripts.js             # JavaScript functionality
├── assets/                # Images and media files
├── package.json           # Project metadata
├── .gitignore            # Git ignore rules
├── .gitattributes        # Git attributes
├── README.md             # Project documentation
└── .vscode/
    ├── settings.json     # VS Code settings
    └── tasks.json        # Build/run tasks
```

## Quick Start

### Start Development Server
Run the "Start Web Server" task in VS Code (Ctrl+Shift+B or Cmd+Shift+B), or run:
```bash
python3 -m http.server 8000
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

### File Organization
- **HTML Files**: Page templates
- **Styles**: CSS styling in `styles.css`
- **Scripts**: JavaScript interactivity in `scripts.js`
- **Assets**: Images and media in `assets/` folder

## Development Workflow
1. Make changes to HTML, CSS, or JavaScript files
2. Refresh your browser to see updates
3. Use your browser's developer tools (F12) for debugging
4. Commit changes using git: `git add .` and `git commit -m "Your message"`

## Notes
- The web server runs on port 8000
- All files are served relative to the project root
- Use relative paths for assets: `assets/image.jpg`
