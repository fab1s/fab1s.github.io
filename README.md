# Fabio Schreiber — Research portfolio

Personal academic website: https://fab1s.github.io

Design adapted from [Minimal Light](https://github.com/yaoyao-liu/minimal-light), with a compact profile sidebar and a homepage centred on research projects and experience. Existing Jekyll content and publishing are retained. Original template licenses are included.

## Add a project

1. Copy `templates/project.md` into `_portfolio/your-project-name.md`.
2. Replace the title, excerpt, order, and text. Projects appear automatically on the Projects page, sorted by `order`.
3. Add images in `images/` and documents in `files/`.
4. Commit to `main`; GitHub Pages builds and publishes the update automatically.

You can edit directly on GitHub: open `_portfolio`, select **Add file → Create new file**, and paste the template. A committed project is public; prepare unfinished text locally or in a pull request.

The homepage automatically highlights the first three projects. Add `area` and `period` metadata to show the project topic and dates.

## Update your details

- `_config.yml`: name, biography, email, institution, and profile links.
- `_data/navigation.yml`: top navigation.
- `_pages/about.md`: homepage biography.
- `_pages/cv.md`: online CV.
- `_pages/research.md`: theses and research contributions.
- `files/fabio-schreiber-cv.pdf`: downloadable CV. Update this separately from the online CV.

To add a portrait, save it in `images/` and set `author.avatar` to its filename in `_config.yml`. No sample portrait or invented publication citations are included. The public site and CV omit the phone number.

## Preview locally

With Ruby 3.2+ and Bundler installed:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000. The publication workflow appears under **Actions → Publish Academic Pages**. Repository Settings → Pages uses **GitHub Actions**.
