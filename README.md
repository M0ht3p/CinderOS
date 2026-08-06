# 🔥 CinderOS

**CinderOS** is a custom, lightweight, Linux distribution built on top of **Arch Linux**. Designed with modern aesthetics and seamless out-of-the-box performance in mind, CinderOS comes pre-configured with the GNOME desktop environment and essential daily-driver applications.

***Current version : 1.0***
**We may soon be able to provide a stable release different from the live environment**

---

## ✨ Features

* **Base:** Arch Linux (Rolling Release)
* **Desktop Environment:** Custom GNOME
* **System Display Manager:** GDM with custom CinderOS branding
* **Session Type:** Wayland

---

## 🚀 Getting Started

### Prerequisites

To test or build CinderOS on an Arch-based system, you will need:
* `archiso`
* `qemu-desktop` (for live testing)
**Note that this distribution isn't currently fully public, and is only a live environment for now. The permanent ISO will come as soon as possible.**

### Live Boot with QEMU

If you have downloaded or built the `.iso` file, you can quickly test it inside a virtual machine without installing:

```bash
run_archiso -i /path/to/cinderos-latest.iso


