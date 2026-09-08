# Contributing to the AI Bio Lab website

This guide is for lab members who want to add themselves, post news, or list a
publication. It assumes you have used git a little and have never touched Hugo.

Every recipe below can be done entirely on GitHub.com — no local setup needed.
Press <kbd>.</kbd> on the repository page to open the web editor, or use
**Add file → Create new file**.

---

## 1. How this site works

- All content lives in `content/` as Markdown files with YAML front matter (the block between the two `---` lines).
- Pushing to `main` publishes the site automatically in about two minutes.
- If you are not an org member with write access: fork the repo, make a branch, and open a pull request. A lab maintainer will merge it.
- **Never edit `config/`, `layouts/`, or `.github/` without talking to the site maintainer.** Those control the whole site, not just your page.

---

## 2. Create or update YOUR profile

**Where:** `content/authors/<your-slug>/_index.md`

Your slug is a short lowercase name, usually your first name — `hugo`, `magnus`,
`connor`. It must match the folder name exactly.

**If you are new:** copy the folder `content/authors/hugo/`, rename the copy to
your slug, then edit every field in `_index.md`.

**Complete example** — copy this and replace the values:

```yaml
---
# Display name — how your name appears on the site
title: Hugo Henry

# Full name, used for search engines and for sorting the People page
first_name: Hugo
last_name: Henry            # the People page sorts alphabetically by this

# Must match your folder name exactly, all lowercase
authors:
  - hugo

# Leave this false — there is only one site owner
superuser: false

# Show your name in bold in listings
highlight_name: true

# Your role, shown under your name on the People page.
# Use "Ph.D. Candidate" only if you have passed your qualifying exam;
# otherwise "Ph.D. Student".
role: Ph.D. Candidate, Aerospace Engineering

organizations:
  - name: University of Cincinnati
    url: 'https://www.uc.edu/'

# One or two sentences. Shown in listings, not on your own page.
bio: 'Hugo is a PhD student working on explainable fuzzy-logic-based control and aircraft safety systems.'

# Short phrases, not sentences. Four to six is plenty.
interests:
  - 'Fuzzy Logic Control'
  - 'Airspace Safety & Air Mobility'
  - 'Explainable & Certifiable AI'

education:
  courses:
    - course: 'Ph.D. in Aerospace Engineering'
      institution: 'University of Cincinnati'
      year: 'Expected 2028'
    - course: 'M.S. in Aerospace Engineering'
      institution: 'University of Bordeaux'
      year: '2025'

# Only include the lines you actually have. Delete the rest.
social:
  - icon: envelope           # email
    icon_pack: fas
    link: 'mailto:henryho@mail.uc.edu'
  - icon: google-scholar
    icon_pack: ai            # note: "ai", not "fas" or "fab"
    link: 'https://scholar.google.com/citations?user=XXXXXXXX'
  - icon: orcid
    icon_pack: ai
    link: 'https://orcid.org/0000-0000-0000-0000'
  - icon: github
    icon_pack: fab
    link: 'https://github.com/yourhandle'
  - icon: linkedin
    icon_pack: fab
    link: 'https://www.linkedin.com/in/yourhandle/'
  - icon: researchgate
    icon_pack: fab
    link: 'https://www.researchgate.net/profile/Your-Name'
  - icon: globe              # personal website
    icon_pack: fas
    link: 'https://example.com'

# EXACTLY one of the six strings listed below
user_groups:
  - 'Ph.D. Students'
---

Write your long biography here, in third person, in Markdown. This is what
appears on your own profile page. Two or three paragraphs is a good length.

### Awards

- Outstanding Student Paper Award, NAFIPS 2026
```

### The six valid groups

`user_groups` must be **exactly** one of these strings, including the em dash (—):

```
Faculty
Ph.D. Students
M.S. Students
Undergraduate Students
Alumni — Ph.D.
Alumni — M.S.
```

A typo here does not cause an error — you will simply **not appear** on the
People page. If you cannot find yourself, check this first. Note the em dash
`—` in the alumni groups is not a hyphen `-`; copy and paste it.

### Your headshot

Save a square image, at least 400×400 pixels, as `avatar.jpg` inside your own
folder: `content/authors/<your-slug>/avatar.jpg`.

Use a **lowercase** extension. `avatar.JPG` will not be found on the build
server, which is case-sensitive. `avatar.png` also works.

**What NOT to touch:** other people's folders, and `content/people/index.md`
(the group list itself). Adding yourself to a group is done from your own file.

---

## 3. When you graduate

Do not delete your folder — alumni stay on the site. Edit your own
`_index.md` and change three things:

1. `user_groups` to `Alumni — Ph.D.` or `Alumni — M.S.`
2. `role` to your new position, e.g. `Senior AI Researcher, Thales`
3. Add one line to the body: your thesis title and defense date.

```yaml
role: Aerospace Engineer, NASA Ames Research Center
user_groups:
  - 'Alumni — Ph.D.'
```

```markdown
Ph.D. in Aerospace Engineering, March 2021. Thesis: *An Intelligent System for
Small Unmanned Aerial Vehicle Traffic Management*.
```

---

## 4. Add a news item

**Where:** create `content/post/<yyyy-mm>-<short-slug>/index.md` — for example
`content/post/2026-05-new-grant/index.md`.

The homepage automatically shows the five newest items. There is nothing else
to edit.

There are three kinds of news item. All three are posts; they differ only in
the body.

### Type A — link-out (press coverage, external articles)

Set `external_link`. Readers who click the headline go straight to the external
article instead of to a page on this site.

```yaml
---
title: 'Lab featured in UC News for work on trustworthy aerospace AI'
date: '2026-05-01'
authors: []
tags:
  - news
featured: false
external_link: 'https://www.uc.edu/news/articles/2026/05/example.html'
---

One sentence of context, in case someone lands on the page directly.
```

### Type B — milestone (qualifier, defense, award, lab event)

Write one to three sentences: who, which program, what is next. Add a photo as
`featured.jpg` in the same folder if you have one.

```yaml
---
title: 'Hugo Henry passes his PhD Qualifier'
date: '2026-02-01'
authors:
  - hugo          # use member slugs; their names become links to their profiles
tags:
  - news
featured: false
---

Hugo Henry passed his Ph.D. qualifying examination in February 2026. He
continues his doctoral research on explainable fuzzy-logic-based control and
aircraft safety systems in the Aerospace Engineering program.
```

### Type C — bare (nothing more to say)

Still needs **at least one sentence**. Never publish an empty body.

**What NOT to touch:** `content/post/_index.md` (the News page settings) and
the homepage. Both pick up new posts on their own.

---

## 5. Add a publication

Two routes. Use the easy one unless you need to attach a PDF or an image.

### Easy route (default)

1. Open `publications.bib` at the root of the repository.
2. Get your BibTeX: Google Scholar → **Cite** → **BibTeX**, or the publisher's page.
3. Paste it at the bottom. Give it a citation key nobody else has used (`lastname` + year + a keyword works well).
4. Commit to `main`.
5. A GitHub Action converts it into a page and opens a pull request. Ask a maintainer to review and merge it.

```bibtex
@inproceedings{henry2026anticollision,
  title     = {A Fuzzy Rule-Based Aircraft Anti-Collision System},
  author    = {Hugo Henry and Kelly Cohen},
  booktitle = {Proceedings of the North American Fuzzy Information Processing Society, 2026},
  year      = {2026},
  doi       = {10.1000/example},
  url       = {https://arxiv.org/abs/0000.00000}
}
```

### Manual route (when you want a PDF or featured image)

1. Copy an existing folder under `content/publication/`, e.g. `content/publication/tsk-phishing/`.
2. Rename the copy to a short descriptive slug.
3. Edit `index.md`.
4. Replace `cite.bib` with your own BibTeX.
5. Drop the paper PDF into the folder, named after the folder: `<folder-name>.pdf`.
6. Optionally add `featured.jpg` for the image shown in listings.

```yaml
---
title: 'A Gradient-Optimized TSK Fuzzy Framework for Explainable Phishing Detection'

# Use lab member slugs — this is what links the paper to your profile page.
# Coauthors outside the lab go in as plain names.
authors:
  - lohith
  - Jon Salisbury
  - kelly

date: '2025-04-25'
doi: '10.1000/example'          # bare DOI, not a doi.org or library-proxy URL

publishDate: '2025-04-25T00:00:00Z'

# One CSL type: paper-conference, article-journal, chapter, thesis, report...
publication_types: ['paper-conference']

publication: 'Proceedings of the North American Fuzzy Information Processing Society, 2025'
publication_short: 'NAFIPS'

abstract: One paragraph, plain text.

tags: []
featured: false                  # true puts it in the homepage's featured list

url_pdf: 'https://arxiv.org/pdf/0000.00000'
---
```

**Either way:** list yourself and your lab coauthors by **slug** in `authors:`.
That is what makes the paper appear on your profile page and your name link
from the paper.

---

## 6. Previewing your changes

**Option A — no setup.** Open a pull request and check that the build in the
**Actions** tab passes. Review the live site after it is merged.

**Option B — locally.**

1. Install Hugo **extended**, version 0.140.0 or newer.
2. In the repository folder, run:
   ```bash
   hugo server
   ```
3. Open <http://localhost:1313>.

---

## 7. Troubleshooting

| Symptom | Cause and fix |
| --- | --- |
| I'm not on the People page | A typo in `user_groups` — it must match one of the six strings exactly, em dash included. Or `authors:` does not match your folder name. |
| My photo doesn't show | The file must be `avatar.jpg` or `avatar.png`, lowercase extension, inside your own author folder. `avatar.JPG` will not be found. |
| The site didn't update | Check the **Actions** tab for a red ✗. Open the failed run — the error log names the file and line that broke. |
| My name isn't linked on a publication | The paper's `authors:` list must use your exact slug, not your written-out name. |
| The site won't build after I edited a date | Dates must be real and in `YYYY-MM-DD` order. `2026-15-01` is not a date and stops the whole build. |
| My publication has the wrong title on the site | The `title:` in `index.md` is what is displayed; `cite.bib` is only used for the citation download. Both need to be right. |

---

## 8. Who to contact

Site maintainer: _TODO — add the current maintainer's name and email here._

For anything touching `config/`, `layouts/`, or `.github/`, ask the maintainer
first.
