# MongoDB – Notes

## What is MongoDB?

**MongoDB** is a NoSQL database.  
It stores data in **JSON-like format (BSON)** instead of using traditional table-based layouts like relational databases such as:

- Microsoft SQL Server  
- MySQL  
- PostgreSQL  

MongoDB does not use rows and columns like relational databases.

MongoDB is a **document-based database**.

---

## What is a NoSQL Database?

A **NoSQL database** stores data in formats other than tabular relationships.

Unlike relational databases:
- Data is **not stored in tables**
- Data is stored as **key-value pairs**
- It can also be stored as **documents, graphs, or wide-column stores**

MongoDB specifically uses the **document model**.

---

## Why is MongoDB Used?

MongoDB is popular because it is:

- Open-source  
- Easy to use  
- Highly flexible  
- Schema-less (Flexible schema)  
- High performance  
- Advanced security  
- Powerful query language  
- Reliable indexing  
- Horizontally scalable  

---

## Accessing MongoDB from Command Prompt

To access MongoDB from the command line:

```bash
mongosh
```

Steps:
1. Make sure MongoDB Shell is installed.
2. Open Command Prompt (or Terminal).
3. Type `mongosh`
4. The MongoDB shell will start.

---

## Important MongoDB Software Tools

There are four important tools in MongoDB:

### 1️⃣ Mongo Shell (`mongosh`)
- Command-line interface
- Execute MongoDB commands directly

### 2️⃣ MongoDB Compass
- GUI tool
- Create, view, and modify data visually

### 3️⃣ MongoDB Drivers
- Connect MongoDB with programming languages
- Available for Java, Python, Node.js, C#, etc.

### 4️⃣ MongoDB Atlas
- Cloud-based MongoDB service
- Fully managed online database platform

---

## MongoDB vs SQL Database (Conceptual Difference)

| SQL Database | MongoDB |
|-------------|----------|
| Tables | Collections |
| Rows | Documents |
| Columns | Fields |
| Fixed Schema | Flexible Schema |
| Structured Data | Semi-structured Data (JSON/BSON) |

---