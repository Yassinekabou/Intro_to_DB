-- SQL script for the ALX Book Store
CREATE TABLE books (
    book_id INT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    author VARCHAR(255),
    published_date DATE,
    price DECIMAL(10, 2)
);
"Add SQL script,"
