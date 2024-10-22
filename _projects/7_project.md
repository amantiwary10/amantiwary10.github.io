---
layout: page
title: Pointcloud Occlusion Culling
description: Point visibility determination from a given viewpoint
img: assets/img/proj_7/proj_7_background.png
importance: 4
category: Research
---

A C++ implementation of [Direct Visibility of Point Sets](https://www.weizmann.ac.il/math/ronen/sites/math.ronen/files/uploads/katz_tal_basri_-_direct_visibility_of_point_sets.pdf) by Katz et al. The animation below shows the input point cloud (white points) on the left, and on the right, the output after occlusion culling, displaying the visible points (red points) from different viewpoints.

<div class="row mt-3">
    <div class="col mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_7/pointcloud_occlusion_culling.mp4" class="img-fluid rounded z-depth-1 custom-dimensions" controls=true autoplay=true %}
    </div>
</div>