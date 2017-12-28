# Dog-Breed-Detection  

### Introduction  

Project was a part of the Udacity's Nanodegree program. Some of the template code and instructions were provided to help the students finish the project.

### Objective
To create a model that detects the breed of the dog when its image is supplied.

The project accepts any user-supplied image as input. If a dog is detected in the image, it provides an estimate of the dog's breed. Additionally, if a human is detected, it provide an estimate of the dog breed that is most resembling(!).  

The image below displays potential sample output of the project.  

![Sample Dog Output](images/sample_dog_output.png)

### Tasks  

Following are the series of tasks perfomed:  
* [Step 0](#step0): Import Datasets  
* [Step 1](#step1): Detect Humans  
* [Step 2](#step2): Detect Dogs  
* [Step 3](#step3): Create a CNN to Classify Dog Breeds (from Scratch)  
* [Step 4](#step4): Use a CNN to Classify Dog Breeds (using Transfer Learning)  
* [Step 5](#step5): Create a CNN to Classify Dog Breeds (using Transfer Learning)  

### Data

Following are the details of the dataset used:  
* 133 total dog categories.  
* 8351 total dog images.  
* 6680 training dog images.  
* 835 validation dog images.  
* 836 test dog images.  
* 13233 total human images

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [Keras](https://keras.io/)  
- [CV2](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_gui/py_image_display/py_image_display.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)  

### Code

Main code is provided in the `dog_app.ipynb` notebook file. The images folder containes images on which the training and testing was conducted. 

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook dog_app.ipynb
```  
or
```bash
jupyter notebook dog_app.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

