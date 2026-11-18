# Browser Games & Practice Pages

Four self-contained HTML projects, ready for GitHub Pages. No build step and no dependencies to install.

| Page | What it is |
|---|---|
| [`desert-dispatch.html`](desert-dispatch.html) | 3D desert driving game (three.js) |
| [`iron-tide.html`](iron-tide.html) | Naval command game |
| [`normandy-landing.html`](normandy-landing.html) | Tank game, Normandy landings |
| [`latihan-php-apeli.html`](latihan-php-apeli.html) | Interactive HTML/PHP practice (Indonesian) |

`index.html` is the landing page that links to all four.

## Publish on GitHub Pages

1. Create a repository and upload every file in this folder to the repository root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- `desert-dispatch.html` loads three.js r128 from cdnjs, and several pages load Google Fonts, so an internet connection is needed on first load.
- `normandy-landing.html` single-player works as-is. Its **Co-op** tab needs a WebSocket server address that you run yourself; GitHub Pages cannot host one.
- `latihan-php-apeli.html` teaches PHP but is a static page. The PHP code in it is shown as lessons and is not executed.
- Pages on the same `github.io` domain share browser storage, so the saved settings keys (`dd.seed`, `ob_opt`, `snd`) do not collide.
