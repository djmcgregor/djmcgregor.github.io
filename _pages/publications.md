---
layout: single
classes: wide
permalink: /publications/
title: ""
excerpt: "publications and presentations"
last_modified_at: 2025-01-29T08:41:35-04:00
# ASME papers: can post on website 12 months after. https://www.asme.org/publications-submissions/journals/information-for-authors/open-access
# SPIE papers: only via email. https://www.spiedigitallibrary.org/article-sharing-policies
# Elsevier: only via email. Accepted version can be posted on personal website immediately and on repositories after embargo (typically 24 months). preprint anywhere / anytime. https://service.elsevier.com/app/answers/detail/a_id/35715/supporthub/publishing/
# Springer: accepted version after embargo. Use SharedIt link for free access! https://www.springernature.com/gp/authors/how-to-share

am-opt:
  image_path: /assets/images/publications/2024-idetc-paper.png
  alt: heat exchanger for optimization problem
  title: 15. Multi-objective surrogate optimization of process parameters for additive manufacturing with applications in laser powder bed fusion
  journal: 'Proc. ASME IDETC-CIE: Vol. 3A'
  date: November 2024
  abstract: We propose an optimization-based approach for selecting additive manufacturing (AM) process parameters for high quality parts made using laser powder bed fusion (LPBF). By optimizing three process parameters (layer thickness, laser power, and scanning speed), we achieved 17% better geometric accuracy while meeting porosity requirements. Our results reveal that laser power is the most influential parameter affecting both geometric accuracy and porosity.
  # press: Test
  # press_url: https://www.google.com
  # press_2: Test
  # press_url_2: https://www.google.com
  doi: 10.1115/DETC2024-143279
  url: https://doi.org/10.1115/DETC2024-143279
  journal_img: /assets/images/publications/cover_idetc_cie.jpg
  access: none
  # pdf:
detect-defects2:
  image_path: /assets/images/publications/2024-nozzle-defect-paper2.jpg
  alt: additively manufactured nozzle with defect
  title: 14. Automatic detection of hidden defects and qualification of additively manufactured parts using X-ray computed tomography and computer vision
  journal: Manufacturing Letters
  date: October 2024
  abstract: We train machine learning models to identify geometric defects in x-ray computed tomography (CT) scans of additively manufactured (AM) parts. We manufactured 155 nozzle parts, some with various intentional defects, and CT scanned each part. A ResNet34 model successfully identified 98% of defects after training on as few as 30 parts, demonstrating the promise of machine learning to identify AM defects in CT scan data.
  doi: 10.1016/j.mfglet.2024.09.147
  url: https://doi.org/10.1016/j.mfglet.2024.09.147
  journal_img: /assets/images/publications/cover_mfg_letters.jpg
  access: open
fed-learning:
  image_path: /assets/images/publications/2024-federated-learning-paper.png
  alt: federated training strategy
  title: 13. Federated learning enables privacy-preserving and data-efficient dimension prediction and part qualification across additive manufacturing factories
  journal: Journal of Manufacturing Systems
  date: June 2024
  abstract: We use federated learning (FL) to predict additively manufactured part dimensions and qualify parts while preserving data privacy. We develop machine learning models using private data from distributed sources, allowing for collaborative model training without compromising privacy. When tested on 405 manufactured parts from multiple factories, FL models outperform individual learning by up to 96%.
  doi: 10.1016/j.jmsy.2024.04.031
  url: https://doi.org/10.1016/j.jmsy.2024.04.031
  journal_img: /assets/images/publications/cover_j_mfg_systems.jpg
  access: open
detect-defects:
  image_path: /assets/images/publications/2024-nozzle-defect-paper.png
  alt: vision transformer architecture for defect classification
  title: 12. Detecting and classifying hidden defects in additively manufactured parts using deep learning and X-ray computed tomography
  journal: Journal of Intelligent Manufacturing
  date: May 2024
  abstract: We train a Vision Transformer (ViT) using computer-generated images of defects and successfully identify real defects in x-ray computed tomography scans of real additively manufactured parts. We demonstrate this work using a data set of 227 parts, some having intentional defects. The ViT model trained on over 50,000 images and achieved over 90% testing accuracy, demonstrating the potential of synthetic data to train ML models for defect detection.
  press: AZO-materials
  press_url: https://www.azom.com/news.aspx?newsID=63140
  press_2: NovusLight
  press_url_2: https://www.novuslight.com/machine-learning-helps-detect-defects-in-additive-manufacturing_N13224.html#atop
  doi: 10.1007/s10845-024-02416-0
  url: https://doi.org/10.1007/s10845-024-02416-0
  journal_img: /assets/images/publications/cover_j_intelligent_mfg.jpg
  access: none
hto:
  image_path: /assets/images/publications/2024-hto-paper.jpg
  alt: additively manufactured patient specific medical devices
  title: 11. Geometry repeatability and prediction for personalized medical devices made using multi-jet fusion additive manufacturing
  journal: Additive Manufacturing Letters
  date: April 2024
  abstract: This research studies the repeatability of an additively manufactured guide for knee surgery that is personalized to the size and shape of a patient and explores concepts for predicting geometric accuracy. We created 258 unique surgical guide designs with different sizes of the critical features to simulate practical conditions, and manufactured 2100 parts using multi-jet fusion AM.
  doi: 10.1016/j.addlet.2024.100200
  url: https://doi.org/10.1016/j.addlet.2024.100200
  journal_img: /assets/images/publications/cover_am_letters.jpg
  access: open
ml-svr:
  image_path: /assets/images/publications/ml_clip.jpg
  alt: additively manufactured clip
  title: 10. Using machine learning to predict dimensions and qualify diverse part designs across multiple additive machines and materials
  journal: Additive Manufacturing
  date: July 2022
  abstract: We developed a data model that describes additive part design information and manufacturing process information using both continuous and categorical variables. A support vector regression (SVR) machine learning model is trained using this data to predict part geometry to within 53 microns. The model is extended to classify the parts as either acceptable or unacceptable with 81% accuracy.
  press: nanoHub 
  press_url: https://nanohub.org/resources/svr
  doi: 10.1016/j.addma.2022.102848
  url: https://doi.org/10.1016/j.addma.2022.102848
  journal_img: /assets/images/publications/cover_addit_manuf_2021.jpg
  access: none
ct-nozzle:
  image_path: /assets/images/publications/ct_nozzle.jpg
  alt: cutaway view of additive nozzle with internal features
  title: 9. Large batch metrology on internal features of additively manufactured parts using X-ray computed tomography
  journal: Journal of Materials Processing Technology
  date: April 2022
  abstract: This study presents an automated method for batch X-ray computed tomography (CT) metrology using open-source software, and investigates 48 nozzle parts made using various additive manufacturing materials and processes. We find that external feature accuracy is not highly correlated with internal feature accuracy. Additionally, part-to-part repeatability for a given material and process is very good.
  doi: 10.1016/j.jmatprotec.2022.117605
  url: https://doi.org/10.1016/j.jmatprotec.2022.117605
  journal_img: /assets/images/publications/cover_jmpt.jpg
  access: none
hblm:
  image_path: /assets/images/publications/thick_hist_by_printer.jpg
  alt: histogram of thickness by printer
  title: 8. Hierarchical data models improve the accuracy of feature level predictions for additively manufactured parts
  journal: Additive Manufacturing
  date: January 2022
  abstract: A Hierarchical Bayesian Linear Model (HBLM) models the effects of multiple additive manufacturing production factors on part geometry. Gaussian process (GP) captures the feature-level spatial variation that can be unique to each part. Together, these models predict part geometry to within 10 microns. 
  doi: 10.1016/j.addma.2022.102621
  url: https://doi.org/10.1016/j.addma.2022.102621
  journal_img: /assets/images/publications/cover_addit_manuf_2021.jpg
  access: none
gaf-hx:
  image_path: /assets/images/publications/joule_gaf_hx.png
  alt: genetic algorithm heat exchanger
  title: 7. Ultra-power-dense heat exchanger development through genetic algorithm design and additive manufacturing
  journal: Joule
  date: September 2021
  abstract: We show design automation and additive manufacturing that can achieve high heat transfer with complex 3D structures internal to the heat exchanger that cannot be made with conventional methods. The resulting device achieves a power density and specific power significantly higher than that of most conventional heat exchangers. 
  press: ASME
  press_url: https://www.asme.org/topics-resources/content/rethinking-and-redesigning-heat-exchangers
  press_2: 3D-printing-industry
  press_url_2: https://3dprintingindustry.com/news/engineers-use-3d-printing-technology-to-boost-heat-exchanger-performance-by-2000-196500/
  doi: 10.1016/j.joule.2021.08.004
  url: https://doi.org/10.1016/j.joule.2021.08.004
  journal_img: /assets/images/publications/cover_joule_nov21.jpg
  access: open
tipmass:
  image_path: /assets/images/publications/fiber_resonance.jpg
  alt: resonating fiber
  title: 6. Effect of an added mass on the vibration characteristics for raster scanning of a cantilevered optical fiber
  journal: ASME J. of Medical Diagnostics
  date: May 2021
  abstract: Piezoelectric tube actuators with cantilevered optical fibers enable the miniaturization of scanning image acquisition techniques for endoscopic implementation. We explore adding a mass at an intermediate location along the length of the fiber to alter the resonant frequencies of the system and enable raster scanning. We provide a mathematical model to predict resonant frequencies for a cantilevered beam with an intermediate mass.
  doi: 10.1115/1.4050691
  url: https://doi.org/10.1115/1.4050691
  journal_img: /assets/images/publications/cover_asme_medical_diagnostics.jpg
  access: pdf
  pdf: https://umd.app.box.com/file/1381401974377
mfgvar:
  image_path: /assets/images/publications/mfg_variation.jpg
  alt: AM lattice qual
  title: 5. Analyzing part accuracy and sources of variability for additively manufactured lattice parts made on multiple printers
  journal: Additive Manufacturing
  date: April 2021
  abstract: Framework for analyzing additive manufacturing variability. Statistical modeling analyzes accuracy for hexagonal lattice parts made on multiple printers. Part accuracy varies for different printers even when all other parameters are constant. 
  press: Press Release
  press_url: https://grainger.illinois.edu/news/stories/33360
  doi: 10.1016/j.addma.2021.101924
  url: https://doi.org/10.1016/j.addma.2021.101924
  journal_img: /assets/images/publications/cover_addit_manuf.jpg
  access: open
rapidvent:
  image_path: /assets/images/publications/rapidvent_cover.jpg
  alt: rapidvent
  title: 4. Emergency ventilator for COVID-19
  journal: PLOS ONE
  date: December 2020
  abstract: In response to the need for mechanical ventilators, we designed and tested an emergency ventilator (EV) that can control a patient’s peak inspiratory pressure (PIP) and breathing rate, while keeping a positive end expiratory pressure (PEEP). This article describes the rapid design, prototyping, and testing of the EV. The development process was enabled by rapid design iterations using additive manufacturing (AM). In the initial design phase, iterations between design, AM, and testing enabled a working prototype within one week.
  press: UIUC RapidVent
  press_url: https://rapidvent.grainger.illinois.edu/
  doi: 10.1371/journal.pone.0244963
  url: https://doi.org/10.1371/journal.pone.0244963
  journal_img: /assets/images/publications/cover_plos_one.jpg
  access: open
auto-scan:
  image_path: /assets/images/publications/hough_transform.jpg
  alt: Hough transfrom
  title: 3. Automated metrology and geometric analysis of additively manufactured lattice structures
  journal: Additive Manufacturing
  date: August 2019
  abstract: Conventional methods for measuring part geometry and performing quality control, which typically use a small number of low-dimensional measurements, are not well suited for the complex structures enabled by additive manufacturing (AM), such as lattice structures. This paper describes a method for scanning and automatically extracting hundreds of individual features and applies this method to characterize AM lattice structures in both two-dimensional and three-dimensional lattices.
  doi: 10.1016/j.addma.2019.05.026
  url: https://doi.org/10.1016/j.addma.2019.05.026
  journal_img: /assets/images/publications/cover_addit_manuf.jpg
  access: none
hex-crush:
  image_path: /assets/images/publications/hex_compression.jpg
  alt: AM lattice compression
  title: 2. Mechanical properties of hexagonal lattice structures fabricated using continuous liquid interface production additive manufacturing
  journal: Additive Manufacturing
  date: January 2019
  abstract: Recent advancements in AM have enabled rapid production speeds, high spatial resolution, and a variety of engineering polymers. An open question remains whether production grade additive manufacturing (AM) can accurately and repeatably produce lattice parts. This study presents design, production, and mechanical property testing of hexagonal lattice parts manufactured using continuous liquid interface production (CLIP) based AM.
  press: 3Dprint.com
  press_url: https://3dprint.com/225193/testing-properties-clip-3d-prints/
  doi: 10.1016/j.addma.2018.11.002
  url: https://doi.org/10.1016/j.addma.2018.11.002
  journal_img: /assets/images/publications/cover_addit_manuf.jpg
  access: none
tate:
  image_path: /assets/images/publications/piezo_spiral_scan.png
  alt: piezo actuated endoscope
  title: 1. Single lens system for forward-viewing navigation and scanning side-viewing optical coherence tomography
  journal: Proc. SPIE 10040, Endoscopic Microscopy XII
  date: February 2017
  abstract: The optical design for a dual modality endoscope based on piezo scanning fiber technology is presented including a novel technique to combine forward-viewing navigation and side viewing OCT. Potential applications include navigating body lumens such as the fallopian tube, biliary ducts and cardiovascular system. A custom cover plate provides a rotationally symmetric double reflection of the OCT beam to deviate and focus the OCT beam out the side of the endoscope for cross-sectional imaging of the tubal lumen.
  press: SPIE
  press_url: https://spie.org/news/spie-professional-magazine-archive/2017-october/imaging-the-cancer-cure
  doi: 10.1117/12.2271555
  url: https://doi.org/10.1117/12.2271555
  journal_img: /assets/images/publications/cover_spie10040.png
  access: none
---
# Publications

[List view](/publications-list/){: .btn .btn--info .align-right}

#### In Review
<!-- *Submitted/Revised/Accepted* -- Title of article  -->
0. Bimrose, M.V., **D.J. McGregor**, C. Wood, S. Tawfick, and W.P. King. “Additive manufacturing source identification from photographs using deep learning.” *Submitted*.
{: type="i"}

#### Published / Accepted
{% include pubbox id="am-opt" %}
{% include pubbox id="detect-defects2" %}
{% include pubbox id="fed-learning" %}
{% include pubbox id="detect-defects" %}
{% include pubbox id="hto" %}
{% include pubbox id="ml-svr" %}
{% include pubbox id="ct-nozzle" %}
{% include pubbox id="hblm" %}
{% include pubbox id="gaf-hx" %}
{% include pubbox id="tipmass" %}
{% include pubbox id="mfgvar" %}
{% include pubbox id="rapidvent" %}
{% include pubbox id="auto-scan" %}
{% include pubbox id="hex-crush" %}
{% include pubbox id="tate" %}

---
# Patents
0. King, W.P., S. Tawfick, M. Bimrose, C. Wood, and **D.J. McGregor**. [“Conformance testing of manufactured parts via neural networks.”](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12125190) *U.S. Patent No. 12125190*, 2024 Oct 22.
{: reversed="reversed"}

---
# Presentations
- Automated metrology enables additive manufacturing process insights and predictions
    - Presentation at the ASTM International Conference on Advanced Manufacturing (ICAM), Atlanta, GA, USA. October 2024.
- [Automated metrology and geometric evaluation for additive manufacturing](https://www.nationalacademies.org/event/41699_03-2024_statistical-and-data-driven-methods-for-additive-manufacturing-qualification-a-workshop)
    - Invited presentation at the National Academies' workshop on Statistical and Data-driven Methods for Additive Manufacturing Qualification, Irvine, CA, USA. March 2024.
- [Machine learning predicts additive manufacturing part quality: Tutorial on support vector regression](https://nanohub.org/resources/36374)
    - Invited presentation at nanoHUB (online). August 2022.
    - Hands on Python / Jupyter Notebook tutorial using SVR to predict the quality of AM parts
    - [YouTube recording](https://www.youtube.com/watch?v=7TskxB4-x5Y) and [Jupyter Notebook](https://nanohub.org/resources/svr)
- Large batch metrology on internal features of additively manufactured parts using X-ray computed tomography
    - Invited presentation at J. of Materials Processing Technology (online). August 2022.
- Monitoring part quality across multiple printers using automated metrology
    - Presentation at the ASTM International Conference on Additive Manufacturing, Anaheim, CA, USA (online). November 2021.
- Factory-level analysis of additively manufactured lattice structures using automated metrology
    - Presentation at the ASME International Mechanical Engineering Congress and Exposition, Portland, OR, USA (online). November 2020.
- [Mechanical properties of hexagonal lattices fabricated using continuous liquid interface production AM](https://docs.lib.purdue.edu/iutam/presentations/abstracts/50/)
    - Poster at the IUTAM Symposium Architectured Materials Mechanics, Chicago, IL, USA. September 2018.
- Mechanical design and characterization of resonant fiber-optic piezoelectric scanners
    - Poster at the AZBio Expo, Phoenix, AZ, USA. March 2017.
    - Poster at the Univ. of Arizona Biomedical Engineering Design & Builders Day, Tucson, AZ, USA. March 2017.
    - Poster at the Univ. of Arizona Student Showcase, Tucson, AZ, USA. February 2017.

---
# Contact / PDF Access
Copyrights limit what I can share on this website. If you are interested in reading one of my publications but do not have journal access, I am happy to privately share a PDF copy. Send an email with subject line "Paper Request" to davisjmcgregor{at}gmail{dot}com. Feel free to reach out for other reasons as well!

<!-- dimensions badge -->
<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
<!-- altmetric badge -->
<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>
