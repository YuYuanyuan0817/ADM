
#  ADM

## 1.Choose one business-model and company type

![business](https://github.com/YuYuanyuan0817/ADM/assets/118308478/3860a4e6-f1b6-44eb-8705-8b9fc3180dfa)

The textbook rental websites can make money from following revenue channels:
Renting/selling books
Banner ads
Monthly subscription to access textbook solution & Experts/Community Q&A
Online tutoring service that may charge students on weekly/monthly basis, depending on how long the session was

## 2.Describe business model of chosen company/organization


The two images below are a brief introduction to the whole business process from both the customer's and the seller's point of view.


![seller process](https://github.com/YuYuanyuan0817/ADM/assets/118308478/741559a4-6c1d-4455-adac-a6b4bf7b8e37) ![customer process](https://github.com/YuYuanyuan0817/ADM/assets/118308478/5de5df8b-2643-4dfa-9bc2-9db81a6873d2)

Below is a description of the specific business process

Business Process Modeling(BPM)


![image](https://github.com/YuYuanyuan0817/ADM/assets/118308478/c8ddb3f2-44e3-4b73-a7fb-014c7ee191b6)

 UML-order registration.drawio.png


![image](https://github.com/YuYuanyuan0817/ADM/assets/118308478/8cd04b96-f4c4-48f6-baf0-4948446366a6)


UML-delivery order.drawio.png


![image](https://github.com/YuYuanyuan0817/ADM/assets/118308478/588fe075-83cf-436e-81ba-cc8156bbb016)


UML-seller book.drawio.png


![image](https://github.com/YuYuanyuan0817/ADM/assets/118308478/a15adeb2-3f7f-4a2f-bc85-547d68a64330)



## 3.Create conceptual logical and physical data model

conceptual data model

![Ze4uuyWMmmI](https://github.com/YuYuanyuan0817/ADM/assets/118308478/83255278-fb73-4a91-85bf-e10cf7514dcb)

 physical data model

![kqNE1DUjoYg](https://github.com/YuYuanyuan0817/ADM/assets/118308478/e65a7fc6-163d-4a4f-882f-4a377e537629) 

logical  data model

![w7rpeRVfM6w](https://github.com/YuYuanyuan0817/ADM/assets/118308478/f020e8f4-b7d9-41e1-a617-24b6c343aab5)


## 4.Create a database and fill the database with real or synthetic data

The DBeaver software was used to link SQLite to create the database and the following is a diagram of the datebase created.

![database_diagram](https://github.com/YuYuanyuan0817/ADM/assets/118308478/c2256571-f699-48d8-aef5-3ade52ff57c7)

These two tables are the payment table and the book_rental_record table in the book_rental database.

![payment](https://github.com/YuYuanyuan0817/ADM/assets/118308478/26a72139-8a33-4c6f-a1d2-4d2f6a112bd8)
![book_rental_record](https://github.com/YuYuanyuan0817/ADM/assets/118308478/55b82c18-577b-408d-bda6-5f4b6bbfcbee)

# 5.Create list or roles,list of data assets,role to asset matrix in CRUD terms

In our book-rental business model, 
roles include:
Client	、
Administrator 、
Warehouse 、
Courier	 、 
Seller


data include:
Order  、
Book  、
Admin data  、
Client data  、
Courier data  、
Seller data  、
Warehouse data  、


activities include:
Processing Order  、
Add book to order  、
Receive order  、
Calculate order price  、
Update order status  、
Deliver order  、
Handling client data  、
Receive client data  、
Check book stock  、
Get payment  、


resources include:
Computer  、
Order sheet  、
Courier’s phone  、
Deliver sheet  、

This is the data to roles CRUD form


![data to roles](https://github.com/YuYuanyuan0817/ADM/assets/118308478/c87ff1d0-bbd1-44a8-b1fc-761d5885cae9)


This is the activities to roles CRUD form


![activities to roles](https://github.com/YuYuanyuan0817/ADM/assets/118308478/7179664b-4176-4457-9ba5-4ebe9886865f)


This is the resources to roles CRUD form


![resources to roles](https://github.com/YuYuanyuan0817/ADM/assets/118308478/685ecfea-adf4-49cc-a78d-05c71e315636)


# 6.Describe master-data standards


Use DBeaver to monitor the database, including server sessions, data read and write queries, database traffic, etc.


![monitor](https://github.com/YuYuanyuan0817/ADM/assets/118308478/0564f47e-eb7d-4c49-a6c2-5722837718a6)

![monitor1](https://github.com/YuYuanyuan0817/ADM/assets/118308478/a2eb3145-36de-492e-83c4-5fe5b335bc4a)


use DME to make Master Data Management(MDM)

![image](https://github.com/YuYuanyuan0817/ADM/assets/118308478/bfb88639-76b9-42f5-9325-6344803a4df3)


# 7.Visual model analysis

Visual analysis with tableau


![仪表板](https://github.com/YuYuanyuan0817/ADM/assets/118308478/632330c1-eb8d-4e33-a696-74acb4a77392)


