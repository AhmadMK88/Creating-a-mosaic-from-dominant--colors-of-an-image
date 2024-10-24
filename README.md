# Image Mosaic Creation Using K-Means

This project leverages K-Means clustering to create a mosaic from the dominant colors of an image. The process involves extracting key color clusters from the image and replacing the original pixels with the corresponding dominant color, resulting in a simplified, artistic representation of the original image.

## How It Works

- **K-Means Clustering**: The algorithm groups pixels of similar colors into clusters and identifies the most dominant colors in the image.
- **Image Mosaic**: These dominant colors are then used to reconstruct the image in a mosaic style, where each section of the image is represented by one of the dominant colors.

## How to Use

1. Add your image to the project directory.
2. Use OpenCV to load your image by writing:
   ```python
   img = cv.imread("image_name")
3. Run the script to process the image and generate the mosaic.

## Requirements
Make sure you have the following modules installed on your machine:
- numpy
- scipy
- sklearn
- opencv
