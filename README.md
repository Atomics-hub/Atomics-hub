### Tom Ryan

Security researcher and engineer. I find memory-safety and authorization bugs in software people actually run — the Linux kernel, V8/Chrome, and the infrastructure that sits in front of everything.

#### Selected security work
- 🐧 **io_uring `SQE_MIXED` out-of-bounds read** — fix merged upstream by Jens Axboe, backported to 6.19-stable
- 🟦 **V8 Maglev uninitialized read** — fixed by the V8 team, credited on the Chrome VRP panel
- 🔓 **Advisories** in Vaultwarden (SSO account takeover) and Plane (cross-workspace IDOR), with more in coordinated disclosure
- → **Full ledger: [tomryan.dev/security](https://tomryan.dev/security)**

#### How I work
The edge is targeting and proof, not volume. I aim AI-driven fuzzers and test harnesses at the specific surfaces that look wrong, then reproduce every promising hit in the target's own compiled code before it reaches a maintainer. When automated scanners flood projects with plausible-but-wrong reports, a reproducible PoC is the bar.

#### Also
iOS apps under Rekishi LLC · writing at [tomryan.dev](https://tomryan.dev)

📫 **overboardapps@gmail.com** · [PGP](https://tomryan.dev/pgp-key.asc) · [GitHub](https://github.com/Atomics-hub)
