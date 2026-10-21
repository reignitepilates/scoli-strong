# Scoliosis Strong — v3

## Deploy
Upload the ZIP directly to the EXISTING Cloudflare Pages project as a new Production deployment. `index.html`, `content.json`, `editor.html`, and icons are at the ZIP root.

## Podcast
The homepage loads the public Apple iTunes lookup API for podcast ID 1878001637. It displays the newest available episode and a searchable episode library. The number of returned episodes and release timing depend on Apple. If Apple is unavailable, a link to the complete Apple Podcasts page remains. The embed player depends on Apple allowing embeds.

## Editor limitations
`/editor.html` is a convenience editor only. It saves drafts to browser localStorage and downloads `content.json`. It DOES NOT authenticate, change the public site, or publish automatically. Do not enter private data or credentials. It is not suitable as a publicly advertised administration portal. The live website may not use every content field dynamically yet; confirm changes after deployment.

## Production next steps
Set up authenticated CMS, GitHub repository owned by Ruth, and Cloudflare Pages Git integration; verify medical copy and product affiliate compliance. Test iOS Safari, Android Chrome, desktop Chrome/Firefox/Safari, and links before handoff.
