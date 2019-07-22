# USING-STORED-PROCEDURE-IN-DB-FIRST-APPROACH-FOR-CRUD-OPERATION ALSO WE USED PARAMETER IN IT 





First Create a DB(angular) then create a table(login) Check Primary key,,and also create a Stored Procedure , after that Create a New Project in VS, Empty MVC, Then In Model Folder add  ADO.net Entity Model, EF designer From DB, create a new connection, give server name, and select DB, give name to your entities , select Table and 3 stored procedure except Select(untick import selected stored procedure ),  edxm diagram will be created , build the solution,and map those three procedure using stored procedure mapping And click on Validate,and now again select update model fro database and select SELECT Stored Procedure(tick import selected stored procedure and function into entity model)(Save File)(select function will get created in Entities class  and then go to Function Import , Right click on Select Procedure=>Select Entities(Employee(table)), A method will get created and we can use that method to call Select Procedure,  For other Procedure do mapping, Then Create Read Write Controller and CRUD View from it

Referece--  https://www.youtube.com/watch?v=UpnJAMCryKE     part1    
                  https://www.youtube.com/watch?v=VELaLOVRlTs        part2

https://www.entityframeworktutorial.net/stored-procedure-in-entity-framework.aspx
https://www.entityframeworktutorial.net/EntityFramework5/CRUD-using-stored-procedures.aspx


https://www.youtube.com/watch?v=whla96PoQo0&t=930s   important
