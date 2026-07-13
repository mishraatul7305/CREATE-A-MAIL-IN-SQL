# CREATE-A-MAIL-IN-SQL 
use college;
create table mail(id int , name varchar(20), mailid varchar(30));
select * from mail;
insert into mail(id, name , mailid)values(1, 'atul', 'atul@gmail.com');
select * from mail;
insert into mail(id, name , mailid)values(2, 'anup', 'anup@gmail.com');
select * from mail;
insert into mail(id, name , mailid)values(3, 'anoop', 'anoop@gmail.com');
select * from mail;
insert into mail(id, name , mailid)values(4, 'maya', 'maya@gmail.com');
select * from mail;
insert into mail (id,name,mailid)values(5,'amit', 'amit@gmail.com' ) ;
drop table mail;


