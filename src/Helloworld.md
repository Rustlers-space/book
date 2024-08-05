# Hello World

Every programming language tutorial starts with a Hello World Program. As a classic, We are following the same.

If you have rust already installed in your system then, you can follow these steps. If not, Please follow this [link ](https://www.rust-lang.org/tools/install) to install rust in your system.

Open your Command prompt/Terminal in your system, follow these steps

```bash
mkdir rustlers_rust
cd rustlers_rust
```

Open the folder in Visual studio code,

What's visual studio code ?

It is a open source Ide from Microsoft, To install you can follow this [link](https://code.visualstudio.com/)

create a new file called Helloworld.rs, .rs is the extension for rust programming language

```rust
fn main(){
  println!("Hello World");
}
```

Then open your terminal , the first step is to compile using the rust compiler

```bash
rustc Helloworld.rs
```

and to run the program

```bash
./Helloworld
```

and yes, you have successfully created the first rust program.

In this example, fn main()  refers to creation of main function , any rust program will start from this section and we are using a println! macro to print Hello world to the console.
