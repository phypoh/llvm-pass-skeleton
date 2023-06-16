# llvm-pass-skeleton

Sample LLVM pass templates. Adapted from [Prof Adrian Sampson](https://github.com/sampsyo)'s template to include support for Module passes. 


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
