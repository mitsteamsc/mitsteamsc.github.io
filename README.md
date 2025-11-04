# Student Company Website (GitHub Pages ready)

This is a simple, customizable static website for your student company. It's designed for GitHub Pages and inspired by modern startup landing pages (clean hero, product menu, clear CTA). You don't need to know much HTML/CSS to customize it — edit a small JSON file or use the built-in quick editor in the browser.

What's included
- index.html — main page (hero, product menu, buy links, simple editor).
- css/styles.css — styling inspired by minimalist startup sites.
- js/scripts.js — loads data.json, renders the site, and provides a simple in-browser editor (saved to localStorage).
- data/data.json — editable product & site content (the place you should edit on GitHub to publish changes).

How to use with GitHub Pages
1. Create a new GitHub repository (or use an existing one).
2. Push these files to the repository root (or a branch like `main`).
3. In repository Settings → Pages, set the source to the `main` branch (root) and save.
4. After a minute, your site will be published at `https://<your-username>.github.io/<repo-name>/`.

Two ways to edit content
- Recommended (publishes on GitHub Pages): Edit data/data.json directly in the repo (GitHub UI → Edit file → Commit).
- Fast local changes (no publishing): Open the site in your browser and click "Edit Site" to change text/products — changes are saved to your browser (localStorage). To publish edits, copy changes into data/data.json in the repository.

Notes
- The "Buy" links are simple anchors. Replace them with your real checkout/Shopify links.
- If you want help publishing or customizing color/logo/fonts, tell me your repo name and I can make a PR or push files for you.

中文说明
我为你做了一个可编辑的静态网站（适用于 GitHub Pages）。推荐的编辑方式是在 GitHub 上修改 data/data.json 来发布到你的网页；如果你想快速试验，可以在浏览器里用“Edit Site”编辑（结果存在本地，不会自动上传到 GitHub）。

If you want, give me:
- your GitHub repo name (owner/repo) and I can push the files for you, or
- the logo text/color choices and product list and I can fill data/data.json for you.
