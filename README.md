# BLOBSVILLE

A slingshot chain-reaction rescue game, built on an original immediate-mode engine in Unity 6.

Pull back the sling, arc a Blob into a cluster, and watch one pop cascade across the
whole chain — spring the trapped Blobs before the Murklings close in. Angry-Birds aim
meets Cut-the-Rope contraptions, with a chain reaction as the payoff.

## The game

- **An overworld of named regions** — Bubble Bay, Contraption Coast, Frothpeak Heights
  and Emberhold Keep, each introducing its own mechanic, with a three-star skill
  objective on every level.
- **Chain-reaction, with a twist** — a detonation drops an expanding cloud; every Blob it
  reaches blooms and spreads its own, so a single well-aimed shot ripples across a spaced
  chain. The twist is the slingshot: you choose where the wave begins.
- **A physics toybox** — see-saws, springs, dominoes, ropes, pendulums, lava and armored
  guards drive multi-stage contraption puzzles on a deterministic pure-C# simulation.
- **Original art and engine** — every Blob, bubble, particle and UI surface is drawn by our
  own immediate-mode renderer. No third-party game assets; no reskin.
- **The Arena** — same-seed deterministic 1v1 VERSUS over the Oddsockets realtime SDK, a
  trophy ladder on the slingshot-physics base.

## Download

| Platform | |
| --- | --- |
| iOS | see [Releases](../../releases/latest) |

### First launch
- **iOS** — a development build: trust the developer profile under
  **Settings → General → VPN & Device Management**, then launch.

## Technology

Unity 6 · a bespoke immediate-mode renderer · a deterministic pure-C# physics simulation ·
the Oddsockets realtime SDK (pub/sub, presence, state channels) · a load-guarded
build-and-install pipeline.

---

Copyright © 2026 Tyga.Cloud Ltd. All rights reserved. BLOBSVILLE™ and the BLOBSVILLE
logo are trade marks of Tyga.Cloud Ltd. Blobsville, its regions, characters, art, music,
and code are original works protected automatically under the Berne Convention; no
licence, express or implied, is granted by the publication of this repository or of any
release attached to it. See [COPYRIGHT](COPYRIGHT).
