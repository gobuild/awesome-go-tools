# Awesome Go Tools
A curated list of awesome Go tools. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

The most import is **The go tools must be an command line tool, not lib**

## Contributing
Please take a quick gander at the [contribution guidelines](CONTRIBUTE.md) first. Thanks to all [contributors](https://github.com/gobuild/awesome-go-tools/graphs/contributors).

#### **If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!**

### Contents
* [Awesome Go Tools](#awesome-go-tools)
  * [Go Compile Helpers](#go-compile-helpers)
  * [Server Applications](#server-applications)
  * [Text Processing](#text-processing)
  * [Code Analysis](#code-analysis)
  * [DevOps Tools](#devops-tools)
  * [Other Software](#other-software)

## Go Compile Helpers
*Libraries for package and dependency management.*

* [colorgo](https://github.com/songgao/colorgo) - A wrapper around `go` command for colorized `go build` output.
* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [goop](https://github.com/nitrous-io/goop) - A simple dependency manager for Go (golang), inspired by Bundler.
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments

## Server Applications
*Libraries for development servers.*

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - A local webserver for developers
* [etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery.
* [GoAPI](https://github.com/hvuhsg/GoAPI) - A simple API writing framework with auto openapi docs.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform
* [yakvs](https://github.com/sci4me/yakvs) - A small, networked, in-memory key-value store.

## Text Processing
*Libraries for parsing and manipulating texts.*


## Code Analysis
*Tools for error-checking, linting, etc.*

* [doc](https://godoc.org/robpike.io/cmd/doc) - Go documentation tool that produces an alternative doc format.
* [dupl](https://github.com/mibk/dupl) - A tool for code clone detection.
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gostatus](https://github.com/shurcooL/gostatus) - A command line tool, shows the status of repositories that contain Go packages.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## DevOps Tools
*Tools for testing and dependencies.*

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool
* [awsenv](https://github.com/soniah/awsenv) - a small binary that loads Amazon (AWS) environment variables for a profile
* [Boom](https://github.com/rakyll/boom) - Boom is a tiny program that sends some load to a web application.
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [Dropship](https://github.com/chrismckenzie/dropship) - A tool for deploying code via cdn.
* [EasySSH](https://github.com/hypersleep/easyssh) - Golang package for easy remote execution through SSH and SCP downloading.
* [Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool.
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [hk](https://github.com/heroku/hk) - Heroku command-line interface in Go.
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [lstags](https://github.com/ivanilves/lstags) - manipulates Docker images across different registries. 
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - A small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server
* [Wide](https://wide.b3log.org/login) - A Web-based IDE for Teams using Golang.

## Other Software
*Tools that did not fit into any above categories.*

* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [Docker](http://www.docker.com/) - An open platform for distributed applications for developers and sysadmins.
* [fleet](https://github.com/coreos/fleet) - A Distributed init System.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store#go-package-store-) - An app that displays updates for the Go packages in your GOPATH.
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - A Fast and Modern Static Website Engine
* [Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
