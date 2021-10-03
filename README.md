# MySQL-MuleSoft-Internship
#A query is written in MySQL to retrieve movies table consisting of slno ,actor ,actress ,movie name ,year of release, movie director name and language using SELECT statement. A #query is written in MySQL to retrieve a record using SELECT statement  from movies table with particular actor name using WHERE clause.
#THE QUERY GOES AS FOLLOWS,I HAVE USED AN ONLINE MySQL ONLINE COMPILER.

create table movies(slno integer auto_increment,actor varchar(20),actress varchar(20),moviename varchar(30) releaseyear year,directorname varchar(20),language varchar(20),primary key(slno));

insert into movies(slno,actor,actress,moviename,releaseyear,directorname,language) 
values(1,"ram","illeana","devadas",2006,"chowdary","telugu")

insert into movies(actor,actress,moviename,releaseyear,directorname,language) 
values("varun","aliabhat","badrinath ki dulhania",2017,"shashank","hindi")

insert into movies(actor,actress,moviename,releaseyear,directorname,language) 
values("prabhas","shradhakapoor","saaho",2019,"sujeeth","telugu")

insert into movies(actor,actress,moviename,releaseyear,directorname,language) 
values("chiranjeevi","nayantara","sye raa",2018,"surender reddy","telugu")

insert into movies(actor,actress,moviename,releaseyear,directorname,language) 
values("sharukhan","kajol","kuch kuch hota hai",1995,"aditya chopra","hindi")
    
select * from movies

select * from movies where actor="prabhas"

