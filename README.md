<h1><p align="center">Capstone Project on Data Science Nanodegree</p></h1>
<h1><p align="center">Starbucks Promotional Offers</p></h1>
<h3><p align="center">Israel Agwu Etu</p></h1>
<h3><p align="center">March 2022</p></h1>

## Introduction
<p align="justify">
This is the Capstone Project of the Udacity Nanodegree Program. In this project, the benaviour of Starbucks customers towards the company's promotional offers is to be analyzed. The company sends informational about her promotional offers from time to time. These offers can come in the form of Buy One Get One free (BOGO), discount after buying goos worth a certain amount or informational, just to pass some information to customers to encourage them to test some products. The offers can be sent out through different media such as email, mobile device, web and social media. This project aims at studying how customers of different ages, genders and income level respond to different promotional offers from different information media. The yardstick is whether they view the offer or they view and also respond accordingly.
</p>

## Problem Statement
<p align="justify">
As mentioned above, the customers are to be studied and their reactions to different promotional offers analyzed and possibly predicted. Whether they received the information or not may be ignored. Also, whether they took action as a result of the offer will also be ignored. The important thing is to estimate their behaviour.
  
The data used for this project is not straight forward. It is too clumsy. It is expected to arrange the data in the best way possible to be used by a machine learning algorithm to make predictions.
</p>

## Python Modules Used
The python modules used in this work include:<br>
- pandas<br>
- numpy<br>
- json<br>
- math<br>
- matplotlib<br>
- seaborn as sns<br>
- sklearn<br>

## Files in the Repository
The work was organized using the following files:

- **portfolio.json:** This is a data file containing information about the offers.

- **profile.json:** This is another data file containing information about the customers.

- **transcript.zip:** This is yet another data file containing the responses of the customers. It compressed with zip because of its large volume.

- **starbucks_project.ipynb:** This is main program file containing the codes written in jupyter notebook.

- **starbucks_project.html:** This is the html version of the main program file.

- **README.md:** This write-up

## Methodology
<p align="justify">
- **Exploratory Data Analysis:** The data in the 3 databases were explored and the necessary statistical information about them were fetched.
  
![image](https://user-images.githubusercontent.com/44449730/158555409-d1fbc50e-1406-40f8-8917-1ab5af41c029.png)<br>
Portfolio data

![image](https://user-images.githubusercontent.com/44449730/158560307-ac7cd1c0-2524-40ad-86f3-ed81f6f0ec0d.png)<br>
Profile data
  
![image](https://user-images.githubusercontent.com/44449730/158560460-bb40678e-5de9-44b5-948e-979bdb72ec82.png)<br>
Transcript data

- **Data Visualization:** The statistical information fetched from the datasets were presented in different visual forms.

![image](https://user-images.githubusercontent.com/44449730/158560759-71772331-69b1-46c7-98b5-fd0d580fbd56.png)<br>
Offer types in portfolio data
  
![image](https://user-images.githubusercontent.com/44449730/158561240-3b5f010b-297b-4bad-889a-c061516fcd2c.png)<br>
Gender in profile data

![image](https://user-images.githubusercontent.com/44449730/158561434-c8731ac8-8b1e-4907-aa9e-13a956daf6ea.png)<br>
Events in transcript data

- **Data Preprocessing:** The 3 datasets were cleaned and rearranged to be fit for subsequent use for machine learning manipulations.
  
![image](https://user-images.githubusercontent.com/44449730/158561696-a0bd7a85-0804-4c1a-8245-7b0de1ac489f.png)<br>
Portfolio channels binarized
  
![image](https://user-images.githubusercontent.com/44449730/158561963-daa9de7d-abe8-4144-8fa7-f375455ff061.png)<br>
Gender, age and income in profile data assigned weights
  
![image](https://user-images.githubusercontent.com/44449730/158563788-908a634a-349b-4ec2-8fe8-891e9ec53cf7.png)<br>
Dummies created for events and data frames merged

- **Modelling:** Machine learning algorithms were then used to prepare models for necessary predictions and metrics evaluations.
    
- **Metrics Calculation:** Some metrics were employed to calculate parameters such as accuracy score, F1 score and recall.
  
![image](https://user-images.githubusercontent.com/44449730/158564096-0e6fd457-7030-45ac-9ebb-7d8783e3c5e9.png)<br>
Metrics calculated
  
- **Demonstration:** Two of the models were used to make a prediction on the behaviour of a certain group of customers to the promorional offers, given certain channels of release of the offers.
  
![image](https://user-images.githubusercontent.com/44449730/158564380-acb50c44-bd98-491b-8659-650e122c655f.png)<br>
Prediction made
</p>

## How To Run the Program
<p align="justify">
Due to the procedural nature of this project, the program is not modularized. A user simply needs to run the program step by step to get any result of choice.
</p>

## Summary
<p align="justify">
The 3 datasets were therefore successfully prepared for machine learning operations. The data preprocessing was indeed a great deal of task and so took more than half of the required work in this work. At the end, certain machine learning metrics were successfully evaluated for the models of the work. Different machine learning algorithms were also  used to test their level of accuracy in making predictions with the final data. A simple prediction was demonstrated to show the likely behaviour of customers chosen from a certain group with certain criteria and the model performed well.
</p>

## Conclusion
<p align="justify">
This is my implementation of the solution of estimating the behaviour of Star Bucks customers towards promotional offers. There could be a different implementation and estimations. Therefore, whatever anyone can add or suggest to make the work more encompassing is highly welcome. Meanwhile, for a more detailed report of this work, please feel free to visit the blog post on 
</p>

## Acknowledgements
<p align="justify">
I thank God so much for enabling me to have come this far in this program. It has been long-awaited and so I thank Him.
I thank the Udacity team for being very responsive with friendly listening ears. I am ever grateful to all of them.
My appreciation also goes to all the sources I got inspiration and information that enabled me to complete this project. The sklearn, numpy and other documentations were very helpful.
I would like to end by thanking Mosh Hamedani. He is my first python teacher and what I learnt from him gave me a good footing to cope with this data science program. My sincere gratitude goes to all of you my dear teachers.
  
**Once again, thank you all.**
</p>

## References
1. https://classroom.udacity.com/nanodegrees/nd025/parts/059c574b-e0d0-4fa7-8acd-47d9df9d53b6/modules/b0daab3f-5ffc-4ce1-af45-0945e87321ad/lessons/7420189a-47a9-43ad-9154-c9c0b98fdce5/concepts/a99ff15a-f9e3-48b1-a9b7-c62f99beeba5
2. https://pandas.pydata.org/docs/user_guide/visualization.html
3. https://pandas.pydata.org/docs/reference/api/pandas.concat.html
4. https://numpy.org/doc/stable/reference/generated/numpy.around.html
5. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html
6. https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html
7. https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html#sklearn.preprocessing.StandardScaler
