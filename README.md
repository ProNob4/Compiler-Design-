# 🛠️ Compiler Design

Welcome to the **Compiler Design** repository! This project explores the theoretical foundations and practical implementation of compilers, covering each major phase from lexical analysis to code generation and optimization.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Compiler Phases](#compiler-phases)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Screenshots / Examples](#screenshots--examples)
- [Resources](#resources)
- [License](#license)

---

## 📖 Overview

A **compiler** is a program that translates source code written in a high-level programming language into target machine code. This repository covers both **theory** and **hands-on** implementation of a compiler's components, including:

- Lexical Analysis
- Syntax Analysis
- Semantic Analysis
- Intermediate Code Generation
- Code Optimization
- Target Code Generation

---

## 🔄 Compiler Phases

| Phase                | Description |
|----------------------|-------------|
| **Lexical Analyzer** | Tokenizes the source code (using DFA, regex). |
| **Syntax Analyzer**  | Builds a parse tree (LL, LR parsers). |
| **Semantic Analyzer**| Checks for semantic errors, builds symbol table. |
| **Intermediate Code**| Converts code to an abstract, machine-independent form. |
| **Code Optimizer**   | Improves intermediate code performance. |
| **Code Generator**   | Outputs final machine or assembly code. |

---

## 📁 Folder Structure

```bash
Compiler-Design/
├── 01_LexicalAnalyzer/
├── 02_SyntaxAnalyzer/
├── 03_SemanticAnalyzer/
├── 04_IntermediateCode/
├── 05_CodeOptimization/
├── 06_CodeGeneration/
├── TheoryNotes/
├── test_cases/
└── README.md
