# matrix-send
Send messages to matrix from command line

Add some changes to use the script as matrix notifications plugin for monitoring tool.

```
$ matrix-send.py --help
usage: matrix-send.py [-h] [--config CONFIG] [--level LEVEL] [message]

Matrix Sender

positional arguments:
  message          Send this message

optional arguments:
  -h, --help       Show this help message and exit
  --config CONFIG  Read given configuration file
  --level LEVEL    Specify alert level (message and notification "design")
```

Most aggresive notifications level are  DOWN and ERROR.
Then WARNING and UNKNOWN, then UP as the most low level.
