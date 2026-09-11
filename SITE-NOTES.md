# Team Pearl website — setup notes

Plain HTML and CSS. No build step, no Jekyll. GitHub Pages serves it as-is.

## Files

```
index.html            home / landing
presentations.html    feasibility deck embed
team.html             bios for all eight members
assets/styles.css     all styling
images/               member photos go here
```

## Three things to fill in

**1. The presentation.** The deck is served as a PDF from `presentations/`. To update
it, export the PowerPoint as PDF, drop it in `presentations/`, and point the iframe
`src` in `presentations.html` at it. Encode any spaces in the filename as `%20`
(e.g. `presentations/DocStock%20Feasibility%20V2.pdf`).

**2. Photos.** Drop a JPG for each member into `images/` using the filenames already
referenced in `team.html` (`isaiah-gamble.JPEG`, `julia-hairston.JPEG`,
`anson-cheng.JPEG`, `shannon-stinnette.JPEG`, `jessica-fischer.JPEG`,
`ab-aljazaeri.JPEG`, `matthew-richards.JPEG`, `toni-sallaku.JPEG`). The extension
is uppercase `.JPEG` and GitHub Pages is case-sensitive, so match it exactly. Roughly square or slightly tall crops
work best. Any missing photo falls back to the member's initials, so the page never
looks broken.

**3. Bios.** Each one has bracketed slots for a personal sentence and a team
contribution, plus an "Add role" line. Keep every bio in third person and about the
same length — the assignment grades on consistent style.

## Publishing

Copy these files into the root of the team repository, commit, and push.

```
git add .
git commit -m "Add landing, presentations, and team pages"
git push
```

Then check Settings → Pages: source should be "Deploy from a branch," branch `main`,
folder `/ (root)`. The URL stays the same as the previous submission.

If the repo already has an `index.html`, decide whether to overwrite it or move the
old content into one of these pages before committing.
