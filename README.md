# GameSir asset references

[Overlay Studio](https://github.com/gfgggggggghhjred/overlay-maker) reference material.

## Uploaded reference

`reference-settings/device-assets.zip` is the original smaller archive supplied in chat. Its five JSON files are also extracted alongside it. They contain saved application settings, not controller artwork.

Confirmed values:

- Asset lookup: `G7ProCE:0x1032` → `G7ProCE/Crown`.
- Local web source: `http://127.0.0.1:8777/`.
- The previously supplied index references `js/app.7ab89ecc.js`, `js/chunk-vendors.afd43107.js`, and `css/app.81be9198.css`.

## Next required source

Inspect the main bundle `js/app.7ab89ecc.js` first. While GameSir Streaming Tool is running, it is referenced at:

`http://127.0.0.1:8777/js/app.7ab89ecc.js`

The `G7ProCE/Crown` value is an asset key, not a verified filesystem path. No original SVG/PNG asset files have been supplied yet. The Tarantula release is held pending inspection of the source assets; no collector or speculative asset-path search is needed.
