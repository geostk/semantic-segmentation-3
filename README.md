# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Run
Run the following file to run the project in jupyter notebook:

```
FCN.ipynb
```
#### Environment 

https://github.com/udacity/CarND-Object-Detection-Lab

```
name: carnd-advdl-odlab
channels:
    - https://conda.anaconda.org/menpo
    - conda-forge
dependencies:
    - python==3.6
    - numpy
    - matplotlib
    - jupyter
    - pillow
    - scipy
    - ffmpeg
    - imageio==2.1.2
    - pip:
        - moviepy
        - tensorflow-gpu==1.2
```


**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission

3. Submit the following in a zip file.
 - `helper.py`
 - `FCN.ipynb`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 in my case, the most recent data is put into 1511221281.479869 folder. 
 
