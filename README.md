# go-lints
A script for calling multiple go lint tools.

# Usage
```
Usage of lint:
  -golint      only use golint to check code
  -gocyclo     only use gocyclo to check code
  -cilint      only use golangci-lint to check code
  -gosec       only use gosec to check code
  -e           interrupt script when detect error

example:
  "go-lints -golint"    only use golint to check code
  "go-lints -gosec -e"  only use gosec and exit on error
```
# Tool
[golint](https://github.com/golang/lint)
[gocyclo](https://github.com/fzipp/gocyclo)
[gosec](https://github.com/securego/gosec)
[golangci-lint](https://github.com/golangci/golangci-lint)
