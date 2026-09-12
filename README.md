# gh0stmahn-ai.github.io

The public home of the **2026 Midterm Forecast**: https://gh0stmahn-ai.github.io/

This repository holds no content of its own. The forecast, the model and the
site build live in
[Gh0stmahn-ai/cd-election-agent](https://github.com/Gh0stmahn-ai/cd-election-agent),
which rebuilds its `site/` folder every day at noon Eastern. The workflow here
(`.github/workflows/publish.yml`) clones that repo 40 minutes later, copies the
built pages and deploys them to GitHub Pages.

One-time setup: Settings -> Pages -> Build and deployment -> Source:
**GitHub Actions**.

To publish immediately at any time: Actions -> Publish forecast site ->
Run workflow.
