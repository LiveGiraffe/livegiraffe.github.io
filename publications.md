---
layout: page
title: Publications
permalink: /publications/
navigation_weight: 3
description: "Journal articles and patents"
items:
  - link: https://www.google.com/patents/US20140222012
    title: "Smart screw-driver for preventing inadvertent screw stripping in bone"
    journal : Patent, 2013
  - link: http://digitool.library.mcgill.ca/R/?func=dbin-jump-full&amp;object_id=110681
    title: "Analysis of trumpet tone quality using machine learning and audio feature selection"
    journal : Master's thesis at McGill University, 2012
  - link: http://www.mitpressjournals.org/doi/abs/10.1162/COMJ_a_00119
    title: "A high-fidelity orchestra simulator for individual musicians’ practice"
    journal : Computer Music Journal, May 2012
  - link: http://www.livegiraffe.com/papers/Knight-VisualizationFeedbackForMusicalEnsemblePractice.pdf
    title: "Visualization feedback for musical ensemble practice: A case study on phrase articulation and dynamics"
    journal : Proc. of the Visualization and Data Analysis Conf., January 2012
  - link: http://www.livegiraffe.com/papers/Knight-PotentialForAutomaticAssessmentOfTrumpetToneQuality.pdf
    title: "The potential for automatic assessment of trumpet tone quality"
    journal : Proc. of Intl. Soc. for Music Information Retrieval (ISMIR), October 2011
  - link: http://gos.sagepub.com/content/2/3/86
    title: "Inadvertent Screw Stripping During Ankle Fracture Fixation in Elderly Bone"
    journal : Geriatric Orthopaedic Surgery &amp; Rehabilitation, May 2011
  - link: http://www.ncbi.nlm.nih.gov/pubmed/20502222
    title: "Mechanical evaluation of a 4-mm cancellous \"rescue\" screw in osteoporotic cortical bone: a cadaveric study"
    journal : Journal of Orthopaedic Trauma, June 2010
  - link: http://www.ncbi.nlm.nih.gov/pubmed/20806776
    title: "Biomechanical comparison of extensile exposures in total knee arthroplasty"
    journal : Orthopedics, June 2010
  - link: http://www.ncbi.nlm.nih.gov/pubmed/20948574
    title: "Bone density and cortical thickness in normal, osteopenic, and osteoporotic sacra"
    journal : Journal of Osteoporosis, June 2009
  - link: http://www.ncbi.nlm.nih.gov/pubmed/19356360
    title: "Suture-button versus screw fixation in a syndesmosis rupture model: a biomechanical comparison."
    journal : Foot and Ankle International, April 2009
  - link: http://www.ncbi.nlm.nih.gov/pubmed/19278196
    title: "Subsidence of uncemented stems in osteoporotic and non-osteoporotic cadaveric femora"
    journal : "Proc. of Inst. Mech. E. H: Journal of Engineering in Medicine, February 2009"
  - link: http://www.ncbi.nlm.nih.gov/pubmed/18988683
    title: "Biomechanical analysis of sacroplasty: Does volume of location of cement matter?"
    journal : American Journal of Neuroradiology, February 2009
  - link: http://www.ncbi.nlm.nih.gov/pubmed/19121169
    title: "Ex vivo biomechanical comparison of the 2.4 mm uniLOCK reconstruction plate using 2.4 mm locking versus standard screws for fixation of acetabular osteotomy in dogs"
    journal : Veterinary Surgery, December 2008
  - link: http://www.ncbi.nlm.nih.gov/pubmed/18778674
    title: "Percutaneous screw configuration versus perimeter plating of calcaneus fractures: a cadaver study"
    journal : Foot &amp; Ankle International, September 2008
  - link: http://www.ncbi.nlm.nih.gov/pubmed/18670283
    title: "Biomechanical comparison of expandable and locked intramedullary femoral nails"
    journal : Journal of Orthopaedic Trauma, August 2008
  - link: http://www.ncbi.nlm.nih.gov/pubmed/18709136
    title: "Visibility of surgical site marking after preoperative skin preparation"
    journal : Eplasty, July 2008
---


{% for item in page.items %}

[{{ item.title }}]({{item.link}})<br>
{{item.journal}}

{% endfor %}