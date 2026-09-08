---
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |
        <style>
          #homeCarousel .carousel-item img { height: 350px !important; object-fit: cover !important; cursor: pointer; border-radius: 8px; }
          #homeCarousel .carousel-control-prev, #homeCarousel .carousel-control-next { position: absolute !important; top: 40% !important; transform: translateY(-50%) !important; bottom: auto !important; }
          .modal-backdrop.show { opacity: 0.9 !important; }
          #modalCarousel .carousel-item img { max-height: 85vh !important; object-fit: contain !important; margin: 0 auto; width: auto; }
          #imageModal .close { position: fixed; top: 25px; right: 35px; z-index: 1060; color: white; font-size: 3rem; opacity: 0.8; text-shadow: none; cursor: pointer; outline: none; border: none; background: transparent; }
          #imageModal .close:hover { opacity: 1; color: white; }
          #imageModal .modal-content { background: transparent; border: none; box-shadow: none; }
          #homeCarousel .carousel-indicators, #modalCarousel .carousel-indicators { position: relative; margin-top: 1.5rem; margin-bottom: 0; }
          #homeCarousel .carousel-indicators li, #modalCarousel .carousel-indicators li { background-color: #bbb; width: 30px; height: 4px; margin: 0 4px; border: none; opacity: 1; }
          #homeCarousel .carousel-indicators .active, #modalCarousel .carousel-indicators .active { background-color: #555; }
        </style>
        <h2 style="text-align: center; font-weight: 400; margin-bottom: 2.5rem; font-size: 2.5rem; color: #333;">AI Bio Lab @ University of Cincinnati</h2>
        <div class="row align-items-start">
          <div class="col-md-6 mb-4 mb-md-0" style="font-size: 1.0rem; line-height: 1.6; padding-right: 2rem;">
            <p style="margin-top: 0;">The AI Bio Lab at the University of Cincinnati, led by Professor Kelly Cohen, is internationally recognized as a pioneer in fuzzy-logic-based, explainable, and trustworthy artificial intelligence. For over three decades, Professor Cohen and his students' research has advanced certifiable AI architectures designed for safety-critical systems, including advanced air mobility, aerospace autonomy, transportation infrastructure, personalized medicine, and human–AI teaming.</p>
            <p>The lab’s mission is uncompromising: <b>AI that is transparent, auditably safe, and operationally trustworthy from the ground up.</b></p>
          </div>
          <div class="col-md-6 mb-4 mb-md-0 position-relative">
            <div id="homeCarousel" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner" style="border-radius: 8px;">
                <div class="carousel-item active">
                  <img src="/images/ksfuaward.jpeg" class="d-block w-100 modal-trigger" alt="Dr. Kelly Cohen wins the K.S. Fu Award at NAFIPS 2026!" data-toggle="modal" data-target="#imageModal" data-slide-to="0" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;"> Dr. Kelly Cohen wins the K.S. Fu Award at NAFIPS 2026!</div>
                </div>
                <div class="carousel-item">
                  <img src="/images/team_rooftop.jpeg" class="d-block w-100 modal-trigger" alt="Our team on the rooftop at El Paso, Texas." data-toggle="modal" data-target="#imageModal" data-slide-to="1" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;">Our team on the rooftop at El Paso, Texas.</div>
                </div>
                <div class="carousel-item">
                  <img src="/images/parallax.jpeg" class="d-block w-100 modal-trigger" alt="AI Bio Lab + Parallax Advanced Research" data-toggle="modal" data-target="#imageModal" data-slide-to="2" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;">AI Bio Lab + Parallax Advanced Research</div>
                </div>
                <div class="carousel-item">
                  <img src="/images/honors.jpeg" class="d-block w-100 modal-trigger" alt="Honors Students visit to the AI Bio Lab" data-toggle="modal" data-target="#imageModal" data-slide-to="3" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;">Honors Students visit to the AI Bio Lab</div>
                </div>
                <div class="carousel-item">
                  <img src="/images/symposium.jpeg" class="d-block w-100 modal-trigger" alt="Dr. Kelly Cohen moderating a panel at the AI Symposium in University of Cincinnati" data-toggle="modal" data-target="#imageModal" data-slide-to="4" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;">Dr. Kelly Cohen moderating a panel at the AI Symposium in University of Cincinnati</div>
                </div>
                <div class="carousel-item">
                  <img src="/images/banff.jpeg" class="d-block w-100 modal-trigger" alt="Awards galore at NAFIPS 2025 in Banff, Canada!" data-toggle="modal" data-target="#imageModal" data-slide-to="5" style="cursor: pointer; height: 350px; object-fit: cover;">
                  <div class="text-center mt-3 text-muted" style="font-size: 0.9rem;">Awards galore at NAFIPS 2025 in Banff, Canada!</div>
                </div>
              </div>
              <a class="carousel-control-prev" href="#homeCarousel" role="button" data-slide="prev" style="position: absolute; top: 40%; transform: translateY(-50%); left: 0; border: none; background: transparent; padding: 1rem; text-decoration: none;">
                <span class="carousel-control-prev-icon" aria-hidden="true" style="font-size: 2.5rem; background-image: none; color: white; display: block; text-shadow: 0 2px 4px rgba(0,0,0,0.8);">&#10094;</span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#homeCarousel" role="button" data-slide="next" style="position: absolute; top: 40%; transform: translateY(-50%); right: 0; border: none; background: transparent; padding: 1rem; text-decoration: none;">
                <span class="carousel-control-next-icon" aria-hidden="true" style="font-size: 2.5rem; background-image: none; color: white; display: block; text-shadow: 0 2px 4px rgba(0,0,0,0.8);">&#10095;</span>
                <span class="sr-only">Next</span>
              </a>
              <ol class="carousel-indicators">
                <li data-target="#homeCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#homeCarousel" data-slide-to="1"></li>
                <li data-target="#homeCarousel" data-slide-to="2"></li>
                <li data-target="#homeCarousel" data-slide-to="3"></li>
                <li data-target="#homeCarousel" data-slide-to="4"></li>
                <li data-target="#homeCarousel" data-slide-to="5"></li>
              </ol>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['3rem', '0', '3rem', '0']

  - block: markdown
    content:
      title: ""
      text: |
        <div class="modal fade" id="imageModal" tabindex="-1" role="dialog" aria-labelledby="imageModalLabel" aria-hidden="true">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
          <div class="modal-dialog modal-xl modal-dialog-centered" role="document">
            <div class="modal-content">
              <div class="modal-body p-0 position-relative">
                <div id="modalCarousel" class="carousel slide" data-ride="false">
                  <div class="carousel-inner" style="border-radius: 8px; overflow: hidden;">
                    <div class="carousel-item active">
                      <img src="/images/ksfuaward.jpeg" class="d-block w-100" alt="Dr. Kelly Cohen wins the K.S. Fu Award at NAFIPS 2026!">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">Dr. Kelly Cohen wins the K.S. Fu Award at NAFIPS 2026!</div>
                    </div>
                    <div class="carousel-item">
                      <img src="/images/team_rooftop.jpeg" class="d-block w-100" alt="Our team on the rooftop at El Paso, Texas.">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">Our team on the rooftop at El Paso, Texas.</div>
                    </div>
                    <div class="carousel-item">
                      <img src="/images/parallax.jpeg" class="d-block w-100" alt="AI Bio Lab + Parallax Advanced Research">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">AI Bio Lab + Parallax Advanced Research</div>
                    </div>
                    <div class="carousel-item">
                      <img src="/images/honors.jpeg" class="d-block w-100" alt="Honors Students visit to the AI Bio Lab">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">Honors Students visit to the AI Bio Lab</div>
                    </div>
                    <div class="carousel-item">
                      <img src="/images/symposium.jpeg" class="d-block w-100" alt="Dr. Kelly Cohen moderating a panel at the AI Symposium in University of Cincinnati">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">Dr. Kelly Cohen moderating a panel at the AI Symposium in University of Cincinnati</div>
                    </div>
                    <div class="carousel-item">
                      <img src="/images/banff.jpeg" class="d-block w-100" alt="Awards galore at NAFIPS 2025 in Banff, Canada!">
                      <div class="text-center mt-3 text-white p-2" style="font-size: 1rem; text-shadow: 0 1px 3px rgba(0,0,0,0.8);">Awards galore at NAFIPS 2025 in Banff, Canada!</div>
                    </div>
                  </div>
                  <a class="carousel-control-prev" href="#modalCarousel" role="button" data-slide="prev" style="position: absolute; top: 50%; transform: translateY(-50%); left: 0; border: none; background: transparent; padding: 1rem; text-decoration: none;">
                    <span class="carousel-control-prev-icon" aria-hidden="true" style="font-size: 3rem; background-image: none; color: white; display: block; text-shadow: 0 2px 4px rgba(0,0,0,0.8);">&#10094;</span>
                    <span class="sr-only">Previous</span>
                  </a>
                  <a class="carousel-control-next" href="#modalCarousel" role="button" data-slide="next" style="position: absolute; top: 50%; transform: translateY(-50%); right: 0; border: none; background: transparent; padding: 1rem; text-decoration: none;">
                    <span class="carousel-control-next-icon" aria-hidden="true" style="font-size: 3rem; background-image: none; color: white; display: block; text-shadow: 0 2px 4px rgba(0,0,0,0.8);">&#10095;</span>
                    <span class="sr-only">Next</span>
                  </a>
                  <ol class="carousel-indicators">
                    <li data-target="#modalCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#modalCarousel" data-slide-to="1"></li>
                    <li data-target="#modalCarousel" data-slide-to="2"></li>
                    <li data-target="#modalCarousel" data-slide-to="3"></li>
                    <li data-target="#modalCarousel" data-slide-to="4"></li>
                    <li data-target="#modalCarousel" data-slide-to="5"></li>
                  </ol>
                </div>
              </div>
            </div>
          </div>
        </div>
        <script>
          document.addEventListener('DOMContentLoaded', function() {
            document.body.appendChild(document.getElementById('imageModal'));
            var allTriggers = document.querySelectorAll('.modal-trigger');
            allTriggers.forEach(function(trigger) {
              trigger.addEventListener('click', function() {
                var slideIndex = this.getAttribute('data-slide-to');
                if (window.jQuery) {
                  $('#modalCarousel').carousel(parseInt(slideIndex));
                }
              });
            });
          });
        </script>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '3rem', '0']
  
  - block: collection
    id: news
    content:
      title: 'Recent News'
      subtitle:
      text:
      count: 5
      filters:
        folders:
          - post
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |
        [See all news →](/post/)
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '3rem', '0']

---
