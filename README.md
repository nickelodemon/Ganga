# From Sacred to Sewage — The Real Story of the Ganga

An interactive, single-page presentation tracing the Ganga from the Gangotri Glacier
to the Bay of Bengal: state-by-state water quality, pollution sources, and the
restoration work under way along the river.

**Live site:** https://YOUR-USERNAME.github.io/ganga-site/

---

## What's in here

| File | Purpose |
|------|---------|
| `index.html` | The entire presentation — HTML, CSS, JavaScript and all seven images inlined as base64. ~3 MB. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is instead of running them through Jekyll. |
| `README.md` | This file. |

There are no dependencies, no build step, and no external requests. The page works
offline and will keep working if you move it anywhere.

---

## How to publish it on GitHub Pages

### 1. Create the repository

Go to https://github.com/new and create a repository named **`ganga-site`**.
Set it to **Public** — GitHub Pages will not serve a private repo on a free account.
Do **not** tick "Add a README file"; you are about to upload your own.

### 2. Upload these files

On the new empty repository page, click **uploading an existing file**
(or go to `https://github.com/YOUR-USERNAME/ganga-site/upload/main`).

Drag in all three files from this folder: `index.html`, `README.md`, and `.nojekyll`.

> If `.nojekyll` is not visible when you drag, your file explorer is hiding dotfiles.
> On Windows: File Explorer → **View** → tick **Hidden items**.
> You can also skip `.nojekyll` entirely — this site works without it.

Click **Commit changes**.

### 3. Turn on Pages

Go to **Settings → Pages** in your repository.

- Under **Source**, choose **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**

### 4. Wait, then visit

The first build takes one to two minutes. When it is done, your presentation is live at:

```
https://YOUR-USERNAME.github.io/ganga-site/
```

Replace `YOUR-USERNAME` with your GitHub username. Update the **Live site** link at the
top of this README once you know the URL.

---

## Using your profile's main address instead

If you would rather serve this at `https://YOUR-USERNAME.github.io/` with no path after it,
name the repository exactly **`YOUR-USERNAME.github.io`** instead of `ganga-site`, and follow
the same steps. Note that a GitHub account gets only one such site, so this address is best
saved for a personal landing page.

---

## Updating the page later

Open the repository, click `index.html`, then the pencil icon to edit — or use
**Add file → Upload files** and drop in a replacement `index.html` with the same name.
Commit, wait about a minute, then hard-refresh the live page (**Ctrl + F5**) to get past
the browser cache.

---

## Sources

All figures are drawn from the project research document and the final infographic —
the Central Pollution Control Board, the Bihar State Pollution Control Board's findings
as reported in the state Economic Survey, the National Mission for Clean Ganga, and the
Press Information Bureau, alongside reporting from Down to Earth, The Indian Express,
India Today and others.
