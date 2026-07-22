# Shesadree Priyadarshani — Portfolio

Personal portfolio site for **Shesadree Priyadarshani**, Applied Data Scientist & AI Researcher (M.S. Applied Data Science, University of Florida).

Styled as a precision instrument reading a live signal — a nod to my electrical-engineering roots and my work in signal-based deep learning, LLM evaluation, and interpretability.

**Live site:** `https://lili1501.github.io/portfolio/` *(after you enable Pages — see below)*

## What's here

A single self-contained `index.html` — no build step, no dependencies, no framework. Just open it or host it. Fonts load from Google Fonts; everything else (the animated ECG signal, scroll reveals, layout) is inline.

## Deploy on GitHub Pages (free, ~2 minutes)

1. Create a new repo on GitHub named **`portfolio`** (or any name).
2. Upload `index.html` and `README.md` to the repo (drag-and-drop in the GitHub web UI, or `git push`).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch **`main`** and folder **`/ (root)`**, then **Save**.
6. Wait ~1 minute. Your site goes live at `https://<your-username>.github.io/portfolio/`.

### Push from the command line (optional)

```bash
git init
git add index.html README.md
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/lili1501/portfolio.git
git push -u origin main
```

## Add it to your resume

Once live, add the URL under your name / contact line, e.g.:

> Portfolio: `lili1501.github.io/portfolio`

**Tip:** For a cleaner link, buy a domain (e.g. `shesadree.dev`) and point it at Pages via **Settings → Pages → Custom domain**.

## Editing

Everything lives in `index.html`. Search for the section you want (`id="work"`, `id="experience"`, etc.) and edit the text directly. To change the accent color, edit the CSS variables at the top:

```css
--trace:#0B8C82;    /* primary signal / teal */
--trace-2:#DC7B32;  /* amber accent */
```

## Accessibility

- Responsive down to mobile
- `prefers-reduced-motion` respected (signal renders static, reveals disabled)
- Keyboard-focusable links, semantic sections
