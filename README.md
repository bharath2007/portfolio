# Bharath A Prabhakar: Portfolio and Blog

Plain HTML, CSS and JavaScript. No install or build step.

## Run locally
Open `index.html` in a browser, or run `python -m http.server` in this folder and visit http://localhost:8000.

## Build
Nothing to build. The folder is the finished site.

## Deploy (GitHub Pages)
1. Create a GitHub repository and upload every file in this folder (keep `.nojekyll`).
2. Repository Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.
(Netlify: drag the folder onto app.netlify.com/drop. Vercel: import the repository.)

## Add your links
Edit `js/site.js`: `github`, `linkedin`, `email`. Until they start with `https://` (or are a real email), they show as dashed placeholders.

## Add a blog post
Copy a block in `js/posts.js`, change slug, title, date, category, tags, summary and body, and add a comma. It appears in the blog list, filters, search and related posts.

## Add a project
Copy the block in `js/site.js` under `PROJECTS`. Put screenshots in an `images/` folder and set `screenshot: "images/name.png"`.

## Finish the placeholders
Search all files for `[ADD` and `[YOUR` and replace each with your own information.
