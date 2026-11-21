# neet pg timetable

installable offline pwa. plain html, no build step.

## deploy (github pages)
1. create a new repo, upload all files in this folder (keep `icons/`)
2. settings > pages > deploy from branch > `main` / root
3. open `https://<username>.github.io/<repo>/` on her phone
4. browser menu > add to home screen

## edit
- timetable data is the `D` array in `index.html`
- after changing files, bump `V` in `sw.js` so phones pick up the update
