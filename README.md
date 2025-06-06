# Panoramic-Image-Stitching

This is a panoramic image stitching application that accepts two overlapping images, and uses industry standard computer vision pipelines to create a seamless panoramic image. The motive behind this was to experiment with the different computer vision pipelines necessary for using an affine image stitching pipeline vs a homography image stitching pipeline while utilizing opencv\cv2 python libraries.

Specific features include:
- Affine image stitching pipeline & homography pipeline
- SIFT for keypoint detection and descriptor identification
- RANSAC implementation used to compute the affine transform used to warp and stitch the images together
- Post Processing to polish the final image product (pixle dialation, regional blending, in paining, image sharpening, and warping adjustments)



1. Example Input:
   
![image](https://github.com/user-attachments/assets/ce3b429b-37b0-431b-8b8a-8f3b25bffd2e) ![image](https://github.com/user-attachments/assets/3d3eb324-b205-45d4-b09d-3db5d86c2c35)


3. Anchor & keypoint detection (RANSAC):
   


4. Stitched Image:

![image](https://github.com/user-attachments/assets/ee0871cf-feb4-4e5c-806a-590a9fdc02a0)


5. Inpainting & post processing (Final Output):

![image](https://github.com/user-attachments/assets/ee0871cf-feb4-4e5c-806a-590a9fdc02a0)


6. Additional performance & accuracy figures:

![image](https://github.com/user-attachments/assets/bcc68909-dd00-4bc3-a511-04c92301b3bb)
