# Restaurant Invoice System :

In this project my aim to create a restaurant invoice system whose provide by the restaurant to the customer.

## Technology & Concept:

In this I am using only command line interface. Mysql is used for database storing the username and password. File handling used for saving the invoice soft copy in text form. You can see on the directory customer in the project and regular expressions and list operations are used for creating the total ammount of the all items in the invoice. 

## System Requirements:

• Python 3.7 [download](https://www.python.org/downloads/)

• Mysql : If need in your system you can be download and install on [link](https://www.mysql.com/downloads/)
    
  ◦ Write command in cmd  pip install pymysql for link between mysql and python.

* I am curently using window 10 operating system

## How to run:

* Open cmd on location where you are save/download project and write the command python Resturant.py ->press enter like:

![cmd](/images/cmd.png)

* After some time the following is appear:

![open file in cmd](/images/login.png)

* Enter user root and password is root which you are enter unter the db restaurant and  in the mysql table like login:
 
   * Firstly you are create a database in mysql name restaurant and create a table under the restaurant database name login. 
    
    ![first screen](/images/database1.png)

    ![change database](/images/changedatabase.png)
    
   * Enter the user whose want to login in yours software like following users:

    ![table data show](/images/tablesdatashow.png)

* Login by the user given into the mysql login table.

* After login the add the customer details like customer number, name, address, mobile number ,allocated table(like following):

![Add Customer](/images/customer.png)

* Select the items under the course whose want to customer :

![Course item select](/images/courseselect.png)

* When you selcet a course then automatically show the Course Detial like following :

![Course item select](/images/showpricelistcourse.png)

* After selection the dishes click on the final button and the click on the bill button:

![Final Bill](/images/finalbill.png)
