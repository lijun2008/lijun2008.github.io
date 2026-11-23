# Jun Li — personal academic website

A standalone static website for GitHub Pages. No installation or build step is required.

## Publish

1. Create a GitHub repository. For a main personal site, name it `YOUR-USERNAME.github.io`. You can also use any other repository name.
2. Upload the **contents** of this folder to the repository root: `index.html`, `assets/`, `.nojekyll`, and this README. Do not upload the ZIP itself or nest these files inside another folder.
3. Commit to the `main` branch.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select **main** and **/(root)**, then click **Save**.
7. Wait for the Pages deployment to finish. The Pages settings will show the published URL.

For a repository named `YOUR-USERNAME.github.io`, the address is `https://YOUR-USERNAME.github.io/`. For another repository, it is usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Edit

- Text, navigation, colours and layout: `index.html`.
- Profile photo: `assets/jun-li.jpg`.
- Team photos and research figures: `assets/sway/`.
- All asset links are relative, so the page works at either a personal-site URL or a repository subpath.
- After committing changes to `main`, GitHub Pages republishes them.

## Preview locally (optional)

Run `python3 -m http.server 8000` in this folder, then visit `http://localhost:8000`.

## Content notes

The hydrogen-storage PhD deadline is 31 December 2026, as provided by Dr Li. Its start date remains to be confirmed. Team roles are labelled as reported in the Sway presentation. Retain the appropriate credits and permissions for supplied photographs and research figures.
