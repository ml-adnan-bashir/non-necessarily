# Khamkha

A static GitHub Pages collection. Start with `index.html`.

## Pages

- `index.html`: Home with exactly three tiles.
- `template.html`: reusable page template for a future project.
- `crossword.html`: Death by Chocolate — a solved Urdu crossword containing all 44 available phrases.
- `cloud.html`: Death by Chocolate — the same 44 Urdu phrases as an interactive word cloud.

Both Urdu apps include six palettes, four embedded fonts, mouse highlighting and touch interaction. The expanded crossword has grid-size and whole-grid controls. Every page links back to Home. Fonts and code are embedded, so no installation or build step is required.

## Publish on GitHub Pages

1. Create your repository named `Khamkha`.
2. Extract this ZIP and upload its contents directly into the repository root. `index.html` must sit at the top level, not inside another folder.
3. Commit the files to `main`.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
6. Open the site URL GitHub shows when publishing finishes.

Official instructions: [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

All internal links are relative, so they work under the repository's GitHub Pages subdirectory and after opening the extracted `index.html` locally. No account, analytics, external requests or server are used by these pages.

## Add a project later

Duplicate `template.html`, change its title and main content, and copy a card in `index.html` with the new filename in its `href`.

## Phrase coverage

The crossword includes the entire 44-phrase collection recovered from the earlier word cloud, rather than the previous 20-phrase subset. Both apps use identical wording. Original spellings were restored where the earlier pasted text was available. The end of the original pasted message could not be recovered beyond the incomplete line «قبر میں جا لی…», so no continuation of that incomplete line has been invented.

Fonts are supplied under the SIL Open Font License. See `FONT-LICENSES.txt`.
