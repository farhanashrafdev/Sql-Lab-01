create database Farhan;
use Farhan;
create table employee1 (name nvarchar(20),ID int,JOB nvarchar(8),Manager nvarchar(17),salary int,  );
insert into employee1 values ('Farhan Ashraf','1','CEO','None','15000000');
insert into employee1 values ('Awais Saleem','2','Devel','None','15000');
insert into employee1 values ('Bill Gates','3','JR dev','None','14000');
insert into employee1 values ('Ben 10','1','Jr dev','None','13000');
insert into employee1 values ('James Charles','1','asistant','None','12000');

Create Table DEPARTMENT 
 (Department_No int ,
 Department_Name varchar(25),
 Location varchar (20));
 insert into department values(1, 'English', 'Lahore' );
 insert into department values(2, 'Urdu', 'Lahore' );
 insert into department values(3, 'Computer', 'Lahore' );
 insert into department values(1, 'finance', 'Lahore' );
 insert into department values(6, 'Science', 'Lahore' );


 --TASK 1------------------------------------------------------------------------------------------
 --1  printing employee
 select * from employee1;
 --2 print department
 select * from department;
 --3 print both
 select * from employee1,department;
 --4 query 4
 select name ,JOB,ID from employee1
 --5 query 5
 select name, salary from employee1

---------------------------------------------------------------Task2---------------------------------
-- 1
 select name, salary*12 "Annual Salary" from employee1
 --2
 select name,salary*12 "Monthly Salary" from employee1;
 --3
 select distinct department_no from DEPARTMENT;
 select distinct * from DEPARTMENT
 --4
  select distinct ID from employee1;
  ----------------------------------------------------TASK 3----------------------------
  --1 
  select * from employee1 order by name desc;
  select * from employee1 order by name asc;
  --2
  select ID,name,salary from employee1 order by salary asc;
  --3
  select upper (name)"Name" from employee1;
  --4
  select lower (JOB)"JOB" from employee1;
  --5
  select CONCAT (name,' is assigned to ID=  ',ID)"Concatinated String" from employee1
   select CONCAT (name,' is assigned to ID= ',ID,' and  Has salary ', salary)"Concatinated String" from employee1
   -----------------------------------------------------task 4-----------------------------------------
   --1
   select substring(name,1,2)from employee1 ;
   --2 
   select substring(location,1,3)from DEPARTMENT;
   --3
   select 171*214+625 "Calculation";
   --4
    select 121*22+44 "RESULT";
	--5
	select ' Farhan Ashraf  03-134182-037 '"My details";
	-------------------------------------------------------------------------------------------------------------------
  





