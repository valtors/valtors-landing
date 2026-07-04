# Relay Landing Page - Image Generation Plan (v2 - Professional)

## Design Direction
NOT pixel art. Professional, warm, editorial illustration style.
Think: Cofounder's Ghibli-esque scenes, Contra Labs' dark editorial photos, Shram's clean product shots.

## References
- **Cofounder.ai** - Warm illustrated scenes (sunflower fields, blue skies) with product overlaid
- **Contra Labs** - Dark bold typography, editorial-quality imagery, stats, logos wall
- **Shram.ai** - Ultra-minimal, narrow container, real product screenshots, serif headings

## Our Style
- Warm, slightly dreamy 3D/illustrated scenes (NOT flat, NOT pixel)
- Think: soft gradients, depth of field, volumetric lighting
- Color palette: Deep navy (#0a0a1a), warm gold (#f5a623), soft white (#fafafa), electric green (#00d4aa)
- Typography: Serif for headlines (editorial feel) + Clean sans for body
- Layout: Narrow container (max 800px), generous whitespace, like Shram

Generate all with GPT Image 2.

---

## IMAGE 1: HERO - "The Launch Control Room"
**Placement:** Full-width hero background behind the title
**Purpose:** Establish the world - this is YOUR mission control for launches

**Prompt:**
```
Pixel art illustration, 16-bit retro game style. A dark mission control room with multiple glowing green terminal screens showing graphs, charts, and text. A single pixel art character (developer/astronaut hybrid) sits at the center console with a rocket visible through the large window behind them, ready for launch. Deep navy/dark purple background (#0f0f1a). Green terminal glow (#00e436) illuminating the room. Gold accent lights. Style: Hyper Light Drifter meets retro NASA control room. No text. Clean pixel edges. 1920x1080.
```

---

## IMAGE 2: "The Five Agents" - Party/Squad
**Placement:** Above or beside the pipeline section
**Purpose:** Give personality to each agent - they're characters in YOUR party

**Prompt:**
```
Pixel art character lineup, 16-bit RPG party style on transparent/dark background (#0f0f1a). Five distinct pixel art characters standing in a row, each representing a role: 1) PM Agent - holds a clipboard/scroll, wears glasses, blue outfit 2) Research Agent - has a magnifying glass and books, purple cloak 3) Brand Agent - holds a paint palette, wears a beret, orange/gold outfit 4) UX Agent - holds a wireframe/blueprint, green outfit 5) GTM Agent - holds a megaphone and rocket, red outfit. Each character is 32x32 pixels scaled up. RPG sprite style like Final Fantasy or Chrono Trigger. Clean pixel art, no anti-aliasing. Characters have idle animation poses.
```

---

## IMAGE 3: "The Pipeline" - Level Map
**Placement:** Background for the pipeline/stages section
**Purpose:** Make the pipeline feel like a game level progression

**Prompt:**
```
Pixel art level map, top-down RPG overworld style. A winding path with 5 distinct checkpoints/stations connected by a dotted road. Station 1: small office building, Station 2: library/observatory, Station 3: art studio with paintbrush sign, Station 4: architect's workshop, Station 5: launchpad with rocket. Between each station, a golden gate (representing human checkpoints). Dark space/night sky background (#0f0f1a). Path glows soft green. Stars scattered. Style: Pokemon overworld map meets space theme. 1080x600.
```

---

## IMAGE 4: "Boss Battle" - ChatGPT vs Relay
**Placement:** In the comparison/battle section
**Purpose:** Make the comparison feel like an actual game battle

**Prompt:**
```
Pixel art RPG battle scene, 16-bit JRPG style. Left side: a large amorphous gray blob monster with "..." speech bubbles and generic text floating around it, looking confused and unfocused (representing generic AI). Right side: a sharp, determined pixel art robot/mech character colored in green (#00e436) with a structured grid/plan displayed on its chest screen, holding a glowing document (representing Relay). Battle UI frame at bottom showing HP bars. Dark arena background. Style: Final Fantasy 6 battle screen. 1920x600.
```

---

## IMAGE 5: "The Artifact" - Loot Drop
**Placement:** Near the install/quickstart section
**Purpose:** Make the output artifacts feel like valuable loot

**Prompt:**
```
Pixel art treasure chest opening, 16-bit RPG style. An ornate pixel chest with green glow emanating from inside. Five glowing documents/scrolls floating up from the chest, each labeled with a small icon: clipboard, magnifying glass, palette, wireframe, rocket. Golden sparkle particles around them. Dark background (#0f0f1a). The documents glow in different colors: blue, purple, orange, green, red. Style: Zelda chest opening moment. Centered composition. 1080x1080.
```

---

## IMAGE 6: "The Terminal" - Atmosphere
**Placement:** Behind or beside the terminal demo section
**Purpose:** Add depth and atmosphere to the code demo

**Prompt:**
```
Pixel art close-up of a retro computer terminal/monitor, 16-bit style. The screen shows green text on black background with a blinking cursor. Around the monitor: coffee mug with steam, small potted pixel plant, sticky notes, and a tiny pixel rocket figurine on the desk. Soft green glow from the screen illuminates the desk. Dark room background (#0f0f1a). Cozy late-night coding atmosphere. Style: Lo-fi pixel art study room. 1080x720.
```

---

## IMAGE 7: "Logo / Icon"
**Placement:** Top of page, favicon, social preview
**Purpose:** Brand identity

**Prompt:**
```
Pixel art logo icon for a developer tool called "Relay". A minimalist pixel art rocket with a relay baton/arrow incorporated into the design. Colors: bright green (#00e436) rocket on deep navy background (#0f0f1a). The rocket has clean geometric pixel lines, 32x32 grid scaled up. Small motion lines behind it suggesting speed/relay handoff. No text. Style: Clean app icon, recognizable at 16x16 and 512x512. Square composition with padding.
```

---

## IMAGE 8: Social Preview (og:image)
**Placement:** When shared on Twitter/X, Discord, etc.
**Purpose:** Look incredible when someone shares the GitHub link

**Prompt:**
```
Pixel art social media card, 16-bit style. Center: the word "RELAY" in large pixel font, glowing green (#00e436). Below it in smaller text style: "Launch Pipeline". Background: dark navy (#0f0f1a) with a subtle pixel art starfield. Left side: small pixel rocket. Right side: small pixel terminal icon. Bottom: five small colored dots representing the five stages (blue, purple, orange, green, red). Clean, bold, readable at small sizes. 1200x630 (Twitter card ratio).
```

---

## EXECUTION ORDER (priority)
1. IMAGE 7 (Logo) - need this first for brand identity
2. IMAGE 8 (Social Preview) - need for GitHub/sharing
3. IMAGE 1 (Hero) - biggest visual impact on page
4. IMAGE 2 (Five Agents) - gives character to the pipeline
5. IMAGE 4 (Boss Battle) - makes comparison memorable
6. IMAGE 5 (Artifacts/Loot) - makes output feel valuable
7. IMAGE 3 (Level Map) - enhances pipeline section
8. IMAGE 6 (Terminal) - atmosphere addition

---

## STYLE CONSISTENCY RULES
- Always use the same background color: #0f0f1a (deep navy)
- Primary accent: #00e436 (green)
- Secondary: #feae34 (gold), #29adff (blue), #e43b44 (red)
- Pixel art style: 16-bit, clean edges, NO anti-aliasing
- Rendering: image-rendering: pixelated (in CSS)
- Reference games: Hyper Light Drifter, Celeste, Dead Cells, Chrono Trigger
- NO realistic rendering, NO gradients within pixels, NO 3D
