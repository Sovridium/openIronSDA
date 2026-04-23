# openIronSDA 🦀⚙️

**openIronSDA** is a modern, Software-Defined Distributed Industrial Control System (SD-DCS) built entirely in Rust. It aims to provide a safe, high-performance alternative to traditional, proprietary SCADA and DCS architectures.

## 🚀 Key Features
- **Memory Safety**: Leveraging Rust to eliminate buffer overflows and memory leaks in critical control loops.
- **Hardware Agnostic**: Run industrial workloads on standard IT hardware or Real-Time Linux (RT-Preempt).
- **Fearless Concurrency**: High-throughput I/O handling powered by `tokio` for real-time responsiveness.
- **Open Standards**: Native support for OPC-UA, MQTT (Sparkplug B), and EtherCAT.

## 🛠️ Architecture
- `open-iron-core`: The real-time runtime engine.
- `open-iron-hal`: Hardware Abstraction Layer for various I/O fieldbus protocols.
- `open-iron-api`: A modern gRPC/REST interface for IT/OT convergence.

## 🏗️ Getting Started

### Prerequisites
- [Rust](https://rust-lang.org) (latest stable)
- `cargo-edit` (optional, for dependency management)

### Installation
```bash
git clone https://github.com
cd openIronSDA
cargo build --release
```

## 🤝 Contributing
We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to get started. Whether it's adding a new fieldbus protocol or improving documentation, your help is valued.

## ⚖️ License
This project is licensed under the **Apache License, Version 2.0**. See the [LICENSE](LICENSE) file for details.

---
*Built with passion for a safer, more open industrial future.*
