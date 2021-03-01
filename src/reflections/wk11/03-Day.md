# Day-3
__2/24/2021__

## What is SQL injection?

SQL injection is where someone takes control of your application by inserting SQL code into your database query. This is an generally an attack by someone with bad intentions.

## What are 3 methods SQL injection can be done by?

One method is through user input. This is where a user includes SQL in a response to a form, which is then passed to the backend and can be used by the database. A Second method is to modify cookies. This will infect a web application's database query. A third method is to use HTTP headers containing SQL to inject code into the database.

## How can we detect and sanitize SQL injection attacks?

SQL injection attacks can be detected by Itrusion Detection System. We can avoid attacks by sanitizing our database inputs. This includes things like avoiding user-supplied input when unnecessary, limiting account privileges, and using stored procedures when possible.

### Afternoon Challenge

https://github.com/JasonSpjute/dntaskmaster