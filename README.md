# Fu Chen — Personal Website

A single-page academic website for [Fu Chen](https://dsdfasfaac.github.io/), adapted from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

All public content is in `_pages/about.md`. The page layout and styling are in `_layouts/home.html` and `assets/css/home.css`. Previous section and publication URLs redirect to the homepage.

Publication thumbnails in `images/publications/` come from the corresponding [Zeva](https://air-embodied-brain.github.io/Zeva/), [Zeva-Ego](https://air-embodied-brain.github.io/Zeva-Ego/), and [Zetta](https://air-embodied-brain.github.io/zetta/) project pages.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config_dev.yml
```

Open <http://localhost:4000>.

## Attribution

Jekyll structure: [Academic Pages](https://github.com/academicpages/academicpages.github.io), MIT License. See [LICENSE](LICENSE).
