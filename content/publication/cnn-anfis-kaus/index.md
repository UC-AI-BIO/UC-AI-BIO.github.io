---
title: 'A Comparative Study of Adversarial Robustness in CNN and CNN-ANFIS Architectures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - kaus
  - ben
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
    Convolutional Neural Networks (CNNs) achieve strong image classification performance but lack interpretability and are vulnerable to adversarial attacks. Neuro-fuzzy hybrids such as DCNFIS replace fully connected CNN classifiers with Adaptive Neuro-Fuzzy Inference Systems (ANFIS) to improve interpretability, yet their robustness remains underexplored. This work compares standard CNNs (ConvNet, VGG, ResNet18) with their ANFIS-augmented counterparts on
    MNIST, Fashion-MNIST, CIFAR-10, and CIFAR-100 under gradient-based (PGD) and gradient-free (Square) attacks. Results show that ANFIS integration does not consistently improve clean accuracy and has architecture-dependent effects on robustness: ResNet18-ANFIS exhibits improved adversarial robustness, while VGG-ANFIS often underperforms its baseline. These findings suggest that neuro-fuzzy augmentation can enhance robustness in specific architectures but is not universally beneficial.



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