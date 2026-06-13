
# 🧛‍♂️ DRC-Crawl (CrabSitemap)
A high-performance, asynchronous web crawler and sitemap generator written in Rust. Features a sleek cyberpunk-inspired web dashboard, live telemetry, and background scheduling options.
## ⚡️ Features
 * Asynchronous Engine: Powered by tokio and reqwest with configurable concurrency limits and semaphores.
 * Multi-Storage Architecture: Supports PostgreSQL, SQLite, and JSON Lines out of the box using an adapter pattern.
 * Live Telemetry Dashboard: Full dark/light tech-noir UI featuring dual-language (EN/FA) support and live monitoring.
 * Automated Sitemaps: Generates, merges, and updates compliant sitemap.xml structures dynamically.
 * Systemd Service Integration: Built-in CLI commands to install or uninstall the panel as a Linux background daemon.
## 🛠 Tech Stack
 * Backend: Rust (axum, tokio, sqlx, scraper, quick-xml, clap)
 * Frontend: Vanilla HTML5, CSS3 (Custom properties/Themeable), Native JavaScript
## 🚀 Getting Started
### 1. Prerequisites
Make sure you have Rust and Cargo installed:
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
### 2. Running the Web Dashboard
To launch the setup wizard and ignite the tech-noir web UI:
cargo run -- release web
Once started, open your browser and navigate to: http://localhost:786
### 3. CLI Mode Direct Scan
If you prefer running a quick crawl directly via the terminal without the UI:
cargo run -- release cli --url https://example.com
## 📦 CI/CD & Automated Releases
## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
