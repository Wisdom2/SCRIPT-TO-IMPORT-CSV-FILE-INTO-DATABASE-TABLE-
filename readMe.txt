-- copy and run the code below in your phpmyadmin
=================================================

create database mycsv;

create table articles(
    id int(5) primary key auto_increment,
    int_value varchar(5),
    title varchar(70),
    msg text,
    created_at varchar(30),
    updated_at varchar(30)
);
