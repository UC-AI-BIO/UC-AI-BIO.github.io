---
title: 'Detecting Jailbreak Attempts in Clinical Training LLMs Through Automated Linguistic Feature Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - tri
  - Huy Hoang Bao Le
  - lohith
  - Laurah Turner
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-02-10'
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

abstract: Detecting jailbreak attempts in clinical training large language models (LLMs) requires accurate modeling of linguistic deviations that signal unsafe or off-task user behavior. Prior work on the 2-Sigma clinical simulation platform showed that manually annotated linguistic features could support jailbreak detection. However, reliance on manual annotation limited both scalability and expressiveness. In this study, we extend this framework by using experts' annotations of four core linguistic features (Professionalism, Medical Relevance, Ethical Behavior, and Contextual Distraction) and training multiple general-domain and medical-domain BERT-based LLM models to predict these features directly from text. The most reliable feature regressor for each dimension was selected and used as the feature extractor in a second layer of classifiers. We evaluate a suite of predictive models, including tree-based, linear, probabilistic, and ensemble methods, to determine jailbreak likelihood from the extracted features. Across cross-validation and held-out evaluations, the system achieves strong overall performance, indicating that LLM-derived linguistic features provide an effective basis for automated jailbreak detection. Error analysis further highlights key limitations in current annotations and feature representations, pointing toward future improvements such as richer annotation schemes, finer-grained feature extraction, and methods that capture the evolving risk of jailbreak behavior over the course of a dialogue. This work demonstrates a scalable and interpretable approach for detecting jailbreak behavior in safety-critical clinical dialogue systems.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2602.13321'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---