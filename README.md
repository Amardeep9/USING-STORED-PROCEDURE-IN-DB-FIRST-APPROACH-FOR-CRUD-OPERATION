# USING-STORED-PROCEDURE-IN-DB-FIRST-APPROACH-FOR-CRUD-OPERATION ALSO WE USED PARAMETER IN IT 





First Create a DB(angular) then create a table(login) Check Primary key,,and also create a Stored Procedure , after that Create a New Project in VS, Empty MVC, Then In Model Folder add  ADO.net Entity Model, EF designer From DB, create a new connection, give server name, and select DB, give name to your entities , select Table and all stored procedure, edxm diagram will be created , build the solution, and then go to Function Import , Right click on Select Procedure=> Complex name=>Select Entities(table), A method will get created and we can use that method to call Select Procedure,  For other Procedure do mapping, Then Create Read Write Controller and CRUD View from it

Referece--  https://www.youtube.com/watch?v=UpnJAMCryKE     part1    
                  https://www.youtube.com/watch?v=VELaLOVRlTs        part2

https://www.entityframeworktutorial.net/stored-procedure-in-entity-framework.aspx
https://www.entityframeworktutorial.net/EntityFramework5/CRUD-using-stored-procedures.aspx
