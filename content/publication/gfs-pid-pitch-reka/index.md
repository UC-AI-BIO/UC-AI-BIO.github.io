---
title: 'Genetic Fuzzy System–Tuned PID Controller for Pitch Attitude Hold of a Fighter Aircraft'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Reka Patel
  - wilhelm
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
    Modern fly-by-wire aircraft and unmanned aerial vehicles increasingly rely on advanced control strategies to ensure performance, robustness, and safety under nominal and degraded operating conditions. Fuzzy logic controllers have demonstrated strong robustness and fast convergence compared to conventional linear and PID-based approaches; however, their performance is highly dependent on manual tuning of membership functions and rule bases. This paper presents a Genetic Fuzzy System (GFS) approach for optimizing a fuzzy PID pitch attitude hold controller for an F-4 fighter aircraft model. A genetic algorithm is employed to automatically tune the membership functions and rule parameters of a Takagi–Sugeno–Kang fuzzy inference system, with the objective of minimizing settling time while preserving stability and robustness. The proposed GFS-PID controller is trained on a nominal approach condition and evaluated on both nominal and 50% degraded aircraft dynamics to assess generalization and robustness under uncertainty. Simulation results demonstrate that the GA-optimized fuzzy PID controller achieves significant reductions in settling time and rise time compared to a manually tuned fuzzy PID controller, without increasing
    overshoot or degrading steady-state performance. In the degraded approach case, the proposed method yields a settling time reduction of up to 25.5%, highlighting its effectiveness in noisy and uncertain environments. These results indicate that genetic optimization provides a systematic and reliable framework for enhancing fuzzy flight control systems and supports the use of Genetic Fuzzy Systems for robust autonomous aircraft control applications.

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