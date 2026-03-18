
<div align="center">

<img src="https://raw.githubusercontent.com/Entrouter/.github/main/profile/logo.png" alt="Entrouter" width="400">

<br><br>

**Infrastructure for packets that can't afford to be lost.**

<br>

We build networking systems that make unreliable links behave like reliable ones without adding latency, without TCP retransmits, and without compromising on encryption.

**Entrouter** is our intelligent routing platform optimised path selection, real-time network telemetry, and resilient packet delivery across global infrastructure.

**Entrouter Line** is the open-source relay engine that powers it.

<br>

---

### Open Source

| Project | Description | Status |
|---------|-------------|--------|
| **[entrouter-line](https://github.com/Entrouter/entrouter-line)** | Zero-loss packet relay adaptive FEC, encrypted UDP tunnels, latency-mesh routing, QUIC 0-RTT edge | [![Build](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml/badge.svg)](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml) |

<br>

### What We Build

**Entrouter** Intelligent routing platform for latency-sensitive traffic. Finds the fastest path, not the cheapest. Adapts in real-time as network conditions change.

**Entrouter Line** The relay layer. Forward Error Correction absorbs packet loss before it reaches your application. ChaCha20-Poly1305 encryption on every hop. Dijkstra mesh routing on live latency data.

<br>

### What We Care About

**Correctness over cleverness.** Real benchmarks, not marketing numbers. Every claim backed by reproducible tests.

**Encryption always on.** ChaCha20-Poly1305 between every hop. No "optional TLS" toggle.

**Zero overhead.** The relay adds 0% packet loss at every tested loss level. If your link drops packets, that's physics we don't make it worse.

---

<sub>Australia · MIT Licensed</sub>

</div>
