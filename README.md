<div align="center">
<img src="https://images.blackroad.io/pixel-art/road-logo.png" alt="BlackRoad OS" width="80" />

# BlackRoad Analytics

**D1 page view tracking and reporting across all BlackRoad domains.**

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad_OS-Pave_Tomorrow-FF2255?style=for-the-badge&labelColor=000000)](https://blackroad.io)
</div>

---

## How It Works

A lightweight tracking pixel/script on each BlackRoad site sends page views to a Cloudflare Worker, which stores them in D1. Dashboard queries aggregate by domain, path, referrer, and time.

## Stack

- Cloudflare Workers (JavaScript)
- D1 (SQLite) for event storage
- Aggregation queries for dashboards

---

*Copyright (c) 2024-2026 BlackRoad OS, Inc. All rights reserved.*
