
# Northeastern University Wireless Club (W1KBN) LaTeX Workshop Materials

Welcome to the repository for the **NU Wireless Club LaTeX Workshop**. This repository contains the slide deck and related materials for the workshop.

## 📄 Workshop Slides
A precompiled PDF of the slide deck is available in the [Releases](https://github.com/melarb/nuwc-latex/releases) section for quick viewing.

## Overview

The slide deck (`main.tex`) covers:
- **What is LaTeX?** – An introduction to the typesetting system.
- **How to Use LaTeX** – Practical guidance on getting started, with a focus on Overleaf.
- **Comparison with Other Tools** – Explaining how LaTeX differs from tools like Microsoft Word.
- **Practical Examples** – Demos (presented in real-time during the workshop) and examples showing both code and rendered output.
- **Tools and Resources** – A short list of documentation, templates, cheat sheets, and essential packages.

## 💻 Compiling the Slides Yourself

To compile the slide deck locally, you will need:
- A LaTeX distribution (e.g., TeX Live, MiKTeX, or MacTeX).
- The `minted` package (requires Python and Pygments; compile with the `-shell-escape` flag). *(Note: For the 2025-spring release, `minted` is defined but not actively used.)*
- A LaTeX editor (e.g., VS Code with the LaTeX Workshop extension).

### Steps to Compile:
1. Clone this repository or download the `main.tex` file.
2. Compile locally using one of the following commands:

Using `latexmk`:
```bash
latexmk --pdf -shell-escape main.tex
```

Using `pdflatex`:
```bash
pdflatex --shell-escape main.tex
```

## Repository Structure
```
nuwc-latex/
├── main.tex         # Main Beamer slide deck source file
├── .gitignore       # Git ignore file
├── LICENSE          # License file
└── README.md        # This README file
```

## 📬 Questions

If you have any questions or feedback, please reach out:
- **Workshop Email:** [workshops@nuwireless.org](mailto:workshops@nuwireless.org)
- **Club Website:** [https://nuwireless.org](https://nuwireless.org)

---

## 🖋 Design and Contributions

All workshop materials, design, and this repository were created by [Muhammad Elarbi](https://melarbi.com) based on LaTeX Beamer. For additional information, contact me at [elarbi.m@northeastern.edu](mailto:elarbi.m@northeastern.edu).

This workshop is revived after its last run in Fall 2020. Special thanks to [Jack Leightcap](https://jack.leightcap.com/) (President '22) and Connor Northway (VP '22).

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt="">
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt="">
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt="">
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="">