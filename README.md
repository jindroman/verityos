# verityos

  # 🟡 Verity OS

> **A Linux operating system with a personality.**

Verity OS is an experimental Linux distribution concept built around a simple idea:

**Your operating system shouldn't just work. It should talk to you.**

Verity combines a Linux desktop environment with a custom command-line experience, an AI-powered assistant, a 3D Verity orb, and its own package-management interface.

![Verity OS](https://placehold.co/1200x500/090909/FFD21A?text=VERITY+OS)

---

## ✨ Features

### 🔮 Verity AI

Meet **Verity** — a 3D orb that lives inside your desktop.

Verity is designed to:

* Talk to you using an AI voice
* Help with terminal commands
* Explain system errors
* Diagnose problems
* Manage packages
* Control parts of your desktop
* Eventually become your personal Linux assistant

Instead of:

```text
$ sudo apt install firefox
```

Verity aims for:

```text
$ sudo verity install firefox
```

And eventually:

```text
$ verity ask "install a browser and make it my default"
```

---

## 🖥️ Two Desktop Experiences

Verity OS is planned to ship with two pre-built desktop profiles.

### ⚡ Verity Hypr

A minimal, fast, keyboard-driven experience based around **Hyprland**.

Designed for:

* Power users
* Developers
* Keyboard workflows
* Performance
* Customization

### 🖥️ Verity Desktop

A more traditional graphical experience based around **KDE Plasma**.

Designed for:

* New Linux users
* Gaming
* Everyday computing
* Users who prefer a familiar desktop

You choose your experience during installation.

---

## 📦 The Verity Package Manager

Verity OS will eventually have its own frontend for Linux package management.

```bash
sudo verity install firefox
sudo verity remove firefox
sudo verity update
verity search discord
```

More advanced commands:

```bash
verity doctor
verity rollback
verity history
verity clean
```

The goal isn't to replace the underlying Linux package ecosystem.

Instead, **Verity provides a simpler interface on top of it.**

---

## 🩺 Verity Doctor

Something broken?

Try:

```bash
verity doctor
```

Verity will inspect things such as:

```text
✓ Kernel
✓ Network
✓ Audio
✓ GPU
✓ Desktop
✓ Package database
✓ System services
⚠ 3 problems detected
```

Eventually, Verity should be able to explain what went wrong and offer to fix it.

---

## 💾 Safe Updates & Rollbacks

Verity OS is planned around a snapshot-based system.

Before major updates:

```text
Creating snapshot...
✓ Snapshot created

Updating system...
✓ Packages updated

Verity OS has been updated successfully.
```

If something goes wrong:

```bash
verity rollback
```

The goal is to make experimenting with Linux much less scary.

---

## 🎨 Verityfetch

Verity OS comes with its own system-information tool:

```bash
verityfetch
```

Example:

```text
                                ▒▒▒▒▒▒▒▒▒▒▒▒▒▒
                           ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
                        ▒▒▒▒▒░██████████████▓███▒▒▒▒▒▒▒
                     ▒▒▒▒░████████████████████████▓█░▒▒▒▒
                   ▒▒▒▒████████████████████████████████▒▒▒▒▒
                 ▒▒▒▒       ██   █████   █   ░   █      █▒▒▒▒
               ░▒▒▒███  ██████  ██████  ████  ██ █  ███▓██▓▒▒▒▒
              ▒▒▒▓████ ▓   ███  ██████  ████░ ▒███ ▒   ██████▒▒▒
             ▒▒▒██████  ███ ██      ██  ▒███   ███ ▓ ██ ██████▒▒▒
            ▒▒▒███████████████████████████████████████████▓██▓█▒▒▒
           ▒▒▒██████  █  █ ██▒██▓ ██    █ █   █ █  █ █▒▓██░██▓█▓▒▒▒
           ▒▒ ██████   █ ▓     █   █░█▓█░██ █ █    █  █  █  █████▒▒
          ▒▒▒████████████████████░           ████████████████▓██▓▒▒▒
          ▒▒░█████████▓▓▓▓█████                ███████▓███████████▒▒
          ▒▒██████▓▓▒▓██▓█▓▓▓▓▒                 ███▒▓▓█████▓▓█▓███▒▒▒
         ░▒▒█████▓▓▓█▓▓▓▒▒▒▓█▓▒    █████   ███   █████████████▓███▒▒▒
          ▒▒███████▓░▓█▓▓▓▒▓ ▓▓                   █▓▓▓█▒▓▓▒███▓▓▓▓▒▒▒
          ▒▒███▓▓▓██▓▓▓▓▒▒▓█░▓▓▓░  ███████████    █▓▓▒▓██████████▓▒▒▒
          ▒▒ ██▓███  ███▓▓▓█▒▒▒▓▓░  ░██  ▓░█▓█    █▓▓▓▓▓▒ ███▓▓▓██▒▒
          ▒▒▒████ ▓▓█▒ ██▓█ █░▒▓▓▓▒ ░▓██▓█  █      ▓▓▓▒░██▓ ███▓█▒▒▒
           ▒▒░█  ███▒█▒ ███░▒█▒▒▒▓█▓           ░░ ███░▒█▒█▓▓  █▓█▒▒▒
           ▒▒▒███▒█▓▒██ ░  █░  █▓░▒▓█████▓▒░  ░ ░    ██▓▒▓ ▓▓██▓▒▒▒
            ▒▒▒█▓▓▒▒▓▓▒███ ▓███████ ░▓     ████░▒█ ██  █▓▓▓░███▒▒▒
             ▒▒▒██▓▒░▓▒▓█  ░██ █████ █░█ ▓ ███▒██▓  ██  ░  ██▓▒▒▒
              ▒▒▒███████░  ██▒███ ██░▒  ░  ███ █ ████████████▒▒▒
               ░▒▒▒▓▓██████▓████░▓██████████▓█████░▒████▓▓▓░▒▒▒
                 ▒▒▒▒███████▓█▓▓██▓▓██▓██▓▓█▓█▓▓▓███████▓█▒▒▒▒
                  ▒▒▒▒░▓▒▒ █████▓▓▓▓▓▓▒█▒▒▓█▓▒ ▓▓▒ ▒█▓▓▓▒▒▒▒
                     ▒▒▒▒▓▒▓▓█▓▓▓█▓██▓▓▓░▒▒▓▒▓▒▒▒▒░▒█▒▒▒▒░
                       ▒▒▒▒▒▒█▓▒▓▓▒▓▒▒▓▓▒▓▒▒▒▒▒░▒▒▒▒▒▒▒
                           ▒▒▒▒▒▒▒▒▒▒░▒▒▒▒▒▒▒▒▒▒▒▒▒▒
                                ▒▒▒▒▒▒▒▒▒▒▒▒▒▒

verity@system
──────────────────────────────
OS          Verity OS
Kernel      Linux
Desktop     Hyprland
Shell       zsh
Assistant   Verity AI
```

---

## 🧠 Project Philosophy

Verity OS isn't trying to make Linux complicated.

It's trying to make Linux **feel alive**.

The design philosophy is:

> **Powerful underneath. Simple on top.**

Advanced users should still have access to the normal Linux ecosystem, terminals, configuration files and tools.

New users should have Verity there to explain what everything means.

---

## 🛠️ Planned Architecture

```text
                    ┌─────────────────┐
                    │    Verity AI    │
                    │   Voice + LLM   │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │   Verity Orb    │
                    │   3D Assistant  │
                    └────────┬────────┘
                             │
              ┌──────────────▼──────────────┐
              │        Verity CLI           │
              │  install / doctor / update  │
              │  rollback / search / ask    │
              └──────────────┬──────────────┘
                             │
                 ┌───────────▼───────────┐
                 │    Linux / Arch       │
                 │   Package Ecosystem   │
                 └───────────┬───────────┘
                             │
                ┌────────────▼────────────┐
                │        Linux Kernel    │
                └─────────────────────────┘
```

---

## 🚧 Current Status

**Very early development / concept stage.**

Currently being worked on:

* [x] Verity branding
* [x] Verity ASCII logo
* [x] Verity OS web prototype
* [x] Initial CLI concept
* [x] Package manager concept
* [x] Desktop concepts
* [ ] Real Arch-based ISO
* [ ] Real `verity` package manager
* [ ] Hyprland profile
* [ ] KDE profile
* [ ] 3D Verity orb
* [ ] AI voice
* [ ] System diagnostics
* [ ] Snapshot/rollback system
* [ ] Installer
* [ ] Verity repositories

---

## 🧪 Prototype

The repository currently contains an HTML prototype demonstrating the visual direction of Verity OS.

Open:

```text
verity_os.html
```

in a browser to see it.

---

## 🗺️ Roadmap

### Phase 1 — Identity

* Verity branding
* UI design
* Terminal experience
* `verityfetch`
* Website

### Phase 2 — Linux Base

* Arch Linux base
* Installer
* Hardware detection
* Networking
* Audio
* GPU support

### Phase 3 — Desktop

* Verity Hypr
* Verity Desktop
* Themes
* Wallpapers
* Panel
* Notifications

### Phase 4 — Verity

* 3D orb
* AI backend
* Voice synthesis
* Speech recognition
* Terminal integration

### Phase 5 — Ecosystem

* Verity repositories
* Package manager
* Extensions
* Themes
* Plugins
* Community packages

---

## 🤝 Contributing

Verity OS is an experimental project and contributions are welcome.

Ideas, UI concepts, Linux development, package management, AI integration, desktop development and terrible jokes are all welcome.

If you have an idea:

1. Fork the repository
2. Create a branch
3. Make your changes
4. Open a pull request

---

## ⚠️ Disclaimer

Verity OS is currently experimental.

Do **not** install early development builds on a machine containing important data.

The project is still evolving rapidly and commands, architecture and features may change.

---

## 🟡 Verity

**Linux, but it talks back.**

```text
$ verity ask "what can you do?"

> Pretty much anything.
> Give me a minute.
```

---

### License

License information will be added as the project matures.
