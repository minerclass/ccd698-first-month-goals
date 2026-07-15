# CCD-698 First-Month Goals

Self-contained HTML slide presentation for Micah Miner's CCD-698 Dissertation Research Seminar.

## Files

- `index.html` contains the complete presentation, styles, navigation, responsive layout, print rules, and repository links.
- No build process, package manager, external font, analytics service, or JavaScript library is required.

## View locally

Open `index.html` directly in a browser. You can also serve the folder locally:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Presentation controls

- Right arrow, Page Down, or Space advances.
- Left arrow or Page Up returns to the previous slide.
- Home and End jump to the first and final slides.
- Touch devices support horizontal swipe navigation.
- Browser printing produces one 16:9 slide per page.

## Add to GitHub Pages

### As a standalone repository

1. Create a public GitHub repository.
2. Copy `index.html` and this `README.md` to the repository root.
3. Push the files to the `main` branch.
4. In **Settings → Pages**, select **Deploy from a branch**, `main`, and `/ (root)`.
5. The presentation will appear at `https://minerclass.github.io/REPOSITORY-NAME/`.

### Inside an existing repository

Copy this folder into the repository, for example as `first-month-goals/`. The presentation will then be available at:

`https://minerclass.github.io/REPOSITORY-NAME/first-month-goals/`

## Public-research boundary

The linked sites are proposal-stage research companions. Some preserve earlier design stages, so the committee copy remains the controlling methodology. The presentation does not report dissertation findings or include participant data.
