# GABL project homepage

This folder is a self-contained static website. It can be hosted directly with
GitHub Pages and does not require a build step.

## Publish with GitHub Pages

1. Create a `docs` folder in the `paulili08/GABL` repository.
2. Copy all files in this folder into `docs`.
3. Commit and push the files to the repository's default branch.
4. In GitHub, open **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the default branch and `/docs`, then save.
7. The expected URL is `https://paulili08.github.io/GABL/`.

Before publishing, confirm that `paper.pdf`, the DOI, author names, and BibTeX
entry match the final ACM version.

To update the page, edit `index.html`. Colors and spacing are defined in
`styles.css`, while paper figures are stored in the `assets` folder.
