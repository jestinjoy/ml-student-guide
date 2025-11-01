# ML Student Guide

This repo contains source for a Jupyter Book (HTML site + notebooks + PDF build capability).

Structure:
- content/  : jupyter-book source (.md and .ipynb)
- notebooks/: raw ipynb files for download
- _config.yml, _toc.yml : jupyter-book config
- environment.yml : conda environment for Binder/CI
- .github/workflows/deploy.yml : GitHub Actions workflow to build & deploy

Run locally:
1. Create and activate conda env: \`conda env create -f environment.yml\`
2. Build book: \`jb build content -o _build\`
3. Serve: \`python -m http.server --directory _build/html 8000\`

(Or copy files into a jupyter-book project root and follow Jupyter Book docs.)
