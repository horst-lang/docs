# Getting started

Right now, there is no proper way to install Horst, so you'll have to build it yourself from source.

## Dependencies
* [Rust](https://www.rust-lang.org/tools/install)
* [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) (Usually included with Rust installation)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Cloning the repo
Having git installed, clone the Horst repo by running
```Bash
git clone https://github.com/horst-lang/horst.git && cd horst
```

## Installing dependencies
To install the needed dependencies, just run
```Bash
cargo install
```

## Building and running Horst
To build, run
```Bash
cargo build
```
Then, run the .horst file that contains your code by running
```Bash
cargo run <filename>
```