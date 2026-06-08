# yellowpancake.github.io

Personal academic homepage of **Bingchen Huang (黄炳琛)** — Algorithm Engineer at Meituan.
Multimodal Large Language Models & Continual Learning.

🔗 Live: https://yellowpancake.github.io/

## Stack

Plain **HTML + CSS + vanilla JS** — no build step, served directly by GitHub Pages
(`.nojekyll` disables Jekyll processing). Light/dark theme, responsive, scroll-spy nav,
scroll-reveal animations.

```
index.html            # the whole page (sections: About / News / Research / Publications)
assets/css/main.css   # styles + theming via [data-theme]
assets/js/main.js     # theme toggle, scroll-spy, reveal, footer year
assets/img/avatar.jpg # web-optimized portrait
files/                # CV
images/               # favicons / site icons
```

## Edit

Everything is in `index.html`. To add a publication, copy a `<li class="pub__item">`
block in the Publications section and update the title / authors / venue badge / links.
To add a news item, copy a `<li>` in the `.news` list.

Preview locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Push to `master` and GitHub Pages redeploys automatically.
