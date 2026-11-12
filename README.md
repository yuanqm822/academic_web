# academic_web

Personal academic website of Simon (Qiming) Yuan, built with Jekyll on the
[academicpages](https://github.com/academicpages/academicpages.github.io) template
and hosted on GitHub Pages at <https://yuanqm822.github.io/academic_web/>.

## Where things live

| To change | Edit |
| --- | --- |
| Name, sidebar text, profile links (email, Google Scholar, ORCID) | `_config.yml`, under `author:` |
| Profile photo | replace `images/profile.jpg` |
| Home page text | `_pages/about.md` |
| Research page | `_pages/research.md` |
| CV | `_pages/cv.md` |
| Grants and awards page | `_pages/grants-and-awards.md` |
| Computation page | `_pages/computation.md` |
| Funders listed in the sidebar | `_data/funders.yml` |
| GitLab projects on the Computation page | `_data/computation.yml` |
| Colours, fonts and layout | `_sass/_custom.scss` (the "Tokens" block at the top) |
| Top menu | `_data/navigation.yml` |

## Adding a publication

Add one file to `_publications/`, named `YEAR-short-title.md`, containing only front matter:

```yaml
---
title: "Paper title"
collection: publications
type: article        # or: thesis
authors: "Yuan Q, Coauthor AB"   # add † after joint first authors
venue: "Journal Name"
year: 2026
date: 2026-03-01     # used for ordering
volume: "12"
issue: "3"           # optional
pages: "100–110"
doi: "10.xxxx/xxxxx"
---
```

It then appears on the Publications page, the CV, and (if recent) the home page.

## Previewing locally

```
bundle install
bundle exec jekyll serve
```
