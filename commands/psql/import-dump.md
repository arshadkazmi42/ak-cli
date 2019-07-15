### Import Database Dump

`psql -h {{HOST}} -d {[DATABASE]} -U {{USERNAME}} -f {{FILE_NAME}}`

- <b>HOST</b>:  Hostname
- <b>DATABASE</b>:  Database name
- <b>USERNAME</b>:  Databse username
- <b>FILE_NAME</b>:  Filename/path of the sql dump file

#### Example:

`psql -h ak-cli-12qq1ww1w.rds.amazonaws.com -d ak-cli-database -U ak-cli-user -f ak-cli-dump-july-2019.sql`

### Related

- [Export Dump](export-dump.md)
