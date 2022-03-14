# Mandelbrot Multithreaded Example.

<p align="center"><b>Output Example</b></p>
<p align="center">
    <img src="./mandel.png" width="400">
</p>

---

This is a little example for multithreading in Rust. 

You can find this example, and many more examples in the Book:

[**Programming in Rust - Fast, Safe Systems Development**](https://www.ebooks.com/en-us/book/210313783/programming-rust/jim-blandy/)

-by Jim Blandy, Jason Orendorff & Leonora F.S. Tindall

## How to run:


Requirements:
* cargo, or better yet rustup installed.

Steps:
1. clone this repository.
2. in the repository root run: ```cargo build --relase```
3. navigate to the newly created ```./target/release/``` directory.
4. launch the created ```mandelbrot``` executable with: 
    * ```./mandelbrot [OutputImageName].png widthxheight UpperLeftReal,UpperLeftImg LowerRightReal,LowerRightImg```

5. to get a nice set right off the bat use: ```./mandelbrot mandelImage.png 1920x1080 -1.20,0.35 -1,0.20```, for example.
