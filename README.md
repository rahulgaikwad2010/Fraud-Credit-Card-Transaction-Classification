# Fraud Credit Card Transaction Classification

Download Dataset from [my kaggle profile](https://www.kaggle.com/rahulgaikwad2010/emotion-detection) 

In the project, we will be working with a specified dataset of images. we will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset. The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half. A goal of the project is to explore the approaches we've leant, or perhaps beyond those, in order to build a high-performing system.

# Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Introduction](#introduction)
-  [Project Goal](#project-goal)
-  [Data Set](#data-set)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Facial Expression Recognition Deep Learning
|  ├── dataset       - this folder contains training & testing data.
|  │    ├──  PrivateTest_data_images.npy
|  |    ├──  PublicTest_data_images.npy
|  |    ├──  Training_data_images.npy (Omitted Because > 25 MB)
|  |    └──  Training_data_labels.npy
|  │
└────── Facial Expression Recognition.ipynb
```

<br/>

### Introduction

In the project, we will be working with a specified dataset of images.  we will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset.  The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half.  A goal of the project is to explore the approaches we've leant, or perhaps beyond those, in order to build a high-performing system.

### Project Goal

The following steps must follow (if you can add more than these steps, it would be great).
1- Describe the structure of the date (statistical summary: number of records, counting max, min, null,...)
2- Plotting histogram of "transactionAmount" column.
3- We have duplicated transactions in the data set—two types: reversed transaction and multi-swipe. You need to answer these questions:
3-1 Identify those types of duplicates
3-2 Estimate of the total number of transactions and total dollar amount 

do you estimate for the reversed transactions and multi-swipe transactions? 
**Note that: the first transaction to be "normal" and exclude it from the number of transaction and dollar amount count**

4- Modeling: Provide modeling algorithms and say why you use those methods? Why used those features?
4-1 There is a type of transactions in the dataset has a field called "isFraud". Build a predictive model to determine whether a given transaction 
will be fraudulent or not.
4-2 Use an estimate of performance using an appropriate sample	

### Data Set

The dataset have images of the faces which have the expressions or 7 classes as angry, disgusted, fearful, happy, sad, surprised, neutral.The Images pixel size is 48 x 48 grey scaled. 

<b>Train data</b> - (9328, 48, 48)

<b>Public Test data</b> - (1136, 48, 48)
    
<b>Private Test data</b> - (1153, 48, 48)

<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>

I welcome your questions. Write to rahul.gaikwad2010@gmail.com

<br/>
