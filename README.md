# MobileApp-Database
Three databases to be worked on:
<ol>
  <li>SQLite Database</li>
  <li>ROOM Database</li>
  <li>Realtime Database</li>
</ol>

> All these implementations of the App follows MVC Architecture.

## SQLite Database
This will help us to use SQL for the CRUD operations. The ContactManager.zip deals with this database management system. Functionalities that have been implemented are:
<ul>
  <li>Create Table</li>
  <li>Insert into table</li>
  <li>Get particular element using ID</li>
  <li>Get all the elements</li>
  <li>Update into inserted elements</li>
  <li>Delete the rows from the table</li>
  <li>Drop the table</li>
  <li>Count number of rows in the table</li>
</ul>
Also we got to use the ContentValues() and Cursor() for the implementations of above mentioned functionalities.

## ROOM Database
This is the library provided by the Android Studio. This also uses SQL but makes our life easier by providing simple ways to implement the whole database management system.
The ContactRoomVersion2.0.zip folder has been implemented using ROOM Database.
<br/>
App Development:
<ul>
  <li>Backend:</li>
  <ul>
    <li>Contact DAO</li>This is where we create an interface using ROOM library to initialize the CRUD functionalities.
    <li>Contact Repository</li>This is where we implement the above functionalities
    <li>Contact View Model</li>This is a class by which we are able to use the functionalites developed above to use in the app.
    <li>ContactRoomDatabaseAdapter</li>This is where we take care of backend implementation of the database by making sure the actual CRUD operations to be held in other thread
    rather than the main thread which is covering the UI of the App.
  </ul>
  <li>Frontend:</li>
  <ul>
    <li>Recycler View</li> This helps us to make effecient use of mobile resources in the actual running of the app.
  </ul>
 </ul>

Whole App has been developed using MVC Architecture. 

> Realtime database to be implemented....
