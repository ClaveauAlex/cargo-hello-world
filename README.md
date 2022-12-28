# First program with Rust and Cargo

If you want to start a project with Rust. It could be interesting to start with Cargo!

You can just start with this command: `cargo new PROJECT_NAME`.

Then, cargo generated a directory with the name. If you choose to move into, you can see a file `Cargo.toml` and a directory `src/` with a file `main.rs`.

Cargo is a good practice when you choose to start a project. It can organize your project and initialize a versioning. So, use it!

It seperate the part with configuration like readme, confs, etc. and the project inside the directory `src/`.

## Build and Running Cargo Project

If you want to build and test your project. You can build the project with the command below:

`cargo build`

This command creates an executable file in ~target/debug/PROJECT_NAME~. TRhe default build is a debug build. Cargo puts the binary in a directory named ~debug~.

So if your want to run, you can just launch this command `./target/debug/PROJECT_NAME`. But we can also use `cargo run` to compile the code and then run the resultant executable.

You can notice, there is another command with cargo. It is `cargo check`. This command can just check your program without compile your project and run it.

## Building for Realease

When your project is finally ready for release, you can use `cargo build --release` to compile it with optimizations. This command will create an executable in ~target/release~ instead of ~target/debug~.
