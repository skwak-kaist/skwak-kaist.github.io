---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of my full CV is available [here]({{ base_path }}/files/Curriculum_Vitae_Sangwoon_Kwak.pdf).

Education
======
* **Ph.D. in Electrical Engineering**, KAIST, Mar. 2021 – Feb. 2026
  * Thesis: *4D Scene Reconstruction based on Dynamic 3D Gaussian Splatting using Global-to-Local Motion Decomposition*
  * Advisor: Prof. Munchurl Kim
  * GPA: 4.01 / 4.3
* **M.S. in Electrical Engineering**, KAIST, Mar. 2012 – Feb. 2014
  * Thesis: *An Extended Least Difference Greedy Clique-Cover Algorithm for Index Coding*
  * Advisor: Prof. Youngchul Sung
  * GPA: 3.98 / 4.3
* **B.S. in Electrical and Electronic Engineering**, Yonsei University, Mar. 2008 – Feb. 2012
  * National Science & Engineering Scholarship (Full tuition, 4 years)
  * GPA: 3.57 / 4.3

Research Experience
======
* **Senior Researcher**, Media Research Division, ETRI, Mar. 2014 – Present

Research Interests
======
Immersive video and computer vision applications, including:
3D/4D scene representation, novel view synthesis, video coding for machines.

Publications
======

{% for category in site.publication_category %}
  <h3>{{ category[1].title }}</h3>
  <ul>{% for post in site.publications reversed %}
    {% if post.category == category[0] %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
{% endfor %}

Awards & Honors
======
* Outstanding Paper Award, Korean Institute of Broadcast and Media Engineers (KIBME) Summer Conference, 2022
* Outstanding Paper Award, Korea Information and Communication Society (KICS) Winter Conference, 2019
* Outstanding Paper Award, International Conference on 3D Systems and Applications (3DSA), 2019
* National Science and Technology Scholarship (Four years full tuition), Ministry of Science and Technology, Korea, 2008 – 2012

Projects
======
* **Spatial Computing Technologies** (Jan. 2022 – Present)
  * Development of immersive video spatial computing technology for ultra-realistic metaverse services
  * Composition, transmission, synthesis, and rendering for immersive media streaming based on MPEG Immersive Video (MIV)
  * Funded by ICT R&D program of MSIT/IITP
* **Video Coding for Machines** (Jan. 2020 – Present)
  * Developing video coding technologies optimized for machine analysis
  * International standardization activity on MPEG Video Coding for Machines (VCM)
  * Funded by ICT R&D program of MSIT/IITP
* **Fundamental Technologies on Light Field** (Jan. 2017 – Dec. 2021)
  * Audio/Video coding and light field media fundamental technologies for ultra-realistic tera-media
  * Virtual view synthesis and rendering for 6DoF immersive media services to HMD users
  * Funded by ICT R&D program of MSIT/IITP
* **Faster-Than-Nyquist Signaling** (Jan. 2014 – Dec. 2016)
  * Development of advanced broadcasting systems based on FTN
  * FTN signaling and iterative interference cancellation to improve spectral efficiency
  * Funded by ICT R&D program of MSIT/IITP

Professional Activities
======
**International Standardization** (ISO/IEC JTC1/SC29 MPEG, 2019 – Present)

Selected MPEG contributions:
* m73774, [VCM] Modification of NNBDR decoding process
* m72245 / m72243, [VCM] Postfilter / Prefilter network for VCM
* m71305 / m71304, [VCM] Neural network based post- / pre-filter for VCM
* m69990, [VCM] Learned joint filter network for VCM
* m54409, [MPEG-I Visual] Ray-based blending weight for 6DoF view synthesis
* m48769, [MPEG-I Visual] Improved Triangle Colorization of RVS for ERP

**Invited Talks and Exhibitions**
* YouTube video, *"[Immersive 3D video without glasses](https://www.youtube.com/watch?v=uzxlxQRPT4g),"* ETRI IT Technology Report, Aug. 2025.
* Exhibition, *"Real-time 3D video synthesis and rendering spatial computing technology,"* ETRI Conference, Jun. 2025.
* Invited Talk, *"Novel view synthesis for various types of immersive displays,"* Optical Society of Korea Winter Conference, Dec. 2024.
* Invited Talk & Exhibition, *"6 Degrees-of-Freedom Immersive Media Technologies,"* ETRI Conference, May 2022.
* Exhibition, *"Real-time view synthesis and rendering for omni-directional LF videos,"* ETRI Communication and Media Technical Exhibition, Jan. 2022.
* Invited Talk, *"View synthesis and rendering for Immersive videos,"* MPEG New Media Forum Technical Workshop, Nov. 2021.
* Invited Talk, *"Novel view synthesis for omni-directional light field videos,"* ETRI Media Techday, Oct. 2020.

**Reviewer**
* IEEE Transactions on Multimedia
* IEEE Transactions on Visualization and Computer Graphics
* ACM Multimedia
* ETRI Journal

Patents
======
**Granted**
* KR 2838985, *Method and apparatus for encoding feature map*, Jul. 22, 2025.
* US 12293567, *Feature-map-encoding method and apparatus for encoding and decoding a feature map for a neural network*, May 6, 2025.
* US 12170785, *Method and apparatus for adaptive image preprocessing and reconstruction*, Dec. 17, 2024.
* US 11706395, *Apparatus and method for selecting camera providing input images to synthesize virtual view images*, Jul. 18, 2023.
* US 11528461, *Method and apparatus for generating virtual viewpoint image*, Dec. 12, 2022.

**Applications**
* US 19/170459, *Method and apparatus for encoding feature map*, Apr. 4, 2025.
* US 19/086288, *Method and device for viewport-based atlas selection*, Mar. 21, 2025.
* KR 2025-0007579, *Method and apparatus for tracking-based adaptive temporal resampling for VCM*, Jan. 17, 2025.
* KR 2025-0002494, *Method and apparatus for representing 3D dynamic scenes based on motion decomposition*, Jan. 7, 2025.
* KR 2024-0151557, *Method and device for image pre-processing filtering for VCM*, Oct. 30, 2024.
* KR 2024-0092940, *Method and device of learning based pre-processing filtering for video coding for machine*, Jul. 15, 2024.
* KR 2024-0039196, *Method and device for viewport-based atlas selection*, Mar. 21, 2024.
* KR 2023-0170135, *Method and apparatus of rate-adaptive video filtering for machines*, Nov. 29, 2023.
* US 18/514150, *Method and apparatus for non-uniform super-resolution of image*, Nov. 20, 2023.
* KR 2022-0003596, *Method and apparatus for image feature vector encoding for machine*, Jan. 10, 2022.
* KR 2022-0000334, *Method and apparatus for combining warping images based on depth distribution*, Jan. 3, 2022.
* KR 2021-0164317, *Method for adaptive pre-processing and restoring image for supporting human and machine simultaneously*, Nov. 25, 2021.

Technology Transfer
======
* *Omnidirectional Virtual View Synthesizing and Rendering System*, transferred to **Overay**, May 2024 (Contract value: 30M KRW).
* *Omnidirectional Virtual View Synthesizing and Rendering System*, transferred to **HanulSoft**, Nov. 2023 (Contract value: 30M KRW).
