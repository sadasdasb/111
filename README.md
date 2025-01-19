# KernelSU-Next for Redmi K40 Gaming / POCO F3 GT

This repository contains the KernelSU-Next kernel build for the **Redmi K40 Gaming** and **POCO F3 GT** smartphones. 

## Make

First, clone KernelSU-NEXT_Mi-ares repository,

then run ``build.sh``. It will create a clang folder in the same directory and download it (thanks to Neutron-Toolchains). Once completed, the kernel build process will begin.

## Some problems
If you encounter the following issue:

```
clang: /lib/x86_64-linux-gnu/libc.so.6: version GLIBC_2.36 not found (required by clang)
ld.lld: /lib/x86_64-linux-gnu/libstdc++.so.6: version GLIBCXX_3.4.32 not found (required by ld.lld)
```

You can refer to [Neutron Documentation](https://github.com/Neutron-Toolchains/clang-build-catalogue#clang-libx86_64-linux-gnulibcso6-version-glibc_236-not-found-required-by-clang) to fix the issue.
