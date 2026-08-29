# Pengyu Chen — personal website

This is a lightweight personal website. It uses plain HTML, CSS, and JavaScript, so it can run locally without Jekyll, Ruby, or a theme framework.

## Pages

- `index.html` — home page
- `blog.html` — Markdown blog reader
- `publications.html` — publication list
- `teaching.html` — teaching page
- `about.html` — biography and education

## Run locally

From this folder, run one of the following:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

The `PengyuChen_CV.pdf` file is linked from the navigation and should stay in the project root.

## Add a blog post

1. Add a Markdown file under `posts/`.
2. Add its title, date, file path, excerpt, and tags to `posts.json`.
3. Open `blog.html`; the post will appear in the list and render in the reader.
