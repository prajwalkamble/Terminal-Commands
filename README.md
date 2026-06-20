# Top 10 Terminal Commands — Cheatsheet

A single-page, zero-dependency cheatsheet of the ten terminal commands worth knowing, styled as a glassmorphic terminal window. Tap any command to copy it. Built to drop straight onto GitHub Pages.

**Live demo:** https://prajwalkamble.github.io/Terminal-Commands/

---

## Features

- **10 hand-picked commands** — each with a one-line description and a real "when you'd use it" example.
- **Tap-to-copy** — click any command to copy it to your clipboard (with a non-async fallback for older browsers).
- **Floating back-to-top arrow** — appears when you reach the bottom, gently floats, and smooth-scrolls you up.
- **Terminal-style UI** — traffic-light title bar, blinking cursor, indigo→violet gradient accents, glassmorphic cards.
- **Responsive & accessible** — works down to mobile, visible keyboard focus, and respects `prefers-reduced-motion`.
- **One file, no build step** — pure HTML/CSS/JS; the only external resource is Google Fonts.

---

## The commands

| #  | Command          | What it does                                 | Example                              |
|----|------------------|----------------------------------------------|--------------------------------------|
| 01 | `cd`             | Move between folders                         | `cd ~/projects/tradeacademy`         |
| 02 | `ls -la`         | List everything, including hidden files      | `ls -la`                             |
| 03 | `grep -r`        | Search text/patterns across files            | `grep -r "TODO" src/`                |
| 04 | `find`           | Locate files by name, type, or age           | `find . -name "*.log"`               |
| 05 | `tail -f`        | Stream a file live as it grows               | `tail -f app.log`                    |
| 06 | `curl`           | Make HTTP requests from the terminal         | `curl localhost:8080/api/health`     |
| 07 | `ps aux \| grep` | List running processes and filter            | `ps aux \| grep java`                |
| 08 | `kill`           | Stop a process by its PID                    | `kill -9 12345`                      |
| 09 | `chmod +x`       | Make a script executable                     | `chmod +x deploy.sh`                 |
| 10 | `ssh`            | Connect securely to a remote machine         | `ssh user@server-ip`                 |

---

## Tech stack

- **HTML / CSS / JavaScript** — single self-contained file, no framework.
- **Google Fonts** — JetBrains Mono (commands) + Inter (body).
- **No dependencies, no build, no bundler.**

---

## License

MIT — free to use, modify, and share.

---

Made by [@prajwalkamble](https://github.com/prajwalkamble)
