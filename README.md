# Database-week-5
SQL Database
-- Create the database
CREATE DATABASE StudentsDB;

-- Switch to the newly created database
USE StudentsDB;

-- Create the table for storing student information
CREATE TABLE Students (
    StudentID INT AUTO_INCREMENT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    DateOfBirth DATE,
    Email VARCHAR(100),
    Major VARCHAR(100)
);

