# jiramttr

Use JIRA tickets to measure MTTR (Mean Time To Recover)

## Command

```
cd mttr
go get
go build
./mttr -url <jira rest api url> -month 2018-08
```

Response will be something like
```
MTTR is 2798044 seconds, 32.4 days
```
