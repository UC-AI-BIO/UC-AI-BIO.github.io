---
title: 'Genetic Generalized Additive Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - kaus
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-02-15'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the North American Fuzzy Information Processing Society, 2026"
publication_short: "NAFIPS"

abstract: |
    Generalized Additive Models (GAMs) balance predictive accuracy and interpretability, but manually configuring their structure is challenging. We propose using the multi-objective genetic algorithm NSGA-II to automatically optimize GAMs, jointly minimizing prediction error (RMSE) and a Complexity Penalty that captures sparsity, smoothness, and uncertainty. Experiments on the California Housing dataset show that NSGA-II discovers GAMs that outperform baseline LinearGAMs in accuracy or match performance with substantially lower complexity. The resulting models are simpler, smoother, and exhibit narrower confidence intervals, enhancing interpretability. This framework provides a general approach for automated optimization of transparent, high-performing models.


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2602.15877v1'
url_code: 'https://github.com/KaaustaaubShankar/GeneticAdditiveModels'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---