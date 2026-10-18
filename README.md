# Huixin Han — personal website

Built with [al-folio](https://github.com/alshedivat/al-folio). Live at https://huixin-han.github.io/.

Edit files on `main` and Commit changes. `gh-pages` is automatically generated.

| Page         | Content file             |
| ------------ | ------------------------ |
| About        | `_pages/about.md`        |
| Research     | `_pages/research.md`     |
| Explorations | `_pages/explorations.md` |
| Teaching     | `_pages/teaching.md`     |
| Service      | `_pages/service.md`      |
| Elsewhere    | `_pages/elsewhere.md`    |

Page copy beyond the supplied biography proposes a structure for future content; it does not claim specific publications, courses, or service roles.

## Upload a portrait

1. Open `assets/img/` and choose Add file → Upload files.
2. Upload your own photograph, for example `portrait.jpg`.
3. Edit `_data/personal.yml`, setting `portrait: portrait.jpg`.
4. Commit. The photograph replaces the text placeholder to the left of the bio.

Other photos go in the same directory. Add one to a page with:

```markdown
![Description of the photo]({{ '/assets/img/trail-autumn.jpg' | relative_url }})
```

Add your own publications to `_bibliography/papers.bib`. Optional public Email and Google Scholar links are in `_data/personal.yml`.

Default images and sample content have been removed from current source; recoverable history remains in Git. No gem-owned layouts, includes, or Sass are overridden. Layout styles are contained in each page.
