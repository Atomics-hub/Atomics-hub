# Tom Ryan / A5omic

Security researcher and software engineer focused on memory safety, authorization boundaries, and reproducible proof.

[Website](https://tomryan.dev) · [Security ledger](https://tomryan.dev/security) · [HackerOne](https://hackerone.com/a5omic?type=user) · [Writing](https://tomryan.dev/writing) · [PGP](https://tomryan.dev/pgp-key.asc)

## Selected security work

| Surface | Result | Public proof |
| --- | --- | --- |
| Linux `io_uring` | Found an `SQE_MIXED` out-of-bounds read. The fix merged upstream and the regression test landed in liburing. | [Kernel fix](https://git.kernel.org/pub/scm/linux/kernel/git/axboe/linux.git/commit/?id=c76e0f1d77f87e258193c2628253782d5ff414c7) · [liburing test](https://github.com/axboe/liburing/commit/a35e4943ec95af0aba795a58fd9d680a54406dc5) |
| V8 / Chrome | Found an uninitialized read in Maglev. The V8 team fixed it and listed the work on the Chrome VRP panel. | [V8 fix](https://chromium.googlesource.com/v8/v8.git/+/2d111040) · [Writeup](https://tomryan.dev/writing/v8-maglev-saved-mode-uninit/) |
| trigger.dev | Reported a cross-tenant task replay issue, fixed in v4.5.2. | [GHSA-9fq3-68cw-r7p2](https://github.com/triggerdotdev/trigger.dev/security/advisories/GHSA-9fq3-68cw-r7p2) |
| Vaultwarden | Independently reported an SSO email verification bypass, published as CVE-2026-47164 and fixed in 1.36.0. | [Writeup](https://tomryan.dev/writing/vaultwarden-sso-email-verified/) · [Advisory](https://github.com/dani-garcia/vaultwarden/security/advisories/GHSA-6x5c-84vm-5j56) |
| Anthropic | One report resolved through HackerOne with a $100 bounty. Technical details are not public. | [HackerOne profile](https://hackerone.com/a5omic?type=user) |

## Building

| Project | What it is |
| --- | --- |
| [reproassert](https://github.com/Atomics-hub/reproassert) | Generates and sandbox-verifies failing pytest reproduction candidates from GitHub issues. |
| [AgentK](https://github.com/Atomics-hub/agentk) | A user-space security kernel for AI agents with typed tool boundaries, policy, receipts, and replayable evidence. |
| [flowdown](https://github.com/Atomics-hub/flowdown) | A zero-dependency, O(1) streaming Markdown renderer for AI output. |

## Elsewhere

I ship apps through Rekishi LLC, write technical and personal essays at [tomryan.dev](https://tomryan.dev), release music as [A5omic](https://open.spotify.com/artist/7L3rQbwQVEGa71Ign85jyd), and publish consciousness research on [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Ryan%2C%20Tom%22).

**Contact:** [overboardapps@gmail.com](mailto:overboardapps@gmail.com) · [GitHub](https://github.com/Atomics-hub) · [HackerOne](https://hackerone.com/a5omic?type=user)
