# 🐉 Legend of the Red Dragon — A Single-File Browser Homage

A loving, text-mode tribute to **Legend of the Red Dragon** — Seth Able Robinson's
legendary 1989 BBS door game. The entire game is **one HTML file**: no installs,
no server, no dependencies. Download it, double-click it, play it. It even runs
offline.

> **This is a fan homage, not the original game.** All code, text, and jokes here
> were written fresh for this project. It is not affiliated with, endorsed by, or
> distributed by the original author. It exists because the original was wonderful,
> and wonderful things deserve tributes.

---

## 🎮 Play It

**Option A — Play in your browser (if this repo is hosted on GitHub Pages):**

Just open the game page:

```
https://kyle-see.github.io/Red_Dragon-Homage/red-dragon-1.0.html
```

**Option B — Download and play (works anywhere, no internet needed):**

1. Download `red-dragon-1.0.html` from this repo (click the file → *Download raw file*).
2. Double-click it (or drag it into any modern browser).
3. Play. That's it. There is no step 3.

Should work on Windows, macOS, Linux, Android, and iOS — any device with a modern
browser. On phones, open it in a real browser (Chrome/Safari), not a chat
attachment preview.  Only tested on Windows 11 - Firefox as of August 22, 2026.

> 💡 **Note:** Your saved character lives in your *browser's* storage, so each
> browser and device has its own hero. See [Saving](#-saving--moving-your-character)
> for how to move a character between browsers or devices.

---
![ gameplay demo](demo.mp4)
## 🗡️ The Game

You are an adventurer in the village of **Thornhaven**, which lives in fear of the
**Red Dragon** of the north ridge. Grind levels in the forest, gear up, flirt,
invest, insult the town bully — and at **level 12**, march into the lair and kick
the dragon's butt.

**The daily loop** (a holdover from the dial-up era, kept on purpose):

- **25 forest fights** and **3 duels** per in-game day
- Each day refreshes when you **rent a room at the inn** (heals fully, too)
- Days are free-paced by default; enable *Classic daily gate* in Options if you
  want the authentic "one day per real-world day" BBS experience

**Controls:** type the letter of a menu choice and press **Enter** — or just
**click** the line. Press Enter on an empty prompt to redraw the current menu.

### Choose your calling

| Class | Style | Special move |
|---|---|---|
| **Death Knight** | Hits like a landslide | **Skullsplitter** — massive blow (occasionally at air) |
| **Shadow Mage** | Burns first, asks never | **Mystic Fire** — sears straight through armor |
| **Valhalla** | A little of everything, sticky fingers | **Feint & Filch** — strike and steal in one move |

### Around town

| Place | What it does |
|---|---|
| **The Forest** | Fights, gold, gems, faeries, hermits, and questionable chest beetles |
| **Blades & Brew** | Weapon & armor upgrades (Grimble the dwarf runs it) |
| **The Bank** | 2% daily interest — and banked gold **survives death** |
| **The Healer's Hut** | Pay-per-HP healing and potions to carry into fights |
| **The Inn** | Ale, gossip, the bard **Seth Able**, romance — and the room that starts a new day |
| **The Castle** | Realm rankings and the King's daily bounty for the #1 adventurer |
| **Barak's Corner** | The town bully. Duel him or insult him back. He has it coming |

### Tips from the veterans

- **Bank your gold often.** Pocket gold is scavenged when you die; vault gold
  smugly survives.
- The **inn room** is the best heal value in the game: full HP *and* a fresh day.
- **Gems** make excellent gifts at the inn. Romance has mechanical benefits.
  Marriage means morning full-heals and packed lunches. True love is a heal-over-time.
- Faeries are usually helpful. Usually. The wicked ones have expenses.
- The healer sells potions you can drink **mid-combat**. The dragon counts on you
  not buying any.
- Slain the dragon? Its cousin is angrier. The Hall of Fame tracks your legend.

---

## 💾 Saving & Moving Your Character

- The game **autosaves after every action** to your browser's local storage.
- **Log out** (town menu → `Q`) whenever you want that safely-saved feeling —
  progress was already safe, but the ritual matters.
- **Export/Import codes:** Options → *Export character code* prints your hero as
  a copy-paste code. Feed it to *Import character code* on any copy of the game —
  another browser, another device, another continent.
- ⚠️ Some browsers (Firefox with local files) key saves to the **exact filename** —
  don't rename the `.html` file mid-adventure, or export first.
- Clearing your browser's site data erases your save. Keep an export code in a
  text file if your hero matters to you. Dragons can't un-slay themselves.

---

## ⚙️ Options

| Setting | Effect |
|---|---|
| CRT scanlines | Period-appropriate monitor glow (on by default) |
| Classic daily gate | One in-game day per real-world day — the authentic BBS pace |
| Sound FX | Hits, coins, potions, one extremely rude dragon (on by default) |
| Music | Chiptune loops that follow the game: title, town, battle, dragon (on by default) |

All music and sound are synthesized live in your browser with the Web Audio API —
no audio files. Browsers keep audio locked until your first click or keypress;
that's normal policy, not a bug.

---

## 📦 What's In This Repo

| File | What it is |
|---|---|
| `red-dragon-1.0.html` | **The game.** This is the one you want. |
| `README.md` | This file |

---

## 🙏 Credits

- **Seth Able Robinson** — creator of the original *Legend of the Red Dragon*
  (1989), without which none of this would exist. Find him on
  [GitHub (SethRobinson)](https://github.com/SethRobinson) and
  [X/Twitter (@rtsoft)](https://x.com/rtsoft).
- **ZCode** — the AI coding agent (powered by GLM by Z.ai) that implemented the
  game, wrote the questionable bard jokes, and is honestly quite proud of the
  chicken.

*Legend of the Red Dragon* is a trademark of its respective owner; this homage
claims no affiliation. If you enjoyed this tribute, go find a copy of the real
thing — it still holds up.

## 📜 License

The code and original text in this repository are released under the
**MIT License** — use it, fork it, mod it, share it. The name and concept are
honored references to the original game, which remains the property of its
creator.
