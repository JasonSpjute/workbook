# Day-4
__2-11-2021__

## In a SQL table, what is the difference between information in a row and information in a column? How does this compare to using a document database?

Rows are complete objects. Columns are specific properties of that object. A document database just holds the objects with the properties.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

Create table Characters(
    id int NOT NULL,
    name VARCHAR,
    age VARCHAR,
    description VARCHAR

)

## What is the difference between the following statements. "Delete from table_name;" "Drop table table_name"?

DELETE FROM is a command used to delete a row of data from a table. DROP TABLE is used to delete an entire table.