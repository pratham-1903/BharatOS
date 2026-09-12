# 🇮🇳 BharatOS

> **A hobby operating system built from scratch by the Turtle Team.**

BharatOS is an experimental operating-system project built from the ground up by the **Turtle Team**.

The goal is simple: **learn how an operating system actually works by building one ourselves** — from booting the machine to memory management, processes, drivers, filesystems, and a shell.

This is a learning/hobby project, not a production operating system.

---

## 🎯 Project Goals

BharatOS will gradually explore and implement:

* 🥾 Boot process
* ⚙️ Kernel
* 🧠 Memory management
* 🔄 Process management
* 🔌 Hardware drivers
* 📁 Filesystem
* 💻 Command-line shell
* 📦 Basic applications
* 🧪 Automated tests
* 📚 Technical documentation

The project will be developed **incrementally**. We do not expect everything to work from day one.

---

## 📂 Project Structure

```text
BharatOS/
│
├── boot/         # Bootloader and early boot code
├── kernel/       # Core operating system kernel
├── memory/       # Memory management
├── process/      # Process and task management
├── drivers/      # Hardware/device drivers
├── filesystem/   # Filesystem implementation
├── shell/        # Command-line shell
├── apps/         # User-space applications
├── tests/        # Tests and validation
└── docs/         # Project documentation
```

Each folder represents a major subsystem of BharatOS.

---

## 👥 Turtle Team

BharatOS is being developed collaboratively by the **Turtle Team**.

Each member is responsible for a specific area of the project. Changes should be made inside the appropriate subsystem rather than directly modifying unrelated parts of the project.

---

## 🚀 Getting Started

### Current Phase

**Phase 0 — Repository Setup**

At the beginning, the priority is to establish a clean project structure and development workflow.

### Repository Setup

1. Create a GitHub repository named:

```text
BharatOS
```

2. Create the following directories:

```text
boot/
kernel/
memory/
process/
drivers/
filesystem/
shell/
apps/
tests/
docs/
```

3. Add all Turtle Team members as repository collaborators.

4. Keep the repository structure clean and organized.

### Important

**Phase 0 does not require coding.**

The initial setup is only about preparing the project so development can begin cleanly.

* ❌ No coding required
* ❌ No need to learn C immediately
* ❌ No OS theory required at this stage
* ✅ Set up the repository
* ✅ Set up the folder structure
* ✅ Add the team
* ✅ Prepare for development

---

## 🗺️ Development Roadmap

BharatOS will be developed in stages:

```text
Phase 0
Repository & Team Setup
        ↓
Phase 1
Boot
        ↓
Phase 2
Minimal Kernel
        ↓
Phase 3
Memory Management
        ↓
Phase 4
Processes & Tasks
        ↓
Phase 5
Drivers
        ↓
Phase 6
Filesystem
        ↓
Phase 7
Shell
        ↓
Phase 8
Applications
        ↓
Phase 9
Testing & Stabilization
```

The roadmap may change as we discover technical limitations or better approaches.

---

## 🧑‍💻 Development Principles

### 1. Build Before Perfecting

We are learning by building. Early implementations do not need to be production-grade.

### 2. Keep Components Separate

Each subsystem should have a clear responsibility.

### 3. Document Important Decisions

Major architectural or technical decisions should be documented in `docs/`.

### 4. Test Changes

Whenever practical, changes should include or update tests in `tests/`.

### 5. Small Changes

Prefer small, understandable commits over huge changes containing multiple unrelated features.

### 6. Learn Together

Nobody is expected to know operating-system development beforehand.

---

## 📚 Documentation

The `docs/` directory contains project documentation, including:

```text
docs/
├── architecture/
├── development/
├── decisions/
└── guides/
```

Documentation should explain **why something exists**, not just what the code does.

---

## 🧪 Testing

Testing is an important part of BharatOS.

The `tests/` directory will eventually contain tests for individual components and system-level functionality.

As the project grows, we will introduce automated builds and testing.

---

## 🤝 Contributing

Before making a significant change:

1. Check the relevant subsystem.
2. Understand the existing implementation.
3. Create a focused branch.
4. Make small, logical commits.
5. Test your changes.
6. Open a Pull Request.
7. Explain what changed and why.

Avoid directly modifying another member's subsystem without coordination.

---

## 📜 Project Status

**Current Status:** 🟡 Early Development / Repository Setup

BharatOS is currently at the beginning of its development journey.

Expect things to be incomplete, experimental, and occasionally broken. That's part of the project.

---

## 🐢 About Turtle Team

**Turtle Team** is a group of developers building BharatOS as a collaborative learning project.

> **Start small. Build slowly. Understand everything.**

---

## ⚠️ Disclaimer

BharatOS is a hobby/educational operating-system project.

It is **not intended for production use** and should be treated as experimental software.

---

## 🇮🇳 BharatOS

**Built from scratch.
Built to learn.
Built by the Turtle Team.**
