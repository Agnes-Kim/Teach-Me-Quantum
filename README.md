<h1 align="center">Teach Me Quantum</h1>

A university-level course on **Quantum Computing** and **Quantum Information Science** that incorporates [IBM Q Experience](https://quantumexperience.ng.bluemix.net/qx/experience) and [Qiskit](https://www.qiskit.org/). This course is adequate for general audiences without prior knowledge on Quantum Mechanics and Quantum Computing (please read to [prior knowledge](#prior-knowledge) before starting) and has an estimated duration of **10 weeks at 2h/week (usually 1h theory + 1h practice)**.

This course is Open-source and fit for both individual learning as well as to be used by teachers, professors and lecturers in their own classes.

## Course Overview

 * 📁 [Week 0 - Hello Quantum World](Week%200%20-%20Hello%20Quantum%20World)
     * 📖 [Slides](Week%200%20-%20Hello%20Quantum%20World/slides.pdf)
 * 📁 [Week 1 - Quantum Tools](Week%201%20-%20Quantum%20Tools)
     * 📖 [Slides](Week%201%20-%20Quantum%20Tools/slides.pdf)
     * 📁 [Exercises](Week%201%20-%20Quantum%20Tools/exercises)
 * 📁 [Week 2 - Quantum Information Science](Week%202%20-%20Quantum%20Information%20Science)
     * 📖 [Slides](Week%202%20-%20Quantum%20Information%20Science/slides.pdf)
     * 📁 [Exercises](Week%202%20-%20Quantum%20Information%20Science/exercises)
     * 📁 [Solutions]()
 * 📁 Week 3 - Quantum Gates
 * 📁 Week 4 - Quantum Circuits
 * 📁 Week 5 - Quantum Algorithms (Deutsch)
 * 📁 Week 5 - Quantum Algorithms (Quantum Fourier Transform - Shor) [Cryptography]
 * 📁 Week 6 - Quantum Algorithms (Amplitude Amplification - Groover)
 * 📁 Week 7 - Quantum Algorithms (Adiabatic Quantum Computation - Farhi _et al._)
 * 📁 Week 8 - Quantum Project
 * 📁 Week 9 - Quantum Cryptography
 * 📁 Week 10 - Quantum Computers, History and Implications

## Prior Knowledge
Students of this course are expected to be familiar with:
 * [Python](https://www.python.org/) language
 * [Jupyter](http://jupyter.org/) Notebook environment
 * Some linear algebra, such as matrix multiplication

## Learning Goals
After completing this course, students should be able to:
 * Understand ...
 * Leverage QISKit for Quantum research and development
 * ...

## Working with PDF slides
Each `.pdf` file for slides may have two versions `NAME.pdf` and `NAME_animated.pdf`. The first ignores animations (by replacing the document class in any `.tex` file for `\documentclass[handout]{beamer}`) and the second contains animations.

Animated slides will only work with an external program, I advise [dannyedel/dspdfviewer](https://github.com/dannyedel/dspdfviewer/releases) which also has dual screen and timer functionality.

## Compiling LaTeX files
To achieve this use any LaTeX compiler of your choice, if you have [pdflatex](https://www.tug.org/applications/pdftex/) you can simply do `pdflatex week_XX.tex`.
