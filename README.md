# sql2c: SQL File (mysql) Checker and CSV Dumper

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

## Examples:

``` bash
# Example 1
python ./sql2c -i <file.sql>

# Example 2
python ./sql2c -h
usage: sql2c [-h] -i INPUTFILE [-o OUTPUTDIR]

Python Script to convert sql files to csv.

options:
  -h, --help            show this help message and exit
  -i INPUTFILE, --inputfile INPUTFILE
                        Path to the input file
  -o OUTPUTDIR, --outputdir OUTPUTDIR
                        Path to the output directory
```
``` bash
# Example 1 using uv
uv run ./sql2c -i <file.sql>

# Example 2 using uv
uv run ./sql2c -h
usage: sql2c [-h] -i INPUTFILE [-o OUTPUTDIR]

Python Script to convert sql files to csv.

options:
  -h, --help            show this help message and exit
  -i INPUTFILE, --inputfile INPUTFILE
                        Path to the input file
  -o OUTPUTDIR, --outputdir OUTPUTDIR
                        Path to the output directory
```

