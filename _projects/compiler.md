---
title: "Compiler"
excerpt: "Assignment for Compiler Design class in Spring 2018 turned personal project"
header:
  image: /assets/images/computer-screen-code.jpg
  teaser: assets/images/computer-screen-code.jpg
sidebar:
  - title: "Github Link"
    text: "[compiler](https://github.com/maiquynhtruong/compilers)"
  - title: "Languages and Technology"
    text: "C, Compiler Theory, LLVM"
gallery:
  - url: /assets/images/computer-screen-code.jpg
    image_path: assets/images/computer-screen-code.jpg
    alt: "placeholder image 1"
  - url: /assets/images/computer-screen-code.jpg
    image_path: assets/images/computer-screen-code.jpg
    alt: "placeholder image 2"
  - url: /assets/images/computer-screen-code.jpg
    image_path: assets/images/computer-screen-code.jpg
    alt: "placeholder image 3"
---

## Architecture and documentation
[**Please check out the wiki**](https://github.com/maiquynhtruong/compilers/wiki) for more documentation and **lessons learned**!

The main purpose of this project is to learn more about compiler. Therefore, I try my best to create a good knowledge base in the wiki that not only documents the code but also the lessons I've learned in the process. I hope this project could be helpful for others in the future, especially those who want to use LLVM C API but struggle with the lack of documentation from the main website.

## Overview
Final Project for Compiler Design class in Spring 2018. The project is to build a simple recursive decent with one lookahead (LL(1)) compiler from scratch (without using external compiler frontend tools such as flex or bison). The file `projectDescription.pdf` gives more details about the project.

This compiler compiles a made-up language. The file `projectLanguageDescription.pdf` in the root folder specifies the grammar and semantics of the language. Some example code in this language can be found in `code_gen/tests` folder.

### There are five development phases:

* **Scanner**: Implemented in the `scanner` folder
* **Parser**: the `parser` folder.
* **Type Checking**: the `symbol_table`, `semantics` and `type_checking` folders.
* **Code Generation**: the `code_gen` folder (current development).
* **Runtime**: To be implemented. However, the compiler can still with `lli` tool.

**Future goals:** After this project, I'm hoping to learn more about compiler optimization.

{% include gallery caption="This is a sample gallery to go along with this case study." %}
