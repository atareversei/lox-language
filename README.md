# Lox — jlox & clox

This repository contains two implementations of the **Lox** language from Robert Nystrom’s *Crafting Interpreters*:

* **jlox** — a tree-walking interpreter implemented in Java.
* **clox** — a bytecode compiler and virtual machine implemented in C.

## Requirements

* **Java 11+** for jlox
* **C compiler** (GCC, Clang, or MSVC) and **CMake** for clox

## Learning goals

| Part     | Focus                   | Key Topics                                    |
| -------- | ----------------------- | --------------------------------------------- |
| **jlox** | Simplicity & clarity    | Lexing, Parsing, ASTs, Interpreter, Resolver  |
| **clox** | Performance & internals | Bytecode, VM loop, Stack frames, Compiler, GC |

---

## Current progress

**jlox**

* [x] Scanner
* [x] Parser
* [x] Interpreter
* [x] Classes & inheritance

**clox**

* [x] Chunk & disassembler
* [x] VM dispatch loop
* [ ] Compiler
* [ ] Closures
* [ ] Garbage Collextion
* [ ] Classes & inheritance
* [ ] Optimization

## References

* [*Crafting Interpreters* by Robert Nystrom](https://craftinginterpreters.com)
* [Official book code](https://github.com/munificent/craftinginterpreters)

Would you like me to generate **separate mini-READMEs** for `jlox/` and `clox/` (each with its exact compile/run instructions for your setup)?
That’s often cleaner than one giant root README.
