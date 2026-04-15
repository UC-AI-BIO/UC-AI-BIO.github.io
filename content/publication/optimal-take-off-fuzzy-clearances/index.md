---
title: 'Optimal Take-off under Fuzzy Clearances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - hugo
  - Arthur
  - kelly

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-02-13'
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

abstract: This paper presents a hybrid obstacle avoidance architecture that integrates Optimal Control under clearance with a Fuzzy Rule Based System (FRBS) to enable adaptive constraint handling for unmanned aircraft. Motivated by the limitations of classical optimal control under uncertainty and the need for interpretable decision making in safety critical aviation systems, we design a three stage Takagi Sugeno Kang fuzzy layer that modulates constraint radii, urgency levels, and activation decisions based on regulatory separation minima and airworthiness guidelines from FAA and EASA. These fuzzy-derived clearances are then incorporated as soft constraints into an optimal control problem solved using the FALCON toolbox and IPOPT. The framework aims to reduce unnecessary recomputations by selectively activating obstacle avoidance updates while maintaining compliance with aviation procedures. A proof of concept implementation using a simplified aircraft model demonstrates that the approach can generate optimal trajectories with computation times of 2,3 seconds per iteration in a single threaded MATLAB environment, suggesting feasibility for near real time applications. However, our experiments revealed a critical software incompatibility in the latest versions of FALCON and IPOPT, in which the Lagrangian penalty term remained identically zero, preventing proper constraint enforcement. This behavior was consistent across scenarios and indicates a solver toolbox regression rather than a modeling flaw. Future work includes validating this effect by reverting to earlier software versions, optimizing the fuzzy membership functions using evolutionary methods, and extending the system to higher fidelity aircraft models and stochastic obstacle environments.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2602.13166'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---