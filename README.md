# Deep Learning

### COMSW4995 - Deep Learning

### Final Project - Scene Parsing using Image Segmentation and Semantic Labelling

Dataset used: [ADE20K dataset](http://groups.csail.mit.edu/vision/datasets/ADE20K/)

<p> Sample Images from ADE20k</p>
<p> Sample 1</p>
<img src="attachments/Sample2.jpg" width="350"/>
<p> Annotations</p>
<img src="attachments/Sample2.png" width="350"/>
<p> Sample 2</p>
<img src="attachments/Sample1.jpeg" width="350"/>
<p> Annotations</p>
<img src="attachments/Sample1_inference.jpeg" width="350"/>

### Steps to follow:

* Clone the repository using:
```
git clone https://github.com/siddhantsomani/DeepLearning.git
```
* Download dataset using:
```
wget http://data.csail.mit.edu/places/ADEchallenge/ADEChallengeData2016.zip
```
* Extract Dataset in the same folder as the above files(i.e, inside the cloned folder)
* Install requirements using:
```
pip install -r requirements.txt
```
* Run the model using:
```
python train.py
```

Notes:
1. Python 2.7 was used. Python 3 might throw errors.
2. Install any missing required libraries using pip. The code has been tested with the latest version of all requirements.

### Sample results from our model
<p> Test Image</p>
<img src="attachments/inference.png" width="350"/>
<p> Annotations</p>
<img src="attachments/inference_annotations.png" width="350"/>
<p> Test Image</p>
<img src="attachments/inference2.jpeg" width="350"/>
<p> Annotations</p>
<img src="attachments/inference2_annotations.jpeg" width="350"/>

### Authors

* **[Aayush Maini](https://www.github.com/amaini503)**
* **[Ishan Jain](https://www.github.com/ishankjain95)**
* **[Siddhant Somani](https://www.github.com/siddhantsomani)**

### Advisors

* **Iddo Drori**
* **Akshay Khatri**
