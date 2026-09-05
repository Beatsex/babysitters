---
name: specialization-programming-languages
description: "Programming Languages and Compilers Development is a foundational technical specialization focused on designing and implementing programming languages, compilers, interpreters, and associated tooling. This specialization encompasses the full spectrum of language implementation from lexical…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: programming-languages
  process-count: 25
---

# specialization-programming-languages

## Overview

Programming Languages and Compilers Development is a foundational technical specialization focused on designing and implementing programming languages, compilers, interpreters, and associated tooling. This specialization encompasses the full spectrum of language implementation from lexical analysis through code generation, including type systems, optimization passes, and runtime support.

## Available Processes (25)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/programming-languages/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `ast-design` (`specializations/programming-languages/ast-design`) | AST Design and Traversal - Process for designing abstract syntax tree structures and implementing |
| `bytecode-vm-implementation` (`specializations/programming-languages/bytecode-vm-implementation`) | Bytecode VM Implementation - Process for implementing a bytecode virtual machine. Covers instruction |
| `code-generation-llvm` (`specializations/programming-languages/code-generation-llvm`) | Code Generation (LLVM) - Process for implementing code generation using LLVM. Covers LLVM IR generation, |
| `concurrency-primitives` (`specializations/programming-languages/concurrency-primitives`) | Concurrency Primitives Implementation - Process for implementing concurrency features including |
| `debugger-adapter-development` (`specializations/programming-languages/debugger-adapter-development`) | Debugger Adapter Development - Process for implementing a Debug Adapter Protocol (DAP) server for |
| `effect-system-design` (`specializations/programming-languages/effect-system-design`) | Effect System Design - Process for implementing algebraic effect systems with handlers, effect tracking, |
| `error-message-enhancement` (`specializations/programming-languages/error-message-enhancement`) | Error Message Enhancement - Process for designing and implementing user-friendly, informative error |
| `ffi-implementation` (`specializations/programming-languages/ffi-implementation`) | FFI Implementation - Process for implementing Foreign Function Interface to enable interoperability |
| `garbage-collector-implementation` (`specializations/programming-languages/garbage-collector-implementation`) | Garbage Collector Implementation - Process for implementing automatic memory management. Covers |
| `generics-polymorphism` (`specializations/programming-languages/generics-polymorphism`) | Generics and Polymorphism - Process for implementing parametric polymorphism, generics, traits/interfaces, |
| `interpreter-implementation` (`specializations/programming-languages/interpreter-implementation`) | Interpreter Implementation - Process for implementing an interpreter for direct program execution. |
| `ir-design` (`specializations/programming-languages/ir-design`) | IR Design and Optimization - Process for designing intermediate representations and implementing |
| `jit-compiler-development` (`specializations/programming-languages/jit-compiler-development`) | JIT Compiler Development - Process for implementing just-in-time compilation to improve runtime |
| `language-grammar-design` (`specializations/programming-languages/language-grammar-design`) | Language Grammar Design - Systematic process for designing and documenting formal grammars for programming |
| `lexer-implementation` (`specializations/programming-languages/lexer-implementation`) | Lexer Implementation - Comprehensive process for implementing a lexer (tokenizer) that converts source |
| `lsp-server-implementation` (`specializations/programming-languages/lsp-server-implementation`) | LSP Server Implementation - Process for implementing a Language Server Protocol server for IDE |
| `macro-system-implementation` (`specializations/programming-languages/macro-system-implementation`) | Macro System Implementation - Process for implementing a macro system for compile-time metaprogramming. |
| `memory-allocator-design` (`specializations/programming-languages/memory-allocator-design`) | Memory Allocator Design - Process for designing custom memory allocators for language runtimes. |
| `module-system-design` (`specializations/programming-languages/module-system-design`) | Module System Design - Process for designing and implementing a module system with namespaces, |
| `parser-development` (`specializations/programming-languages/parser-development`) | Parser Development - Systematic process for implementing a parser that converts token streams into |
| `pattern-matching-implementation` (`specializations/programming-languages/pattern-matching-implementation`) | Pattern Matching Implementation - Process for implementing advanced pattern matching with destructuring, |
| `repl-development` (`specializations/programming-languages/repl-development`) | REPL Development - Process for building an interactive REPL (Read-Eval-Print Loop) for the language. |
| `semantic-analysis` (`specializations/programming-languages/semantic-analysis`) | Semantic Analysis - Process for implementing semantic analysis including name resolution, scope analysis, |
| `source-map-generation` (`specializations/programming-languages/source-map-generation`) | Source Map Generation - Process for generating source maps to enable debugging of compiled/transpiled |
| `type-system-implementation` (`specializations/programming-languages/type-system-implementation`) | Type System Implementation - Comprehensive process for implementing type checking and type inference. |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `programming-languages` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
