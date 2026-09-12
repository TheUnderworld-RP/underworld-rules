# Underworld RP — Server Rules

A single-file website ready for GitHub Pages. The styles and small navigation script are included in `index.html`; there are no dependencies or build commands. All rules remain readable with JavaScript disabled.

## Publish for free

1. Sign in to GitHub as **TheUnderworld-RP** and create a new **public** repository named `underworld-rules`. Add a README when creating it.
2. In that repository, choose **Add file → Upload files** and upload `index.html` from this folder. Commit the upload to `main`. You can also upload the optional `.nojekyll` file to bypass Jekyll processing.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose **main** and **/(root)**, then **Save**.
6. Wait for the Pages deployment to finish. The live address appears in **Settings → Pages**. For this account and repository, the expected address is `https://theunderworld-rp.github.io/underworld-rules/`.

Only the files in this website folder belong in the public repository. The surrounding UnderworldRP directory contains separate server files.

GitHub Free requires a public repository for Pages. The supplied GitHub address costs nothing; a purchased custom domain is optional.

Official setup documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

Publishing source documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Update a rule

Open `index.html` on GitHub and select the pencil icon. Find the relevant `<section class="rule" id="rule-...">`, edit its paragraph, and commit the change. Pages republishes automatically. If changing a heading, also change its matching text in both navigation lists. Keep the rule IDs stable so existing Discord links still work.

## Local preview

Double-click `index.html` to open it in a browser. On the published HTTPS site, each rule offers a **Copy link** control. If clipboard access is unavailable, its link still opens the rule directly.
