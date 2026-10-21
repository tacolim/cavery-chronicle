# Chronicle of Interpretability Exploration

Cassidy Avery's journal of learning AI interpretability. Live at https://chronicle.cassidyavery.com (GitHub Pages + Jekyll).

## Writing a post

Add `_posts/YYYY-MM-DD-slug.md`:

```markdown
---
title: "Entry N: Title"
description: "One or two sentences. Shown on the home page list and in link previews."
---

Post body in Markdown...
```

## Local preview

GitHub Pages doesn't support Ruby 4 yet, so use Homebrew's Ruby 3.4 (`brew install ruby@3.4`):

```sh
export PATH="/opt/homebrew/opt/ruby@3.4/bin:$PATH"
bundle config set --local path vendor/bundle   # first time only
bundle install                                 # first time / after Gemfile changes
bundle exec jekyll serve                       # http://localhost:4000
```
