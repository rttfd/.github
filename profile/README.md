## rttf

**Run The Thing First.**

rttf started as four keys on the left half of my split keyboard. It meant nothing. Then it turned into the only rule
here: nothing ships until it has run on the real thing. Usually it breaks there first, which is where the good fixes
come from.

A one-person workshop in Berlin. No layers of management, no meetings about meetings: you talk to the person who
wrote the code, probably while he's waiting for it to compile.

---

### What I build

**Embedded:** Rust for small chips. `no_std` libraries that run on real boards, not just in a simulator.

- [nanofish](https://github.com/rttfd/nanofish): a small `no_std` HTTP client and server, with Embassy, smoltcp and
  optional TLS, zero-copy into your own buffers.
- [leasehund](https://github.com/rttfd/leasehund): a `no_std` DHCP server for when your device *is* the network.
- On the bench: an e-ink home-lab status display on an ESP32-C3, with open Rust firmware.

**Lab:** tested Flux + k3s recipes for home-lab clusters, and a book about running one. Every recipe is deployed from
zero on a fresh VM, on x86_64 and arm64, before it ships.

**Apps:** native tools, free to download: [Matcha](https://rttf.dev/apps/matcha/) (a regex workbench) and
[Shokirei](https://rttf.dev/apps/shokirei/) (screenshots, made beautiful).

---

### Why Rust

Fast, safe, and I don't spend weeks chasing memory bugs on a chip with 400 KB of RAM. Most of the time.
(`unsafe` exists. I use it the way you use a fire extinguisher: rarely, and with a story afterwards.)

---

### The stack

- **Languages:** Rust, Elixir
- **Embedded:** microcontrollers, Embassy, `no_std`, IoT
- **Infrastructure:** k3s, Flux, Postgres, and a home lab that's backed up and has actually been restored

---

### Elsewhere

- **Website:** [rttf.dev](https://rttf.dev)
- **Shop:** [shop.rttf.dev](https://shop.rttf.dev)
- **Why "rttfd"?** `rttf` was taken on GitHub, hence the extra d.

Got a project, or just want to trauma-bond over compiler errors? [Drop a line](mailto:github@rttf.dev).
