# Grep Invert Match

I'm frequently scanning through log files looking for specific values such as a specific response code. Often times I'm parsing through a file where a large amount of 401 codes are cluttering the file making it difficult to find the less frequently occuring codes.

```
$ grep -v 401 <your-log-file>
```

The command above inverts the matching case, filtering out all lines that contain `401`, making the log less difficult to parse through.

