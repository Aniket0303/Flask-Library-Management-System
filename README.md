# Flask-Library-Management-System
A library management system is software designed for the purpose of managing all the functions of a library.
(Built with flask, jinja, sqlite)

--> A library management system is used for maintaining accurate library records by keeping track of: 
   
      * The records of the number of books in the library.
      * How many books are issued.
      * How many books have been returned.
      * List of all members.
      * Graph which shows the top 10 borrowed books and top 10 paying members.
    
--> Install all requirements with
      
       pip install -r requirements.txt
 
--> Set your secret key in /library/__init__.py file

--> For creating a local DB

    python
    >> from library import db
    >> db.create_all()
    
    
--> run command to start the server
    
    flask run
