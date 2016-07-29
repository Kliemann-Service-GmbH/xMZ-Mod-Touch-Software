# xMZ-Mod-Touch-Software
Git Superproject, enthält alle Repository die die xMZ-Mod-Touch-Software bilden.

## Benutzung

```bash
cd
git clone https://github.com/Kliemann-Service-GmbH/xMZ-Mod-Touch-Software.git
cd xMZ-Mod-Touch-Software
git submodule init
```

Zum Update des Repo folgenden Git Befehl verwenden. Dieser Befehl muss auch bei
einem frischen checkout ein mal ausgeführt werden.

```bash
git submodule update
```

# Rust
Alle Projekte sind in [Rust][rust] geschrieben.

## Rust Installation
Rust kann ganz einfach mit dem Projekt [Rustup][rustup] installiert werden.
https://github.com/rust-lang-nursery/rustup.rs

```bash
curl https://sh.rustup.rs -sSf | sh -s -- --default-toolchain nightly
```

[rust]: https://www.rust-lang.org/
[rustup]: https://www.rustup.rs/
