# Archetype Identity Engine

Two interactive single-file demos exploring the 12 Jungian Brand Archetypes — now with a third tool for building animated ASCII characters.

## Files

### 1. `archetype-engine.html`
- Visual overview of the 12 archetypes
- Shows drives, fears, tone profiles, and reasoning styles
- Interactive **Archetype Blender** (mix up to 3 with weights)
- Live output simulator with identity-consistent responses

### 2. `jungian-archetype-sprites.html`
- Animated ASCII sprite viewer for the 12 archetypes
- Real-time customization: eyes, hats, animation speed, shiny mode
- Rarity tiers, stats (Debugging, Patience, Chaos, Wisdom, Snark)
- Filter by rarity + live frame animation

### 3. `ASCII-character-builder.html`
- Comprehensive animated ASCII character foundry using the clean **base** sprite
- 20+ individual animations (Idle, Death/KO, Hit/Flinch, Jump, Level Up, Climb, Swim, etc.)
- All animations play independently and simultaneously
- Eye style selector
- One-click **Copy** button on every animation that outputs ready-to-use JavaScript frame arrays
- Optimized rendering (grid created once, only text content updates)

## Tech

- Pure HTML + CSS + JavaScript (no build step)
- Retro terminal / cyberpunk aesthetic
- Fully self-contained and open-source ready

All three files demonstrate archetypes as **executable behavioral models** and visual systems:

**Output = Archetype(Input, Context, Constraints)**

The `ASCII-character-builder.html` specifically serves as a production tool for creating consistent, personality-driven ASCII animations for games or interactive experiences.

---

Made for exploring Jungian brand psychology and building expressive ASCII characters in a fun, interactive way.