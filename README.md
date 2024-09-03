# Cartoonise-Video
Project to cartoonise any video with Image processing and Machine Learning</br>
<h3>Approaches used :</h3>
<h4>1.Using OpenCV image processing capabilities.</h4></br>
The cartoonise.py file contains the code for simple cartoonising the iamge with the use of Bilateral Filtering and edge detection 
using the openCV. Here first the image's edge are detected and then bilateral filter are applied to it for its smoothening.
Finally both the images are merged into one by taking the inverse Binary mask of the edges.</br>
<h4>2.Using the K-Means Clustering Algorithm from Machine Learning</h4></br>
The Cartoonise_Kmeans.py file contains the code for this implementation. In this approach the iamge is flattened to an array then
it is put to the kmeans algorithm from which centres are found and finally these centres are used to segregate the different color 
regions in the image. This technique is basically used for Colour reduction in image processing .</br>
<h5>System Requirements: Python 3 , OpenCV, Numpy installed.</br>

