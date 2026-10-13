# zablotchi.com

Source of Igor Zablotchi's personal website. GitHub Pages builds it with Jekyll
from the `master` branch and serves it at https://zablotchi.com (the `CNAME`
file). Old `zablotchi.github.io` links redirect there automatically, so keep
this repository's name.

## Editing content

| What | Where |
|---|---|
| Papers (home page shows those with `selected: true`) | `_data/papers.yml` |
| Recognition, experience | `_data/awards.yml`, `_data/experience.yml` |
| Talks and posters | `_data/talks.yml` |
| Bio | `index.html` |
| Name, tagline, email, profile links, interests | `_config.yml` |
| Styles | `assets/css/site.css` |
| CV | replace `files/cv.pdf` |

## Previewing locally

```bash
conda activate jekyll
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Then open http://localhost:4000. Restart the server after editing `_config.yml`.

The design is inspired by [kevinroose.com](https://kevinroose.com).
