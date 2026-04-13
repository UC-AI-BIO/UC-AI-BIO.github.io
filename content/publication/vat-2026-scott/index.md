---
title: 'Visualization Assessment of Tendency in Clustering – 58K × 58K in 60 seconds
'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Scott Phillips
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-15'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-paper']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the North American Fuzzy Information Processing Society, 2026"
publication_short: "NAFIPS"

abstract: |
    Visualization Assessment of Tendency (VAT) in Clustering has been a technique for the identification of data clusters since 2002. Although a proven
    technique, it has suffered from the curse of dimensionality, leading to limited performance for datasets with more than 5000 elements. The core of the model is based on Prim’s algorithm, a greedy Minimum Spanning Tree search that uses Bubble Sort at its core. By replacing Bubble Sort with Merge Sort using a priority queue, the updated ”mergeVAT” algorithm complexity changes from O(N) = N^3 to O(N) = N^2*logN. For datasets with 1,000 elements, this leads to a speed up of 30×. In addition, by identifying the permutation loops and bit-masking, it is now possible to compute the full VAT of a 58000 element dataset in place while requiring only O(N) = N^2/16 additional working memory in less than 2 minutes.

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