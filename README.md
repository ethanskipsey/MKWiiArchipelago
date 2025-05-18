## 🗓️ Development Timeline & To Do List

### ✅ Phase 1: Foundation (Weeks 1–3)

**Goal: Build core functionality and test ISO patching pipeline.**

* [x] Set up GitHub repository and development environment
* [ ] Extract Mario Kart Wii ISO and identify editable assets (course files, item tables, character data, etc.)
* [ ] Implement CLI script for basic ISO randomisation

  * [ ] Track randomiser (starting cups, progressive cups, random races)
  * [ ] Character & vehicle randomiser
* [ ] Implement seed generation and logging
* [ ] Automate ISO repacking using Wiimms SZS Tools
* [ ] Add test mode for Dolphin Emulator support

### ⏳ Phase 2: Game Logic Randomisation (Weeks 4–6)

**Goal: Add logic-based progression, locking, and custom rules.**

* [ ] Implement progressive cup unlocking (Yes/No)
* [ ] Add "Lock Mechanics" and "Mechanics Unlock" logic
* [ ] Lock item boxes based on rules (Placement / Tracks / Specific Items)
* [ ] Develop basic flags configuration system (user-defined ruleset)

### ⏳ Phase 3: Sanity Checks & Win Conditions (Weeks 7–9)

**Goal: Create a more integrated and replayable challenge structure.**

* [ ] Implement Time Trial Checks (Off / Easy / Hard)
* [ ] Implement Placementsanity modes

  * [ ] 1st Place, Top 3, Full (On)
* [ ] Implement Starsanity logic (Star rewards as checks)
* [ ] Add support for various mod goals:

  * [ ] Clear 150cc
  * [ ] Clear Mirror Mode
  * [ ] Clear All Grand Prix
* [ ] Build in compatibility for Riivolution patch output

### ⏳ Phase 4: Traps & Chaos (Weeks 10–11)

**Goal: Add challenge elements and chaotic mechanics.**

* [ ] Implement Trap System

  * [ ] Blue Shell
  * [ ] Shock
  * [ ] Thunder Cloud
  * [ ] Blooper
  * [ ] POW Block
* [ ] Add toggle options for trap inclusion

### ⏳ Phase 5: Deathlink & Archipelago Prep (Weeks 12–14)

**Goal: Enable multi-game integration via Archipelago.**

* [ ] Implement **Deathlink support**:

  * [ ] Detect going OoB → trigger Deathlink to others
  * [ ] Receive Deathlink → trigger Lakitu respawn
* [ ] Create JSON bridge layer for Archipelago communication
* [ ] Build Archipelago item/location pool:

  * [ ] Characters, vehicles, stars, placements, item boxes, TT checks
* [ ] Write Archipelago YAML logic and script integration
* [ ] Register game as unofficial AP forked module

### ⏳ Phase 6: Polish & Release (Weeks 15–16)

**Goal: Finalise the mod and open it to testers.**

* [ ] Create UI or web-based settings randomiser frontend
* [ ] Clean up file structure, document architecture
* [ ] Write user manual and GitHub README
* [ ] Final testing on hardware and emulator
* [ ] Release v1.0 build with Archipelago support (optional module)

---

## 📦 Stretch Goals / Future Features

* [ ] **Item Boxsanity**

  * [ ] Every Item Set
  * [ ] Every Individual Box
* [ ] **Per-Track Music Randomisation**
* [ ] **Save-compatible unlock progression**
* [ ] **Multiplayer support**
* [ ] **Achievements / bonus goals**
* [ ] **Random HUD/UI elements**
