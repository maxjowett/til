# Pipe Output Into New Vim Buffer

Often times when running a command in the terminal, the result spits out into your terminal and is troublesome to deal with and sift through.

To make dealing with the output easier, pipe the output into a new empty vim buffer like so:

```
$ echo foo | vim -
```

You're now able to use standard vim keybindings to search and navigate the output.

