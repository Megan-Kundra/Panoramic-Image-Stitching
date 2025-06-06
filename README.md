# Panoramic-Image-Stitching

This is a panoramic image stitching application that accepts two overlapping images, and uses industry standard computer vision pipelines to create a seamless panoramic image. The motive behind this was to experiment with the different computer vision pipelines necessary for using an affine image stitching pipeline vs a homography image stitching pipeline while utilizing opencv\cv2 python libraries.

Specific features include:
- Affine image stitching pipeline & homography pipeline
- SIFT for keypoint detection and descriptor identification
- RANSAC implementation used to compute the affine transform used to warp and stitch the images together
- Post Processing to polish the final image product (regional blending, in paining, image sharpening, and warping adjustments)
