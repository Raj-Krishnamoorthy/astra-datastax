# astra-datastax
 Create astra database, insert records via swagger ui and bulk insert via python

How to create astra database, insert records using swagger ui and bulk insert via python

High level steps


1. goto datastax.com and sign up for astra database

2. create astra database
<img src="images/image1.png">


3. Click on the connect
<img src="images/image2.png">

4. Click on the REST API. Create app user and generate the client_id, client_secret and token. Also download
<img src="images/image3.png">

5. Launch swagger link 
<img src="images/image4.png">

6. Use Swagger UI to create table, post records. To create table click on the schema and look for V2 option to create table

<img src="images/image5.png">


7.Add the App token you generated and keyspace is demo06 that was created as part of the database creation. Then create users table and click on execute
<img src="images/image6.png">


9 CSQL - to check if table was created.
<img src="images/image7.png">


10. Insert records via swagger UI - same above look for v2 option under data 


<img src="images/image8.png">

<img src="images/image9.png">



11. Go to dashboard and click python. Now download secure connect bundle under python and connect to database

<img src="images/image10.png">

12. run bulkinsert python script for batch insert.
run the script - batchinsert.py 


13. CQL to check the record count.

<img src="images/image11.png">
