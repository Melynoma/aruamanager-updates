# What's New in AruaManager

Written for players — what changed and what it means for you, not how it was built.

> **Adding an entry?** Keep it plain. Say what you can now do, or what stopped going
> wrong. No file names, no class names, no packet opcodes. If a line only makes sense
> to someone who has read the code, rewrite it or leave it out.

---

## 3.2.13

**Fixed: Update downloads**
The download attached to each update now publishes reliably.

## 3.2.12

**Fixed: Downloads are now attached to each release**
Update notifications pointed at a releases page that had nothing on it, so there was no way to
actually get the new version. Builds now publish the download alongside the update notice.

## 3.2.11

**Fixed: Cleric levelling build was wrong**
The Levelling Helper's Cleric build said "INT until 300" — but the level cap is 228, and INT
can only reach 320 without gear, so that advice wasn't achievable. It now maps out the whole
route level by level: pure INT until it caps at 320 around level 147, then Charm to 150 by
163, then Dex to 320, finishing at INT 320, Dex 320, Charm 169 and Str 46 at level 228. Every
step has been checked against the stat points you actually have at that level.

**New: Charm shown in levelling builds**
Build recommendations can now include Charm, which the Cleric build needs. It appears in the
Levelling Helper alongside the other stats and can be edited in Edit Builds.

## 3.2.10

**New: Update checking**
AruaManager now tells you when a newer version is out. It checks quietly when the app starts
and shows you what changed, with a link to download it. There's also a **Check for Updates**
button and a **What's New** button in Options if you'd rather look yourself.

**New: Show or hide Cleric buttons on the combined overlay**
The Cleric tab's "Overlay shows" checkboxes now apply to the Custom tab's combined overlay as
well, so a button you've hidden stays hidden in both.

**Improved: Search boxes now say "Search"**
The search boxes on Accounts and Parties show a faint "Search" hint until you start typing.

## 3.2.9

**New: Backup & Restore**
Save everything AruaManager remembers — accounts, parties, Cleric keybinds, saved builds,
item names and all your settings — into a single file. Restore it after a reinstall or on
a new PC. Find it at the bottom of the Options tab.

**New: Whisper alerts**
Get a sound and a pop-up when someone whispers you, telling you which of your characters
received it. Useful when you're running several clients and most windows are hidden.
Turn it on in Options under Alerts. Needs Npcap and Administrator, same as the Loot Tracker.

**New: Event alerts**
The Timers tab can now warn you before an event starts, with two separate warning times —
say 15 minutes to wrap up what you're doing and 5 to be in position. Choose which events
you care about, pick the sound, and place the pop-up wherever suits you (or drag it there).

**New: Search on Accounts and Parties**
A search box at the top right of both tabs. Searching finds accounts by character name and
by your own notes, so "which account is my cleric on?" is now one search.

**New: Close All Clients**
One button on the Parties tab closes every running game client. Each one is asked to close
properly so the game logs out cleanly.

**New: Character notes**
Every character now has a note field — "needs weapon upgrade", "bank mule", whatever helps.

**New: Session history**
The Loot tab now has a History button listing your past sessions with the items and Zuly
earned in each, so you can see what a night actually made.

**New: Follow Leader button**
Added to the Cleric overlays. Re-targets the leader and presses your Follow key, for when
the cleric gets knocked off following.

**Fixed: Buff timer counted from the wrong point**
The buff countdown measured from the last buff cast instead of the first. Since each buff
starts expiring the moment it lands, the timer ran a few seconds long and auto-recast fired
late, leaving buffs briefly dropped. It now counts from the first buff.

**Fixed: Buffs missing a character after using Tile**
Tiling client windows resized them, which quietly invalidated the party-panel positions
saved by Scan Party. Casting then clicked the wrong spot. The app now spots this, re-scans
automatically, and marks any client that still needs re-scanning.

**Fixed: Settings forgotten on restart**
If AruaManager was installed somewhere Windows protects — Program Files, for example — it
couldn't save your Options settings and said nothing about it, so they reset every launch.
It now saves elsewhere automatically, and tells you if a save ever fails.

**Improved: Timers tab**
Events are now laid out as a table showing when each one starts, with anything imminent
highlighted. Added filters for Monster Hunts and Sun God, and the Oro drop lists are now
properly aligned and easier to read.

**Improved: Options tab**
Split into clearly separated sections, and every tab now shares the same background.

**Improved: Importing accounts**
The import prompt no longer makes Classic the easy accidental choice, warns that Classic and
Arua keep separate lists, and highlights whichever server you've set as your default.
