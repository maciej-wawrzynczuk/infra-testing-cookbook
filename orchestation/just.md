# Just

[Home Page](https://just.systems/)

A nice command runner written in rust. My favorite installation method:
Have [rust toolchain installed](https://rust-lang.org/tools/install/). Then run:
`cargo install just`. That's it.

Let's start with "hello world".

```just
hello:
    echo "hello world!"
```

Just type `just hello`.

It is a good idea to have a reasonable default task, especially
in projects without an obvious default. This one works for me as
a justfile stub.

```just
help:
    @just --list
```
