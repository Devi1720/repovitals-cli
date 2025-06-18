# RepoVitals CLI

A lightweight CLI tool to scan and evaluate open-source projects across health, security, and sustainability.

Built for maintainers, researchers, and OSS contributors.

### 🔍 What It Does

- Runs multiple OSS intelligence tools in one command:
  - OSSF Scorecard
  - OSSF criticality_score
  - GitHub metadata extraction
- Produces a unified project health report
- Supports local output, JSON export, or syncing with [repovitals.com](https://repovitals.com)


## 🚀 Quick Start

```bash
go install github.com/repovitals/cli@latest
repovitals scan --repo=github.com/ossf/scorecard
```

## ✨ Features

- ✅ Unified scoring and report summary
- 🧠 Offline or synced modes
- 📊 JSON or CLI table output
- 🔐 GitHub token support for rate limits
- ⏱️ Smart caching for repeated scans

## 🛠️ Usage

```bash
repovitals scan --repo=<REPO_URL> [--json] [--upload]
```

Example:
```bash
repovitals scan --repo=github.com/vercel/next.js --json
```

## 🤝 Contribute

We welcome contributors to extend new data sources or improve reporting! See CONTRIBUTING.md.

## 📄 License

MIT License.
