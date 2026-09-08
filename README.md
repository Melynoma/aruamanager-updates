# AruaManager

A multi-client launcher and toolkit for AruaROSE Online — built for players who run several
game clients at once.

**[Download the latest version](https://github.com/Melynoma/aruamanager-updates/releases/latest)**

---

## What it does

- **Accounts & Parties** — store your logins, launch a whole party with one click, and place
  each client's window exactly where you want it on screen
- **Cleric Helper** — automates buff casting across your clients, with auto-recast, healing
  and follow, plus a floating overlay so you can control it without alt-tabbing
- **Loot Tracker** — records what you pick up and how much Zuly you earn, per session, with
  history so you can see what a night actually made
- **Storage Viewer** — read your storage contents outside the game
- **Timers** — live countdowns for Union Wars, instances, Monster Hunt, Sun God and the Oro
  drop schedule, with alerts before an event starts
- **Stat Calculator** — plan a build and see the resulting combat stats
- **Levelling Helper** — recommended stat spreads and levelling spots per class
- **Whisper alerts** — a sound and a pop-up when someone whispers you, telling you which of
  your characters received it

## Getting started

1. Download the zip from the [releases page](https://github.com/Melynoma/aruamanager-updates/releases/latest)
2. Extract it anywhere you like — no installer needed. Avoid `Program Files`, as Windows
   restricts writing there
3. Run `AruaManager.exe` and follow the first-launch setup

Some features need extra bits:

| Feature | Requirement |
|---|---|
| Loot Tracker, Storage Viewer, whisper alerts | [Npcap](https://npcap.com/#download), and running as Administrator |
| Cleric Helper | A licence key |

Everything else works without either.

## What's new

See **[CHANGELOG.md](CHANGELOG.md)** for the full history. AruaManager also checks for updates
on its own and shows you what changed — you can turn that off in Options.

## Support

Found a bug or want to suggest something?

- **Forum:** Melyn
- **Discord:** Melynade

---

## About this repository

This repo hosts AruaManager's downloads and update feed — the app reads `version.json` here to
know when a new version is out. It doesn't contain the application's source code.
