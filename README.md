# PRT563 Assessment 4 – Sydney Group 6

Moving our Assessment 2 real estate database from SQL to **Neo4j**.

Group: Adarsha Luitel (s401477), Abhishek Poudel (s400605), Ashish Dhakal (s395996), Bishal KC Chhetri (s396125)

## Files

- `import.txt` – Task 2: Cypher script that imports the CSV files and creates constraints and indexes
- `data/` – all CSV files used by `import.txt`
- `queries.txt` – Task 3: four Cypher queries
- `gds_algorithms.txt` – Tasks 4 and 5: centrality and similarity (GDS library)

## How to run

1. Neo4j Desktop with Neo4j 5.20.0 and the APOC and Graph Data Science plugins.
2. Copy all files from `data/` into the database's **import** folder.
3. Start the database, open Neo4j Browser and run `import.txt`.
4. Run the queries in `queries.txt` and `gds_algorithms.txt` one at a time.
