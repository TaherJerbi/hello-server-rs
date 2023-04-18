# Multithreaded Web Server

This is the final project in the [Rust Book](https://doc.rust-lang.org/stable/book). It is a multithreaded web server that usess a thread pool to handle requests.

## Purpose

Solidify understanding of Rust by building a web server from scratch.

## What I Learned

- How to use the `thread` module to create and manage threads
- How to use the `mpsc` module to create a channel for communication between threads
- How to use the `Arc` and `Mutex` types to share data between threads
- How to use the net module to create a TCP server
- Graceful shutdown of a server using the `Drop` trait

## Usage

```
cargo run
```
