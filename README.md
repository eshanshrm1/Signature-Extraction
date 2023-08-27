# Signature-Extraction
Signature Extraction Using OpenCV

**Summary of Code**

The code defines a Python function named extract_signatures that processes an input image to identify and extract potential signature regions. The extracted regions are stored in a list and visualized by drawing rectangles around them in the original image. This code snippet can serve as a template for building an automated signature extraction system.

**Key Steps:**

The extract_signatures function performs the following steps:

Load the input image and convert it to grayscale.
Apply Gaussian blur to reduce noise.
Perform edge detection using Canny.
Find contours in the edge-detected image.
Iterate over the contours and filter out small ones.
Extract signature regions based on the bounding rectangles of the contours.
Draw green rectangles around the extracted signature regions in the original image.
Save the modified image with rectangles drawn (for visualization).
Return the list of extracted signature regions.
