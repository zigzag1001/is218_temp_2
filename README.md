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

## Publish

GitHub Actions builds this MkDocs site and deploys it to GitHub Pages whenever changes are pushed to `main`. You can also start a deployment manually from the repository's **Actions** tab. The Pages site is available at <https://zigzag1001.github.io/is218_temp_2/>.

After both sites are published, add the actual career site/repository URLs to the game research site's overview and the actual programming site/repository URLs to the career site's overview. Add reciprocal links on both published sites. Do not claim publication or peer review until they happen. Keep the full career comparison, personal eligibility circumstances, and reflection in the private Canvas submission.
