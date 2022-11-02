# LaTeX Template for Personal Purposes

Made by Zirui XIA, November 2, 2022.

This is a private LaTeX template used in my daily work.

## Introduction

**main.tex**

Main TeX file with initial parameters, supporting multiple-file compilation.

**packages.tex**

All features I've ever used are listed in `packages.tex`. If you need some of them, directly copy them to `main.tex`.

**mathcmd.tex**

`mathcmd.tex` is used to defined new commands used in Hover Preview and Math Preview Panel. When editting large LaTeX files, it is unwise to directly enable `Hover > Preview > Newcommand > Parse TeX File` since large file would result in slow response speed. Instead, I enable `Hover > Preview > Newcommand > Newcommand File`, put all new commands in a single file named `mathcmd.tex` to solve the problem. `main.tex` has also included this file.
