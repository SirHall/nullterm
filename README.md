Simply runs [ClearScreen](https://crates.io/crates/clearscreen) to clear the terminal, useful if you want your terminal to be truly cleaned if you often recompile and want to clear previous compilation output.

Go a step further and create a symlink `cls` to this program, and clear+build on any platform using `cls && cargo build`.
