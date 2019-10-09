### Dump database from MongoDB

`mongodump --db={{DB_NAME}} --out={{DESTINATION_DIRECTORY}}`

- <b>DB_NAME: </b> Database's name.
- <b>DESTINATION_DIRECTORY:</b> Directory to save the output files. However, it is an optional parameter. By default, the command saves the registers in the current path.

#### Example:

`mongodump --db=ak-cli --out=/arshad/ak-cli/db/dump`
