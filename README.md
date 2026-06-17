# John Kruze

Deterministic physics engine. 14 substrates. 1000Hz. SHA-256 sealed at every integration step.

The G^G stack generates the proprioceptive ground truth that lets autonomous systems feel forces instead of just measuring them — the substrate layer between what a VLA policy intends and what physics allows.

---

## The Stack

```
genesis-core          14 substrates · 113 Monte Carlo binaries · pure CPU Rust
ztp-runtime           Zero-dependency FFI kernel — C-compatible, bare-metal speeds
zero-trust-physics    13 ZTP somatic grounding interfaces — Python → C FFI → 1000Hz Rust
kid-cosmo             Reasoning kernel — local MLX inference · sealed manifests · Dark Window
aegis-os              Per-body OS — 8 body daemons · fleet commander · ICP manifest sealing
spectra-1             Physics oracle on ICP mainnet — deterministic, publicly callable
gg-mcp                8-tool MCP server connecting Claude to the physics pipeline
datasets              Open datasets — GitHub LFS + HuggingFace mirror
```

---

## The Design Constraint

The Dark Window — spacecraft behind Mars, submarine under thermoclines, drone under active jamming — is not an edge case. It is the condition this stack is built for.

A platform at the physical frontier either carries its own somatic ground truth in local registers, or it has nothing when the link goes dark. G^G generates that ground truth at scale. Zero-Trust Physics projects it as 1000Hz spinal reflexes. Kid Cosmo reasons through it without uplink. Aegis OS seals every decision on-chain.

The question is not how to contain the machine. The question is how far it can reach.

---

## Entry Points

**VLA and policy engineers** — the gap between a 5Hz planner and physical reality:
[`zero-trust-physics`](https://github.com/johnkruze/zero-trust-physics) · start with `vla_somatic_bridge.py`
[`datasets`](https://huggingface.co/spiderpilot89) · 8 open datasets · MIT · 1000Hz

**GNC and embedded engineers** — C-compatible FFI, zero dependencies, bare-metal:
[`ztp-runtime`](https://github.com/johnkruze/ztp-runtime) · Terran 131M/s · Orbital 8.6M/s · Atheric 6.1M/s at 1 kHz

**Researchers and physicists** — 14 substrates from Boussinesq soil to transmon qubits:
[`genesis-core`](https://github.com/johnkruze/genesis-core) · every equation traces to a verified mechanical reference

**Autonomy and systems engineers** — per-body sovereign decision loop, on-chain proof:
[`aegis-os`](https://github.com/johnkruze/aegis-os) + [`spectra-1`](https://github.com/johnkruze/spectra-1)

---

## Physics Substrates

| Substrate | Physics |
|-----------|---------|
| Energy Grid | Swing equation, renewable intermittency, cascade failure |
| Tokamak | MHD plasma stability, Z-axis shear, beta-limit disruption |
| Atheric | Shannon capacity, Friis path loss, SHA-256 frequency hopping |
| Terran | Boussinesq soil stress, glomalin coupling, robot-soil contact |
| Swing Grid | Inertia floor collapse, PLL tracking error, IBR penetration |
| Reactor | Neutron kinetics, 6-group delayed precursors, Xenon-135 poisoning |
| Mycelial | Kirchhoff flow, hyphal conductance, percolation threshold |
| Orbital | J2–J4 geopotential, quaternion attitude, 1PN corrections |
| Mars | CO₂ exponential atmosphere, EDL trajectory, powered descent |
| Plutonian | Entropy decay, phase crystallization, deep-cold thermodynamics |
| Celestial | Yoshida 4th-order symplectic, N-body ephemeris |
| Marine | Archimedes buoyancy, 6-DOF GPS-denied nav, IMU drift |
| Asteroid | O(N²) N-body gravity, Hookean contact, Metal GPU |
| Josephson | RCSJ transmon qubit phase dynamics, 500GHz solver, decoherence boundary |

*Rates live-measured on Apple Silicon M-series. Run `corpus_sweep` for current numbers.*

---

[ZeroTrustPhysics.com](https://ZeroTrustPhysics.com) · kruze@zerotrustphysics.com
