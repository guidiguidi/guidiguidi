# Hi, I'm Valentyn Hrodiuk 👋
### Web Scraping & Backend Developer (Go & Python)

[![Go](https://img.shields.io/badge/Go-1.24%2B-00ADD8?style=flat&logo=go&logoColor=white)](https://golang.org)
[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Playwright](https://img.shields.io/badge/Playwright-Automation-2EAD33?style=flat&logo=playwright&logoColor=white)](https://playwright.dev)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat&logo=docker&logoColor=white)](https://docker.com)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-Passing-success?style=flat&logo=githubactions&logoColor=white)](https://github.com/guidiguidi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/valentyn-hrodiuk-85025a447/)

---

### 👨‍💻 What I do

I specialize in reverse-engineering web targets, taking apart protected private APIs, and building high-throughput scrapers that don't get banned:

- **Bypassing anti-bot protections without bloated browsers:** Wherever possible, I avoid running heavy headless Chrome instances. In [`depop-tls-scraper`](https://github.com/guidiguidi/depop-tls-scraper), I spoof TLS fingerprints (JA3/JA4) and HTTP/2 frames directly in Go (`bogdanfinn/tls-client`) to bypass Cloudflare at raw HTTP wire speeds (~20 MB RAM instead of hundreds of megabytes per browser).
- **Cryptographic auth & private API reverse engineering:** Rather than scraping raw HTML, I inspect mobile apps and frontend bundles to find private REST/GraphQL gateways. In [`unifeed-marketplace-core`](https://github.com/guidiguidi/unifeed-marketplace-core), I reverse-engineered Mercari Japan's DPoP authentication by generating ephemeral **ECDSA P-256** key pairs and signing **ES256 JWT** tokens on Go. In [`xianyu-mtop-scraper`](https://github.com/guidiguidi/xianyu-mtop-scraper), I implemented Alibaba's MTOP MD5 HMAC request signing with automatic Playwright session self-healing.
- **Stealth browser automation:** When a target strictly requires a real browser environment, I use **Camoufox** (anti-detect Firefox C++ fork) with Playwright to beat advanced browser fingerprinting, CDP leak detection, and behavioral heuristics ([`x-stealth-automation`](https://github.com/guidiguidi/x-stealth-automation)).
- **Adversarial computer vision & anti-crawling defense:** In [`lens-cloak`](https://github.com/guidiguidi/lens-cloak), I built an adversarial perturbation pipeline that injects high-frequency noise and micro-geometric warping into images, disrupting CNN and Vision Transformer embeddings (Google Lens, PimEyes) while completely sanitizing digital footprints (EXIF/GPS/ICC).
- **High-concurrency systems & streaming:** Writing clean concurrent worker pools, managing low-level memory/file ring buffers ([`go-mac-shadowplay`](https://github.com/guidiguidi/go-mac-shadowplay)), proxy rotation, handling 429 rate-limits, and persisting clean data to SQLite/PostgreSQL.

---

### 🛠️ Featured Projects

- [**depop-tls-scraper**](https://github.com/guidiguidi/depop-tls-scraper) — Fast Go scraper using JA3/JA4 TLS spoofing to bypass Cloudflare without launching a browser. Thread-safe deduplication cache and CI test suite.
- [**unifeed-marketplace-core**](https://github.com/guidiguidi/unifeed-marketplace-core) — High-concurrency Go aggregator for East Asian resale markets featuring Mercari JP ephemeral ECDSA P-256 / ES256 DPoP signing, Yahoo Auctions DOM parsing, and Bunjang API ingestion.
- [**xianyu-mtop-scraper**](https://github.com/guidiguidi/xianyu-mtop-scraper) — Reverse-engineered Alibaba Xianyu (Goofish) MTOP API with client-side MD5 signing, dynamic proxy rotation, and Playwright session self-healing.
- [**x-stealth-automation**](https://github.com/guidiguidi/x-stealth-automation) — Stealth automation agent built on Camoufox (C++ modified Firefox) and Playwright for bypassing bot detection heuristics.
- [**lens-cloak**](https://github.com/guidiguidi/lens-cloak) — Adversarial perturbation & metadata sanitization engine evading AI visual search crawlers (Google Lens, PimEyes) with Python CLI & Web Canvas Studio.
- [**go-mac-shadowplay**](https://github.com/guidiguidi/go-mac-shadowplay) — ShadowPlay-style instant replay and screen recorder for macOS written in Go with ScreenCaptureKit, AVFoundation H.264 ring buffers, and Objective-C bridge.
- [**etsy-api-pipeline**](https://github.com/guidiguidi/etsy-api-pipeline) — Concurrent listing pipeline in Go with worker pools, OAuth2 PKCE flow, filtering, and database storage.
- [**polymarket-intelligence**](https://github.com/guidiguidi/polymarket-intelligence) — Prediction market data crawler with cursor pagination, rate-limiting, and exponential backoff.

---

### 💻 Stack

- **Languages:** Go, Python, SQL, Bash, Objective-C / C (CGO)
- **Scraping & Stealth:** Playwright, Camoufox, bogdanfinn/tls-client (JA3/JA4), Headless Chrome/Firefox
- **Security & Cryptography:** ECDSA P-256, ES256 JWT / DPoP, MD5 HMAC, Adversarial Perturbation
- **Network & Proxies:** HTTP/2, SOCKS5, Residential/Mobile proxy rotation, rate-limit backoff
- **Storage & DevOps:** SQLite, PostgreSQL, Docker, Docker Compose, Git, GitHub Actions

---

### 📬 Contact

- **Email:** [guidiclub@gmail.com](mailto:guidiclub@gmail.com)
- **LinkedIn:** [linkedin.com/in/valentyn-hrodiuk-85025a447](https://www.linkedin.com/in/valentyn-hrodiuk-85025a447/)
- **GitHub:** [github.com/guidiguidi](https://github.com/guidiguidi)
- **Status:** Open to **Warsaw Hybrid** (ready to relocate) or **Remote B2B** opportunities.
