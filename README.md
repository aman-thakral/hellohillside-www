# hellohillside.com

Static marketing page for Hillside, served by GitHub Pages at the apex domain.
The app itself lives at https://app.hellohillside.com (separate, private repo).

Single `index.html` (no build step) plus `screens/` — mobile, light-theme
product screenshots used in the "A peek inside" gallery. `CNAME` binds the Pages
site to `hellohillside.com`.

The screenshots are captured from a curated demo household ("The Larsens") in
the app's local dev DB — never real household data. Reshoot after UI changes by
reseeding that household and re-running the capture script against a local
server.
