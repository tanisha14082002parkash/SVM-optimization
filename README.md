# SVM-optimization
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Avila](https://archive.ics.uci.edu/ml/datasets/Avila))

DATA SET DESCRIPTION 
The Avila data set has been extracted from 800 images of the the "Avila Bible", a giant Latin copy of the whole Bible produced during the XII century between Italy and Spain.  
The palaeographic analysis of the  manuscript has  individuated the presence of 12 copyists. The pages written by each copyist are not equally numerous. 
Each pattern contains 10 features and corresponds to a group of 4 consecutive rows.

The prediction task consists in associating each pattern to one of the 12 copyists (labeled as: A, B, C, D, E, F, G, H, I, W, X, Y).
The data have has been normalized, by using the Z-normalization method, and divided in two data sets: a training set containing 10430 samples, and a test set  containing the 10437 samples.

Class distribution (training set)   

A: 4286   
B: 5  

C: 103    

D: 352     

E: 1095    

F: 1961    

G: 446    

H: 519   

I: 831    

W: 44    

X: 522     

Y: 266    


ATTRIBUTE DESCRIPTION

ID      Name   
F1       intercolumnar distance     
F2       upper margin     
F3       lower margin      
F4       exploitation      
F5       row number      
F6       modular ratio       
F7       interlinear spacing       
F8       weight     
F9       peak number     
F10     modular ratio/ interlinear spacing     
Class: A, B, C, D, E, F, G, H, I, W, X, Y      




## Final Result Table
![image](https://user-images.githubusercontent.com/79708114/233185956-709842a0-e568-46aa-848b-4bdd89b84d1b.png)


## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Tanisha Parkash
  
Roll No. : 102003447

Sub-Group: 3CO18

Predictive Analytics Assignment
