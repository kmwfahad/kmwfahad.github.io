# Personal academic website

Static site for GitHub Pages. It needs no build step: plain HTML and CSS.

- `index.html` holds all the content (sections: About, News, Research, Publications, Teaching, Experience, Projects, Awards, Contact)
- `assets/style.css` holds the styling, with light and dark themes
- `assets/profile.jpg` is the profile photo

## Publish
1. Create a public GitHub repository named exactly `USERNAME.github.io`.
2. Upload these files to it, or push them with git.
3. Go to Settings → Pages → Source: "Deploy from a branch" → `main` / root.
4. After about a minute the site is live at `https://USERNAME.github.io`.

## Update
- To add a news item, copy a `<li>` in the News section.
- To add a paper, copy a `<div class="pub">` block in the Publications section.
- To add a CV, Google Scholar or GitHub link, uncomment the lines in the sidebar `<!-- Add when ready -->` block and put `cv.pdf` in `assets/`.
