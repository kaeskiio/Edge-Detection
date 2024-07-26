# Edge Detection 

This project explores multiple sophisticated edge detection methodologies, each with unique attributes and advantages:

## **Sobel Operator**

The Sobel operator is a discrete differentiation operator that computes the gradient of the image intensity function. It emphasizes regions of high spatial frequency that correspond to edges. By calculating the gradient in both the horizontal (x) and vertical (y) directions, the Sobel operator provides a comprehensive edge detection mechanism.

## **Canny Edge Detector**

The Canny edge detection algorithm is renowned for its robustness and precision. It is a multi-stage process involving:

1. **Noise Reduction**: Applying a Gaussian filter to smooth the image and reduce noise.
2. **Gradient Calculation**: Computing the intensity gradient of the image.
3. **Non-Maximum Suppression**: Thinning the edges to create a binary image that highlights the strongest edge responses.
4. **Double Thresholding**: Using two threshold values to detect strong and weak edges.
5. **Edge Tracking by Hysteresis**: Finalizing the edge detection by suppressing all weak edges that are not connected to strong edges.

## **Displaying Results**

The results of the edge detection are visualized using Matplotlib, enabling a clear and intuitive comparison of the different methodologies.
