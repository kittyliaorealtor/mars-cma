# MARS CMA Builder

A fill-in CMA report builder for The MARS Team. Agents type or import their comps, and the report adds pages as needed, then downloads as a letter-size PDF.

## What's in this folder

- `index.html`: the builder itself
- `lib/`: the tools that read CSV files and build the PDF (don't change these)
- `logo.png`: **add this yourself** (see below)

## Add the team logo

1. Export the logo as a PNG with a transparent background.
2. Use the white or gold version. The cover is black, so a black logo won't show.
3. Name the file exactly `logo.png` and put it in this folder, next to `index.html`.

If `logo.png` is missing, the cover shows the team name in gold letters instead.

## Put it online with GitHub Pages (free)

1. Sign in to github.com and click **New repository**.
2. Name it something like `mars-cma`. Set it to **Public**, because free GitHub Pages sites need a public repository.
3. On the new repository page, click **uploading an existing file**.
4. Drag in everything from this folder, including the `lib` folder and your `logo.png`. Click **Commit changes**.
5. Go to **Settings → Pages**. Under "Branch," choose `main` and `/ (root)`, then click **Save**.
6. Wait a minute or two, then refresh. GitHub shows the site address, usually `https://YOUR-USERNAME.github.io/mars-cma/`.
7. Send that link to the team.

## Things to know

- Each agent's work is saved only in their own browser, so nobody can overwrite anyone else. If an agent clears their browser data, an unsaved draft is lost. Use **Save draft file** to keep a copy.
- A public repository means anyone with the link can open the blank builder. No client data is stored on the site, because drafts stay on each agent's own computer.
- To change the layout later, replace `index.html` in the repository with the new version. Everyone gets the change on their next visit.
- The font is Helvetica on Macs and iPhones. Windows computers don't include Helvetica, so they use Arimo, a free font built to match it.
