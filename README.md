# MATH578F22CSULB

MATH 578 - Numerical Linear Algebra, Fall 2022

California State University -- Long Beach

The content of this course closely follows *Computational Linear Algebra for Coders* that was taught by Rachel Thomas (fast.ai) in USF Data Science program, which is accessible through this website: [https://github.com/fastai/numerical-linear-algebra/blob/master/nbs/0.%20Course%20Logistics.ipynb](https://github.com/fastai/numerical-linear-algebra/blob/master/nbs/0.%20Course%20Logistics.ipynb). The course is taught in Python with Jupyter Notebooks, using libraries such as Scikit-Learn, Numpy, Scipy, Matplotlab, Pandas for most lessons, as well as Numba (a library that compiles Python to C for faster performance) and PyTorch (an alternative to Numpy for the GPU) in a few lessons. 

Throughout the semester, I will be using Jupyter Notebook to write most of my lecture notes and coding; while sometimes handwriting some mathematical derivations using notability. Meanwhile, I will record all my lecture videos. All the notability notes, jupyter notebook notes, and lecture videos will be linked under the Course Content below. 

## Course Syllabus

Click here for the Course Syllabus: [https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb)

## Additional CSULB Syllabus Statements

* [COVID-19 Health and Safety Requirements](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#COVID-19-Health-and-Safety-Requirements)
* [Title IX Prohibits Gender Discrimination](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Title-IX-Prohibits-Gender-Discrimination)
* [Supporting Undocument Students](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Supporting-Undocument-Students)
* [Syllabus Statement on Basic Needs](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Syllabus-Statement-on-Basic-Needs)
* [Syllabus Statement on Eliminating Anti-Blackness](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb#Syllabus-Statement-on-Eliminating-Anti-Blackness)

## Course Content

The following listing links to the notebooks in this repository, rendered through the [nbviewer](http://nbviewer.jupyter.org) service. The contents will be added and updated dynamically throughout the semester. 

### 1. Course Logistic, Downloads and Install, Basic Introduction (*[Lecture01 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EdlgVcVHcm1LhyK9WIRc6mQBbJ_O4y0rmtiZRCxaXAqobQ?e=E9hsxJ) covering 1.1-1.3*, *[Lecture02 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/ETy-K785D8BAqnSJw9RXpb0BfE86Nf5axYm_UfZ0YLFljQ?e=jupcra) covering 1.4 and Assignment 1*)
* 1.1 [Course Syllabus](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Syllabus/Syllabus.ipynb)
* 1.2 [Downloads and Install](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Downloads.ipynb)
* 1.3 [Jupyter Notebook and Markdown Language](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Markdown.ipynb)
* 1.4 [Introduction to Python](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec01.ipynb)
* **[Assignment #1](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment01.ipynb)**  *Due Aug 30, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 2. Linear Algebra Basics (*This chapter is the reading part of [Assignment 2](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment02.ipynb).*)
* 2.1 [What is an array?](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#What-is-an-array?)
* 2.2 [Creating arrays](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Creating-arrays)
* 2.3 [Array maths](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Array-maths)
* 2.4 [Indexing and Slicing](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Indexing-and-Slicing)
* 2.5 [Types of operations](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Types-of-oper5tions)
* 2.6 [Linear algebra and other advanced math](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec02_numPy.ipynb#Linear-algebra-and-other-advanced-math)
* **[Assignment #2](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment02.ipynb)**  *Due Sep 6, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 3. Topic Modeling with NMF and SVD (*[Lecture03 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EXutjbDjYaJFsUNsYKOTqo0BaZWn-CzXozLuFjCq4hm0vQ?e=zYfWEU) covering 3.1*, *[Lecture04 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUCxJYsdxrVNnxcMXm3aUukBEhs6ltP8WFkTnhpB-p6ogQ?e=l0gtVw) covering 3.1, 3.2*, *[Lecture05 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EXI36rawlXpElDWiezwZa5sBKawX4yJECeldG74l2ow5Jg?e=OiuCHL) covering 3.2, 3.3*, *[Lecture06 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EWL5dD33yvVIvLykQmOrJ0YBl_G7vOGgq29UU6xY8E8IPg?e=YxZko6) covering 3.4--3.7*)
* 3.1 [Set up data](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Set-up-data)
* 3.2 [Singular Value Decomposition (SVD)](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Singular-Value-Decomposition-(SVD))
* 3.3 [Non-negative Matrix Factorization (NMF)](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Non-negative-Matrix-Factorization-(NMF))
* 3.4 [PyTorch](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#PyTorch)
* 3.5 [Truncated SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Truncated-SVD)
* 3.6 [Randomized SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Randomized-SVD)
* 3.7 [Implementing our own Randomized SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec03_NMF_SVD.ipynb#Implementing-our-own-Randomized-SVD)
* **[Assignment #3](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment03.ipynb)**  *Due Sep 20, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 4. [Background Removal with Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb)(*[Lecture07 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EQchEBpN84NHjtB1jqb1N0cBadjPBF1Fizwk3qKFJV6Zrw?e=gBsBha) covering 4.1--4.2*)
* 4.1 [Getting Started](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Getting_Started)
* 4.2 [SVD](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#SVD)
* 4.3 [PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Principal_Component_Analysis_(PCA))
* 4.4 [Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/Lec04_PCA.ipynb#Robust_PCA_(via_Primary_Component_Pursuit))
* **[Book Chapter on SVD and PCA](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/topics/10457733) has been added to Beachboard.** (*[Lecture08 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EUC4-P-lRvJHnH8A4lYrLJcBf2XgMxuWqR-5WS2Zr6cLTg?e=7ChC0Y) covering SVD and PCA, [notes](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/topics/10458541) posted in Beachboard.*)
* **[Lecture notes on Robust PCA](https://bbcsulb.desire2learn.com/d2l/le/lessons/882936/units/10458538) has been added to Beachboard.** (*[Lecture09 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EeteMrXExyJOn7CI-vHElGkBgMctX2a-qzzke8mrhkiUXQ?e=a88gSd) covering Robust PCA*) 
* **[Yale Face denoising with Robust PCA](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Lectures/yaleB_RPCA.ipynb)(*[Lecture10 Video](https://csulb-my.sharepoint.com/:v:/g/personal/paul_sun_csulb_edu/EfnG5I020EdEh1mCp-hx6ToBaFLO4HYgpSkf5qeQwdki4A?e=EPCWtV)*)
* **[Assignment #4](https://nbviewer.org/github/huiprobable/MATH578F22CSULB/blob/main/Assignments/Assignment04.ipynb)**  *Due Oct 4, 11:59pm. Please submit one .ipynb file to Beachboard.*

### 5. Compressed Sensing with Robust Regression

### 6. Predicting Health Outcomes with Linear Regressions

### 7. How to Implement Linear Regression

### 8. PageRank with Eigen Decompositions 

### 9. Implementing QR Factorization 
