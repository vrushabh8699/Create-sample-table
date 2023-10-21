# Create-sample-table
creating table in sql queries
create table student
(
 RollNo int primary key identity,
 Name varchar(50),
 Gender varchar(50),
 Gmail varchar(50),
 Age int check(age>0 and age<=150)
)
go
insert into student values ('rahul','male','ra@r.com',85),('sonu','female','sa@s.com',45),
('vrushabh','male','va@v.com',15),('nilesh','male','na@n.com',47)
select * from student
