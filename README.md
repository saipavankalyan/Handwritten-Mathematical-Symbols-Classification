# Final Project

This is a **group assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

The final project is due Tuesday, December 6 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/455013/assignments/5244219) in the Canvas assignment.

## Training Data

The training data set is the same for every team in this course.

You can download the training data from the Canvas page:

* ["data_train.npy"](https://ufl.instructure.com/files/72247539/download?download_frd=1)
* ["t_train.npy"](https://ufl.instructure.com/files/72245951/download?download_frd=1)

## Classification of Basic Handwritten Mathematical Symbols using Conventional Machine Learning Techniques

### Introduction
 The experiment highlights the signifiance of transfer learning approaches in enhancing the accuracy of various classification algorithms on sparse datasets such as image,speech and many more. Furthermore, the study evaluates and contrasts the efficacy of various machine learninng and transfer learning frameworks on the given sparse dataset housing ten distinct caegories of images. Furthermore, the training code generated a distinct model file upon recieving the training files titled data_train and t_train respectively. Finally the test code requires the genrated model files as well as the test image array and label files for reproducing the results
 
 #### Note: Due to the size of the generated model file, we have compressed the file into a zipfile and provided a url for accesing the same based onyour convenience.Kindly do the needfull.
 
 
### Team members
1) Ganeson Ravichandran
2) Bhagya Raj Varadaraju
3) Sai Pavan Kalyan Munaga
4) Vishal Balaji Sivaraman

### Dependencies

This codebase uses pytorch and opencv in addition to default dependencies that comes with anaconda3. 
The same environment could be recreated using the following command which uses the conda 
[environment file](environment.yml).

```shell
conda env create -f environment.yml
```

### Training Notebook and Inputs

The training notebook is [Training.ipynb](Training.ipynb).

* ["data_train.npy"](https://ufl.instructure.com/files/72247539/download?download_frd=1)
* ["t_train.npy"](https://ufl.instructure.com/files/72245951/download?download_frd=1)

### Testing Notebook and Inputs

The test notebook is [Test.ipynb](Test.ipynb).

The test notebooks expects two numpy files. The data_test.npy and t_test.npy. These files should be available in the 
same location folder as that of the [Test.ipynb](Test.ipynb) notebook file.

* data_test.npy - Numpy file of format (90000 * N)
* t_test.npy - Numpy file of formal (N,)

### Download Link for generated model file
 * ["Model File"](https://shorturl.at/jkl27)

### Steps to Execute

#### Training.

Note: Training takes considerable time.

*Steps*

1. Put the training data and labels in the same folder as that of [Training.ipynb](Training.ipynb).
2. Execute [Training.ipynb](Training.ipynb).

The model will be stored as .pth file.

#### Testing.

*Steps*

1. Please download the [model file](https://shorturl.at/jkl27) and put in the same folder as that [Test.ipynb](Test.ipynb).
2. Put the test data and labels in the same folder as that of [Test.ipynb](Test.ipynb).
3. Execute [Test.ipynb](Test.ipynb)

## Thank You
 


