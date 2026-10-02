# shuoxing98.github.io

Source of [Shuo Xing](https://shuoxing98.github.io/)'s academic homepage, built with Jekyll on the [academic-homepage](https://github.com/luost26/academic-homepage) template. Every push to `main` is deployed automatically by GitHub Pages.

## Where things live

| What | File |
| --- | --- |
| Bio, positions, links, CV, education, experience | `_data/profile.yml` |
| Co-author homepage links (and bolding my name) | `_data/authors.yml` |
| News items | `_news/*.md` |
| Publications (`selected: true` shows it on the homepage) | `_publications/<year>/*.md` |
| Paper teaser images | `assets/images/covers/` |

In a publication's `authors` list, append `*` for equal contribution and `#` for corresponding author (they can be combined, e.g. `Junyuan Hong*#`).

## Preview locally

```bash
bundle install
bundle exec jekyll serve
```
