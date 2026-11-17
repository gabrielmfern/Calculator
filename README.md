# Calculator

A small, fast native calculator, built with [forbear](https://github.com/gabrielmfern/forbear).

https://github.com/user-attachments/assets/8f44906e-5859-49f7-9908-214f0a1e52a8

- Exe size: 3.6 MB, a single file with the font built in
- Window shows up in about 50 ms
- Memory: 10.5 MB working set
- 1,155 lines of jai

[Download for Windows](https://github.com/gabrielmfern/Calculator/releases/latest/download/Calculator.exe)

Features:
- Type full expressions with parentheses and powers, such as `1234.5*(78-9)/3`;
- the result updates as you type, and Enter writes it into your clipboard;
- a real text input: selection, word jumps, clipboard, undo, and redo;
- follows the system light and dark theme (Windows only for now).

## Build

Requirements: the Jai programming language, which is in private beta.

```sh
jai build.jai
```

This writes `Calculator.exe` on Windows. forbear and the libraries it needs are bundled in [modules/forbear](./modules/forbear), so there's nothing else to install.

---

<a href="https://github.com/gabrielmfern/forbear">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/forbear-definition-dark.png">
    <img alt="forbear: to politely or patiently restrain an impulse to do something" src="assets/forbear-definition-light.png">
  </picture>
</a>
