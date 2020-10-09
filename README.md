# gabitOS

This is an experimental trying of making my an operating-system-kernel in RUST.
Creating a new OS also means that means we can't use threads, files, heap-memory, network tools, and other things that require OS abstractions.
As a consequence, we can't use most of Rust Standard library features.

## How to run

1. `git clone https://github.com/gbrmachado/gabitOS/ && cd gabitOS`
2. ```qemu-system-x86_64 -drive format=raw,file=bin/bootimage-gab-os.bin```
