# Standard UTAU Library

C++ utility library for Ameya/UTAU, providing foundational support for C++ applications to process UTAU data.

## Features

+ Read and write UTAU files(`*.ust`, `oto.ini`, `prefix.map`)

+ Read and write plugin temporary file for UTAU plugins(`*.tmp`)

+ Convert UTAU project to synthesis arguments

## Requirements

+ CMake 3.16
+ C++ 17

## References

+ [LibUtau 2.16](https://w.atwiki.jp/libutau/)
    + Copyright 2014 SHINTA(翔星 P)
    + 「Lib UTAU」は、「UTAU プラグイン開発支援用 C++ クラスライブラリ」です。

+ [utau-zh-docs](https://suibianp.github.io/utau-zh-docs/)
    + Copyright SuibianP

+ [UTAU Wiki](https://w.atwiki.jp/utaou/)

## Notes

+ I believe there's no need to provide extra documentations because the interfaces and comments are quite easy to understand.

+ Check comments in `.cpp` files for API reference.

## License

This library is released under the Apache 2.0 License.

Copyright (C) 2020-2024 SineSriker.