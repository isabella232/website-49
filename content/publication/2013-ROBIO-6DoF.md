+++
abstract = "We present a 6-degree-of-freedom (6-DoF) pose localization method for a monocular camera in a 3D point-cloud dense map prebuilt by depth sensors (e.g., RGB-D sensor, laser scanner, etc.). We employ fast and robust 2D feature detection on the real camera to be matched against features from a virtual view. The virtual view (color and depth images) is constructed by projecting the map's 3D points onto a plane using the previous localized pose of the real camera. 2D-to-3D point correspondences are obtained from the inherent relationship between the real camera's 2D features and their matches on the virtual depth image (projected 3D points). Thus, we can solve the Perspective-n-Point (*PnP*) problem in order to find  the relative pose between the real and virtual cameras. With the help of *RANSAC*, the projection error is minimized even further. Finally, the real camera's pose is solved with respect to the map by a simple frame transformation. This procedure repeats for each time step (except for the initial case). Our results indicate that a monocular camera alone can be localized within the map in real-time (at QVGA-resolution). Our method differentiates from others in that no chain of poses is needed or kept. Our localization is not susceptible to drift because the history of motion (odometry) is mostly independent over each *PnP + RANSAC* solution, which throws away past errors. In fact, the previous known pose only acts as a region of interest to associate 2D features on the real image with 3D points in the map. The applications of our proposed method are various, and perhaps it is a solution that has not been attempted before."
abstract_short = "A 6-degree-of-freedom (6-DoF) pose localization method for a monocular camera in a 3D point-cloud dense map prebuilt by an RGB-D sensor."
authors = ["Carlos Jaramillo", "Ivan Dryanovski", "Roberto G. Valenti", "Jizhong Xiao"]
date = "2013-12-12"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Conference on Robotics and Biomimetics (ROBIO)*, IEEE."
publication_short = "In *ROBIO*"
selected = false
title = "6-DoF Pose Localization in 3D Point-Cloud Dense Maps Using a Monocular Camera"
#url_code = "#"
#url_dataset = "#"
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_pdf = "https://ubuntuslave.github.io/files/others/Jaramillo-ROBIO2013.pdf"
#url_project = "project/gums/"
#url_slides = "#"
url_video = "https://youtu.be/0O28HHFl4VU"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "publications/ROBIO2013-digest.png"
caption = "Digest"

+++