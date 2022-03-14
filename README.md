# Mandelbrot Multithreaded Example.

This is a little example for multithreading in Rust. 

You can find this and many more examples in the Book:

**Programming in Rust - Fast, Safe Systems Development**

-by Jim Blandy, Jason Orendorff & Leonora F.S. Tindall

## How to run:


Requirements:
* cargo, or better yet rustup installed.

Steps
1. clone this repository.
2. in the repository root run: ```cargo build --relase```
3. navigate to the newly created ```./target/release/``` directory.
4. launch the created ```mandelbrot``` executable with: 
    * ```./mandelbrot [OutputImageName].png widthxheight UpperLeftReal,UpperLeftImg LowerRightReal,LowerRightImg```
