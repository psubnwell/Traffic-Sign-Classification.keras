# Traffic_Sign_Classification

## My modifications after forking

* Since `Keras 2` was released, so I just rewrote the code in new APIs and switched backend of `keras` to `tensorflow`. (Use `tensorflow`-styled data format, ie, `tf`/`channels_last`)

* I prefer a pure text interface, and think `Jupyter Notebook` a little bit clumsy though it's a creative tool. So I rewrote the code in `.py` simply, keeping the original author's `.ipynb`. Pick one that fit your preference.

## Old (chsasank's) README

Code for CNNs to solve The German Traffic Sign Recognition Benchmark(GTSRB) in keras. 
A blog post explaining the code is availabe at https://chsasank.github.io/keras-tutorial.html

The problem is to to recognize the traffic sign from the images. 
Solving this problem is essential for self-driving cars to operate on roads.

![classes](/classes.jpg)
