# Olivier Elleaume

Systems and low-level developer, currently at **42 Lyon**.

> 🔍 Looking for an internship in Rust / systems development.
> 💼 [LinkedIn](https://www.linkedin.com/in/olivier-elleaume)

- 🐧 Linux native (Arch + Hyprland): Bash scripting, system tooling
- 🦀 Rust: ownership/borrowing, WebAssembly, async (tokio), multicrate workspaces
- 🔧 C/C++ from 42 projects: memory management, syscalls, sockets, epoll

---

## Featured Projects

### [♟️ ChessGame](https://github.com/LeMuffinMan/ChessGame) — Rust + WebAssembly
A chess engine compiled to WASM, playable in the browser without any backend. Its Lichess bot sits around 1900 Elo over 6000+ games.

- Minimax with alpha-beta pruning and search optimizations (LMR, quiescence, transposition table)
- UCI protocol: tournament-ready, integrated with cutechess-cli
- Dedicated UI for desktop and mobile
- CI/CD: fmt, clippy, WASM build, node-count regression gate, automated deploy and release via GitHub Actions

→ [Play it](https://lemuffinman.github.io/ChessGame/) · [Challenge my bot on Lichess](https://lichess.org/@/LeMuffinBot)


---

## 42 Common Core

### [💬 ft_irc](https://github.com/LeMuffinMan/ft_irc) — IRC server in C++98, async tester in Rust
An RFC 2812 server built on `epoll` (C++98, written with a teammate), and a tester written in Rust — async tokio; Single-threaded event loop on epoll: non-blocking sockets, partial-message buffering, no thread per client; Three async bots sharing one connection loop, interacting with users and with each other

### [🐳 Inception](https://github.com/LeMuffinMan/Inception) — Docker infrastructure from scratch
NGINX reverse proxy, TLS, single entry point; Docker secrets for every credential, isolated internal network, healthchecks and dependency ordering; Bash scripts, including a environment checker and a sourced helper library

### [🐚 Minishell](https://github.com/LeMuffinMan/Minishell) — POSIX shell in C
Parsing, pipes, redirections, environment handling, builtins, signal management. Ships with a differential tester that compares stdout, stderr and exit code against `bash`, with Valgrind in the loop.

### [🧵 Philosophers](https://github.com/LeMuffinMan/philosophers) — Multithreading in C
Dining philosophers: thread synchronization, mutexes, semaphores, deadlock prevention, performance tuning.

### [✨ Fract'ol](https://github.com/LeMuffinMan/fract-ol) — Fractal explorer in C
Mandelbrot and Julia sets, real-time zoom, rendering optimization via MinilibX.

---

[📄 Dotfiles](https://github.com/LeMuffinMan/Dotfiles) — my home made (and borrowed) dotfiles: Hyprland, Waybar, Alacritty, Zed, and more.

---

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux">
</p>
