# NomoLynx

NomoLynx is a RISC-V development platform focused on building a complete low-level toolchain for assembly, linking, and native code generation. The project brings together RISC-V assembly tooling, linker infrastructure, and Clang-based compiler integration to support experimentation with embedded and system-level software.

The codebase includes `riscv_asm_lib` for RISC-V assembly parsing and code generation, linker-related components for ELF and binary linking workflows, and compiler-facing support around Clang so C/C++ sources can be mapped into the RISC-V execution model. Together these components form a practical environment for exploring custom toolchain behavior and code generation pipelines.

The Rust side of the project also includes `rust_macro` and `rust_macro_internal`, which provide procedural macro support to help generate and simplify Rust code used across the toolchain. These macros are designed to support compiler, parser, and code-generation work in a cleaner and more reusable way during Rust development.

## Conference PPT

- [RustLab 2026 — Rethinking Pattern Matching: Flowcharts and PEG Parsing in a RISC-V C Compiler](Conference%20PPT/Rustlab%20Italy%202026/Rustlab2026.pptx)

This repository is the home for the full project ecosystem, combining the assembler, linker, Clang integration, and Rust macro infrastructure into a single development workspace.
