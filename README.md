### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Execution Instructions](#execution)
5. [Results Summary](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.


## Project Motivation<a name="motivation"></a>

For this project, I was interested in learning about how to create a algorithm that was able to process images and classify them according to some criteria. In addition, within the field of Computer Vision I was interested in getting expertice working with Convolutional Neural Networks and Transfer Learning.


## File Descriptions <a name="files"></a>

a) dog_app.ipynb: python script that build and execute the dog breed predictor.

b) images folder: it contains the images that are used to run individual tests over the breed_predictor() function.

c) saved_models folder: it contains the models that are saved during the python script execution.

d) haarcascades/haarcascade_frontalface_alt.xml: XML file with pre-trained face detectors provided by OpenCV.

e) bottleneck_features folder: it contains the bottleneck features used by the models created in the dog_app.ipynb script.

f) extract_bottleneck_features.py: script that contains the functions to extract the bottleneck features.

g) README.md


## Results Summary <a name="results"></a>

A algorithm that estimate the breed of dogs was created using Convolutional Neural Networks (CNN). Accuracy was the metric used for measuring the sucess of the different CNNs developed during the project.

Firstly, a CNN architecture was created from scratch, reaching around 4% of accuracy when the solution was tested using a dog image testing dataset. Secondly, tranfer learning was used by incorporating into the solution a pre-trained ResNet-50 model that allowed to us to achieve a test accuracy > 80%, which was high enough to fulfill the target set at the beginning of the project.

Blog post with more detailed information: https://medium.com/@javiles.garcia/whats-my-dog-s-breed-79713d3d4fb4


## Execution Instructions<a name="execution"></a>

1. Upgrade your local Anaconda distribution for using Python versions 3.*

2. Download all files in this repository to your local machine.

3. Execute step by step the code cells of the dog_app.ipynb script following the instruction included in the notebook.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to [Udacity](https://www.udacity.com/) for providing the means and motivation for carrying out this project.
