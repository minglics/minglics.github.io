# Ming Li Website

This repository contains the Jekyll source for `https://minglics.github.io`.

The site is based on the Minimal Mistakes Jekyll theme and is deployed with GitHub Actions. Source content lives mainly in:

- `_pages/`
- `_posts/`
- `images/`
- `publications/`
- `slides/`
- `videos/`

The generated `_site/` folder is not committed. GitHub Actions builds it during deployment.

## Local Preview

```sh
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
