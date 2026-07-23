# First App

## Deployment

Bu repository GitHub Pages uzerine GitHub Actions ile avtomatik deploy olunur.

Saytin URL formati:

```text
https://<github-username>.github.io/<repository-name>/
```

`master` branch-e her push edilende `Deploy static site to GitHub Pages` workflow-u avtomatik isleyir ve statik sayt GitHub Pages-e deploy edilir.

Ilk defe GitHub repository-de bu ayari secmek lazimdir:

```text
Settings -> Pages -> Build and deployment -> Source -> GitHub Actions
```

Manual deployment ucun:

```text
Actions -> Deploy static site to GitHub Pages -> Run workflow
```

Xeta olarsa, GitHub-da repository-nin `Actions` bolmesine daxil olun, `Deploy static site to GitHub Pages` workflow run-ini acin ve ugursuz job/addim loglarina baxin.
