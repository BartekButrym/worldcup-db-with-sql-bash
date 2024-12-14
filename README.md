# Worldcup Database

The `games.csv` file contains a comma-separated list of all games of the final three rounds of the World Cup tournament since 2014.

## How to run

Rebuild the database by entering in the terminal:

```bash
psql -U postgres < worldcup.sql
```

To insert data to database two script `(.sh)` files should have executable permissions.
You can do that by entering in the terminal:

```bash
chmod +x insert_data.sh
chmod +x queries.sh
```

Insert data by entering:

```bash
./insert_data.sh
```

To run queries run command in the terminal:

```bash
./queries.sh
```
