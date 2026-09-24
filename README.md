# Fu Chen — Academic Homepage

Personal academic website for [Fu Chen](https://dsdfasfaac.github.io/), built from the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Content

- `_pages/about.md`: homepage and selected work
- `_pages/research.md`: research overview
- `_pages/cv.md`: education, experience, and skills
- `_publications/`: one Markdown page per paper
- `_config.yml`: site and author information
- `_data/navigation.yml`: top navigation
- `assets/css/main.scss`: small site-specific styles

The site intentionally uses a typographic avatar instead of a personal photo. A downloadable résumé PDF can be added later if a public version is desired.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config_dev.yml
```

Open <http://localhost:4000>. The repository is configured for the GitHub Pages URL `https://dsdfasfaac.github.io/`.

## Attribution

Theme and Jekyll structure: [Academic Pages](https://github.com/academicpages/academicpages.github.io), MIT License. See [LICENSE](LICENSE).
