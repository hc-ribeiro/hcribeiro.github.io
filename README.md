# hcribeiro.github.io

A simple portfolio and résumé site powered by GitHub Pages (Jekyll Minimal theme).

## Structure
- `index.md`: Home page with quick links
- `resume/`: Online résumé page embedding the PDF
- `(en)curriculum-vitae.pdf`: Source résumé PDF
- `assets/`: Custom styles and images

## Customize
- Edit `_config.yml` for title, description, and logo.
- Replace `assets/img/profile.svg` with your photo or logo (optional).
- Update `index.md` with your content and links.
- To add a custom domain, create a root `CNAME` file with your domain.

## Local preview (optional)
GitHub Pages builds this automatically when pushed. To run locally you need Ruby + Bundler and the GitHub Pages gem.

```bash
# Optional local preview
gem install bundler github-pages
bundle init
# Add to Gemfile: gem 'github-pages', group: :jekyll_plugins
bundle exec jekyll serve
```
