<h1 align="center">Flux</h1>
<p align="center"><em>Is a lightweight, open-source GNU/Linux command shell</em></p>
<p align="center">
  🐞 <a href="https://github.com/VorPijakov23/flux/issues/new?template=bug_report.md">Report a Bug</a> ·
  ✨ <a href="https://github.com/VorPijakov23/flux/issues/new?template=feature_request.md">Request a Feature</a> ·
  💬 <a href="https://github.com/VorPijakov23/flux/discussions">Ask a Question</a>
</p>

<br />

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Getting Started](#getting-started)
  - [Build flux](#build-flux)
    - [Build with LLVM](#built-with-llvm)
  - [Install](#install)
    - [Quick install](#quick-install)
- [Development](#development)
- [License](#license)
- [Author & Copyright](#author_copyright)
</details>

---

## About

<table>
<tr>
<td>

Flux was born out of a desire to create a command shell that strips away unnecessary complexity without sacrificing speed or reliability.

As an open-source, lightweight GNU/Linux shell, Flux focuses on delivering a **clean**, efficient terminal experience-fast to start, easy to use, and **free from the bloat** that slows down everyday workflows.
</td>
</tr>
</table>

## Getting Started

### Build Flux
```bash
make
```

#### Build with LLVM (Recommended)
```bash
make LLVM=1
```

### Install
```bash
sudo make install
```

#### Quick install
```bash
make LLVM=1 && sudo make install && make clean
```

## 👩‍💻 Development
For internal development standards, see the [Style Guide](STYLEGUIDE.md).

## 📄 License
Flux is licensed under the MIT. See the [here](LICENSE) for details.

## 👤 Author & Copyright
© 2025 [VorPijakov23](https://github.com/VorPijakov23). All rights reserved.
