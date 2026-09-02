<div align="center">

# Arcel

**AI agent runtimes, post-quantum transports, and cryptographic systems.**

[arcel.org](https://arcel.org) &nbsp;·&nbsp; [contact@arcel.org](mailto:contact@arcel.org) &nbsp;·&nbsp; [install.arcel.org](https://install.arcel.org)

</div>

---

## Post-Quantum Networking

### [Seam](https://github.com/Arcel-Org/Seam) &nbsp;·&nbsp; Post-quantum UDP transport

Hybrid Noise_XX + ML-KEM-768 handshake. Multi-stream mux, Reed-Solomon FEC, DDoS-resistant stateless cookies. **247 µs handshake. 568 MiB/s encrypted throughput per core.** Replaces `scp`, `netcat`, and `ssh -L`.

```sh
curl -fsSL https://install.arcel.org/seam.sh | sh
```

---

## Cryptographic Systems

### [Signet](https://github.com/Arcel-Org/Signet) &nbsp;·&nbsp; Cryptographic photo watermarking SDK

Camera apps embed an unforgeable drand beacon proof at shutter press — before encoding. Verification is binary, non-interactive, and decentralized. iOS, Android, and C/C++ via FFI.

### [Fob](https://github.com/Arcel-Org/Fob) &nbsp;·&nbsp; Encrypted vault on any USB drive

Passwords, TOTP, SSH keys, and secure notes. Argon2id + XChaCha20-Poly1305. Plausible deniability. No install required on the host machine.

```sh
curl -fsSL https://install.arcel.org/fob.sh | sh
```

---

<div align="center">

MIT / AGPL-3.0 &nbsp;·&nbsp; [arcel.org](https://arcel.org)

</div>
