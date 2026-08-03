# 🔥 CinderOS

**CinderOS** is a custom, lightweight, Linux distribution built on top of **Arch Linux**. Designed with modern aesthetics and seamless out-of-the-box performance in mind, CinderOS comes pre-configured with the GNOME desktop environment and essential daily-driver applications.

---

## ✨ Features

* **Base:** Arch Linux (Rolling Release)
* **Desktop Environment:** Custom GNOME
* **Keyboard Layout:** French (AZERTY) default
* **System Display Manager:** GDM with custom CinderOS branding
* **Session Type:** Wayland

---

## 🚀 Getting Started

### Prerequisites

To test or build CinderOS on an Arch-based system, you will need:
* `archiso`
* `qemu-desktop` (for live testing)
* Therefor, please contact me for any test or build of CinderOS, as it is not currently public, though you can just ask me for it.

### Live Boot with QEMU

If you have downloaded or built the `.iso` file, you can quickly test it inside a virtual machine without installing:

```bash
run_archiso -i /path/to/cinderos-latest.iso
