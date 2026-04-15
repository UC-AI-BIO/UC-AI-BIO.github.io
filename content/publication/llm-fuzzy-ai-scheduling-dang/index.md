---
title: 'Hybrid LLM–Fuzzy Task Scheduling for Software Developers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - dang
  - tri
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-15-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: "paper-conference"
publication_short: ""

abstract: |
    Software task assignment in modern development teams remains largely manual, relying on informal managerial judgment about skill fit and workload. This approach does not scale well as teams and task backlogs grow, often leading to uneven workload distribution and suboptimal task–developer matching. In this paper, we propose an interpretable decision-support framework for developer–task allocation that combines large language model (LLM)–based task understanding, embedding-based skill similarity, and Mamdani-type fuzzy inference systems. Task descriptions are assumed to be preprocessed into structured technical and non-technical skill requirements, while developer profiles capture heterogeneous skill sets and availability constraints. We introduce similarity mechanisms that handle variable-length technical skill sets and fixed-length non-technical skill profiles, and aggregate these signals through a two-stage fuzzy inference architecture that separately models availability and overall suitability. The resulting system produces transparent suitability scores that managers can inspect, adjust, and override, rather than relying on fully automated black-box assignment decisions. This work lays a foundation for future extensions of our framework toward interpretable, human-centered task allocation in software teams under uncertainty.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---