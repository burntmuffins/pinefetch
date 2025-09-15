# pinefetch
a script to fetch informations about your system

<img width="800" height="600" alt="screenshot" src="https://github.com/user-attachments/assets/a67e032c-d955-4b8e-a3f5-c7fa0430c8b7" />

# How to install
## Dependencies required to run the script
- `sed`

## Installation
we can start by cloning the repository:
```
$ git clone https://github.com/burntmuffins/pinefetch
```

now we can `cd` into the directory that we just cloned and make the script executable:
```
$ chmod +x ./pinefetch
```

now copy the script to `/usr/local/bin`:
```
# cp ./pinefetch /usr/local/bin
```
after this, we should be able to run the script by just typing `pinefetch`

## Problems
on Debian based distros, the script output may look very, VERY messed up

to fix this, replace the first line of the file from:
```
#!/bin/sh
```
to
```
#!/bin/bash
```
or any other posix compliant shell.
