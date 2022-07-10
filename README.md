# Experimental-Design-Recommendations
### **Recommendations with IBM**

## Table of Contents
 * [Installations](#installations)
 * [Project Motivation](#project-motivation)
 * [Project Structure](#project-structure)
 * [Files](#files)
 * [Acknowledgements](#acknowledgements)
 
 
## **Installations**

NumPy · Pandas · Seaborn · Matplotlib · Pickle

## **Project Motivation**
In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform:
![](https://github.com/Fernandes2692/Experimental-Design-Recommendations/blob/main/IBM-articles.png)


## **Project Structure** 
 
The project is divided into the following tasks:

#### **I. Exploratory Data Analysis**

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

#### **II. Rank Based Recommendations**

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

#### **III. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

#### **IV. Matrix Factorization**

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

## **Files**

```bash

├── data:
   └── articles_community.csv 
   └── user-item-interactions.csv
  
├── Recommendations_with_IBM.ipynb

├── top_5.p
├── top_10.p
├── top_20.p
     
├── user_item_matrix.p
        
├── project_tests.py

```

## **Acknowledgements** 

* [Udacity](https://www.udacity.com/) for the starter files, testing advice, and instructions
* [IBM](https://eu-gb.dataplatform.cloud.ibm.com/login?preselect_region=true) for providing the data 
