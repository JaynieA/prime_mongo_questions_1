# Prime Mongo Shell Solo Challenge

Now that I have been introduced to some of the basics of querying MongoDB via the mongo shell, I will use that information to query a collection of bios.

## Instructions

### Setup

1. Load the data using this command `mongoimport --db challenge --collection bios --drop --file bios.json`
2. Start the Mongo shell with `mongo`.
3. Connect to the `challenge` database using the mongo shell command `use challenge`

### Queries

Create a file, `queries.js` that will contain the queries that correctly address the criteria in the
steps that follow.

1. Find documents that have awards.
2. Find documents that don't have awards.
3. Find documents that have contribs for OOP or UNIX.
4. Find documents with "Turing Award" awards.
5. Find documents with IDs between 3 and 7.
6. Find documents with awards that were awarded before the year 2000.
7. Find documents with birth dates, but no death dates.
