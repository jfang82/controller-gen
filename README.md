controller-gen
==============

Generate Kubernetes controller stubs that sync configurable resource types

## Installation

Install Go 1.9+
`go get github.com/llparse/controller-gen`

## Usage

```sh
controller-gen \
  --input-dirs k8s.io/api/core/v1 \
  --output-base "$GOPATH/src" \
  --output-package "github.com/llparse/controller-gen/example_generated" \
  --go-header-file /dev/null \
  --name example \
  -v 3
```

