# Martin Nikolov — Portfolio Site

## 📁 Structure

```
portfolio/
├── index.html          ← Homepage (the grid)
├── style.css           ← All global styles
├── main.js             ← Tiny JS (animations, year)
│
├── pages/
│   ├── about.html
│   ├── portfolio.html
│   ├── resume.html
│   ├── blog.html       ← Auto-loads post list from posts.json
│   └── contact.html
│
├── blog/
│   ├── post-template.html   ← Single post renderer
│   ├── blog-loader.js       ← Fetches & renders .md files
│   ├── blog.css             ← Blog-specific styles
│   ├── posts.json           ← LIST OF ALL POSTS (edit this when adding a post)
│   └── posts/
│       ├── hello-world.md
│       └── why-i-code.md
│
└── assets/
    ├── img/
    │   ├── profile.jpg        ← Your photo (used in the big square)
    │   ├── about-thumb.jpg
    │   ├── portfolio-thumb.jpg
    │   ├── resume-thumb.jpg
    │   ├── blog-thumb.jpg
    │   └── contact-thumb.jpg
    └── resume.pdf             ← Your actual CV
```
