# Rust
https://www.rust-lang.org/


## Learn Rust

### [Rust book](https://doc.rust-lang.org/book/title-page.html)

https://doc.rust-lang.org/book/
https://doc.rust-lang.org/stable/book/

#### local copy
```
rustup docs --book
```
file:///home/UID/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/share/doc/rust/html/book/index.html


### [Install Rust on Ubuntu](https://doc.rust-lang.org/book/ch01-01-installation.html)
https://github.com/derekbanas/Rust-Tutorial
```
sudo apt install rustc
rustc -V  # 1.50.0
```

Or
```
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

```

### [Hello Rust](https://doc.rust-lang.org/book/ch01-02-hello-world.html)
create `main.rs`:
```
fn main() {
    println!("Hello Rust!");
}
```

compile:
```
rustc main.rs
```

run:
```
./main
```

### [Hello Cargo](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)
`cargo` is Rust's build system and package manager.

```
cargo --version
# cargo 1.50.0 (f04e7fab7 2021-02-04)

cargo new hello_cargo
cd hello_cargo
cargo build
cargo run  # equivalent to ./target/debug/hello_cargo
# Hello, welcome to Rust world!

cargo build --release
./target/release/hello_cargo
# Hello, welcome to Rust world!

```


### [Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)

```
cargo new guessing_game
cd guessing_game/

cargo run
# Hello, a guessing game!

```





## Rust-Tutorial
Rust is the language of choice for those looking for high performance, memory safety and all the tools needed to write error free code with ease. In this tutorial I created a full course on programming with Rust.
