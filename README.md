# LeafNet
Deep Learning and Computer Vision powered system used to detect and classifiy plant diseases. This can be used in the Agriculture industry to help detect diseases that may not be visible to the naked eye.
## Getting Started
To use with your image, modify the beginning of the script to open the file picker.
### Prerequisites
The following dependencies are required:
* Python 3.6
* Keras with Tensorflow Backend
* OpenCV 3.4.2
* NumPy
* imutils
### Installing
Perform the following steps to run the system locally:
* Obtain the dataset by using `git clone https://github.com/spMohanty/PlantVillage-Dataset.git`
* Download the python script
* Modify paths to match local paths

**Weights available on-demand due to few contraints set by GitHub**

## Built With
* <a href="https://github.com/AlexeyAB/darknet">Darknet</a>
* <a href="https://keras.io/">Keras</a>
* <a href="https://github.com/ManivannanMurugavel/YOLO-Annotation-Tool">YOLO Annotation Tool</a>

## Process Explanation
<img src="https://github.com/AravindhanV/images1/raw/master/block_diagram.png">

It consists of 3 parts:
- **Leaf Detector**: Detects leaf in image and crops it
- **Leaf Classifier**: Classifies the leaf into 1 of 8 classes
- **Disease Classifier**: Checks for disease in the leaf and returns the disease name, if there exists any

### Leaf Detector
<p align="Center">
  <img width=240 height=320 src="https://github.com/AravindhanV/images1/raw/master/leaf_before_yolo.jpeg">
  &nbsp&nbsp&nbsp&nbsp
   <img width=240 height=320 src="https://github.com/AravindhanV/images1/raw/master/leaf_after_yolo.jpeg">
</p>
<p align="center">Before & After</p>

### Leaf Classifier
<p align="Center">
  <img src="https://github.com/AravindhanV/images1/raw/master/Flow%20diagram.png">
</p>

### Disease Classifier
<p align="Center">
  <img src="https://github.com/AravindhanV/images1/raw/master/subClasses.png">
</p>
