# Create a log of your day, using Alfred.

## Use

Type 'log' followed by your message.

e.g
```
log Filing in TPS reports
```

This will create a file in your ~/Dropbox/Timelog directory, with this line, and a timestamp in it.

## Configuration

Open the workflow and edit the bash script. Change the first line to change which directory the log is created in.

```sh
LOG_DIR=~/Dropbox/Timelog
```
