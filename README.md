# Day3
create database todo;
use todo;
create table listt(task_id int primary key, task_name varchar(255), description_ varchar(255), is_completed varchar(255));
insert into listt(task_id,task_name,description_, is_completed) values(1,'Exercise','4*12 Sets','Yes');

select * from listt;
