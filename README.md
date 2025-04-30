# flux
flux - is a **lightweight**, open-source GNU/Linux **command shell**, designed with a focus on performance and **simplicity**
It aims to deliver a fast and reliable terminal experience with minimal overhead

## Build:
#### Building flux:
```bash
make
```

#### If you want install it:
```bash
make && sudo make install && make clean
```

#### Uninstall all:
```bash
sudo make uninstall
```

#### Check manpage locate:
```bash
make check-man
```

#### If you want use LLVM (recommend) instead of gcc (default compiler):
```bash
make LLVM=1
```

## Development
For internal development standards, including branch naming and commit message conventions, see the [style guide](STYLEGUIDE.md)

## License
Flux is licensed under the GPL3 - see the [here](LICENSE) file for details

## Copyright
© 2025 [VorPijakov23](https://github.com/VorPijakov23). All rights reserved
