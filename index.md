---
title: Home
layout: home
---

# Feature Detection Algorithms

## Harris (corner)
The most famous corner detector is the Harris Corner Detector, which uses image gradient information to identify pixels that have a strong change in intensity in both x and y directions.

### issue: the corners detected by Harris corner detectors are not scale invariant, meaning that the corners can look different depending on the distance the camera is away from the object generating the corner. 

Harris-Laplace (corner)
To remedy this problem, researchers proposed the Harris-Laplace corner detector. Harris-Laplace detectors detect corners at different scales and choose the best scale based on the Laplacian of the image.

Features from accelerated segment test (FAST) (corner)
researchers have also been able to machine learn corners. One prominent algorithm, the fast corner detector, is one of the most used feature detectors due to its very high computational efficiency and solid detection performance. 

Other scale invariant feature detectors are based on the concept of blobs such as:
Laplacian of Gaussian (LOG) detector (blob)
Difference of Gaussian (DOG) detector (blob)

Example
Here you can see corners detected by the Harris Corner Detector. The features primarily capture corners as expected, where strong illumination changes are visible. 

Here you can see Harris-Laplace features on the same image. By using the Laplacian to determine scale, we can detect scale and variant corners that can be more easily matched as a vehicle moves relative to the scene. Scale is represented here by the size of the circle around each feature. The larger the circle, the larger the principal scale of that feature.

----
see the new page at [newpage](newpage.md)
