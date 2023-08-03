Time information on [[Linux]]

From stackexchange: https://unix.stackexchange.com/questions/14728/ls-how-do-i-list-directories-sorted-by-timestamps-of-the-files-it-contains

```
ls -ltcr         # sort by and show change time, most recent last
ls -ltur         # sort by and show access time, most recent last
ls -ltr          # sort by date, most recent last
```