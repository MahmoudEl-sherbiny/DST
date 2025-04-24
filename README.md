# MongoDB CRUD Operations with PyMongo

This script demonstrates how to perform basic **MongoDB operations** using Python's `pymongo` library. It includes creating, reading, updating, and deleting documents across multiple collections in a MongoDB database.

## 🔌 Database Connection
- Establishes a connection to a local MongoDB server using `MongoClient()`.
- Accesses a database named `FCDS`.

---

## 👔 Employees Collection

1. **Insert One Employee**
   - Adds an individual employee document for `Hagar Nassar`.

2. **Insert Multiple Employees**
   - Adds a batch of 9 employee documents with fields: `Name`, `Address`, `Age`, and `salary`.

3. **Delete One Employee**
   - Removes the document where `Name` is `Mia Martinez`.

4. **Delete Many Employees**
   - Removes employees with `Age > 35`.

5. **Update Many Employees**
   - For employees where `Age > 30`, updates the `salary` field to `"4000$"`.

6. **Update One Employee**
   - Updates `Hagar Nassar`'s salary to `"5000$"`.

7. **Display Employees**
   - Prints all remaining employee documents using `pprint()`.

---

## 🎓 Students Collection

1. **Insert One Student**
   - Adds a student document for `Mahmoud Elsherbiny`.

2. **Update the Student**
   - Adds a `Department` field: `"Computing & Data Science"`.

3. **Insert Multiple Students**
   - Adds 5 more student documents with additional fields `Department` and `ID`.

---

## 📚 Courses Collection

1. **Create Collection**
   - Creates a new collection named `Courses`.

2. **Insert Courses**
   - Inserts 3 courses: `Linear Algebra`, `Probability I`, and `Calculus`.

3. **Drop Collection**
   - Deletes the `Courses` collection from the database.

---

## ✅ Summary
This script serves as a comprehensive demonstration of:
- Inserting single and multiple documents
- Querying documents
- Updating fields within documents
- Deleting documents
- Managing multiple collections

It also shows how to use `pprint()` for clean output formatting.

This is a great starter example for anyone learning how to work with MongoDB in Python!

