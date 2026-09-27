# ACPUD — Asynchronous CPU Designer

> Design clockless CPUs. Visual + RTL async CPU designer built in Rust with Veryl.

Sync CPUs burn 20–40% of their power on the clock tree — even when idle.
Async (clockless) CPUs only spend energy on real work: cooler, more efficient,
and naturally parallel. But the tooling never existed.

**ACPUD is that tooling.**

## ✨ Features
- 🎨 Visual async design — drag-and-drop blocks, handshake wires, no clock
- 🦀 Rust-powered — fast, safe, cross-platform
- 📝 Veryl RTL — generate clean, modern HDL
- ⚡ Event-driven simulation — watch handshakes fire
- 📊 Ops/event + events/sec metrics — the async performance model, built in
- 🔋 Power estimation — see the "no clock waste" advantage
- 🌐 Web demo (WASM) — try it in your browser

## 🚀 Quick start
```bash
cargo install acpud
acpud new my-async-cpu
acpud gui

## 📜 License
Licensed under either of:
- Apache License, Version 2.0 [LICENSE-APACHE](.LICENSE-APACHE))
- MIT license [LICENSE-MIT](.LICENSE-MIT)

at your option.
