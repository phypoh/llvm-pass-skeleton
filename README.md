# llvm-pass-skeleton

Sample LLVM pass templates. Adapted from [Prof Adrian Sampson](https://github.com/sampsyo)'s template to include support for Module passes. For more details on how to create a LLVM pass, check out Prof Sampson's [LLVM for Grad Students](https://www.cs.cornell.edu/~asampson/blog/llvm.html)


It's for LLVM 14.

Build:

    $ cd llvm-pass-skeleton
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ cd ..

Run:

    $ clang -flegacy-pass-manager -Xclang -load -Xclang build/skeleton/libSkeletonPass.* something.c



Thanks to [LeadroyaL](https://github.com/LeadroyaL) for the [issue fix](https://github.com/sampsyo/llvm-pass-skeleton/issues/7)!
