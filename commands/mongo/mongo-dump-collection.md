### Dump single collection from MongoDB

`mongodump --db={{DB_NAME}} --collection={{COLLECTION_NAME}} --out={{DESTINATION_DIRECTORY}}`

- <b>DB_NAME: </b> DB to get backup from
- <b>COLLECTION_NAME: </b>Collection which needs to be dumped in destination directory
- <b>DESTINATION_DIRECTORY: </b>Directory/path where to dump the backup collection

#### Example:

`mongodump --db=ak-cli --collection=cli_commands --out=/arshad/ak-cli/db/dump`

#### Related Commands

- [Restore collection to mongoDB](mongo-restore-collection.md)
