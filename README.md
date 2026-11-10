# Doc as code example

This repo showcase how to use doc as code and use the Zensical tool for
rendering the documentation.

## Enable GH Pages

This repo is configured to use GitHub Pages. To enable it, go to the Settings
tab of the repo, then select "Pages" from the left menu. Under "Source", select
the branch you want to use for GitHub Pages (e.g., `main` or `gh-pages`) and
click "Save".

## Python virtual environment for Zensical

To create and use Python virtual environment for Zensical, follow these steps:

```bash
python3 -m venv .venv
source .venv/bin/activate
zensical serve
```
