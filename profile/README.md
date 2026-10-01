<div align="center">

# A2Compute

### Agent to Computer

*Isolated computers, built for AI agents.*

</div>

---

## The Idea

AI agents are increasingly capable of complex reasoning — but most of them operate without a body. They can think, plan, and respond, yet they cannot open a browser, drag a file, read a screen, or run a program the way a person would.

**A2Compute** is built around a simple premise:

> *If an agent needs to do something a human would do on a computer — it should have a computer.*

---

## What We Do

We provision isolated, fully operational Linux desktop environments that AI agents can control through a structured interface. Each environment behaves exactly like a real computer: it has a screen, a keyboard, a mouse, a terminal, a filesystem, and network access.

Agents interact with these environments the same way they interact with any tool — through API calls. They can observe the screen, click, type, run commands, move files, and browse the web. The computer handles the execution. The agent handles the thinking.

---

## How It Works

```
                        ┌─────────────────────────────────────┐
                        │      Isolated Computer              │
                        │                                     │
  AI Agent              │  ┌─────────┐      ┌─────────────┐  │
      │                 │  │ Desktop │      │   Terminal  │  │
      │   API calls     │  │  (GUI)  │      │   (Shell)   │  │
      ├────────────────►│  └─────────┘      └─────────────┘  │
      │                 │                                     │
      │   • screenshot  │  ┌──────────────────────────────┐  │
      │   • click       │  │   Browser · Files · Apps     │  │
      │   • type        │  └──────────────────────────────┘  │
      │   • scroll      │                                     │
      │   • bash        └─────────────────────────────────────┘
      │   • files
      │
      │   Observes:
      └──────────────── screen · output · events · state
```

Each computer is sandboxed, ephemeral, and dedicated to a single agent or task. Spin one up in seconds. Tear it down when the job is done.

---

## Why Isolated?

| Concern | How isolation addresses it |
|---|---|
| **Safety** | Agents operate inside a container — nothing they do affects the host system |
| **Reproducibility** | Each computer starts from a clean, known state |
| **Parallelism** | Run hundreds of agents on separate computers simultaneously |
| **Observability** | Every action and screen state can be logged and reviewed |
| **Control** | Pause, snapshot, restore, or delete any computer at any time |

---

## What Agents Can Do

A computer given to an agent is not a limited sandbox — it is a real, general-purpose Linux desktop. Agents can:

- **See** — capture screenshots and read the screen at any moment
- **Point and click** — move the cursor, click, right-click, drag, scroll
- **Type** — send keystrokes, key combinations, and full text strings
- **Use the terminal** — run shell commands and stream their output
- **Write code** — execute scripts directly inside the environment
- **Manage files** — read, write, upload, and download from the filesystem
- **Browse the web** — open URLs and interact with live web pages
- **Hear** — stream audio output from the desktop environment

---

## Who Is This For?

A2Compute is for anyone building systems where an AI agent needs to interact with the world the way a human does — not through a narrow API, but through a complete computing environment.

That includes researchers building agent benchmarks, engineers automating complex workflows, teams running AI-driven QA pipelines, and anyone exploring what agents can do when given the same tools a person has.

---

<div align="center">

**A2Compute — computers for agents.**

[a2compute.com](https://a2compute.com)


</div>
