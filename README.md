# episode-006
Where we do some calculations

## Setup
We need to prepare the following

* A [Rust][rust-lang] project with the name `calculations`
* Editor with the project open

## Script
Historically computers where people that would do calculations. We honor that tradition by making a [Rust][rust-lang] program that does some calculations

The `println!` macro als nows how to print numbers. Here the program prints `42`

```rust
println!("The answer: {}", 42);
```

We will use it to explore the answers of various calculations. For example

```rust
println!("What is 6 times 7: {}", 6 * 7);
```

or 

```rust
println!("What is 17 + 25: {}", 17 + 25);
```

In case you are wondering if [Rust][rust-lang] knows about rules of mathematics

```rust
println("What is 17 + 5 * 5: {}", 17 + 5 * 5);
```

[Rust][rust-lang] adheres to familiar precedence rules.

And there you have it, we did some calculations.

[rust-lang]: https://www.rust-lang.org/