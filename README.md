# chabadmc.org site styles

The custom CSS for chabadmc.org, served by GitHub Pages at:

https://ari-cmc.github.io/chabadmc-site-styles/chabadmc.css

ChabadOne loads it from **Settings → General Settings → Advanced → Custom Header Code** with this one line:

```html
<style type="text/css">@import url("https://ari-cmc.github.io/chabadmc-site-styles/chabadmc.css");</style>
```

Edit `chabadmc.css`, commit to `main`, and the live site picks it up within about 10 minutes (GitHub Pages cache). To undo a change, revert its commit.

This repo is public on purpose: browsers only load stylesheets from public addresses, and a website's CSS is visible to anyone anyway. Put nothing private here.
