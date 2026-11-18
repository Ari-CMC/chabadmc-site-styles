# chabadmc.org site styles

The custom CSS for chabadmc.org, served by GitHub Pages at:

https://ari-cmc.github.io/chabadmc-site-styles/chabadmc.css

ChabadOne loads it from **Settings → General Settings → Advanced → Custom Header Code** with this one line:

```html
<style type="text/css">@import url("https://ari-cmc.github.io/chabadmc-site-styles/chabadmc.css");</style>
```

Edit `chabadmc.css`, commit to `main`, and the live site picks it up within about 10 minutes (GitHub Pages cache). To undo a change, revert its commit.

## previews/

Page previews and page source that the live site does **not** load. Each folder holds screenshots, a small viewer page with a copy button, and the HTML that goes into a ChabadOne page's Source view. They are here so the code can be opened in any browser without signing in.

- `previews/glow-2026/`: the Chanukah Palooza 2026 page (chabadmc.org/glow). Viewer: https://ari-cmc.github.io/chabadmc-site-styles/previews/glow-2026/

This repo is public on purpose: browsers only load stylesheets from public addresses, and a website's CSS is visible to anyone anyway. Put nothing private here.
