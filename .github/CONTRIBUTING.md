# Contributing to COMP 458 Notes

Thank you for your interest in contributing to the **COMP 458: Quantum
Computing Algorithms** notes! This repository is a collaborative space for
students, researchers, and quantum computing enthusiasts to improve and
expand the course materials. We welcome contributions of all kinds — from
fixing typos to adding new content or enhancing the GitHub Wiki.

---

## How to Contribute

### 1. Reporting Issues

If you find errors, typos, or unclear sections in the notes, please open an
issue:

- Go to the **Issues** tab.
- Click **New Issue** and use the provided template.
- Clearly describe the problem, including the file (e.g.,
  `lectures/phase-i/lecture1.tex`) and line number if possible.
- Suggest a fix if you have one.

---

### 2. Submitting Pull Requests

To contribute changes (e.g., fixing errors, adding content, or improving
formatting), follow these steps:

#### a. Fork the Repository

- Click the **Fork** button at the top of the repository page.
- Clone your fork:

  ```bash
  git clone https://github.com/micahkepe/comp458-notes.git
  cd comp458-notes
  ```

##### b. Create a Branch

Create a new branch for your changes:

```bash
git checkout -b your-branch-name
```

#### c. Make Changes

- Edit the relevant `.tex` files or other resources.
- Ensure your changes are clear, well-documented, and maintain the existing
  LaTeX structure.
- Test compilation to verify your changes (see README.md for instructions).

#### d. Commit and Push

Commit your changes with a descriptive message:

```bash
git add .
git commit -m "Fix typo in lecture1.tex"
git push origin your-branch-name
```

#### e. Open a Pull Request

- Go to the Pull Requests tab.
- Click New Pull Request and select your branch.
- Provide a clear description of your changes and reference any related issues.
- Submit the pull request for review.

---

### 3. Contributing to the Wiki

The GitHub Wiki is the primary space for FAQs, detailed explanations, and
supplementary content. To contribute:

- Navigate to the Wiki and click Create new page or edit an existing page.
- Add content in Markdown format, ensuring clarity and relevance.

Examples of valuable wiki contributions:

- Explanations of complex topics (e.g., QAOA, Grover’s Algorithm)
- FAQs based on common course questions or GitHub issues
- Links to external resources or tutorials
- Guides for tools like Cirq, PennyLane, or Qiskit

If you have ideas for new wiki pages, you can also propose them by opening an
issue.

---

## Guidelines

- Be Respectful: Maintain a positive and inclusive tone in issues, pull
  requests, and wiki contributions.
- Stay On-Topic: Contributions should relate to COMP 458 or quantum computing.
- Follow LaTeX Standards: Use consistent formatting and avoid breaking
  existing compilation.
- Test Changes: Ensure your LaTeX changes compile without errors before
  submitting.
- Credit Contributions: Acknowledge any external sources or collaborators in
  your pull request or wiki page.

---

## Code of Conduct

We follow a simple code of conduct:

- Be kind and respectful to others.
- Provide constructive feedback.
- Avoid harassment or inappropriate behavior.

---

## Questions?

If you’re unsure how to contribute or have other questions, you can:

- Open an issue for specific problems or suggestions.
- Add or edit a wiki page to share questions or insights.

---

Thank you for helping make these notes a valuable resource for the quantum
computing community!
