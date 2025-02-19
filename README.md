# [COMP 458: Quantum Computing Algorithms 🧬](https://micahkepe.com/comp458-notes/)

Personal course notes from COMP 458: Quantum Computing Algorithms (Spring 25).

The latest version of the notes can be found [here](https://micahkepe.com/comp458-notes/).

This repository is meant as an educational resource and collaboration space
for reinforcing the concepts learned in the course. The notes are written fully
in LaTeX.

> [!IMPORTANT]
> These notes are a work-in-progress and are being updated as I progress through
> the course. If you find any errors or have any suggestions for improvement,
> feel free to open an issue or a pull request.

> [!NOTE]
> Personally, I compile the `*.tex` using the VimTeX plugin for Vim/Neovim, but
> you can use any LaTeX editor of your choice. The notes are written in a way that
> they can be easily compiled using any LaTeX editor and viewer. See the section
> [below](#compiling-the-latex-with-vimtex) for instructions on how to compile the
> LaTeX files using VimTeX.

## Table of Contents

<div align="center">

|                    Section                    | Topics                                                             |
| :-------------------------------------------: | ------------------------------------------------------------------ |
|           <strong>Phase I</strong>            | <em>Introduction and Background</em>                               |
| [Lecture 1](./lectures/phase-i/lecture1.tex)  | Overview of Quantum Computing Concepts                             |
| [Lecture 2](./lectures/phase-i/lecture2.tex)  | Review of Linear Algebra Concepts                                  |
| [Lecture 3](./lectures/phase-i/lecture3.tex)  | Quantum Bits and Quantum States                                    |
| [Lecture 4](./lectures/phase-i/lecture4.tex)  | Quantum Gates and Transformations                                  |
| [Lecture 5](./lectures/phase-i/lecture5.tex)  | Other Quantum Gates, Measurement, Multi-Qubit Systems              |
| [Lecture 6](./lectures/phase-i/lecture6.tex)  | Multi-Qubit Gates and Circuit Construction                         |
| [Lecture 7](./lectures/phase-i/lecture7.tex)  | More Multi-Qubit Gates, Reversibility Property, No-Cloning Theorem |
|          <strong>Phase II </strong>           | <em>Fundamentals of Quantum Algorithms</em>                        |
| [Lecture 8](./lectures/phase-ii/lecture8.tex) | Entanglement, Bell State, and Intro to <code>Cirq</code>           |

</div>

---

## Contributing

If you find any errors or have any suggestions for improvement, feel free to
open an issue or a pull request. I would be happy to review and merge any
contributions.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](./LICENSE)

## Compilation

### Compiling the LaTeX with VimTex

<details>
<summary>Instructions</summary>

1. Clone the repository:

```code
git clone https://github.com/micahkepe/comp458-notes.git
cd comp458-notes
```

2. Open the `main.tex` file in Vim or Neovim:

```
nvim main.tex
```

3. Ensure that you have the [`VimTeX`](https://github.com/lervag/vimtex) plugin
   installed. This will be used to compile the LaTeX files and preview the
   PDF in real-time in a PDF viewer of your choice (I use `sioyek`).

4. Compile the LaTeX file by running the following command in Vim:

   ```
   :VimTexCompile
   ```

5. Preview the compiled PDF:

   ```
   :VimTexView
   ```

If you have any issues with the compilation, feel free to open an issue or
reach out to me directly.

</details>
