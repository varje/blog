# Jekyll Blog

Site runs at: https://varje.github.io/blog/

## Requirements
- Ruby 3.1–3.2
- Bundler

## Local Setup
```bash
bundle install
bundle exec jekyll serve
```

Site runs at: http://localhost:4000/blog/

### Adding new post
1. Create a file in _posts: 
```bash
YYYY-MM-DD-title.markdown
```
1. Add header:
```bash
---
layout: post
title:  "Title of your post"
date:   YYYY-MM-DD HH:MM:SS ±HHMM
categories: category
comments: true
---
```

1. Add your blog post text

1. Include comment area
```bash
{% include comment_area.html %}
```

1. Build:
```bash
bundle exec jekyll build
```
