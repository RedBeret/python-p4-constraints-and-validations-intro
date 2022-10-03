# Validations Introduction

## Learning Goals

- Learn about validation and how to deal with invalid data

***

## Key Vocab

- **Validation**: Validation is an automatic check to ensure that data entered is sensible and feasible.
- **Forms**: A web form (or HTML form) is a place where users enter data or personal information that's then sent to a server for processing

***

## Introduction

Invalid data is the bogeyman of web applications: it hides in your database
until the worst possible moment, then jumps out and ruins everything by causing
confusing errors.
In this module we will learn how to deal with invalid data.
Using validators we will check the data we are passing into the database and we will validate forms using the Flask-WTF library.

***

## Resources

- [SQLAlchemy Validations][SQLAlchemy Validations]
- [Flask-wtf](https://flask-wtf.readthedocs.io/en/1.0.x/)

[SQLAlchemy Validations]: https://docs.sqlalchemy.org/en/14/orm/mapped_attributes.html
