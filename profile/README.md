<p align="center">
  <img src="https://raw.githubusercontent.com/AutomationForgeHQ/automation-forge/main/docs/icon-256.png" width="96" alt="" />
</p>

<h1 align="center">Automation Forge</h1>

<p align="center"><b>Playable Ops for Unreal Engine 5.8.</b><br />
Motion, voice, faces, meshes and staging — generated in the editor, reviewed, placed on the right target, and traceable back to what made them.</p>

<p align="center">
  <a href="https://kovati.dev">Site</a> ·
  <a href="https://kovati.dev/download">Download the hub</a> ·
  <a href="https://app.kovati.dev">Account</a> ·
  <a href="https://github.com/AutomationForgeHQ/automation-forge/tree/main/docs">Documentation</a> ·
  <a href="https://kovati.dev/whitepaper">Whitepaper</a> ·
  <a href="https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/MANIFESTO.md">Manifesto</a> ·
  <a href="https://github.com/AutomationForgeHQ/releases/releases">Releases</a>
</p>

---

## What this is

AI made a candidate cheap — an animation, a voice take, a face solve, a
mesh, in minutes. It didn't make that candidate part of a game: the result
still has to fit a character, respect timing, carry gameplay events,
survive review, and stay replaceable when the real work arrives.

**Automation Forge** is a family of Unreal Engine plugins built for exactly
that gap. We call the discipline **Playable Ops**: turning creative intent
into content that's playable, reviewable, traceable and replaceable — by a
person, or by an agent working the same rules.

> The game you cannot playtest is the game you never make.

Read the short version in [docs/PLAYABLE-OPS.md](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/PLAYABLE-OPS.md), the values version in the [manifesto](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/MANIFESTO.md), or the long argument in the [whitepaper](https://kovati.dev/whitepaper).

## Who's behind it

**Kovati** is the product brand. **MetaWorx LLC** founded Kovati and holds
its IP; **Blackcode SA** (Switzerland) backs it and currently runs the
infrastructure the account and the plugins' cloud services sit on.
Automation Forge is developed and dogfooded inside **Colony Origins**, a
real Unreal Engine production — the whitepaper exists because the people
making these tools still have to make the same game the tools are meant to
unblock.

## Open, Fab and paid

Every plugin is one of three things, decided per plugin — never per project:

| | Source | Cost | Where |
|---|---|---|---|
| **Open** | Public, in this organisation | Free | Here, and packaged on Fab |
| **Fab** | Stays private | Free | Fab, and the account app |
| **Paid** | Stays private | Paid | The account app, and Fab where listed |

**Free on your own hardware. Open where it counts.** The rule: if it runs on
your machine and costs us nothing to operate, it stays open and useful on
its own. Paid value begins only where we operate something on your behalf —
see [docs/DISTRIBUTION.md](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/DISTRIBUTION.md) for why every plugin landed where it did, and every plugin's link.

Whichever tier, nothing installs without an account first — a free plugin
is added with one click, a paid one bought once. See
[docs/ACCOUNTS.md](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/ACCOUNTS.md).

## The Forge sets

| Set | Goal | Status |
|---|---|---|
| [AutomationForge](https://github.com/AutomationForgeHQ/automation-forge) | The ledger, graduation rule and pipeline executor everything else plugs into; the in-editor Hub menu | Working |
| [MotionForge](https://github.com/AutomationForgeHQ/MotionForge) | Text or a posed performance → an `AnimSequence` on your own skeleton, local, rented or hosted | Working (beta) |
| [SpeechForge](https://github.com/AutomationForgeHQ/SpeechForge) | A written line → a timed `SoundWave`, cast, localized and dubbed, on your own provider account | Working (beta) |
| [FaceForge](https://github.com/AutomationForgeHQ/FaceForge) | Spoken audio → facial animation, solved locally or on NVIDIA Audio2Face, retargeted to your rig | Working |
| [MontageForge](https://github.com/AutomationForgeHQ/MontageForge) | An animation sequence → a gameplay-ready montage, built from a recipe | Working |
| [MeshForge](https://github.com/AutomationForgeHQ/MeshForge) | A prompt or reference image → a game-ready static mesh, dressed with a fitted garment | Working (beta) |
| [SurfaceForge](https://github.com/AutomationForgeHQ/SurfaceForge) | A prompt or reference image → PBR material candidates and Unreal material assets | New / developer preview |
| [PerformanceForge](https://github.com/AutomationForgeHQ/PerformanceForgeToolset) | A mic/webcam performance stage, end to end to a baked character take | Paid — flagship path |
| [Tools](https://github.com/AutomationForgeHQ/MeshWeightRemapToolset) | Leader-pose weight remapping across a whole folder of garments | Working |

Goals, current features and honest status for each, in more depth:
[docs/PLUGINS.md](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/PLUGINS.md).

## Repositories

- [`automation-forge`](https://github.com/AutomationForgeHQ/automation-forge) — the hub, the `forge` command line, the release manifest, and this documentation. Start here.
- [`releases`](https://github.com/AutomationForgeHQ/releases) — every plugin build, per engine version, with checksums.
- Every open plugin's source, one repository each — indexed by set in [docs/DISTRIBUTION.md](https://github.com/AutomationForgeHQ/automation-forge/blob/main/docs/DISTRIBUTION.md), or just browse this organisation's repositories directly.

## Also from Kovati

[`kovati-companion`](https://github.com/AutomationForgeHQ/kovati-companion) is the recording app for **Kovati Studio**, a separate video-production workspace. It isn't part of Automation Forge — it lives in this organisation because Kovati ships it too.

---

Unreal Engine is a trademark of Epic Games, Inc.; Automation Forge is an independent product and is not endorsed by Epic Games, Inc.

Questions: [bojan@blackcode.ch](mailto:bojan@blackcode.ch)
