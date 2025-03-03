# sql2c: SQL File Checker and CSV Dumper

## Purpose:

* Validates SQL file syntax.
* Optionally dumps SQL Data to CSV.

## Features:

* Checks SQL file syntax for errors.
* (Optional) Executes valid SQL queries.
* (Optional) Exports query results to CSV files.
* User-defined CSV output directory.

## Requirements:

* Python 3.12
* Python libraries:
    * Docker
    * mysql-connector-python
    * tqdm
* `.sql` file as input.

## Installation:

* Clone or download script.
* `cd` into the directory.
* Run
    * ``` bash
    uv run sql2c -i <file.sql>
    ```

