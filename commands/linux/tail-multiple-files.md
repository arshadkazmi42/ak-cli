### Tail Multiple File

- It print content of all the files with file name as header of the content

`tail -n +1 {{FILES_PREFIX}}*`

- <b>FILE_PREFIX</b>: Prefix for the files to tail. It can also be an empty string to tail all the files of the directory

#### Example

`tail -n +1 ak*`

or 

`tail -n +1 *`

#### Related

- [Tail File](tail-one-file.md)