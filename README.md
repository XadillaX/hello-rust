# Hello Rust

Rust files always end in a .rs extension. If you're using more than one word in your filename, use an underscore. hello_world.rs rather than helloworld.rs.

Now that you've got your file open, type this in:

```rust
fn main() {
    println!("Hello, world!");
}
```

Save the file, and then type this into your terminal window:

```shell
$ rustc main.rs
$ ./main # or main.exe on Windows
Hello, world!
```
