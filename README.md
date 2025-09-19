# benhorvath.github.io — Quarto personal site scaffold

This repo is a Quarto (Python) personal website scaffold prepared for GitHub Pages hosting at `benhorvath.github.io`.

Local preview

Install Quarto (https://quarto.org) and Python packages, then preview:

```bash
# install python dependencies
python -m pip install -r requirements.txt

# preview the site (serves at http://localhost:...
quarto preview
```

Build the site locally:

```bash
quarto render
```

Publishing

Rename the repository to `benhorvath.github.io` (this repo already assumes that name). The included GitHub Actions workflow will build and publish the site to GitHub Pages.
