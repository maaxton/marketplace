# Waiveo Extension Marketplace

Public catalog consumed by the Waiveo box `CatalogService`. The box's `catalog_index_url`
setting points at the raw `index.json` below; each entry's `tarball` URL is a GitHub
Release asset.

- **Index:** `https://raw.githubusercontent.com/maaxton/marketplace/main/index.json`
- **Artifacts:** GitHub Releases (one tag per catalog build, e.g. `v1`)

Built by `scripts/catalog/build-catalog.mjs` in the main repo. Do not hand-edit `index.json`.
