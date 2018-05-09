# Gomon

`gomon` forks from acoshift/goreload and remove unused features.

Just run `gomon` in your app directory.
`gomon` will automatically recompile your code when it
detects a change.

## Installation

```shell
go get -u github.com/TonPC64/gomon
```

## Basic usage

```shell
gomon .
```

Options

```txt
   --bin value, -b value         name of generated binary file (default: ".gomon")
   --path value, -t value        Path to watch files from (default: ".")
   --build value, -d value       Path to build files from (defaults to same value as --path)
   --excludeDir value, -x value  Relative directories to exclude
   --all                         reloads whenever any file changes, as opposed to reloading only on .go file change
   --godep, -g                   use godep when building
   --buildArgs value             Additional go build arguments
   --logPrefix value             Setup custom log prefix
   --notifications               enable desktop notifications
   --help, -h                    show help
   --version, -v                 print the version
```
