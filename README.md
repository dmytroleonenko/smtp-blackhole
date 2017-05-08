# smtp-blackhole
Docker smtp-blackhole

# Whats inside?
Built statically from github.com/stone/mail-sink.git using:
```
CGO_ENABLED=0 GOOS=linux go build -a -tags netgo -ldflags '-w' .
```
