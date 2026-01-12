# Vetale Browser – Legacy (WPF, 2024)

⚠️ **Legacy project – not actively maintained**

This repository contains the **first generation of Vetale Browser**, created in 2024 as an experimental desktop web browser. The project represents an early production-style prototype focused on **simplicity, fast startup, and minimal footprint**, without additional features or persistent storage.

---

## Project Overview

Vetale Browser (Legacy) is a **super-light desktop web browser** built with:

* **WPF (Windows Presentation Foundation)**
* **Microsoft WebView2 (Chromium-based)**
* **.NET 7**

The application already supported **tabs, browsing history, multi-window mode, and early-stage UI customization**, but intentionally avoided complex subsystems such as user profiles, cloud sync, or heavy background services. The goal was to understand the real-world behavior of WebView2 in a minimal production setup.

> Despite its simplicity, the browser launched successfully on a previously unused system without any additional configuration.

---

## Key Characteristics

* Tab support (basic implementation)
* Browsing history
* Multi-window support (independent windows)
* Early-stage UI customization
* Core navigation: Back / Forward / Reload
* No cloud sync or accounts
* No telemetry or analytics
* Minimal internal state
* Lightweight architecture
* Small distribution size (~22 MB including WebView2 runtime)

---

## Purpose of This Project

This project was created as:

* Hands-on training with **WPF + WebView2**
* First production-oriented desktop application
* Experiment with **deployment size and startup behavior**
* Foundation for later, more complex browser architectures

It also served as a learning step toward modern desktop application design and distribution.

---

## Current Status

* ❌ No active development
* ❌ No new features planned
* ✅ Kept for historical and educational purposes

The project remains public to demonstrate **early-stage engineering decisions and growth over time**.

---

## Evolution

Vetale Browser later evolved into newer generations with:

* More advanced architecture
* Improved UI concepts
* Extended browser functionality

This repository documents the **starting point** of that evolution.

---

## Links

* **Microsoft Store**: *[link here]*
* **GitHub Repository**: *[link here]*

---

## Notes for Reviewers

This repository should be evaluated as:

* A legacy prototype
* A minimal WebView2 integration example
* Evidence of practical experimentation, not a final product

---

© 2024–2026 Vetale Browser Project
