[![GoDoc](https://godoc.org/github.com/garsue/watermillzap?status.svg)](https://godoc.org/github.com/garsue/watermillzap)
[![Release](https://img.shields.io/github/release/garsue/watermillzap.svg)](https://github.com/garsue/watermillzap/releases/latest)
[![Go Report Card](https://goreportcard.com/badge/github.com/garsue/watermillzap)](https://goreportcard.com/report/github.com/garsue/watermillzap)
[![workflows](https://github.com/garsue/watermillzap/workflows/Go/badge.svg)]()
[![codecov](https://codecov.io/gh/garsue/watermillzap/branch/master/graph/badge.svg)](https://codecov.io/gh/garsue/watermillzap)

# watermillzap

watermillzap provides the implementation of `watermill.LoggerAdapter` using [go.uber.org/zap](https://github.com/uber-go/zap).

## Notice

`Trace` writes debug log instead of trace log because zap does not support trace level logging.
