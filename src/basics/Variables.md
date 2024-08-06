# Variables

In Rust, we use **let** keyword
To declare a variable, the following syntax is used

```rust
let variableName : dataType = value;
```

Example:

```rust
fn main(){
  let a: i32 = 5;
  println!("{}", a);
}

```

The variables are immutable by default, The following program will get errored as we try to set value on the immutable variable a.

```rust
fn main(){
  let a: i32 = 5;
  println!("{}", a);
  a = 20;
  println!("{}", a);
}
```

In order to create a mutable variable, we use a keyword mut inbetween the let and variable name

```rust
fn main(){
  let mut a: i32 = 5;
  println!("{}", a);
  a = 20;
  println!("{}", a);
}
```

In next chapter, we will learn about different ways of how to represent data types.
