
<div align="center">

# Entrouter

**Infrastructure for packets that can't afford to be lost.**

<br>

We build low-level networking systems that make unreliable links behave like reliable ones — without adding latency, without TCP retransmits, and without compromising on encryption.

<br>

---

### 🔬 Open Source

| Project | Description | Status |
|---------|-------------|--------|
| **[entrouter-line](https://github.com/Entrouter/entrouter-line)** | Zero-loss cross-region packet relay with adaptive FEC, encrypted tunnels, and mesh routing | [![Build](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml/badge.svg)](https://github.com/Entrouter/entrouter-line/actions/workflows/ci.yml) |

<br>

### What We Care About

**Correctness over cleverness.** Real benchmarks, not marketing numbers. Every claim backed by reproducible tests.

**Encryption always on.** ChaCha20-Poly1305 between every hop. No "optional TLS" toggle.

**Zero overhead.** The relay adds 0% packet loss at every tested loss level. If your link drops packets, that's physics — we don't make it worse.

---

<sub>Melbourne, Australia · MIT Licensed</sub>

</div>
