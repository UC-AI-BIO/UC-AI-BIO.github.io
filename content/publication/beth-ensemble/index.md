---
title: 'Bridging the Closed-World Gap: Interpretable Anomaly Detection via a Hybrid TSK-FCM Ensemble on the BETH Dataset'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - lohith
  - Josette Riep
  - justin-ouwerkerk
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-15'
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
    A fundamental paradox plagues the deployment of Machine Learning in cybersecurity: supervised models generalize poorly to novel, Out-of-Distribution (OoD) attacks, whereas unsupervised models often suffer from poor separability, leading to unmanageable false-alarm rates. This challenge is exemplified by the BETH dataset, a kernel-level benchmark in which the training data consists solely of benign and ``suspicious'' insider behaviors, whereas the test set consists almost entirely of novel botnet activation attacks. To bridge this detection gap, we propose a Hybrid Fuzzy Ensemble that synergizes the precision of supervised learning with the adaptability of unsupervised clustering. Our architecture integrates a gradient-optimized Takagi-Sugeno-Kang (TSK) fuzzy classifier to act as an expert on known insider threats, with a parallel Fuzzy C-Means (FCM) module to detect geometric anomalies. A critical finding of our research is that traditional fuzzy membership scores degrade in high-dimensional feature spaces due to the curse of dimensionality. We overcome this by introducing a robust Min Distance metric that exploits the raw geometric isolation of botnet activation attacks. This approach yields a state-of-the-art AUROC of 0.9951 on the BETH test set, outperforming the original Isolation Forest baseline by 17.1%. By combining near-perfect OoD detection with the intrinsic interpretability of fuzzy logic, our framework offers a viable path toward robust, transparent, and autonomous network defense.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false
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