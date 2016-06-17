# Cangjie-Database-Builder
A simple C program for building a SQLite3 database that contains cangjie code mapping. The database is optimized to get the input code from a given Chinese character.

This project is forked from [libcanjie](https://github.com/Cangjians/libcangjie). Anything but cangjie table files and the code for building a database from the table are removed becasue this project focuses on building database only.

## How to build
    $ gcc -o dbbuilder dbbuilder.c -lsqlite3 

## How to use
    ./dbbuilder table.txt cangjie.db
