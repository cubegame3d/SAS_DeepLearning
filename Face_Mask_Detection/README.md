# Face Mask Detection
<img src="misc/Face_Mask_Detection.jpg" alt="Face Mask Detection" align='left' style="width: 40%; height: 100%"/> <br clear='left'>

### Why:
Due to the Corona crisis many governments decided that people should wear face masks when they're in public areas such as public transporation, supermarkets, etc.<br>
Closely related to my other [example](https://github.com/Mentos05/SAS_DeepLearning/tree/master/Social%20Distancing%20Demo) where I track social distancing rules this demo shows how Computer Vision can help us to identify whether people wear a mask or not.<br>

In this example I train a Tiny YOLOv2 model to detect faces and covered faces on images. This model is then used in a SAS Event Stream Processing project to score frames from a video.<br>

### Further ideas
* Generate warnings if people are not wearing masks
* Restrict access if a person is not wearing a mask

### Data
The data was collected and annotated manually via Google Image Search.<br>
Annotations were performed using [CVAT](https://github.com/opencv/cvat).<br>
Additionally the data and labels were augmented with several transformations including, flipping, HSV transformations and mosaic stitching.

### Demo
Demo video can be found here:
* Face Mask Detection

[![Face Mask Detection with Computer Vision](https://img.youtube.com/vi/C8ROYvP-XYc/0.jpg)](https://www.youtube.com/watch?v=C8ROYvP-XYc)

### Further Ressources
[Medium.com Article](https://medium.com/@michaelgorkow/face-mask-detection-using-computer-vision-54563a905a84)
