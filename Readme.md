# Guessing Game Rust Learning Project
This is a learning project for Rust programming. I learn the very basic concept about Rust.

## Running the code
1. Clone this project.
2. Run `cargo build` to install all dependencies and compile the code.
3. Run `cargo run` to run the source code.

## Note
Here I have learned how to build a random number guessing application. The following concepts has been taught:
1. Module importing (For example `use std::io`).
2. Declaring an empty string (`let guess = String::new();`).
3. Taking user input (`io::stdin().read_line(&mut guess);`).
4. Basic concept about mutability.
5. Error handling on `Result` type using `expect()` and match pattern.
6. Converting string to number (For example, `guess.trim().parse()`). 
7. Shadowing variable. I declare the same variable name in the same scope. This is very useful for type conversion use case. I don't need to separately declare the same variable for different types (e.g., let guess_str, and let guess_num, etc.).
8. Infinite loop using `loop` keyword rather than `while`.

## Reference
This tutorial comes from the official Rust document: https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html.