# [COMP 458: Quantum Computing Algorithms 🧬](https://micahkepe.com/comp458-notes/)

Complete course notes from COMP 458: Quantum Computing Algorithms (Spring 25).

The latest version of these notes is available at [micahkepe.com/comp458-notes](https://micahkepe.com/comp458-notes/).

This repository is meant as an educational resource and collaboration space
for reinforcing the concepts learned in the course. The notes are written fully
in $\LaTeX$.

> [!IMPORTANT]
> These notes are a work-in-progress and will undergo updates and revisions
> as new developments arise, mistakes are corrected, etc. If you find any
> errors or have any suggestions for improvement, feel free to open an issue
> or a pull request.

> [!NOTE]
> Personally, I compile the `*.tex` using the VimTeX plugin for Vim/Neovim, but
> you can use any LaTeX editor of your choice. The notes are written in a way that
> they can be easily compiled using any LaTeX editor and viewer. See the section
> [below](#compiling-the-latex-with-vimtex) for instructions on how to compile the
> LaTeX files using VimTeX.

## Table of Contents

<div align="center">

|                     Section                      | Topics                                                                  |
| :----------------------------------------------: | ----------------------------------------------------------------------- |
|             <strong>Phase I</strong>             | <em>Introduction and Background</em>                                    |
|   [Lecture 1](./lectures/phase-i/lecture1.tex)   | Overview of Quantum Computing Concepts                                  |
|   [Lecture 2](./lectures/phase-i/lecture2.tex)   | Review of Linear Algebra Concepts                                       |
|   [Lecture 3](./lectures/phase-i/lecture3.tex)   | Quantum Bits and Quantum States                                         |
|   [Lecture 4](./lectures/phase-i/lecture4.tex)   | Quantum Gates and Transformations                                       |
|   [Lecture 5](./lectures/phase-i/lecture5.tex)   | Other Quantum Gates, Measurement, Multi-Qubit Systems                   |
|   [Lecture 6](./lectures/phase-i/lecture6.tex)   | Multi-Qubit Gates and Circuit Construction                              |
|   [Lecture 7](./lectures/phase-i/lecture7.tex)   | More Multi-Qubit Gates, Reversibility Property, No-Cloning Theorem      |
|            <strong>Phase II </strong>            | <em>Fundamentals of Quantum Algorithms</em>                             |
|  [Lecture 8](./lectures/phase-ii/lecture8.tex)   | Entanglement, Bell State, and Intro to <code>Cirq</code>                |
|  [Lecture 9](./lectures/phase-ii/lecture9.tex)   | Grover's Search Algorithm                                               |
| [Lecture 10](./lectures/phase-ii/lecture10.tex)  | Quantum Logic Gates, Applying Grover's Search Algorithm to SAT          |
| [Lecture 11](./lectures/phase-ii/lecture11.tex)  | Quantum Circuit Optimizations                                           |
|           <strong>Phase III </strong>            | <em>Advanced Quantum Algorithms</em>                                    |
| [Lecture 12](./lectures/phase-iii/lecture12.tex) | Introduction to Variation Quantum Algorithms                            |
| [Lecture 13](./lectures/phase-iii/lecture13.tex) | Introduction to Quantum Approximate Optimization Algorithms (QAOA)      |
| [Lecture 14](./lectures/phase-iii/lecture14.tex) | More on QAOA: Cost and Mixer Hamiltonians, Full Circuit                 |
| [Lecture 15](./lectures/phase-iii/lecture15.tex) | Wrapping Up QAOA: Intro to Coding in PennyLane, QUBO                    |
|            <strong>Phase IV </strong>            | <em>Special Topics in Quantum Computing</em>                            |
| [Lecture 16](./lectures/phase-iv/lecture16.tex)  | Quantum Compiler Optimizations                                          |
| [Lecture 17](./lectures/phase-iv/lecture17.tex)  | More on Quantum Compiler Optimizations, Quantum Computer Architectures  |
| [Lecture 18](./lectures/phase-iv/lecture18.tex)  | Quantum Circuits as DAGs, Qubit Topologies, Logical to Physical Mapping |
| [Lecture 19](./lectures/phase-iv/lecture19.tex)  | More on Logical to Physical Mapping                                     |
| [Lecture 20](./lectures/phase-iv/lecture20.tex)  | Quantum Error Correction: Bit Flip Errors                               |
| [Lecture 21](./lectures/phase-iv/lecture21.tex)  | Quantum Error Correction: Phase Flip Errors                             |
|            <strong>Phase V </strong>             | <em>Concluding Lectures</em>                                            |
|  [Lecture 22](./lectures/phase-v/lecture22.tex)  | Quantum Annealers, Trapped Ion Quantum Computers                        |
|  [Lecture 23](./lectures/phase-v/lecture23.tex)  | Neutral Atom Quantum Computers, Photonic Quantum Computers              |
|          <strong>Supplementary</strong>          | <em>Additional supplementary material.</em>                             |
|   [Cheatsheet](./supplementary/cheatsheet.tex)   | Quick reference to important concepts and facts.                        |

</div>

---

## Contributing

If you find any errors or have any suggestions for improvement, feel free to
open an issue or a pull request. I would be happy to review and merge any
contributions.

Please see the [CONTRIBUTING.md](./.github/CONTRIBUTING.md) for details on
how to contribute.

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
