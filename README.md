# V-Dem Australia and New Zealand

Website of the V-Dem Regional Centre for Australia and New Zealand, served with GitHub Pages.

- `index.html` is the whole site, no build step.
- `vdem_logo_tagline.svg` is the V-Dem logo.
- `.nojekyll` tells GitHub Pages to serve the files as they are.
- `v-dem-anz.github.io.Rproj` opens the folder as an RStudio project, so the Git pane can be used to commit and push.

Only public content belongs in this repository. Drafts, feedback and anything confidential stay in separate private folders.

## Publishing

1. Create a GitHub organisation called `v-dem-anz`.
2. Create a repository in it called exactly `v-dem-anz.github.io`.
3. Push this folder to the `main` branch.
4. In the repository, open Settings, then Pages, and choose "Deploy from a branch", branch `main`, folder `/ (root)`.
5. The site appears at https://v-dem-anz.github.io after a minute or two.

GitHub Pages works from a public repository on the free plan. A private repository needs a paid plan (GitHub Pro or Team), and the published site is public either way.

To use a custom address later, add it under Settings, then Pages, then Custom domain, and point a CNAME record at `v-dem-anz.github.io`.

## Still to connect

- **Mailing list.** As on the QuantLab site, the "Subscribe via Email" button opens a pre-filled email to constanza.sanhueza@anu.edu.au, and the list is kept by hand. Change the address in the `mailto:` link in `index.html` if a shared mailbox is set up.
- **LinkedIn.** Replace the "Link to follow" block in the Links section with the link, the HTML comment next to it shows how.
- **Yellow markers.** Eventbrite link, contact details, workshop date and the panelists marked (tbc). Remove each marker when it is confirmed.
