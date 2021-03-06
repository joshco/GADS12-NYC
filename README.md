# General Assembly Data Science 12

## Contact Information

* Gavin Hackeling: [gmh283@nyu.edu](mailto:gmh283@nyu.edu)
* James Beveridge: [jamesbev@gmail.com](jamesbev@gmail.com)
* Shawn Oakley: [shawnoakley@gmail.com](mailto:shawnoakley@gmail.com)


## Questions and Discussions:

* [Closed and Open Issue List (via pulse)](https://github.com/gavinmh/GADS12-NYC/pulse#closed-issues)
* [Create a new issue](https://github.com/gavinmh/GADS12-NYC/issues/new)


## Classes

### Lecture 1: Introduction to Data Science
_Thursday, 2014/08/07_

#### Class Materials

* [Lecture](https://docs.google.com/presentation/d/1r2pWzZ3-ZvA4OiRVqTzDCSMj33RSI7_UrLn6kt9BZzQ/edit?usp=sharing)
* [lab_01a.md](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-1/lab-1a.md)
* [lab-1a-submission-example.md](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-1/lab-1a-submission-example.md)
* [lab_01b.md](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-1/lab-1b.md)


### Lecture 2: Simple Linear Regression
_Tuesday, 2014/08/12_

#### Class Materials

* [Lecture](https://docs.google.com/presentation/d/1b9bYZ9MIBqEmsJ3x5dBVlwxbSW-v0n-SazICmxh_iwU/edit?usp=sharing)
* [simple-linear-regression-lab.pdf](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-2/simple-linear-regression-lab.pdf)
* [python-lab.ipynb](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-2/python-lab.ipynb)
* [numpy-lab.ipynb](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-2/numpy-lab.ipynb)


### Lecture 3: From Simple Linear Regression to Multiple Linear Regression & an Introduction to scikit-learn
_Thursday, 2014/08/14_

#### Class Materials

* [Lecture](https://docs.google.com/presentation/d/1nzGQyOeE-kkv5SUXrBfSgBD_s4FaFeY1GekmqjqgQbE/edit?usp=sharing)
* [lecture_3_numpy_review.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-3)
* [lecture_3_intro_to_sklearn.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-3)
* [lab_3_multiple_linear_regression.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-3)


### Lecture 4: Introduction to pandas & matplotlib, Multiple Linear Regression Review
_Tuesday, 2014/08/19_

#### Class Materials

* [Lecture](https://docs.google.com/presentation/d/11QwBL5HggOPv5VBLLyCjVGu1C41nLxTEEJXNrFWWwb8/edit?usp=drive_web)
* [multiple_linear_regression_review.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-4)
* [object_oriented_programming_lab.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-4)
* [matplotlib_intro_lecture.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-4)
* [pandas_intro_lecture.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-4)
* [pandas_lab.ipynb](https://github.com/gavinmh/GADS12-NYC/tree/master/lecture-4)


#### Project 1

* [Project 1: Regression](https://github.com/gavinmh/GADS12-NYC/blob/master/lecture-4/project-1-regression.md)


### Lecture 5: From Multiple Linear Regression to Polynomial Regression & Regression Project Workshop
_Tuesday, 2014/08/19_

#### Class Materials

* [Lecture]()
*
*


### Lecture 6: From Multiple Linear Regression to Logistic Regression & Text Feature Extraction
_Tuesday, 2014/08/26_

#### Class Materials

* [Lecture]()
*
*


### Lecture 7: Non-linear Classification and Regression with K-Nearest Neighbors & Image Feature Extraction
_Thursday, 2014/08/28_

#### Class Materials


### Lecture 8: (optional class) Kaggle Competitions
_Tuesday, 2014/09/02_

#### Class Materials


### Lecture 9: Non-linear Classification and Regression with Decision Trees and Ensemble Learning
_Thursday, 2014/09/04_

#### Class Materials


### Lecture 10: Cluster Analysis with K-Means
_Tuesday, 2014/09/09_

#### Class Materials


### Lecture 11: Dimensionality Reduction with Principal Component Analysis
_Thursday, 2014/09/11_

#### Class Materials




## Git Workflow and Command Line Tips:

* [Tips](https://github.com/gavinmh/GADS12-NYC/tree/master/tips)

Using a virtual machine
----

For further help/troubleshooting, feel free to come by the office hours or contact us for further help.

In case you're running into issues setting the environment up on your local environment, you can download a machine image from the following link: 

 https://www.dropbox.com/s/7nt0rt54m7jtxj5/GADS-InstalledEnv_1%28import%29.ova

Use the following user info to login: 

User: GADS

Password: gadspassword

**NOTE**: VMWare Player appears to occassionaly throw errors when dealing with this image.  Therefore, it would probably be easier to use [VirtualBox]

To install the virtual machine on VirtualBox

* Install VirtualBox
* Select File>Import Appliance
* When prompted, select 'GADS-InstalledEnv_1(import).ova' (or whatever you decided to name the downloaded image)
* Click through the rest of the import process
* In the main menu of VirtualBox, highlight the name of the machine (it should be whatever you named the ova file), and press 'Start'.

The image has Ubuntu 14.04 installed.  I found that the default RAM allocation (512 MB) was running a bit slow, so I adjusted the default allocation to 1024 MB.  If you're running into performance issues, you may need to adjust the memory allocation settings.

The image has the following libraries installed on it:

* [scikit-learn] (v 0.15.1)
* [numpy] (v 1.8.1)
* [pandas] (v 0.13.1)
* [scipy] (v 0.13.3)
* [pip] (v 1.5.6)
* [matplotlib] (v 1.3.1)
* [git]
* [nltk] (v 2.0.4)


#####  Git Repository in VM image

The class's git repo has been cloned as the following directory:

~/Desktop/courseGit/GADS12-NYC

There is a small bash script (~/Desktop/courseGit/GADS12-NYC/update) that allows you to type 'update-GADS' in order to clone the latest version from the repo.  The command is only soft-linked to the script, meaning that if 'update' is moved, the command won't work anymore.  Even if that happens though, you can just type 'git pull' in the repo's directory to update your local repo.


[scikit-learn]:http://scikit-learn.org/stable/
[numpy]:http://www.numpy.org/
[pandas]:http://pandas.pydata.org/
[scipy]:http://www.scipy.org/
[pip]:https://pypi.python.org/pypi/pip
[matplotlib]:http://matplotlib.org/
[git]:http://git-scm.com/
[nltk]:http://www.nltk.org/
[VirtualBox]:https://www.virtualbox.org/
