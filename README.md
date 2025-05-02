# flux ✨
flux - is a **lightweight**, open-source GNU/Linux **command shell**, designed with a focus on performance and **simplicity**
It aims to deliver a fast and reliable terminal experience with minimal overhead.

## 🚀 Quick Start:
### Build flux
```bash
make
# If you want use clang (recommend) with:
make LLVM=1
```

### Install flux
```bash
sudo make install && make clean
```

## ✅ Recommended command
```bash
make LLVM=1 && sudo make install && make clean
```
## ⚙️ Other
### Check manpage locate:
```bash
make check-man
```

### ❌ Uninstall
```bash
sudo make uninstall
```

## 👩‍💻 Development
For internal development standards, including branch naming and commit message conventions, see the [style guide](STYLEGUIDE.md).

## 📄 License
Flux is licensed under the GPL3. See the [here](LICENSE) for details.

## 👤 Author & Copyright
© 2025 [VorPijakov23](https://github.com/VorPijakov23). All rights reserved.
