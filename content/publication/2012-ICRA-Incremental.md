+++
abstract = "An RGB-D camera is a sensor which outputs range and color information about objects. Recent technological advances in this area have introduced affordable RGB-D devices in the robotics community. In this paper, we present a real-time technique for 6-DoF camera pose estimation through the incremental registration of RGB-D images. First, a set of edge features are computed from the depth and color images. An initial motion estimation is calculated through aligning the features. This initial guess is refined by applying the Iterative Closest Point algorithm on the dense point cloud data. A rigorous error analysis assesses several sets of RGB-D ground truth data via an error accumulation metric. We show that the proposed two-stage approach significantly reduces error in the pose estimation, compared to a state-of-the-art ICP registration technique."
abstract_short = "We present a real-time technique for 6-DoF camera pose estimation through the incremental registration of RGB-D images."
authors = ["Ivan Dryanovski", "Carlos Jaramillo", "Jizhong Xiao"]
date = "2012-05-14"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Conference on Robotics and Automation (ICRA)*, IEEE."
publication_short = "In *ICRA*"
selected = false
title = "Incremental Registration of RGB-D Images"
#url_code = "https://github.com/ccny-ros-pkg/mav_tools"
#url_dataset = "#"
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_pdf = "https://ubuntuslave.github.io/files/others/Dryanovski-ICRA2012.pdf"
#url_project = ""
#url_slides = "#"
#url_video = "https://youtu.be/v5Jq6SVClpY"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/2012-ICRA-Incremental.png"
caption = "Edge correct association on RGB-D image"

+++