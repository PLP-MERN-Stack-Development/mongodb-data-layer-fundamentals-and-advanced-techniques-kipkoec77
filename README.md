# MongoDB Week 1 Assignment

## How to Run the Scripts

### Prerequisites
- Node.js installed
- MongoDB Atlas account
- All dependencies installed (`npm install`)

### Step 1: Populate the Database
Run the script to insert sample book data into your MongoDB Atlas database:

```bash
node insert_books.js
```

This will:
- Connect to your MongoDB Atlas cluster
- Create the `plp_bookstore` database
- Create the `books` collection
- Insert 12 sample books with complete metadata

### Step 2: Run All MongoDB Queries
Execute all the required MongoDB operations:

```bash
node queries.js
```

This will run all assignment tasks:
- Basic CRUD operations
- Advanced queries with projection and sorting
- Aggregation pipelines
- Indexing with performance analysis

### What You'll See
Both scripts will show detailed output including:
- Connection status
- Operation results
- Query outputs
- Performance metrics

### Files Included
- `insert_books.js` - Database population script
- `queries.js` - All MongoDB operations and queries
- `package.json` - Dependencies configuration

### Troubleshooting
If you encounter connection issues:
1. Check your MongoDB Atlas connection string
2. Ensure your IP is whitelisted in Atlas
3. Verify your username and password are correct
4. Make sure the cluster is running

That's it! Your MongoDB assignment is ready to run.
