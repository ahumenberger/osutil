# osutil [![GoDoc](https://godoc.org/github.com/zimmski/osutil?status.png)](https://godoc.org/github.com/zimmski/osutil) [![build](https://github.com/zimmski/osutil/actions/workflows/go.yml/badge.svg?branch=master)](https://github.com/zimmski/osutil/actions?query=branch%3Amaster)

The [os](http://golang.org/pkg/os/) package of the std packages of Go does not support some functionality which is then implemented over and over again in a lot of projects. One example is to copy a file. This looks simple at first but is very complicated if everything has to be done right (e.g. permissions, ACLs, attributes, ...). osutil handles the simple cases which can be done right. If you have any ideas on how to improve this package or have problems of any kind with it, please [submit an issue](https://github.com/zimmski/osutil/issues/new) through the [issue tracker](https://github.com/zimmski/osutil/issues).
