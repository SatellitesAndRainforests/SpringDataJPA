SpringJPA, Hibernate, 

+ Encapsulate complexity for simplified interactivity with a database.

SpringDataJPA with JPA with Hibernate ... objects and ORM (Object Relational Model).

Map classes to database tables
Repository (Data Access Layer) for CRUD functionality.
again, encapsulates complexity, to reduce boilerplate code, for database interactivity.
JPAReposity for {'crud','flush','batch'} functionality, extends 'PagingAndSorting','Crud' repositories. 

+ JPARepository
By extending this interface and passing the mapped class and it's pk, we can use all of it's crud functionality, methods {.save(), .find(), .delete() ... } 

-- commands--------------------------------------------------------
with postgresql and postgresql-contrib installed (ubuntu 20.04)

$ sudo systemctl start postgresql.service
$ sudo -i -u postgres
$ psql


------------------------------------------------------------------


