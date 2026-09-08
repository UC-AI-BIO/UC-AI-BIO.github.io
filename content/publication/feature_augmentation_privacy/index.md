---
title: 'Fuzzy Feature Augmentation for Privacy-Preserving Machine Learning: Improving Model Robustness Under Noise Perturbation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - john
  - tri
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
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the North American Fuzzy Information Processing Society, 2026"
publication_short: "NAFIPS"

abstract: |
    Differential privacy has emerged as a common way for protecting sensitive information in machine learning systems. Adding noise to a database before processing serves as the primary mechanism for achieving privacy guarantees. This creates a fundamental privacy-utility tradeoff that varies across model architectures, motivating the search for techniques that improve robustness under noise. Fuzzy inference systems, with their inherent tolerance for imprecision and uncertainty, asks: do soft decision boundaries provide resilience to privacy-preserving noise? We investigate fuzzy feature augmentation which adds fuzzy c-means cluster membership values to conventional model inputs as a practical strategy for enhancing noise resilience. Using a medical cost prediction dataset, we compare four models (Ridge Regression, Multi-Layer Perceptron, Gradient Boosting, and Random Forest) with and without fuzzy augmentation across multiple noise levels ranging from 0% to 5% perturbation. Our results demonstrate consistent improvements for non-linear models: Gradient Boosting improves by 2.88%, MLP by 2.36%, and Random Forest by 1.92%, while Ridge Regression shows no benefit. Analysis reveals that fuzzy membership features encode local geometric structures that tree-based and neural models can exploit for improved predictions, even when original features are corrupted by noise. These findings establish fuzzy feature augmentation as a low-overhead technique for improving privacy-utility tradeoffs in machine learning applications involving sensitive data.


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