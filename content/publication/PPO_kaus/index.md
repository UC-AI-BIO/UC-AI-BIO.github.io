---
title: 'On-Policy Optimization of ANFIS Policies Using Proximal Policy Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kaaustaaub Shankar
  - wilhelm
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-06-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-paper']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the North American Fuzzy Information Processing Society, 2025"
publication_short: "NAFIPS"

abstract: |
    We present a reinforcement learning method for training neuro-fuzzy controllers using Proximal Policy Optimization (PPO). Unlike prior approaches that used Deep Q-Networks (DQN) with Adaptive Neuro-Fuzzy Inference Systems (ANFIS), our PPO-based framework leverages a stable on-policy actor-critic setup. Evaluated on the CartPole-v1 environment across multiple seeds, PPO-trained fuzzy agents consistently achieved the maximum return of 500 with zero variance after 20000 updates, outperforming ANFIS-DQN baselines in both stability and convergence speed. This highlights PPO's potential for training explainable neuro-fuzzy agents in reinforcement learning tasks.


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2507.01039v2'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---