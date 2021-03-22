# Create-Panorama-using-OpenCV
Creating a panoramic view using 2 pictures which diides the rigion into different parts

# For creating a panorama, we need to go through certain steps as follows :
• Keypoint detection
• Local invariant descriptors using SIFT/SURF
• Feature matching to match the feature points detected in the 2 images
• Homography estimation using RANSAC
• Perspective warping

References : [https://towardsdatascience.com/image-panorama-stitching-with-opencv-2402bde6b46c]