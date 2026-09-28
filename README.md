# MusicAthletes.com

Landing page for MusicAthletes, a resource hub for musician-athletes heading to the Olympic Games.

Plain HTML + CSS. No build step, no dependencies.

```
index.html    the page

favicon.svg   browser tab icon
CNAME         custom domain for GitHub Pages
```

## Publish with GitHub Pages

1. Create a new repository on GitHub and upload these files to the root (or `git push` them).
2. In the repo, go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. At your domain registrar, point `musicathletes.com` to GitHub Pages:
   - `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www`: `<your-github-username>.github.io`
4. Back in **Settings → Pages**, confirm the custom domain and tick **Enforce HTTPS** once it's available.

Not using the custom domain yet? Delete `CNAME` and the site will live at `https://<username>.github.io/<repo>/`.

## Editing

- **Accent color:** change `--accent` near the top of `index.html` (inside the <style> tag) (alternates: `#FFC21A`, `#3D7BFF`, `#C6F432`).
- **Contact email:** search `support@musicathletes.com` in `index.html`.
- **Copy:** all text is in `index.html`.
