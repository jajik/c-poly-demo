## Simple C polymorphism demo

Although C is usually considered as a language without polymorphism, there
are multiple techniques how to do polymorphism in it.

This is a simple demo of doing polymorphism through macros and different
translation units. The universal function implementation is in `common/common.c`
and relies on a `TYPE` macro that is defined differently for each module.

You can build the demo by yourself, you just need a C compiler and `cmake`. Simply
execute

```shell
mkdir build
cd build
cmake ..
make
```

you'll find the executables in `module1/` and `module2/` sub-directories.

