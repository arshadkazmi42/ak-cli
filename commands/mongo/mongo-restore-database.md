### Restore database to MongoDB

`mongorestore --db={{DB_NAME}} --drop {{PATH}}`

- <b>DB_NAME: </b> Database's name.
- <b>PATH:</b> Path to the backup. 
- <b>drop:</b> Optional flag to remove the collections from the database before restoring from backup.

#### Examples:

`mongorestore --db=ak-cli /arshad/ak-cli/db/dump/ak-cli`

`mongorestore --db=ak-cli --drop /arshad/ak-cli/db/dump/ak-cli`

#### Related Commands

- [Dump database from MongoDB](mongo-dump-database.md)
