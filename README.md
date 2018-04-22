# TF Places365
Tensorflow implementration of Places365 using pretrained Caffe model.
## Dependencies
Package dependency:
* Python 2.7
* TensorFlow
* Numpy
* Pillow
* resizeimage (pip install python-resize-image)
## Getting the model
Download the places365 model in Caffe from [GitHub repository](https://github.com/CSAILVision/places365). 
Download both the deploy file and the weights file. 
Doanload category index file from [here](https://github.com/CSAILVision/places365/blob/master/categories_places365.txt)

Convert the Caffe model to a TensorFlow model using the [caffe-tensorflow](https://github.com/ethereon/caffe-tensorflow) converter. [Guide to use the conversor [here](https://docs.google.com/document/d/1UhPTyDTFJHDx94yDH8x_dCnNpM9K9irAKZSvn97ps6c/edit?usp=sharing)].
## Running
Update image path, the converted weights paths and the labels (category index file) path. 
Note that the input's width and height are set for a VGG16 model.
