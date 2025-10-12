# sofiaschroeter.github.io

Personal website built with Jekyll using the Minimal Mistakes remote theme.

## Local development

This site is built with Jekyll. To run it locally you need Ruby (3.0+ recommended) and Bundler.

On macOS, it's best to use a user-level Ruby (via Homebrew or a version manager) rather than the system Ruby.

### 1) Install dependencies

```bash
bundle install
```

If you don't have Bundler:

```bash
gem install bundler
bundle install
```

### 2) Serve with live reload

```bash
bundle exec jekyll serve --livereload
```

Then open http://127.0.0.1:4000 in your browser.
Stop serving the site with control+c.

## Notes

- The theme is configured as a remote theme in `_config.yml`:
	- `remote_theme: mmistakes/minimal-mistakes`
	- Plugins enabled: `jekyll-remote-theme`, `jekyll-include-cache`
- You generally do not need Node/Vite to run this site. Vite does not render Liquid/Jekyll templates. If desired, Vite can be added later only to bundle custom JS/CSS and its built assets can be referenced from Jekyll.

