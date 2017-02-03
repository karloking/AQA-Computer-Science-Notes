#SQL

**Query** - this is a question posed to the database. This is done using SQL. SQL (Structured Query Language) is a programming language designed to manage data with a relational database.

> * Be able to use SQL to retrieve, update, insert and
> delete data from multiple tables of a relational
> database.
> * Be able to use SQL to define a database table.

## Query Methods
### Fetching Data using SQL
>	* **The SELECT, FROM clause**:
>	  * **SELECT * FROM table1**
>	    *This retrieves all of the information from ’table1’
>	* **SELECT Name, ID, D.O.B FROM table1**
>	  * This retrieves data from columns ‘Name’, ‘ID’ and ‘D.O.B’ from ‘table1’ 
>	  * The column will be shown in this order


>* **The WHERE clause**:
> 	* **SELECT Name, ID, D.O.B FROM table1 WHERE ID = 10**
>	    * This does the same as before but only selects the data whose ID is not equal to 10 (= means equal to)


>* **ordering results from an SQL SELECT query**:
>  * **ORDER BY column-name ASC**
>	    * The ASC means the results are ordered alphabetically.
> ```
>  SELECT Name, ID, D.O.B, BookName
>  FROM Users, Books
>  WHERE Users.ID = 10 and Books.ID = 10
>  ORDER BY BookName ASC
>```
>    *This retrieves data from columns ‘Name’, ‘ID’ and ‘D.O.B’ and 'BookName' FROM 'Users' and 'Books'.*
>    *`WHERE Users.ID = 10 and Books.ID = 10` select data where ID = 10 on both tables to show what BookName has been borrowed.*
>    *`ORDER BY BookName ASC` Order the data retrieved by the name of the books in alphabetical order.*
>


