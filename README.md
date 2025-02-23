# Multiple Mutable Borrows in Rust

This repository demonstrates a common error in Rust: attempting to create multiple mutable borrows of the same variable.  This is prevented by the Rust compiler to avoid data races and ensure memory safety.

## Bug

The `bug.rs` file contains code that attempts to create two mutable references (`y` and `z`) to the same variable (`x`). This will result in a compile-time error.

## Solution

The `bugSolution.rs` file shows a way to resolve this, avoiding multiple mutable borrows.  This example showcases using a single mutable reference or other techniques.