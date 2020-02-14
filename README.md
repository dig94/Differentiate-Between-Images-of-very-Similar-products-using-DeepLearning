# Differentiate-Between-Images-of-very-Similar-products-using-DeepLearning
Keypoint detection and matching between images, used a pretrained Neural network SuperPoint to match objects.
## Introduction 
This Repository contains some simple hacks like edge detection, segmentation, histogram equalization and observe the results in Matplotlib.Detect and plot different keypoints on images using LoG, DoG in Scikit Image.Performed all these tasks on images from CPG dataset here.https://www.dropbox.com/s/n8zh37udjmrydad/20150320_DM4VM_dataset.zip?dl=0
Image Matching using old school techniques. Took images from Grozi dataset http://grozi.calit2.net/grozi.html and try to match images using traditional local features. (ORB and CENSURE).
Used RANSAC to match product images and calculated accuracy of the traditional local features method.
Used pretrained neural network(Superpoint) to match local images.
## Superpoint is a research project at Magic Leap. The SuperPoint network is a fully convolutional deep neural network trained to detect interest points and compute their accompanying descriptors. The detected points and descriptors can thus be used for various image-to-image matching tasks.
