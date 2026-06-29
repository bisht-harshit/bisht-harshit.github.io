# Your Academic Website

A clean, responsive personal site built with **zero dependencies** — just HTML and CSS.

## Quick Start

1. Create a new GitHub repository (e.g. `yourusername.github.io`)
2. Upload all these files into it, keeping the folder structure:
   ```
   index.html
   publications.html
   blog.html
   style.css
   blog/
     sample-post.html
   ```
3. Go to **Settings → Pages** in your repo
4. Under "Source", select your main branch
5. Your site will be live at `https://yourusername.github.io` within a minute

## Customizing

- **Your name & info:** Search for "Harshit Bisht" across the HTML files and replace with your details
- **Your photo:** Drop a `photo.jpg` in the root folder and update the `<img>` tag in `index.html`
- **Colors:** Edit the CSS custom properties in `style.css` under `:root` (light) and `[data-theme="dark"]` (dark)
- **Add a publication:** Copy a `.pub-item` block in `publications.html`
- **Add a blog post:** Copy `blog/sample-post.html`, edit the content, and add a link in `blog.html`

## Structure

```
index.html          ← Home page (bio + news)
publications.html   ← Papers grouped by year
blog.html           ← Blog post index
blog/               ← Individual blog posts go here
  sample-post.html
style.css           ← All styling (shared across pages)
```

No build tools. No `npm install`. No config files. Just edit and push.
