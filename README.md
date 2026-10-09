# 💻 Computer Science Foundations — Educational Web Portal

> A comprehensive, semantically structured educational web portal presenting fundamental pillars of computer science: hardware architecture, software paradigms, network engineering, computing history, artificial intelligence, and supercomputing.

[![Standards](https://img.shields.io/badge/Standards-HTML5%20%7C%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Project](https://img.shields.io/badge/Project-Semester%20Assignment-blue?style=for-the-badge)](https://github.com/kersonik/pololetni-projekt)
[![Language](https://img.shields.io/badge/Content-Czech%20(cs--CZ)-critical?style=for-the-badge)](index.html)
[![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](LICENSE)

---

## 📖 Overview

This static web project serves as an interactive study portal for computer science students. Built with pure semantic HTML5 and modern modular CSS, it features a unified dark navigation shell, responsive layout, illustrative media (diagrams, photos, and animated GIFs), and structured definitions referenced to academic and historical sources.

---

## 📚 Curriculum Topics & Module Breakdown

| Page / Module | Topic | Core Contents & Concepts |
| :--- | :--- | :--- |
| **[`index.html`](index.html)** | **Úvod & Architektura** | Portal homepage, conceptual definition of computer programs, relationship between algorithms and data structures. |
| **[`historie.html`](historie.html)** | **Historie počítačů** | Evolution across five computing generations: vacuum tubes, discrete transistors, integrated circuits, microprocessors, and modern parallel architectures. |
| **[`hardware.html`](hardware.html)** | **Počítačový hardware** | In-depth breakdown of physical components: Central Processing Units (CPU), Graphics Processing Units (GPU), volatile memory (RAM), storage technologies (NVMe SSD / HDD), and motherboard bus interconnects. |
| **[`software.html`](software.html)** | **Software & Bezpečnost** | System software (OS, kernels) vs. application software, malware taxonomy (viruses, trojans, ransomware, spyware), and defensive cybersecurity practices. |
| **[`site.html`](site.html)** | **Počítačové sítě** | Network reference models (OSI 7-layer vs. TCP/IP 4-layer), switching mechanisms (circuit vs. packet switching), network topologies, client-server vs. P2P architectures, and geographic scopes (PAN, LAN, MAN, WAN). |
| **[`ai.html`](ai.html)** | **Umělá inteligence** | Foundations of AI, Machine Learning (ML), Deep Learning neural networks, Natural Language Processing (NLP), ethical dilemmas (bias, black-box decisions, hallucinations), and legislative frameworks such as the EU AI Act. |
| **[`super.html`](super.html)** | **Superpočítače** | High-Performance Computing (HPC), parallel computing architectures (Flynn's taxonomy: SIMD, MIMD, SMP, NUMA, GPGPU), distributed computing initiatives (BOINC, Folding@home, SETI@home), and iconic machines (Deep Blue, GRAPE). |

---

## 🎨 Design & Technical Features

- **Semantic HTML5**: Native use of `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, and `<footer>` containers.
- **Unified Navigation Header**: Consistent, accessible navbar across all sub-pages allowing effortless browsing between topics.
- **Rich Media Integration**: Includes diagrams, schematics, and animations within `img/` and `gif/` directories.
- **Zero Build Tools Required**: Pure client-side static files — runs immediately in any browser with zero installation overhead.

---

## 📁 Repository Structure

```
pololetni-projekt/
├── index.html        # Portal landing page
├── historie.html     # History and generations of computing
├── hardware.html     # Physical hardware components guide
├── software.html     # Software classification & cybersecurity
├── site.html         # Network engineering & protocols
├── ai.html           # Artificial intelligence & machine learning
├── super.html        # Supercomputers & distributed systems
├── css/              # Stylesheets and visual themes
├── img/              # Illustrative photographs and diagrams
├── gif/              # Animated demonstrations and hardware visuals
└── README.md         # Project documentation and summary
```

---

## 🚀 How to Run & Preview

Because this is a pure static web application, no compilation or runtime environment is needed.

### Quick Browser Launch

- **Linux**:
  ```bash
  xdg-open index.html
  ```
- **macOS**:
  ```bash
  open index.html
  ```
- **Windows**:
  Double-click `index.html` or execute in PowerShell:
  ```powershell
  Start-Process index.html
  ```

### Local HTTP Server (Optional)
If you prefer running via a local web server:

```bash
# Using Python 3 built-in HTTP server:
python3 -m http.server 8080
```
Then navigate to `http://localhost:8080` in your web browser.

---

## 📄 License

Created as a high school semester project at SŠPU Opava. Released under the MIT License.
