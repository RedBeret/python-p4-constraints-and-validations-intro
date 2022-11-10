# Intro to Constraints and Validations

## Learning Goals

- Define constraints and validations in data processing.
- Restrict database input to specific formats using constraints.
- Ensure that only acceptable input is sent to the database using validations.

***

## Key Vocab

- **Constraint**: a rule enforced on the data columns of a table. Ensures that
  only appropriate data is saved to the database.
- **Validation**: an automatic check to ensure that data entered
  is sensible and feasible.
- **Forms**: A web form (or HTML form) is a place where users enter data or
  personal information that's then sent to a server for processing.

***

## Introduction

Invalid data is the boogeyman of web applications: it hides in your database
until the worst possible moment, then jumps out and ruins everything by causing
confusing errors.

For most of the curriculum so far, we have been entering our own data. This
isn't always perfectly safe as far as data validity is concerned, but at least
we know that we're causing any errors on our own. Now that we're working on the
web, there are a lot more users capable of causing errors (maybe even in the
hundreds of millions, if you're at Meta or Google).

It is critical (and expected in your Phase 4 project!) that you consistently and
thoroughly validate data in your applications. In this module we will learn how
to deal with invalid data using SQLAlchemy **constraints** and **validations**.

***

## Resources

- [Defining Constraints and Indexes - SQLAlchemy](https://docs.sqlalchemy.org/en/14/core/constraints.html)
- [Changing Attribute Behavior - SQLAlchemy][SQLAlchemy Validations]

[SQLAlchemy Validations]: https://docs.sqlalchemy.org/en/14/orm/mapped_attributes.html
