# KrashPad

A writing and sight-word practice pad for young kids (pre-K to 3rd grade). One HTML file, works offline, no accounts, nothing leaves the device.

Open: https://mcrimaldi12.github.io/krashpad/

- `zone.html`: **Krash Zone**, the sight-word arcade: Krash Kart racing (Number Rally, Word Kart, Math Kart), Trace It (strict stroke-by-stroke tracing, plus a keyboard button to add a word for good), Draw a Buddy (OT drawing: head, oval body, stick arms and legs), Flash Cards, Match Up, Memory Garage, Fire Rescue, Police Chase, Wreck It, Dig & Dump, Turbo Race, Word Train, a crew of four original heroes, plus a detonator reward and a garage of vehicles to collect. Word list and progress are in the grown-ups panel (press and hold the gear for 2 seconds).
- `index.html`: the writing pad. Free writing is here; its tracing buttons open Trace It in Krash Zone.
- `letters.html`: the old letter tracer.
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png`: let it be added to a tablet's home screen as an app that opens full screen and works offline.

Progress (bolts, garage, word scores, buddies) saves on the device the moment it changes, in two places (localStorage and IndexedDB). The grown-ups panel can copy a backup code and restore from it.
