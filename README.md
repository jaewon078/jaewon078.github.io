# jaewon078.github.io

Personal site + blog, built with Jekyll and hosted on GitHub Pages.

## Editing

| What | Where |
| --- | --- |
| Name, description, social links | `_config.yml` |
| About (the homepage) | `index.md` |
| Blog posts | `_posts/YYYY-MM-DD-title.md` |
| Colors, fonts, spacing | `assets/css/style.css` |
| Favicon | `assets/favicon.svg` |

Commit and push to `main`; GitHub rebuilds the site automatically (~1 min).

## Preview locally (optional)

Needs Homebrew Ruby (`brew install ruby`). macOS's built-in Ruby is too old.

```sh
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.
