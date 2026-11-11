# Career Research Site

This is the separate IS218 Portfolio Plan career-research site, not a finished portfolio. The existing root MkDocs site covers the creative game project.

## Preview and build

Python 3.11+ and Material for MkDocs are required. From this directory:

```powershell
python -m pip install -r requirements.txt
python -m mkdocs serve --dev-addr 127.0.0.1:8001
```

Open the address printed by MkDocs. Validate the site with:

```powershell
python -m mkdocs build --strict
```

## Publish separately

Place this folder's contents in the root of a **separate GitHub repository**, commit and push them, then run `python -m mkdocs gh-deploy` from that repository. In its GitHub settings, set Pages to deploy from the `gh-pages` branch. See the [official publishing guide](https://squidfunk.github.io/mkdocs-material/publishing-your-site/). The existing root repository's automatic workflow publishes only the game research site; it does not deploy this career site.

After both sites are published, add the actual career site/repository URLs to the game research site's overview and the actual programming site/repository URLs to the career site's overview. Add reciprocal links on both published sites. Do not claim publication or peer review until they happen. Keep the full career comparison, personal eligibility circumstances, and reflection in the private Canvas submission.