# Image-Classification-using-keras
Classifying images with Keras using resnet50 and investigating how the classifier works using heat maps. The code is also tested on a video ( output file included)

Heat maps can be used to visually detect bias in the data. 
The quality of a model's predictions depends heavily on the data on which it was trained. If the data is biased, that will reflect in the predictions.
For the sake of testing, I used 2 images - one of a dog and cat and other with a human and chimpanzee. 
Using resnet50, the predictions turn out to be 'redbone' for the first image and 'chimpanzee' for the second image. 
The heatmap shows how the classifier has focussed on the dog in the first image and chimpanzee in the second one. 
