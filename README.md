# Dir Checksum
A bash shell script used to compute a directory(folder) checksum and output change information.

## Details
It computes md5sum of all files in one directory recursively and saved to a checksum file in it. Subsequent execution on that directory will compare the last checksum with current one and report missed/added/modified files.

## Dependent commands
```md5sum/md5; diff; comm; xargs; find; sort; grep; sed; rm; mv; wc; cut; uniq```

## Optional commands
```pv```
(use ```brew install pv``` to get progress bar for large folders)
 
## Notice

Tested in Ubuntu Linux and macOS.

