# zk-bpf

This is a tool allowing for zero-knowledge execution of eBPF programs, by compiling eBPF to RISC-V and using RISC Zero as a backend. Note that this is still in a very preliminary state, and we only have a small portion of the eBPF instruction set implemented.

To try it out, pass an assembly file with `--asm` or an ELF file with `--elf`. Currently, the tool needs `cargo` available in order to run, since we add in some Rust code to make the final RISC-V binary.

## License

This project is distributed under the Apache License (Version 2.0).
