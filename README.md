# RSQLite

## A hands-on project to learn how databases work

### Abstract

As engineers, we use databases all the time. But how do they work?
In this project I will try to understand how databases really work.
I'll try to do this with a hands-on project by building my own SQLite-compatible database.

### Prerequisites

- sqlite
- rust

#### Building the test Database

```bash
sqlite3 minimal_test.db
sqlite> create table table1(id integer);
sqlite> create table table2(id integer);
sqlite> .exit
```
