+++
abstract = "We design a novel 'folded' spherical catadioptric rig (formed by two coaxially-aligned spherical mirrors of distinct radii and a single perspective camera) to recover near-spherical range panoramas (about $360^o$ x $153^o$) from the fusion of depth given by optical flow and stereoscopy. We observe that for rigid motion that is parallel to a plane, optical flow and stereo generate nearly complementary distributions of depth resolution. While optical flow provides strong depth cues in the periphery and near the poles of the view-sphere, stereo generates reliable depth in a narrow band about the equator instead. We exploit this dual-modality principle by modeling (separately) the depth resolution of optical flow and stereo in order to fuse them later on a probabilistic spherical panorama. We achieve a desired vertical field-of-view and optical resolution by deriving a linearized model of the rig in terms of three parameters (radii of the two mirrors plus axial distance between the mirrors' centers). We analyze the error due to the violation of the single viewpoint constraint and formulate additional constraints on the design to minimize this error. We evaluate our proposed method via a synthetic model and with real-world prototypes by computing dense spherical panoramas of depth from cluttered indoor environments after fusing the two modalities (stereo and optical flow)."
abstract_short = "We design a novel 'folded' spherical catadioptric rig (formed by two coaxially-aligned spherical mirrors of distinct radii and a single perspective camera) to recover near-spherical range panoramas."
authors = ["Igor Labutov", "[Carlos Jaramillo](http://me.vision2pi.com)", "Jizhong Xiao"]
date = "2011-05-09"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Conference on Robotics and Automation (ICRA)*, IEEE."
publication_short = "In *ICRA*"
selected = false
title = "Fusing Optical Flow and Stereo in a Spherical Depth Panorama Using a Single-Camera Folded Catadioptric Rig"
#url_code = "https://github.com/ccny-ros-pkg/mav_tools"
#url_dataset = "#"
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_pdf = "https://ubuntuslave.github.io/files/others/Labutov-ICRA2011.pdf"
#url_project = ""
#url_slides = "#"
#url_video = "https://youtu.be/v5Jq6SVClpY"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/spherical_rig-geometric_model.png"
caption = "Single-camera Spherical Catadioptric Geometric Model"

+++