# COMP 458 Spring 2025 Notes

My personal notes for COMP 458: Quantum Computing Algorithms (Spring 25).

🚨 Under **NO CIRCUMSTANCES** may you distribute the contents of the repository
without the explicit permission of the repository owner(s).

This repository is meant as an educational resource and collaboration space
for working through and verifying the correctness of the algorithms with real code.

## Compiling the LaTeX with VimTex

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
   installed. This will be used to compile the LaTeX files and preview the PDF in
   real-time in a PDF viewer of your choice (I use `sioyek`).

4. Compile the LaTeX file by running the following command in Vim:

   ```
   :VimTexCompile
   ```

5. Preview the compiled PDF:

   ```
   :VimTexView
   ```
