DBMS Schema:
https://sqlfiddle.com/mysql/online-compiler?id=0f960b20-854e-45a6-a47c-ec1a4aaa694c


Tables:
- Books (book_id, title, author)
- Students (student_id, student_name)
- IssueRecords (issue_id, book_id, student_id, issue_status)

Primary Keys:
- book_id
- student_id
- issue_id

Foreign Keys:
- book_id → Books
- student_id → Students

Sample SQL Queries:
SELECT * FROM Books;
SELECT * FROM IssueRecords;


