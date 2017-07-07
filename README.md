# deep-face-tutorial

This repository hosts the IPython notebooks for the "Deep Faces" tutorial that was presented in the
[Summer School on Computer Vision](http://cvit.iiit.ac.in/cvsummerschool2017/) (SSCV 2017) at 
[CVIT](http://cvit.iiit.ac.in/), [IIIT Hyderabad](https://www.iiit.ac.in/). 
All implementations are in [PyTorch](http://pytorch.org/).

### Contents
In this lab session, we take a look at the applications of Deep Learning in the specific and
very important domain of face images. Here are some details of the topics that are covered -

1. **Basics** [[1-FaceRecognition](https://github.com/samyak-268/deep-face-tutorial/blob/master/1-FaceRecognition.ipynb)]: Introduction to the pre-trained VGG-Face [1] network.
2. **Gender Classification** [[1-FaceRecognition](https://github.com/samyak-268/deep-face-tutorial/blob/master/2-GenderClassification.ipynb)]: Fine-tune the pre-trained VGG-Face representations for the task of gender classification on a subset of the [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset [2].
3. **Metric Learning**
    1. [[3a-FaceVerification](https://github.com/samyak-268/deep-face-tutorial/blob/master/3a-FaceVerification.ipynb)] Intoduction to the problem of face verification and performance metrics used for measuring verification accuracies. We use the [CFPW](http://mukh.com/) [3] dataset for all verification/metric learning related experiments.
    2. [[3b-MetricLearning](https://github.com/samyak-268/deep-face-tutorial/blob/master/3b-MetricLearning.ipynb)] Improving the performance of VGG-Face features on the face verification task via metric learning using (dis)similarity labels.

The datasets and the pre-trained models will be uploaded soon.

### References
[[1](http://www.robots.ox.ac.uk/~vgg/publications/2015/Parkhi15/parkhi15.pdf)] Parkhi et al., "Deep Face Recognition", BMVC 2015 <br>
[[2](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Liu_Deep_Learning_Face_ICCV_2015_paper.pdf)] Liu et al., "Deep Learning Face Attributes in the Wild", ICCV 2015 <br>
[[3](http://ieeexplore.ieee.org/document/7477558/)] Sengupta et al., "Frontal to Profile Face Verification in the Wild", WACV 2016 <br>
