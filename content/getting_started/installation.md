---
title: "Installation"
date: 2018-05-18T09:59:40-07:00
draft: false
---

## As a Binary

Grab the latest version from here:

```bash
https://github.com/wtfutil/wtf/releases
```

expand it, and `cd` into the resulting directory. Then run:

```bash
./wtf
```

and that should also do it.

## From Source

Download the source code repo and install the dependencies:

```bash
go get -v -u github.com/wtfutil/wtf
cd $GOPATH/src/github.com/wtfutil/wtf
go install -ldflags="-s -w"
make run
```
and that should do it.

