# Circuits and Systems

### A Foundational, Structural, and Operator-Based Approach

> **Author:** Tunay Arıcı<br>
> **Status:** Structure in place · writing not yet started<br>
> **Typeset in:** LuaLaTeX

Circuit theory is usually taught in pieces. DC analysis, transient analysis and AC analysis arrive as separate topics with separate tools, and the student is left to discover on their own that they were one subject all along. This book is an attempt to make that discovery the point.

Its central argument is that the circuits of a first and second course share a single foundation, and that reading them through the language of operators and systems does more than tidy up the material: it changes how everything that comes after, from signals and control to electronics, is understood.

## The idea

The differential operator is the thread. Once a circuit is written as an operator acting on a signal, the same object explains the steady state of a DC network, the transient of an RLC circuit, the phasor of an AC analysis and the transfer function of a system. Laplace transforms, frequency response and convolution then appear not as new machinery but as different readings of the same structure.

The approach is inspired by Artice M. Davis, *Linear Circuit Analysis*, which unifies DC, AC and transient analysis under a single Heaviside operator method.

## How it is written

- **Every concept is earned.** No tool is introduced before the reader has been given a reason to need it.
- **Bottom-up, then top-down.** The book builds from physical principles upward, and closes by reframing everything as special cases of the most general description.
- **Threads, not silos.** Ideas such as power and duality run through the whole book instead of being confined to single chapters.
- **Boundaries are named.** Each mathematical tool comes with a discussion of where it stops working, and the book says plainly where the linear, analog world ends.
- **An exploratory voice.** The tone is conversational, closer to working through the material together than to a reference text.

## Roadmap

The analytic arc is organised into ten groups.

| Group | Theme | Status |
|---|---|---|
| I | Legitimacy, construction and structural constraints | Planned |
| II | Mathematical preparation | Planned |
| III | Opening the circuit world | Planned |
| IV | The time domain | Planned |
| V | The dynamic language: complex numbers, Heaviside operators, state space, Laplace, transfer functions, stability | Planned |
| VI | Passage to AC | Planned |
| VII | Foundations of the frequency domain | Planned |
| VIII | AC analysis, filtering, two-port networks and coupled circuits | Planned |
| IX | Spectral theory: Fourier and Hilbert transforms, sampling | Planned |
| X | Unity of the theory | Planned |

A later part on design and synthesis, covering network synthesis, filter design, op-amp design and linear control, is planned as a separate phase.

**Out of scope:** stochastic signals, tolerance analysis and the Z-transform.

## Building

The book is written in LuaLaTeX. Compile the main file with

```
lualatex main.tex
```

## License

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may share and adapt it with credit, for non-commercial purposes, under the same license.
