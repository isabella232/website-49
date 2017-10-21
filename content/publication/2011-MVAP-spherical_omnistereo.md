+++
abstract = "We design a novel 'folded' spherical catadioptric rig (formed by two coaxially-aligned spherical mirrors of distinct radii and a single perspective camera) to recover near-spherical range panoramas (about $360^o$ x $153^o$) from the fusion of depth given by optical flow and stereoscopy. We observe that for rigid motion that is parallel to a plane, optical flow and stereo generate nearly complementary distributions of depth resolution. While optical flow provides strong depth cues in the periphery and near the poles of the view-sphere, stereo generates reliable depth in a narrow band about the equator instead. We exploit this dual-modality principle by modeling (separately) the depth resolution of optical flow and stereo in order to fuse them later on a probabilistic spherical panorama. We achieve a desired vertical field-of-view and optical resolution by deriving a linearized model of the rig in terms of three parameters (radii of the two mirrors plus axial distance between the mirrors' centers). We analyze the error due to the violation of the single viewpoint constraint and formulate additional constraints on the design to minimize this error. We evaluate our proposed method via a synthetic model and with real-world prototypes by computing dense spherical panoramas of depth from cluttered indoor environments after fusing the two modalities (stereo and optical flow)."
abstract_short = "We design a novel 'folded' spherical catadioptric rig (formed by two coaxially-aligned spherical mirrors of distinct radii and a single perspective camera) to recover near-spherical range panoramas."
authors = ["Igor Labutov", "Carlos Jaramillo", "Jizhong Xiao"]
date = "2011-09-17"
image_preview = "publications/spherical_rig-geometric_model.png"
math = true
publication_types = ["2"]
publication = "In *Machine Vision and Applications*, Springer"
publication_short = "In *MVAP*"
selected = true
title = "Generating near-spherical range panoramas by fusing optical flow and stereo from a single-camera folded catadioptric rig"
#url_code = "https://github.com/ubuntuslave/omnistereo_sensor_design"
#url_dataset = "#"
url_pdf = "https://link.springer.com/article/10.1007%2Fs00138-011-0368-2"
#url_project = "project/omnistereo_sensor/"
#url_slides = "#"
#url_video = "https://youtu.be/8c7fTHMSUFM"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/spherical_rig-prototypes.png"
caption = "Single-camera Catadioptric Spherical Prototypes"

+++