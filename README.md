# Update Go version script

A simple script to update Go version to a specified one.

Simple use:
```sh
$ sudo ./update-go.sh 1.17.6
```

How to dowgrade version:
```sh
$ sudo ./update-go.sh 1.17.5 --force
```

## Attention

- This script doesn't add go binary to your `ENV`.
- You need to `run` with `sudo`.
