# gorocksdb, a Go wrapper for RocksDB

[![Build Status](https://travis-ci.org/tecbot/gorocksdb.svg)](https://travis-ci.org/tecbot/gorocksdb) [![GoDoc](https://godoc.org/github.com/tecbot/gorocksdb?status.svg)](http://godoc.org/github.com/tecbot/gorocksdb)

If you want to understand how compile gorocksdb, please visit [original repo](http://github.com/tecbot/gorocksdb). this repo adding the go module. I'm used the rocksdb works as persisted storage in my distributed cache.

## Install
In macOS, doesn't need complie rocksdb, only need install rocksdb by homebrew:
```
brew install rocksdb
```
Once installed, you would see DLL `librocksdb.6.7.dylib` and `librocksdb.6.7.3.dylib` in directory `/usr/local/lib`.
