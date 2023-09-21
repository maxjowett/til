# Generate a UUID

I use UUIDs frequently for generating datasets to seed database tables.

```
$ uuidgen
6545441A-A1F1-4C59-A454-BD023FB8688A
```

At some point at work we decided to use lowercase letters, to accomplish that, pipe the result into `tr` as follows:

```
$ uuidgen | tr '[:upper:]' '[:lower:]'
5e2f9c9c-49a7-4eef-8107-c027a95ede8d
```

Get fancy and make a script that runs the command above, and pipes the result to your clipboard so you can paste it wherever you need it. As seen below:

```
$ uuidgen | tr '[:upper:]' '[:lower:]' | pbcopy
```

`pbcopy` will only work on macOS.

