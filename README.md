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
<img src="https://raw.githubusercontent.com/AravindhanV/images1/master/block_diagram.png?token=AHSQE2SEFF5BNU5BMMLFRUS5IWBI4">

It consists of 3 parts:
- **Leaf Detector**: Detects leaf in image and crops it
- **Leaf Classifier**: Classifies the leaf into 1 of 8 classes
- **Disease Classifier**: Checks for disease in the leaf and returns the disease name, if there exists any

### Leaf Detector
<p align="Center">
  <img width=240 height=320 src="https://raw.githubusercontent.com/AravindhanV/images1/master/leaf_before_yolo.jpeg?token=AHSQE2W2CIAQUOTK6QKKIBK5IWBKG">
  &nbsp&nbsp&nbsp&nbsp
   <img width=240 height=320 src="https://raw.githubusercontent.com/AravindhanV/images1/master/leaf_after_yolo.jpeg?token=AHSQE2W4CPCBPMWXW5LRVB25IWBLO">
</p>
<p align="center">Before & After</p>

### Leaf and Disease Classifiers
<p align="Center">
  <img src="https://raw.githubusercontent.com/AravindhanV/images1/master/Flow%20diagram.png?token=AHSQE2RUQJPS3US37AFGX4K5IWBHY">
</p>
