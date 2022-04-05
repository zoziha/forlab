# Forlab

[![MIT](https://img.shields.io/github/license/zoziha/forlab?color=pink)](LICENSE)
[![fpm](https://github.com/zoziha/forlab/workflows/fpm/badge.svg)](https://github.com/zoziha/forlab/actions)
[![msys2-fpm](https://github.com/zoziha/forlab/workflows/msys2-fpm/badge.svg)](https://github.com/zoziha/forlab/actions)

`Forlab` is a Fortran module that provides a lot of functions for scientific computing mostly inspired by Matlab and Python's package NumPy.

## Build with Fortran-lang/fpm

Fortran Package Manager (fpm) is a package manager and build system for Fortran. <br>
You can build `forlab` using the provided `fpm.toml`:

```sh
fpm build --profile release
```

To use `forlab` within your `fpm` project, add the following lines to your `fpm.toml` file:

```toml
[dependencies]
forlab = { git="https://github.com/zoziha/forlab" }
```

## Links

- [keurfonluu/Forlab](https://github.com/keurfonluu/Forlab)  
   Forlab is mainly developed by Keurfon Luu originally.
- [stdlib](https://github.com/fortran-lang/stdlib)  
   Fortran standard library.
- [fortran-fans/forlab](https://github.com/fortran-fans/forlab)