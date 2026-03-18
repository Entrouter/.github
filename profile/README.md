<div align="center">

<img src="https://raw.githubusercontent.com/Entrouter/.github/main/profile/logo.png" alt="Entrouter" width="380">

<br><br>

### Infrastructure for packets that cannot afford to be lost.

<br>

We build low-level networking and data integrity systems in Rust. Every component is designed for environments where correctness is not optional and performance is measured, not assumed.

<br>

---

<br>

<table>
<tr>
<td align="center" width="50%">

<h3><a href="https://github.com/Entrouter/entrouter-line">Entrouter Line</a></h3>

<br>

[![crates.io](https://img.shields.io/crates/v/entrouter-line.svg?style=flat-square&color=e94560)](https://crates.io/crates/entrouter-line)
[![Build](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml/badge.svg)](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/Entrouter/entrouter-line/blob/main/LICENSE)

**Zero-loss cross-region packet relay network.**

Adaptive forward error correction, encrypted UDP tunnels, real-time latency-mesh routing, and QUIC 0-RTT edge termination. Benchmarked on one of the longest internet routes on Earth.

```
cargo install entrouter-line
```

</td>
<td align="center" width="50%">

<h3><a href="https://github.com/Entrouter/entrouter-universal">Entrouter Universal</a></h3>

<br>

[![crates.io](https://img.shields.io/crates/v/entrouter-universal.svg?style=flat-square&color=fc8d62)](https://crates.io/crates/entrouter-universal)
[![Build](https://github.com/Entrouter/entrouter-universal/actions/workflows/ci.yml/badge.svg)](https://github.com/Entrouter/entrouter-universal/actions/workflows/ci.yml)
[![License](https://img.shields.io/crates/l/entrouter-universal?style=flat-square&color=8da0cb)](https://github.com/Entrouter/entrouter-universal/blob/main/LICENSE)

**Pipeline integrity guardian.**

What goes in, comes out identical. Base64 encoding, SHA-256 fingerprinting, cryptographic audit chains, per-field tamper detection, and a CLI that eliminates shell escaping across SSH, Docker, Kubernetes, and cron.

```
cargo install entrouter-universal
```

</td>
</tr>
</table>

<br>

---

<br>

### What We Do

</div>

**Packet Relay** - Relay infrastructure that absorbs packet loss using forward error correction before it reaches your application. Encrypted, globally routed, and measured against raw TCP on real networks.

**Data Integrity** - Tools for verifying that data survives every layer of your stack. Encoding, fingerprinting, tamper detection, and audit trails from ingress to storage.

**Routing** - Real-time path selection based on live latency measurements, not static BGP defaults. The fastest path, not the cheapest.

**Secure Transport** - Encryption on every hop. No optional toggles. No cleartext fallbacks.

<div align="center">

<br>

---

<br>

### Beyond Open Source

We are building additional infrastructure products that are not yet public. These span managed relay networks, traffic engineering, and integrity-as-a-service for production workloads. If you are interested in early access or commercial licensing, reach out at **hello@entrouter.com**.

<br>

---

<br>

### Principles

**Correctness over cleverness.** Every claim is backed by reproducible benchmarks and tests, not marketing copy.

**Measured, not estimated.** We publish real numbers from real infrastructure. If a metric is not tested, we do not advertise it.

**Rust everywhere.** Memory safety, zero-cost abstractions, and fearless concurrency. No garbage collection pauses. No runtime overhead.

<br>

---

<br>

<sub>Melbourne, Australia</sub>

</div>
