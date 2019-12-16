# webhook

A simple webhook server for use with Gophish events.

# Installation

```
go get github.com/gophish/gophish
```

# Usage

```
./webhook --help
usage: webhook [<flags>]

Flags:
      --help              Show context-sensitive help (also try --help-long and --help-man).
  -u, --path="/webhook"   Webhook server path
  -p, --port="9999"       Webhook server port
  -h, --server=127.0.0.1  Server address
  -s, --secret=SECRET     Webhook secret
```