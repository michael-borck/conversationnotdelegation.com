# conversationnotdelegation.com

Single-page framework microsite for [Conversation not Delegation](https://conversationnotdelegation.com), authored by Michael Borck.

Astro 5, plain CSS, deployed to GitHub Pages.

## Local development

```bash
npm install
npm run dev    # → http://localhost:4321
npm run build
```

## Structure

```
src/
  layouts/Base.astro
  pages/index.astro      # The whole site
  styles/global.css
public/
  CNAME
  favicon.svg
.github/workflows/deploy.yml
```

## Pre-launch checklist

- [ ] Confirm GitHub Pages source is set to "GitHub Actions" in repo Settings → Pages
- [ ] Configure DNS A/CNAME records pointing `conversationnotdelegation.com` to GitHub Pages
- [ ] (Optional) Update book card descriptions if more accurate summaries are available
- [ ] (Optional) Add real book cover images and adjust the `.book-title` block to render them
- [ ] Cross-link tested: CTA from microsite goes to `borck.consulting/services`; About page on `borck.consulting` links back here
