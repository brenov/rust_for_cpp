# `rust_for_cpp`

Codes for learning to build FFI APIs in Rust for C++.

## How to compile

```bash
g++ --std=c++11 -o target/test examples/test.cpp -Ltarget/debug/ -lffiapi
```

or

```bash
g++ --std=c++11 -o target/test examples/test.cpp target/debug/libffiapi.so
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details.
