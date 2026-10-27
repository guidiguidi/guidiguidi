# Hi, I'm Valentyn 👋
### Web Scraping & Backend Developer (Go & Python)

[![Go](https://img.shields.io/badge/Go-1.24%2B-00ADD8?style=flat&logo=go&logoColor=white)](https://golang.org)
[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Playwright](https://img.shields.io/badge/Playwright-Automation-2EAD33?style=flat&logo=playwright&logoColor=white)](https://playwright.dev)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat&logo=docker&logoColor=white)](https://docker.com)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-Passing-success?style=flat&logo=githubactions&logoColor=white)](https://github.com/guidiguidi)

---

### 👨‍💻 What I do

I love reverse-engineering web targets, taking apart private APIs, and building fast scrapers that don't get banned. Most of my work is focused around Go and Python:

- **Bypassing anti-bot protections without bloated browsers:** Wherever possible, I avoid running heavy headless Chrome instances. For example, in [`depop-tls-scraper`](https://github.com/guidiguidi/depop-tls-scraper), I spoof TLS fingerprints (JA3/JA4) and HTTP/2 frames directly in Go (`bogdanfinn/tls-client`) to get past Cloudflare at raw HTTP speeds (~20 MB RAM instead of hundreds of megabytes per browser).
- **Cracking private and mobile APIs:** Instead of scraping raw HTML, I prefer sniffing mobile apps or frontend bundles to find private REST/GraphQL endpoints. In [`xianyu-mtop-scraper`](https://github.com/guidiguidi/xianyu-mtop-scraper), I reverse-engineered Alibaba's MTOP gateway, implemented MD5 request signing, and used Playwright only when necessary to refresh session tokens automatically.
- **Stealth browser automation:** When a site strictly requires a real browser, I use **Camoufox** (anti-detect Firefox C++ fork) with Playwright to beat browser fingerprinting and behavioral checks ([`x-stealth-automation`](https://github.com/guidiguidi/x-stealth-automation)).
- **Concurrency & proxies:** Writing clean concurrent worker pools in Go, managing residential/datacenter proxy pools, handling 429 rate-limits, and persisting clean data to SQLite/PostgreSQL.

---

### 🛠️ Projects

- [**depop-tls-scraper**](https://github.com/guidiguidi/depop-tls-scraper) — Fast Go scraper using JA3/JA4 TLS spoofing to bypass Cloudflare without launching a browser. Thread-safe deduplication cache and CI test suite.
- [**xianyu-mtop-scraper**](https://github.com/guidiguidi/xianyu-mtop-scraper) — Reverse-engineered Alibaba Xianyu (Goofish) MTOP API with client-side MD5 signing, dynamic proxy rotation, and Playwright session self-healing.
- [**x-stealth-automation**](https://github.com/guidiguidi/x-stealth-automation) — Stealth automation agent built on Camoufox (C++ modified Firefox) and Playwright for bypassing bot detection heuristics.
- [**etsy-api-pipeline**](https://github.com/guidiguidi/etsy-api-pipeline) — Concurrent listing pipeline in Go with worker pools, OAuth2 PKCE flow, filtering, and database storage.
- [**polymarket-intelligence**](https://github.com/guidiguidi/polymarket-intelligence) — Prediction market data crawler with cursor pagination, rate-limiting, and exponential backoff.

---

### 💻 Stack

- **Languages:** Go, Python, SQL, Bash
- **Scraping & Stealth:** Playwright, Camoufox, bogdanfinn/tls-client (JA3/JA4), Headless Browsers
- **Network & Proxies:** HTTP/2, SOCKS5, Residential/Mobile proxy rotation, rate-limit backoff
- **Storage & DevOps:** SQLite, PostgreSQL, Docker, Docker Compose, Git, GitHub Actions

---

### 📬 Contact

- **Email:** [guidiclub@gmail.com](mailto:guidiclub@gmail.com)
- **GitHub:** [github.com/guidiguidi](https://github.com/guidiguidi)
- **Status:** Open to **Warsaw Hybrid** (ready to relocate) or **Remote B2B** opportunities.
