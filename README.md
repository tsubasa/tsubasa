
<h1 align="center">&lt;👋 Hello, World! /&gt;</h1>

```sh
$ man --help
Usage: man [OPTION...] [SECTION] PAGE...

  Options:
    -w, --whoami        Display a short bio
    -s, --skills        Display technologies used
    -V, --version       Display the profile version
    -?, --help          Display this help message

  Examples:
    man --whoami
    man --skills

Report bugs to: https://github.com/tsubasa/tsubasa/issues
```

```sh
$ man --whoami
NAME
  tsubasa - Web Developer

SYNOPSIS
  tsubasa [--location=Tokyo,JP] [--timezone=JST] [--coffee=yes]

DESCRIPTION
  I'm an engineer who loves frontend development, crafting intuitive
  and polished user experiences. I also build full-stack applications
  with Next.js, backend services, and databases.

ENVIRONMENT
  EDITOR=vscode
  SHELL=zsh
  OS=macOS / Linux / Windows
```

```sh
$ man --skills
SKILLS

  Languages   : TypeScript, Python, Go, Rust
  Frontend    : Electron, React, Next.js, Tailwind CSS
  Backend     : Node.js, FastAPI, REST APIs, WebSocket
  Database    : PostgreSQL, SQL
  Infra/Tools : Docker, Kubernetes, Terraform, GitHub Actions
```

```sh
$ man --version
tsubasa 35.0.0 (build 2026-10-10)
License: MIT — Fork me, but bring snacks.

$ echo $?
0

$ _
```
