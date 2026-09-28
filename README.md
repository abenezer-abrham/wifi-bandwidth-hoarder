# ⚡ WiFi Bandwidth Hoarder & Speed Engine ⚡

> **Ultra Network Throughput Accelerator, Dynamic Wi-Fi Spectrum Cockpit & Speedtest Engine.**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![Cross Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20macOS%20%7C%20Web-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🚀 Key Features

- ⚡ **Bandwidth Hoarding Optimization**:
  - Dynamically maximizes TCP Receive & Transmit buffers (up to 16MB).
  - Activates high-speed modern congestion algorithms (BBR / CUBIC).
  - Enables RFC 1323 TCP Window Scaling, TCP Fast Open (Mode 3), and Explicit Congestion Notification (ECN).
  - Disables Wi-Fi hardware power-saving packet sleep throttling.
  - Expands adapter transmit packet queues for zero-drop packet queuing.

- 📊 **Real-Time Speed & Latency Engine**:
  - Multi-round high-precision Ping & Jitter measurement.
  - Live streaming chunk Download bandwidth testing.
  - High-throughput Upload test stream.
  - Dynamic interactive gauge with live speedometer readout.

- 📡 **2.4 GHz & 5 GHz Wi-Fi Spectrum Analyzer**:
  - Discovers nearby access points, signal percentages, BSSIDs, and channels.
  - Visual spectrum bar chart powered by Chart.js.
  - Intelligent channel recommender to avoid co-channel congestion.

- 🌐 **Ultra-Fast DNS Benchmark & 1-Click Switcher**:
  - Benchmarks Cloudflare (1.1.1.1), Google (8.8.8.8), Quad9 (9.9.9.9), AdGuard (94.140.14.14), OpenDNS, and Mullvad.
  - Automatically sorts by lowest latency.
  - 1-Click active DNS applicator with automatic cache flushing.

- 📈 **Live Network Throughput Meter**:
  - Real-time download & upload bandwidth graphs and total RX/TX data counters.

- 💻 **Real-Time Diagnostic Kernel Console**:
  - Live timestamped execution logs with one-click clipboard copying.

---

## 🛠️ Quick Start

### Option A: Node.js / Express (Recommended)
```bash
npm install
npm start
```
Open **`http://localhost:8080`** in your browser.

### Option B: Python 3
```bash
python3 app.py
```
Open **`http://localhost:8080`** in your browser.

---

## ☁️ Deploy to Vercel

This repository is pre-configured for instant zero-configuration deployment to **Vercel** with full serverless routing in `vercel.json` and `api/index.js`.

```bash
npx vercel
```

---

## 📄 License
MIT License. Created with ⚡ for high-speed network performance.
