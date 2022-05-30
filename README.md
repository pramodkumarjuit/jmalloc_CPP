# jmalloc_CPP
How to use the jemalloc memory management module in C++ programs to improve the performance.

## Introduction to jemalloc
It is a very popular memory management module that can used as a replacement of libc's malloc. It is a general purpose malloc implementation that emphasizes fragmentation avoidance and scalable concurrency support. See https://github.com/jemalloc/jemalloc for details.

## About this repo
1. Download libjemalloc.so and compile it.
2. Write C/C++ program where malloc function is used from libjemalloc.so.
3. Verify that malloc() is from libjemalloc.so using gdb.


