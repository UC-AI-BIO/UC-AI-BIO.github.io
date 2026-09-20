---
title: 'Performance Evaluation and Explainability Assessment of Deep Learning Architectures for Age-Related Macular Degeneration Diagnosis in OCT Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tam Thanh Minh Nguyen
  - Nguyen Hoang Phuong
  - tri
  - Vladik Kreinovich
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

abstract: |
    Age-related Macular Degeneration (AMD) is a leading cause of blindness, necessitating early and accurate diagnosis via Optical Coherence Tomography (OCT) imaging. This study evaluates and compares the performance of three deep learning architectures: ResNet50 (a conventional convolutional neural network), ResNet50 enhanced with a Convolutional Block Attention Module (CBAM), and the Tiny Swin Transformer (a Vision Transformer model) for three-class classification (CNV, Drusen, Normal). Cross-validation results on the OCT dataset show that ResNet50 achieves the highest overall performance, with a Macro AUC of 0.985 ± 0.005 and Accuracy of 0.934 ± 0.015. Notably, Res-Net50+CBAM optimizes clinical performance by achieving the highest CNV recall (0.940 ± 0.036), underscoring the importance of attention mechanisms in improving sensitivity and reducing the risk of missing critical pathological cases. The study concludes that while ResNet50 remains the most effective overall, ResNet50+CBAM offers superior stability, interpretability, and clinically relevant sensitivity, making it a promising model for retinal disease screening and diagnostic support.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/398417093_Performance_Evaluation_and_Explainability_Assessment_of_Deep_Learning_Architectures_for_Age-Related_Macular_Degeneration_Diagnosis_in_OCT_Images?channel=doi&linkId=693493c99aa6b4649dbdfad2&showFulltext=true'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---