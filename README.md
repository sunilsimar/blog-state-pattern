# Blog State Pattern (Rust Book)

Examples from *The Rust Programming Language* demonstrating two approaches to the blog post workflow:
- **OOP-style state pattern** using a `State` trait and dynamic dispatch.
- **Typestate** using distinct types for each state to enforce transitions at compile time.

## Project layout
- `src/oop.rs`: dynamic-dispatch state pattern
- `src/typestate.rs`: typestate version
- `src/bin/oop.rs`: binary entry for the OOP version
- `src/bin/typestate.rs`: binary entry for the typestate version
- `src/lib.rs`: re-exports the two modules

## Run
- OOP version: `cargo run --bin oop`
- Typestate version: `cargo run --bin typestate`

## Notes
- Code is adapted from the Rust Book state pattern chapter.


