# Rule Book LaTeX Template

Homepage: <https://github.com/larixium/rule-book-latex-template>

Welcome to the Rule Book LaTeX Template repository!

## Introduction

This repository contains a non-professional LaTeX template for creating rulebooks or instructions for various board games or any other real-life games. I created this template some time ago because I couldn't find something similar and now I have decided to release this program to the public.

## Compatibility

The template is designed to be compatible with both PDFLaTeX and XeLaTeX.

### Rule Book Preview

https://github.com/larixium/rule-book-latex-template/blob/main/sample/japanese-express.pdf

[Preview](https://github.com/larixium/rule-book-latex-template/blob/main/sample/japanese-express.pdf)

## Getting Started

To use this template, you need a LaTeX distribution installed on your system. If you don't have LaTeX installed, follow these steps to get started:

### Installing LaTeX

#### Windows

Download and install MiKTeX from https://miktex.org/.

#### Ubuntu

```sh
sudo apt-get install texlive-full
```
#### Arch
```sh
sudo pacman -S texlive-bin texlive-core texlive-latexextra
```

### Cloning the Repository

To clone this repository open a terminal and run the following command:

```sh
git clone https://github.com/larixium/game-rules-latex-template
```
### Compiling

To compile with PDFLaTeX, use the command:

```sh
pdflatex game_rules.tex
```

To compile with XeLaTeX, use the command:

```sh
xelatex game_rules.tex
```

Warning: Sometimes the file background doesn't render correctly. To fix this, recompile the file.

## Acknowledgments
I would like to express my thanks to the RPG-LaTeX-Template project and "The Law of Root" rulebook from the board game called "Root" for inspiring and contributing to the creation of this template.

## License
This project is licensed under the MIT License, allowing you to use, modify, and distribute the template freely.
