<div align="center">

# Arcel

**Open-source security infrastructure for the post-quantum era.**

[arcel.org](https://arcel.org) &nbsp;·&nbsp; [contact@arcel.org](mailto:contact@arcel.org) &nbsp;·&nbsp; [install.arcel.org](https://install.arcel.org)

</div>

---

Arcel builds Rust-based open-source tools that stay secure after quantum computers arrive — starting with how you move data and how you keep secrets.

## [Seam](https://github.com/Arcel-Org/Seam) &nbsp;·&nbsp; Post-quantum encrypted transport

A UDP transport that replaces `scp`, `netcat`, `ssh -L`, and `rsync` with one tool — faster on real-world links and safe against quantum computers.

- **Hybrid Noise_XX + ML-KEM-768 handshake** — session keys stay secret even if elliptic-curve crypto is broken later
- **Forward secrecy** via double ratchet, plus **traffic-analysis resistance** via padding, chaff, and jitter
- Multi-stream multiplexing with Reed-Solomon FEC — no head-of-line blocking, absorbs packet loss without retransmits
- **568 MiB/s** encrypted throughput · **247 µs** handshake, per core

```sh
curl -fsSL https://install.arcel.org/seam.sh | sh
```

## [Fob](https://github.com/Arcel-Org/Fob) &nbsp;·&nbsp; Encrypted vault on any USB drive

A cryptographic key on any USB stick. Plug it in, unlock with a passphrase, and your credentials are ready — nothing is installed on the host and the vault opens entirely in your browser.

- **Passwords, TOTP codes, SSH keys, secure notes, and file attachments** in one encrypted store
- **Argon2id + AES-256-GCM** — memory-hard key derivation that resists GPU/ASIC brute force
- **Plausible deniability** (decoy + duress slots) and a post-quantum hybrid recovery key (X25519 + ML-KEM-1024)
- Same Rust crypto in the CLI and the browser (WASM) — a vault created on the command line opens in the browser and vice versa

```sh
curl -fsSL https://install.arcel.org/fob.sh | sh
```

---

<div align="center">

[Seam](https://github.com/Arcel-Org/Seam) · AGPL-3.0 &nbsp;·&nbsp; [Fob](https://github.com/Arcel-Org/Fob) · MIT OR Apache-2.0

[arcel.org](https://arcel.org) &nbsp;·&nbsp; [contact@arcel.org](mailto:contact@arcel.org)

</div>
