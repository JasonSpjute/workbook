# Day-4
__2/18/2021__

## In a SQL table, what is the difference between information in a row and information in a column?

Rows are complete objects that are stored in the table. The colomns are the specific properties of the objects.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters(
    name VARCHAR(255),
    age VARCHAR(255),
    description VARCHAR(255),
    id int NOT NULL,
    PRIMARY KEY (id)
);

## What is the difference between the following statements: DELETE FROM table_name; DROP TABLE table_name;

DELETE FROM will delete all the rows from the table without deleting the table itself and it's columns. DROP TABLE will delete the entire table including both rows and columns.

## Afternoon Challenge
https://github.com/JasonSpjute/winter20-burgershack