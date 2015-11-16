# Oral_tests_algorithm.sql

drop database if exists 5c;

create database 5c;

create table alunni(

numero int;

);

insert alunni(numero) values(1);

insert alunni(numero) values(2);

insert alunni(numero) values(3);

insert alunni(numero) values(4);

insert alunni(numero) values(5);

insert alunni(numero) values(6);

insert alunni(numero) values(7);

insert alunni(numero) values(8);

insert alunni(numero) values(9);

insert alunni(numero) values(10);

insert alunni(numero) values(11);

insert alunni(numero) values(12);

insert alunni(numero) values(13);

insert alunni(numero) values(14);

insert alunni(numero) values(15);

insert alunni(numero) values(16);


select numero from alunni order by rand() limit 1;
