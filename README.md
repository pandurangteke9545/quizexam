Database Command

create database velocity;
use velocity;

create table quize(Questiions varchar(255), Answers varchar(255));

insert into quize values('Who invented java language?','James gosling');
insert into quize values('In which year java is inroduced?','1995'),
('How many primitive datatypes are their in java?','eight'),
('What is default value of string?','null'),
('What is the size of short variable?','16bits'),
('which component is used to compile java program?','JDK'),
('Which one of the following is not a java feature?','Use of Pointer'),
('What is the extension of java code file? ','.java'),
('Which of the following is not OOPs Concept?','compilation'),
('Which of the following is selection statement of java?','if');

select * from quize;

create table student(Name varchar(255), ID int not null primary key ,
Score int);

