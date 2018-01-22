rust-rocksdb
============
[![Build Status](https://travis-ci.org/ethereumproject/emerald-rocksdb.svg?branch=master)](https://travis-ci.org/r8d8/emerald-rocksdb) 
[![Build status](https://ci.appveyor.com/api/projects/status/hqfck32sw09eft0i?svg=true)](https://ci.appveyor.com/project/r8d8/emerald-rocksdb)
[![crates.io](http://meritbadge.herokuapp.com/rocksdb)](https://crates.io/crates/rocksdb)
[![documentation](https://docs.rs/rocksdb/badge.svg)](https://docs.rs/rocksdb)

Feedback and pull requests welcome!  If a particular feature of RocksDB is important to you, please let me know by opening an issue, and I'll prioritize it.

This binding is statically linked with a specific version of RocksDB. If you want to build it yourself, make sure you've also cloned the RocksDB and Snappy submodules:

    git submodule update --init --recursive
