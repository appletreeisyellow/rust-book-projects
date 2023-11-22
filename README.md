# rust-book-projects

Each crate is an individual project from the interactive Rust book https://rust-book.cs.brown.edu/

- guessing_game: https://rust-book.cs.brown.edu/ch02-00-guessing-game-tutorial.html

## Notes

To build and run the binary:

```
cargo run
```

Which is equivalent to:

```
cargo build
./target/debug/guessing_game
```

To check your code compiles but doesn't produce an executable:

```
cargo check
```

To build documentation provided by all your dependencies locally and open it in your browser:

```
cargo doc --open
```
