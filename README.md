# Travel-TourDesktopApp
**** Run TravelAndTour.java file

Create database first using this commands.
1.  create database tms;
2.  use tms;
3.  create table account(username varchar(30), name varchar(40), password varchar(30), question varchar(100), answer varchar(50));
4.  create table customer(username varchar(30), id_type varchar(20), number varchar(20), name varchar(30), gender varchar(15), country varchar(20), address varchar(50), phone varchar(20), email varchar(40));
5.  create table hotels(name varchar(30), cost_per_day varchar(20), food_charges varchar(20), ac_charges varchar(20));
6.  insert into hotels values("Hotel1-name", "per day cost", "food cost", "ac charges"); //this way you can add hotels
7.  create table bookHotel(username varchar(30), name varchar(30), persons varchar(20), days varchar(20), ac varchar(10), food varchar(10), id varchar(30), number varchar(20), phone varchar(20), cost varchar(20));
8.  create table bookPackage(username varchar(30), package varchar(40), persons varchar(20), id varchar(30), number varchar(20), phone varchar(20), price varchar(20));

******next configure your database connection in Conn.java file. Put your database url, mysql username and password
******add mysql-connector and rs2xml jar file to library

***** now your file is ready to launch. Hope you enjoy
