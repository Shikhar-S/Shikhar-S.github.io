# shikhar-s.github.io

Personal academic homepage of Shikhar Bharadwaj, built with Jekyll.

Based on [luost26/academic-homepage](https://github.com/luost26/academic-homepage), following the
modifications by [Pengfei Xu](https://github.com/pengfeixu/pengfeixu.github.io) (education/experience
cards with logos, year-grouped news, date-sorted publications).

## Editing content

- **Bio, photo, education, experience, links:** `_data/profile.yml`
- **Publications:** one markdown file per paper in `_publications/<year>/` (only the YAML front matter matters)
- **News:** one markdown file per item in `_news/`
- **Co-author display names/links:** `_data/authors.yml`
- **Navigation:** `_data/navigation.yml`
- **Section visibility & footer:** `_data/display.yml`

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
