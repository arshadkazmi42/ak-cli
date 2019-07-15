### Export Database Dump 

`pg_dump -U {{USERNAME}} -h {{HOST}} {[DATABASE]} > {{DUMP_FILE_NAME}}`

- <b>USERNAME</b>:  Databse username
- <b>HOST</b>:  Hostname
- <b>DUMP_FILE_NAME</b>:  Filename/path to store the dump into. (This should be `.sql` file)

#### Example:

`pg_dump -U ak-cli-user -h ak-cli-12qq1ww1w.rds.amazonaws.com ak-cli-database > dump-july-2019.sql`


### Related

- [Import Dump](import-dump.md)
