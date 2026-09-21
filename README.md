# SparseArrayConsortium.github.io

Build with:

```sh
bundle exec jekyll serve
```

GitHub Actions exports `assets/SACLogo.png` from `SACLogo.drawio` before the Jekyll build. To regenerate locally:

```sh
drawio --export --format png --transparent --theme light --scale 4 --output assets/SACLogo.png SACLogo.drawio
```
