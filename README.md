# SIC - Telec Customer prediction

## Introduction

Customer success does not only stop at acquiring new customers, it is extended to a longer lifecycle as this obviously depend on direct and indirect reasons. Churn customer metrics can significantly indicate the customer success Lifecycle. Figure 1 illustrate the story behind customer engagement along the time. It can be seen that after the acquisition stage, the customer is more likely to be get more engaged to the company services/product. After the customer gets satisfied with the company, the customer tends to be more loyal to the company as the time goes. However, the risk of losing the customer increases as the customer keeps utilizing the service/product. This would indicate to make more customized services/product to the customer to keep him satisfied, otherwise the customer is more likely to be churn. 

## Deployed Project
  https://ml-sic.000webhostapp.com
![plot](UI.png)


## Goals

Minimize the Customer Churn Rate using ML techniques that can help the companies to see which customers are about to leave their services so they can develop proper strategy to re-engage them before it is too late.


## Code Structure

The code is mainy divided to two part, Front-end and Back-end.

### 1- Front-end 
  The project front-end developed using Flutter Framework that bulit using Dart Programing Language. The power of the framework is the flexibility, where it can bulied website, IOS, and Android app using the same source code. 

### 2- Back-end 
  The project back-end developed using Flask Framework that bulit using Python Programing Languages. the power of the framework that it is easy to get started with as a beginner because there is little boilerplate code for getting a simple app up and running. Also, it easy to integrate it with other framework.



## How to Install the Project

### Front-end
1- 
  Since this project is using Flutter as framwork, So you need to install flutter to you divice.
  Here is the link how to install flutter for different operating system.
  https://flutter.dev/docs/get-started/install

2- 
  After installing Flutter you can simplely clone the project using following command.
  > git clone https://github.com/ffalowaini/Churn_Prediction.git 

3- 
  Open the project in your favorite IDE tool and run the main.dart file our using following command.
  > flutter run

### Back-end
1- 
  Since this project is using Flask as framwork, So you need to install python and install flask package to you divice.
  Here is the link how to install python for different operating system.
  https://www.python.org/

2- 
  After installing Pyhton you need to need to install Flask package using following command.
  > pip install flask

3- 
  After installing Pyhton you can simplely clone the project using following command.
  > git clone https://github.com/ffalowaini/Churn_Prediction.git 

4- 
  Open the project in your favorite IDE tool and run the app.py file our using following command.
  > flask run


##### to use the back-end for other project

send the data as array in json formate contain the following in the same order (where true is 1, false is 0)
  - tenure month
  - monthly charge
  - is_male
  - is_senior_citizen
  - is_partner
  - has_dependent
  - has_Phone_Service
  - has_Multiple_Lines
  - has_Internet_Service_Fiber? optic
  - has_Online_Security
  - has_Online_Backup
  - has_Device_Protection
  - has_Tech_Support
  - has_Streaming_TV
  - has_Streaming_Movies
  - contract_year
  - contract_two_year
  - payment_credit
  - payment_Electronic
  - payment_Mail

  the response formate as follow in json format ['will churn or not'], where 0 mean customer is likely to Churn, and 1 mean customer is not likely to Churn.

## How to deploy the Project to server

  For the font-end We used 000WebHost web hosting service. Here is a simple tutorial
  https://www.youtube.com/watch?v=wyz0qYnS2TQ&t=341s


  For the back-end We used Heroku cloud service. Here is a simple tutorial
  https://devcenter.heroku.com/articles/getting-started-with-python#set-up