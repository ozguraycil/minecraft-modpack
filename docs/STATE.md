# 🎮 MINECRAFT MODPACK - CURRENT STATE

**Last Updated:** 2026-02-04  
**Total Mods:** 19 installed, 281+ remaining (300+ target)  
**Status:** ✅ Core mods tested, 🔄 Planning progression system

---

## 📊 QUICK FACTS

- **Project:** Custom 1.20.1 Forge modpack (Kitchen Sink)
- **Platform:** MacBook Air M4, 16GB RAM
- **Minecraft:** 1.20.1
- **Forge:** 47.4.10 (Recommended)
- **Instance:** Test-1.20.1 (Prism Launcher)
- **Performance:** Excellent (~100-150 FPS)
- **GitHub:** https://github.com/ozguraycil/minecraft-modpack

---

## ✅ COMPLETED PHASES

### Phase 0: Development Environment ✅
- [x] Homebrew 5.0.13 installed
- [x] Java 17 (Zulu) installed  
- [x] Prism Launcher installed
- [x] Git/GitHub Desktop configured
- [x] Repository structure created

### Phase 1: Core Mods (19 mods) ✅
**Library Mods (13):**
- JEI, Architectury, Cloth Config, Balm, Curios
- Bookshelf, GeckoLib, Patchouli, Moonlight Lib
- Placebo, Puzzles Lib, Kotlin for Forge, Mantle

**Performance Mods (6):**
- Embeddium, Oculus, FerriteCore
- ModernFix, Entity Culling, ImmediatelyFast

**Status:** All tested, working perfectly!

---

## 🔄 CURRENT PHASE: Planning Progression

### Decision Needed:
**Main Progression System:**
- Option A: Apotheosis (World Tiers + Affixes)
- Option B: Pufferfish's Skills (Skill Trees)
- Option C: Both (Hybrid)

**Mob Scaling:**
- Option A: Scaling Health
- Option B: None (rely on progression mods)

**Storage System:**
- Option A: Applied Energistics 2 (complex)
- Option B: Refined Storage (simple)
- Option C: Defer to later

---

## 📁 KEY FILES & PATHS

**Repository:** ~/Documents/GitHub/minecraft-modpack  
**Prism Instance:** ~/Library/Application Support/PrismLauncher/instances/Test-1.20.1/  
**Mods Folder:** ~/Library/.../Test-1.20.1/.minecraft/mods/

**Documentation:**
- `/docs/core-mods-v1.md` - Complete list of 19 mods
- `/docs/STATE.md` - This file
- `/docs/HANDOFF.md` - Last session summary
- `/docs/sessions/` - Detailed session logs

---

## 🎯 NEXT STEPS

1. **Decide on progression system** (Apotheosis vs Skills vs Hybrid)
2. **Install progression mods** (6-10 mods)
3. **Test progression system** (create world, play 1-2 hours)
4. **Add tech mods** (Phase 3: ~15-20 mods)
5. **Add world gen** (Phase 4: ~10 mods)

**Target Milestone:** 50 mods by end of week

---

## ⚠️ IMPORTANT NOTES

- AutoRegLib excluded (not available for 1.20.1)
- Entity Culling from Modrinth (not on CurseForge)
- Embeddium + Oculus working together
- No shaders planned
- Tinkers' Construct 1.20.1 still in beta (usable but evolving)

---

## 🔧 TECHNICAL DECISIONS

- **Mod Loader:** Forge (not NeoForge) - maximum compatibility
- **Recipe Viewer:** JEI (not REI/EMI) - best mod integration
- **Performance:** Embeddium stack (not OptiFine)
- **Java:** 17 (not 23) - required for Forge 47.x

---

## 📞 FOR NEW CONVERSATIONS

**Quick Start Command:**
```
Read STATE.md and HANDOFF.md to understand current project status.
Repository: ~/Documents/GitHub/minecraft-modpack
```

**Context Files:**
- STATE.md (this file) - current status
- HANDOFF.md - last session details
- core-mods-v1.md - installed mods list
- sessions/YYYY-MM-DD.md - session history
