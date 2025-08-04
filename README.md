✅ 1. Chosen Domain:
Library Management System 📚

✅ 2. Identified Entities & Relationships:
📦 Entities:
    -Authors
    -Books
    -Members

🔗 Relationships also known as Cardinalities:
--> One Author can write many Books → Books.author_id is a foreign key referencing Authors.author_id
--> Members can borrow books (you can later add a Loans table if needed)

✅ 3. Created Tables using CREATE TABLE command

✅ 4. Defined Primary and Foreign Keys:
Primary keys: author_id, book_id, member_id

Foreign key: Books.author_id (author_id from Books table) → Authors.author_id (author_id from Authors table)
