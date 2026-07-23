# First App

## Deployment

Bu repository GitHub Pages üzərinə GitHub Actions ilə avtomatik deploy olunur.

Saytın URL formatı:

```text
https://<github-username>.github.io/<repository-name>/
```

`main` branch-ə hər push ediləndə `Deploy static site to GitHub Pages` workflow-u avtomatik işləyir və statik sayt GitHub Pages-ə deploy edilir.

İlk dəfə GitHub repository-də bu ayarı seçmək lazımdır:

```text
Settings -> Pages -> Build and deployment -> Source -> GitHub Actions
```

Manual deployment üçün:

```text
Actions -> Deploy static site to GitHub Pages -> Run workflow
```

Xəta olarsa, GitHub-da repository-nin `Actions` bölməsinə daxil olun, `Deploy static site to GitHub Pages` workflow run-ını açın və uğursuz job/addım loglarına baxın.
