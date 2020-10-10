# My Bash Scripts
#### A collection of bash scripts I have written for personal use

## Scripts

### Clean Up
Major user directories on my Macbook (`downloads` and `desktop` especially) are usually crowded with different kinds of files: screenshots, mp3 music, videos, documents, e.t.c. This script cleans up major user directories by moving files to where they should be with just one command: `cleanup`.
ie: move all videos to the to `/movies`, audios to `/music`, documents(pdfs, docx, xls, e.t.c) to `/documents` all jpgs/pngs/jpegs to `/pictures` e.t.c.

#### Usage:
Clean up directories: (/downloads, /desktop, /documents, /pictures, /movies)
``` 
cleanup 
```
Clean up a specific directory
``` 
cleanup desktop 
```

### Create Script

This initializes an empty executable file with the executable directive and the `execute` permission set for the current user

##### Usage

```
create_script pushit python
```
creates an empty Python executable script named 'pushit'


```
create_script pushit ruby
```
creates an empty Ruby executable script named 'pushit'
