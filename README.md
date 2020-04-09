# My Bash Scripts
#### A collection of bash scripts I have written for personal use

## Scripts

### Clean Up
Major user directories on my Macbook (`downloads` and `desktop` especially) are usually crowded with different kinds of files: screenshots, mp3 music, videos, documents, e.t.c. This script cleans up major user directories by moving files to where they should be with just one command: `cleanup`.
E.g: moves all videos to the to `/movies`, mp3s/m4as to `/music`, documents(pdfs, docx, xls, e.t.c) to `/documents` all jpgs/pngs/jpegs to `/pictures` e.t.c.

#### Usage:
Clean up all directories (/downloads, /desktop, /documents, /pictures, /movies)
``` 
cleanup 
```
Clean up a specific directory
``` 
cleanup desktop 
```
