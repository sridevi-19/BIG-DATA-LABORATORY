CREATE KEYSPACE Students WITH REPLICATION = {
'class':'SimpleStrategy',
'replication_factor':1
};
CREATE KEYSPACE Students WITH REPLICATION = { 'class':'SimpleStrategy', 'replication_factor':1 };
CREATE KEYSPACE Employee WITH REPLICATION = { 'class':'SimpleStrategy', 'replication_factor':1 };
describe keyspaces
use employee
;
use employee ;
CREATE TABLE Employeeinfo(Empid int PRIMARY KEY, empname text, date timestamp,designation text salary int, dept text);
CREATE TABLE Employeeinfo(Empid int PRIMARY KEY, empname text, date timestamp,designation text, salary int, dept text);
describe tables
BEGIN BATCH
insert into employeeinfo(empid,empname,date,designation,salary,dept)
values(1,'ABC','2020-12-12','hr',10000,'sales');
apply batch
;
BEGIN BATCH insert into employeeinfo(empid,empname,date,designation,salary,dept) values(1,'ABC','2020-12-12','hr',10000,'sales'); apply batch ;
select * from employeeinfo;
update employeeinfo SET empname='efg' where empid=1;
select * from employeeinfo;
update employeeinfo SET empname='efg' and dept='abc' where empid=1;
update employeeinfo SET empname='efg', dept='abc' where empid=1;
select * from employeeinfo;
exit
