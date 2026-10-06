# Unclutter Remix

> A customized fork of [kitze/unclutter](https://github.com/kitze/unclutter).

---

## 📌 About This Fork

This project is a fork of **Unclutter** created by [Kitze](https://github.com/kitze). 

Unclutter is a browser extension that uses AI to detect and hide annoying page clutter, ads, and cookie banners across the web.

### What is different in this remix?
* **10-Second Auto-Cleanup:** Automatically reapplies your page cleaning rules 10 seconds after the page loads. This catches late popups, delayed ads, and sticky banners that take a few seconds to appear.
* **Upstream Tracking:** Built directly on top of the original code and kept up to date with the main project.

---

## 🛠️ Prerequisites

Before you start, make sure you have installed:
* [Node.js](https://nodejs.org/) (v22.12 or newer)
* [Bun](https://bun.sh/)

---

## 🚀 How to Build and Install

### 1. Clone and Install

```bash
git clone [https://github.com/glennsvel90/unclutter-remix.git](https://github.com/glennsvel90/unclutter-remix.git)
cd unclutter-remix
bun install --frozen-lockfile
bun run build
