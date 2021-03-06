# Introduction

This guide will help you implement an alien shooter demo application on COMP.CE.100 Introduction to Embedded Systems. The guide is aimed at your average second year IT student at Tampere University. First, we will cover [how to build and run](./2_build-and-run.md) the application template on PYNQ-Z1. Then we will cover the topics related to writing Rust code. Finally, there's instructions on [how to set up](./4_setup-environment.md) and get started on a platform that's not maintained by the course staff (e.g. a personal computer).

The guide is written to be read "in-order" like a book, but if you need to set up your own computer, skip to [how to set up](./4_setup-environment.md).


## Motivation

Here's a really high-level comparison between C and Rust:

C is a standard tool in embedded and low-level programming. More than 50 years of history have seen it become abundant, omni-present, in the (more or less) thin layer of software between metal and other software.

Rust, on the other hand, was created in the last 10 years. Rust aims to keep what's good with C, discard what's no longer useful, and add that which helps make more complex systems more programmable. Much like C and assembly, Rust and C are designed to interoperate, and we are going to take a deep dive into that matter in this course work.

But since you're already here, I won't spend more time discussing ["Why Rust?"](https://doc.rust-lang.org/book/foreword.html)


## This guide will not discuss...
... the following topics, for which you should refer to the main exercise guide:
* exercise specs, exercise requirements,
* board configuration (Development environment tutorial / Board),
* interrupt configurations,
* important memory addresses and bit order,
* led matrix driver,
* reference on course provided function templates (also provided in Rust).
