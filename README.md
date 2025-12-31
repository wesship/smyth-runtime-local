> [!NOTE]
> This project is a fork of [SmythOS/smyth-runtime-local](https://github.com/SmythOS/smyth-runtime-local). The original project and its contributors can be found there.

# Smyth Runtime Local (SRE)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/smyth-runtime-local/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/smyth-runtime-local/actions/workflows/ci.yml)

> A free, lightweight, and standalone runtime for executing SmythOS AI agents locally on Mac, Windows, and Linux. It allows developers to run, test, and develop agents with complete privacy and control over their data.

---

## ✨ Features

- **Run Agents Locally**: Execute SmythOS agents on your own hardware.
- **Cross-Platform**: Supports Mac, Windows, and Linux.
- **Lightweight**: Minimal resource consumption (CPU, memory) and no GPU required.
- **Privacy-Focused**: No communication with the SmythOS SaaS, ensuring complete data privacy.
- **Free for Personal & Commercial Use**: No cost to use for any purpose.

---

## 🚀 Getting Started

### Prerequisites

- None! The runtime is fully contained with no dependencies.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wesship/smyth-runtime-local.git
   cd smyth-runtime-local
   ```
2. Copy the example vault and add your API keys:
   ```bash
   cp vault.json.example vault.json
   ```

### Usage

Execute the runtime binary for your platform with the desired agent and parameters:

```bash
./bin/smyth-runtime-linux \
 --agent agents/llm.smyth \
 --vault vault.json \
 --post question="What is the capital of France?" \
 --endpoint ask
```

---

## 🛠️ Built With

- [Node.js](https://nodejs.org/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
