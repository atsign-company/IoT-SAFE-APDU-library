# Building on a Raspberry Pi

## Dependencies

We need PCSC and CMake:

```
sudo apt install -y libpcsclite-dev cmake
```

## Build

Clone the repo and `cd` into it.

Run CMake:

```
cmake CMakeLists.txt
```

This generates a Makefile, which can be run with:

```
make
```

That then creates a binary: `bin/basic_test`
