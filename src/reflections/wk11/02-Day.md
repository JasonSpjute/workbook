# Day-2
__2/23/2021__

## What is the difference between a primary key and a foreign key

A primary key is a unique information used to identify a specific record within a table. A foreign key is a reference to the primary key from another table. This allows you to keep refence to that specific record from another table.

## What is an Alias?

An alias can be used in place of writing out the full name of a table. It is declared following the first instance of the written table name. This allows you to have more condensed code, but keep it readable.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorspatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

@"
SELECT
p.*,
dp.id as DoctorPatientId
FROM doctorpatients dp
JOIN patients p ON vk.keepId = p.id
WHERE doctorId = @id;";

### Afternoon Challenge

https://github.com/JasonSpjute/contract_manager