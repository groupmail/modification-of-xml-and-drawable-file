 Report  of database problem 
The major problems we face :-
**The slowdown of the app and the duplication  those were caused by  inserting data of our font  after launching the  app more than one time also, this cause crash to the app.

Solution of this problem :- 
**we decided to create our database out Dbhealper  class to prevent inserting data every time we use our app ,therefore prevent the duplication 
--steps of our solution :-
1-  insert the  database in excel  file
2-convert the excel file to database access file  
3- we import access file in  SQLite database  by using  navigate premium  program  
4- inside the SQLite database we created android meta data file 
5-we put (.db file) that produced by navigate premium  program  in  the asset  file  of our app 
6- inside Dbhealper we :-
i)	first we removed insert function 
ii)	call (ASL.db)  in this class by put its path and the name of this file
iii)	change the Quarry that was creating the old database to SELECT QUERRY  

   
