# Esolang‑NET

Esolang‑NET is a collection of high‑quality, engineering‑focused implementations of esoteric programming languages for .NET.  
Each project provides a clean architecture, a unified execution model, and optional Roslyn Source Generators for high‑performance code generation.

The goal of Esolang‑NET is to make esolangs *practical* to use in modern .NET applications—without sacrificing correctness, performance, or maintainability.

---

## Projects

### 🧩 Piet — *Esolang.Piet*
A fully‑featured .NET implementation of the Piet esolang, including a high‑performance parser, processor, and Roslyn Source Generator.  
Repository: https://github.com/Esolang-NET/Piet

### 🧱 Funge‑98 — *Esolang.Funge*
A modular and extensible .NET implementation of the Funge‑98 family, designed with a unified execution model and generator architecture.  
Repository: https://github.com/Esolang-NET/Funge

### ➕➖ Brainfuck — *Esolang.Brainfuck*
A mature and optimized .NET implementation of Brainfuck, featuring a fast interpreter and a highly efficient Source Generator.  
Repository: https://github.com/Esolang-NET/Brainfuck

---

## Design Principles

- **Unified execution model**  
  Shared abstractions for instruction pointers, execution contexts, and I/O pipelines.

- **High‑performance Roslyn Source Generators**  
  Optional compile‑time code generation for maximum runtime speed.

- **Separation of concerns**  
  Parser, processor, runtime, and generator are cleanly isolated.

- **Modern .NET architecture**  
  Nullable‑aware, allocation‑conscious, and optimized for .NET 8+.

- **Engineering‑grade esolang implementations**  
  Not toys—real libraries designed for correctness and performance.

---

## License

All projects under Esolang‑NET are released under the MIT License.

---

## Contributing

Contributions, issue reports, and discussions are welcome.  
Esolang‑NET aims to provide the most robust esolang implementations available for .NET, and community feedback is valuable.
