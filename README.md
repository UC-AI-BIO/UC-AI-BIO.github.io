# AI Bio Lab website

Source for the website of the [AI Bio Lab](https://uc-ai-bio.github.io/) at the
University of Cincinnati, led by Prof. Kelly Cohen. The lab develops
assurance-ready, interpretable fuzzy and hybrid AI for aerospace, healthcare,
cybersecurity, and other safety-critical applications.

**Live site:** <https://uc-ai-bio.github.io/>

## Stack

Hugo (extended) with the [Hugo Blox](https://hugoblox.com/) research group
theme. Every push to `main` triggers `.github/workflows/publish.yaml`, which
builds the site and deploys it to GitHub Pages — live in about two minutes.

## Running locally

Requires Hugo **extended** 0.140.0 or newer.

```bash
hugo server        # then open http://localhost:1313
hugo --minify      # production build, output in public/
```

## Editing content

**Lab members: see [CONTRIBUTING.md](CONTRIBUTING.md).** It has step-by-step
recipes, with complete copy-pasteable examples, for the three things people
actually need to do:

- [create or update your profile](CONTRIBUTING.md#2-create-or-update-your-profile) (and [what to change when you graduate](CONTRIBUTING.md#3-when-you-graduate))
- [post a news item](CONTRIBUTING.md#4-add-a-news-item)
- [add a publication](CONTRIBUTING.md#5-add-a-publication)

Every recipe works from the GitHub.com web editor, so no local setup is needed
for content-only edits.

### Adding a publication, in short

Two routes, both covered in detail in the contribution guide:

1. **BibTeX (easy).** Paste the entry into `publications.bib` at the repository
   root and push to `main`. A GitHub Action converts it into a page under
   `content/publication/` and opens a pull request for review.
2. **By hand (full control).** Copy an existing folder under
   `content/publication/`, edit `index.md` and `cite.bib`, and drop in the PDF
   and a featured image.

## Layout

```
content/authors/      one folder per lab member and alum
content/publication/  one folder per paper
content/post/         news items
content/research/     the lab research profile
config/_default/      site configuration — ask the maintainer before editing
```
