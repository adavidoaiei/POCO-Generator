# POCO-Generator

<img src="https://s3.amazonaws.com/codegenerator/3c75c4da782c0fba2108779781e05c70047b697b.jpg" />

While starting to code for any new application we are required to write POCO (Plain Old CLR Objects) classes for our database tables as Models (if you are using any ORM for data access) and we also need the stored procedures for our database tables. The process is simple but most of time repetitive and just like other developers I try to avoid it, so I wrote this simple windows forms application which helps me create database tables of POCO/model classes, base repository and related repository classes for the database tables in order to use EntityFramework Code First ORM framework (which I mostly use in my web applications) and basic stored procedures scripts (like insert, update, delete etc) for the selected database tables. This saves time and helps me to avoid writing repetitive code.

This application is primarily targeting databases designed in SQL Server.
