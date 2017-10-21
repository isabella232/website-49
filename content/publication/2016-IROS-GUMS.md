+++
abstract = "This paper introduces GUMS, a complete projection model for omnidirectional stereo vision systems. GUMS is based on the existing generalized unified model (GUM), which we extend in order to satisfy a tight relationship among a pair of omnidirectional views for fixed baseline sensors. We exemplify the proposed model's calibration via a single-camera coaxial omnistereo system in a joint bundle-adjusted fashion. We compare our *coupled* method against the naive approach where the calibration of intrinsic parameters is first performed individually for each omnidirectional view using existing monocular implementations, to then solve for the extrinsic parameters as an additional step that has no effect on the intrinsic model solutions initially computed. We validate GUMS and its calibration effectiveness using both real and synthetic systems against ground-truth data. Our calibration method proves successful for correcting the unavoidable misalignment present in vertically-configured catadioptric rigs. We also generate 3D point clouds employing the calibrated GUMS systems in order to demonstrate the qualitative outcome of our contribution."
abstract_short = "GUMS is a complete projection model for omnidirectional stereo vision systems. GUMS is based on the existing generalized unified model (GUM), which we extend for fixed baseline sensors."
authors = ["Carlos Jaramillo", "Roberto G. Valenti", "Jizhong Xiao"]
date = "2016-10-09"
image_preview = "publications/gums-coaxially_constrained-50.png"
math = true
publication_types = ["1"]
publication = "In *International Conference on Intelligent Robots and Systems (IROS)*, IEEE."
publication_short = "In *IROS*"
selected = true
title = "GUMS: A Generalized Unified Model for Stereo Omnidirectional Vision"
#url_code = "#"
#url_dataset = "#"
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_pdf = "https://ubuntuslave.github.io/files/GUMS/GUMS-IROS2016.pdf"
#url_project = "project/gums/"
#url_slides = "#"
url_video = "https://youtu.be/8c7fTHMSUFM"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/gums-coaxially_constrained.png"
caption = "GUMS"

+++