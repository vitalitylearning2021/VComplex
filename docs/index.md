The repository contains complex type classes for CUDA programmers.

`int2_`, `float2_` and `double2_` classes are defined. The needed operator overloads and result promotions are defined.

If a complex variable `a` is of type `int2_`, `float2_` and `double2_`, then its real part is accessed as `a.c.x` while its imaginary part is accessed as `a.c.y`.
