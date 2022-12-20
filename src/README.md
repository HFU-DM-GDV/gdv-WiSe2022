## Tutorials

### Tutorial #1
Load, resize and rotate an image. And display it to the screen.
- [empty code](./01-img-manipulation.problem.py)
- [complete code](./01-img-manipulation.solution.py)

### Tutorial #2
Direct pixel access and manipulation. Set some pixels to black, copy some part of the image to some other place, count the used colors in the image
- [empty code](./02-pixel-manipulation.problem.py)
- [complete code](./02-pixel-manipulation.solution.py)

### Tutorial #3
Show camera video and mirror it.
- [empty code](./03-video-cam.problem.py)
- [complete code](./03-video-cam.solution.py)

### Tutorial #4
Loading a video file and mirror it.
- [empty code](./04-video-file.problem.py)
- [complete code](./04-video-file.solution.py)

### Tutorial #5
Use the webcam image stream and draw something on it. Animate one of the drawings.
- [empty code](./05-webcam-draw.problem.py)
- [complete code](./05-webcam-draw.solution.py)
Note that the solution uses the "map" function. Check [this tutorial](https://www.learnpython.org/en/Map%2C_Filter%2C_Reduce) if you are not familiar with map paradigm from functional programming.

### Tutorial #6
Playing around with colors. We convert some values from RGB to HSV and then find colored objects in the image and mask them out. Includes a color picker on double-click now. The RGB version is meant to demonstrate that this does not work in RGB color space.
- [empty code](./06-rgb-to-hsv.problem.py)
- [bad code](./06-rgb-to-hsv.bad.py)
- [complete code](./06-rgb-to-hsv.solution.py)

### Tutorial #7
Counting colored objects by finding connected components in the binary image. Modify the binary image to improve the results.
- [empty code](./07-connected-components.problem.py)
- [complete code](./07-connected-components.solution.py)

### Tutorial #8
Demonstrating how to do template matching in OpenCV. 
- [empty code](./08-template-matching.problem.py)
- [complete code](./08-template-matching.solution.py)

### Tutorial #9
Demonstrating Gaussian blur filter with OpenCV. 
- [empty code](./09-blur.problem.py)
- [complete code](./09-blur.solution.py)
- [complete code with 3D plot of the kernel using matplotlib](./09-blur-3d.solution.py)
  - Note that matplotlib and PyQT5 need to be installed as described [here](https://matplotlib.org/stable/users/installing.html)

### Tutorial #10
Doing the Fourier Transform for images and back.
- [empty code](./10-fourier-transform.problem.py)
- [complete code](./10-fourier-transform.solution.py)

### Tutorial #11
Geometric transformations a.k.a. image warping.
- [empty code](./11-transformations.problem.py)
- [complete code](./11-transformations.solution.py)

### Tutorial #12
Select three points in two images and compute the appropriate affine transformation.
- [empty code](./12-affine-transformation.problem.py)
- [complete code](./12-affine-transformation.solution.py)

### Tutorial #13
Select four points in two images and compute the appropriate projective/perspective transformation.
- [empty code](./13-proj-transformation.problem.py)
- [complete code](./13-proj-transformation.solution.py)

### Tutorial #14
Compute the edges of an image with the Canny edge detection. Adjust the parameters using sliders.
- [empty code](./14-edge-detection.problem.py)
- [complete code](./14-edge-detection.solution.py)

### Tutorial #15
Compute the features of an image with the Harris corner detection. Adjust the parameters using sliders.
- [empty code](./15-feat-detection.problem.py)
- [complete code](./15-feat-detection.solution.py)

### Tutorial #16
Compute the Harris corner response image and detect isolated corners with non-maximum suppression.
- [empty code](./16-harris-corner.problem.py)
- [complete code](./16-harris-corner.solution.py)

### Tutorial #17
A demonstration of the OpenCV Simple Blob Detector. Adjust the parameters using sliders.
- [empty code](./17-blob-detector.problem.py)
- [complete code](./17-blob-detector.solution.py)

### Tutorial #18
A demonstration of SIFT Detector and Descriptor for object recognition.
- [empty code](./18-sift.problem.py)
- [complete code](./18-sift.solution.py)

### Tutorial #19
A demonstration of object detection using a pre-trained deep neural network. Heavily based on https://learnopencv.com/deep-learning-with-opencvs-dnn-module-a-definitive-guide/
- [empty code](./19-dnn-detection.problem.py)
- [complete code](./19-dnn-detection.solution.py)

### Tutorial #20
Image classification with k-nearest neighbor approach using the CIFAR-10 data. Code is similar to the one used in assignment #4 and hence a bit cluttered.
- [empty code](./20-knn-classifiction.problem.py)
- [complete code](./20-knn-classifiction.solution.py)
