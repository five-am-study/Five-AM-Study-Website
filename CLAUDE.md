# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a documentation website built with MkDocs and the Material for MkDocs theme. The project uses Python and focuses on creating and serving markdown-based documentation.

## Development Commands

### Environment Setup
```bash
# Activate virtual environment
source .venv/bin/activate  # Linux/Mac
# or
.venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
```

### MkDocs Commands
```bash
# Start live-reloading development server
mkdocs serve

# Build the static documentation site
mkdocs build

# Deploy to GitHub Pages
mkdocs gh-deploy
```

## Project Structure

- `mkdocs.yml` - MkDocs configuration file (site name, theme, navigation)
- `docs/` - All markdown documentation files
  - `index.md` - Homepage for the documentation site
- `requirements.txt` - Python dependencies (MkDocs, Material theme, extensions)
- `site/` - Generated static site (ignored in git, created by `mkdocs build`)

## Technology Stack

- **MkDocs 1.6.1** - Static site generator for documentation
- **Material for MkDocs 9.7.1** - Material Design theme
- **PyMdown Extensions 10.19.1** - Markdown extensions for enhanced features
- **Python 3.12** - Runtime environment

## Key Considerations

- All documentation content is written in Markdown and placed in the `docs/` directory
- The site configuration (theme, navigation, plugins) is managed through `mkdocs.yml`
- Live development server at `mkdocs serve` automatically reloads on file changes
- Built site output goes to `site/` directory (gitignored)
