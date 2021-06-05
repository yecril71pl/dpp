![image.png](image.png?raw=true)
![julia.png](julia.png?raw=true)
# dpp
This is a an easily understandable **decimal** floating point library library for non-critical tasks and testing. The library does not adhere to any particular standard.

The first test image was generated by [`smallpt.cpp`](https://www.kevinbeason.com/smallpt/), adapted to use 64-bit decimal floats. The second test image was generated by [`julia.cpp`](https://github.com/user1095108/dpp/blob/master/julia.cpp), using 32-bit decimal floats.
# alternatives
* [DEC64](https://github.com/douglascrockford/DEC64) - legendary, asm, one 64-bit type, unfamiliar interface,
* [decimal_for_cpp](https://github.com/vpiotr/decimal_for_cpp) - fixed-point, bloated, unfamiliar interface,
* [libdecnumber](https://github.com/gcc-mirror/gcc/tree/master/libdecnumber) - legendary, supported by gcc, complex, huge, unfamiliar interface.

There also exists a host of arbitrary-precision fixed-point, floating-point and rational libraries. The universal problem appears to be an unfamiliar interface. Additional problems are: throwing, allocations, complexity and size of these libraries.
