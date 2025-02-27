# Feature Descriptors
our end goal is to use match features between two different images for localization, object detection, and other perception tasks that require depth estimation to points in the environment. To do so, we need to describe features in a way that it allows for feature comparison to determine the best match between frames. We therefore assign a descriptor to every feature point in an image.

## Feature descriptor definition
Mathematically, we define a feature point by its coordinates u and v in the image frame.
We describe a descriptor f as an n dimensional vector associated with each feature.
