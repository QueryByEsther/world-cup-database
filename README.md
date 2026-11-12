# World Cup Database Analysis

## Project Overview

This project involved building a relational PostgreSQL database to store and analyze FIFA World Cup match results from the 2014 and 2018 tournaments.

The database captures teams, match rounds, goals scored, winning teams, and opposing teams. SQL queries were used to extract meaningful information and answer analytical questions about tournament performance.

## Technologies Used

- **PostgreSQL:** Database creation, relational table design, data storage, and querying.
- **SQL:** Data manipulation, aggregation, filtering, sorting, and joining tables.
- **Bash:** Automating database population and executing SQL queries through shell scripts.
- **Git and GitHub:** Version control and project documentation.

## Database Structure

The project uses two relational tables:

### 1. Teams
Stores unique team records.

- `team_id` – Primary key
- `name` – Team name

### 2. Games
Stores individual match records.

- `game_id` – Primary key
- `year` – Tournament year
- `round` – Match stage
- `winner_id` – Foreign key referencing the winning team
- `opponent_id` – Foreign key referencing the opposing team
- `winner_goals` – Goals scored by the winning team
- `opponent_goals` – Goals scored by the opposing team

The tables are connected using primary and foreign keys to maintain relational integrity and avoid duplicate team records.

## Key Technical Skills Demonstrated

- Designing relational database tables.
- Implementing primary keys, foreign keys, and unique constraints.
- Importing and organizing CSV data.
- Writing SQL queries using `SELECT`, `WHERE`, `JOIN`, `GROUP BY`, and aggregate functions.
- Calculating totals, averages, and maximum values.
- Filtering and sorting analytical results.
- Using Bash scripts to automate database operations.
- Connecting shell scripts to PostgreSQL using the `psql` command-line tool.

## Project Files

| File | Description |
|---|---|
| `worldcup.sql` | Database backup containing the database structure and records. |
| `insert_data.sh` | Bash script used to populate the database from CSV data. |
| `queries.sh` | Bash script containing SQL queries for analyzing match results. |

## What I Learned

Through this project, I strengthened my understanding of relational database management, SQL querying, data integrity, and Bash automation.

I also gained practical experience transforming raw CSV data into structured relational data that can be queried to generate useful insights.

## Project Outcome

Successfully created and populated a PostgreSQL database with World Cup match records from 2014 and 2018, and completed the required analytical queries and project tests.

---

**Author:** Esther Murigi

**Focus Areas:** SQL | PostgreSQL | Database Management | Data Analysis | Bash Scripting
