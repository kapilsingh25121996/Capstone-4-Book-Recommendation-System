# Book recommendation system
 The book recommendation system must recommend books that are of interest to buyers. The main objective of this project  is to create a Book recommendation system that best predicts user interests and recommend the suitable/appropriate books to them ,using various approaches.The approaches used here are:


![image](https://user-images.githubusercontent.com/114326008/227332816-b015597d-7970-4a8f-9473-34feb3edca10.png)
<p align="center"> 



<p> </p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Table of Content</h2>


  * [Introduction](#Introduction)
  * [Problem Statement](#Problem-Statement)
  * [Dataset Information](#dataset-information)
  * [Tools and Technologies used](#tools-and-technologies-used)
  * [Project Description](#Project-Description)
  * [Conclusion](#Conclusion)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> 📄 Introduction</h2>

With an increasing amount of information on the internet and a considerable increase in the number of users, it is essential for companies to search, map, and offer relevant information based on the preferences of users. Aan important functional means of providing personalized service to users is **Recommendation System**. This system uses algorithms and data analysis techniques to suggest items,content, or services that should be of interest to customers based on their past choices or by analyzing the preferences of similar users. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or content for them. 

🎯 The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> ❓ Problem Statement</h2>

 During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.
In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).
Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> :book: Dataset information </h2>

 Dataset used in this project is the Amazon Book-crossing dataset.This dataset has been compiled by Cai-Nicolas Ziegler in 2004, and it comprises of three file.They are: 

**Users**

* User-ID: A unique identification number for each user
* Location:It contains city,state and country  to which the user belongs ,separated by commas
* Age:The age of the user

**Books**

* ISBN:International Standard Book Number unique to each edition of the book
* Book-Title:Title of the book
* Book-Author:Author of the book(incase of several authors only the first is provided)
* Year-of-Publication:The year in which the particular edition of the book was published
* Publisher:Name of the Book Publishing company
* Image-URL-S: URL link to a small version of the book cover displayed on the Amazon website
* Image-URL-M:	URL link to Medium version image of the book cover displayed on the Amazon website
* Image-URL-L: URL link to Large sized image of the book cover displayed on the Amazon website

**Ratings**

* User-ID:as mentioned above
* ISBN:as mentioned above
* Book-Rating: The rating given by the user (identified by User-ID) for the book (identified by ISBN). It is either explicit,expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,expressed by 0.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>🛠️ Tools and Technologies used </h2>


The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

* **Pandas** :  For loading the dataset and performing data wrangling
* **Matplotlib**: For  data visualization.
* **Seaborn**: For data visualization.
* **NumPy**: For some math operations in predictions.
* **Sklearn**:  For the purpose of analysis,prediction and evaluation.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📑 Project Description </h2>

* **Data Cleaning** : Missing value imputation,Outlier Treaatment.
* **Feature Selection** : Used User-ID,ISBN and Books-Rating for model development.
* **Model development** :  Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).
* **Exploratory Data Analysis** : Performed exploratory data analysis on numerical and categorical data.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)



<h2> :bulb: Conclusion</h2>

* In EDA, the Top-10 most rated books were essentially novels. Books like The Lovely Bone and The Secret Life of Bees were very well perceived.
* Majority of the readers were of the age bracket 20-35 and most of them came from North American and European countries namely USA, Canada, UK, Germany and Spain.
* If we look at the ratings distribution, most of the books have high ratings with maximum books being rated 8. Ratings below 5 are few in number.
* Author with the most books was Agatha Christie, William Shakespeare and Stephen King.
* For modelling, it was observed that for model based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE).
* Amongst the memory based approach, item-item CF performed better than user-user CF because of lower computation .

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Kapil Singh > | Keen Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kapilsingh025/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kapilsingh25121996)

