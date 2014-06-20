# rpm

Is a Ruby Package Manager following the path of [`dep`](https://github.com/cyx/dep) and [`rep`](https://github.com/frodsan/rep) only that it's entirely written in bash.
It only expects a `.gems` file (or any given name during install) to install only the missing dependencies.

## Install

```bash
./configure
make install
```

## Commands

```bash
rpm add cuba:3.1.1 ohm:2.0.0
```

```bash
rpm install
```

## Internal dependencies

This is just a bunch of bash scripts, inside `rpm` you'll find use of `ruby`, `gem`, `comm`, `sed`.
