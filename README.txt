EXPERIMENTAL MCU MANIFEST

All 76 movie/TV titles are physically embedded in manifest.json under:
- catalogs[0].items
- releaseOrderItems

This is intentionally experimental: "items" and "releaseOrderItems" are not
standard Stremio manifest fields, so Stremio may ignore them. No separate
movie/TV catalog JSON is included.

Upload manifest.json to GitHub Pages and test the manifest URL.
