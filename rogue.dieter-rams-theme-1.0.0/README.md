# weniger, aber besser — a Dieter Rams VS Code theme

> "less, but better." — Dieter Rams

two color themes for Visual Studio Code inspired by the design philosophy and product palette of **Dieter Rams** for Braun and Vitsœ.

---

## themes

### ☀️ Light — "Snow White's Coffin"
named after the SK-4 record player's famous nickname. warm whites, restrained olive greens, Braun orange accents, and the quiet confidence of brushed aluminum. the editor should feel like a well-designed tool — present when you need it, invisible when you don't.

### 🌙 Dark — "RT 20"
named after the iconic RT 20 table radio. deep warm charcoals, sand-toned keywords, and the same deliberate use of color that Rams championed — every hue earns its place.

---

## design philosophy

this theme follows Rams' ten principles of good design:

- **good design is as little design as possible.** color is used sparingly and deliberately.
- **good design makes a product useful.** syntax colors serve readability, not decoration.
- **good design is unobtrusive.** the UI chrome recedes. your code is the product.
- **good design is honest.** no gradients, no glow, no unnecessary effects.

### color mapping

| role | light | dark | inspiration |
|---|---|---|---|
| background | warm white `#F5F2ED` | deep charcoal `#1E1B18` | SK-4 surface / RT 20 enclosure |
| keywords | warm brown `#5F503E` | sand `#C09C6F` | Braun dial markings |
| strings | olive green `#5F6B2D` | lifted olive `#A4B060` | ET calculator keys |
| constants | amber `#BF7C2A` | Braun orange `#ED8008` | the "=" button |
| types | slate blue `#5A6D7A` | cool aluminum `#AAB7BF` | brushed metal panels |
| tags (HTML) | leather brown `#736356` | warm taupe `#C09C6F` | Braun cases |
| attributes | olive gold `#84764B` | sage `#B7B183` | Vitsœ upholstery |
| comments | muted `#9C9488` | recessed `#5F5549` | back-panel labels |
| accent | Braun orange `#ED8008` | Braun orange `#ED8008` | universal |

---

## installation

### from VSIX (local install)

1. copy the `rogue.dieter-rams-theme-1.0.0` folder to your VS Code extensions directory:
   - **macOS**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **Linux**: `~/.vscode/extensions/`

2. restart VS Code

3. open the command palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)

4. type **"Color Theme"** and select:
   - `Dieter Rams — Light (Snow White's Coffin)`
   - `Dieter Rams — Dark (RT 20)`

### recommended font pairing

for the full Rams experience, pair with a clean, geometric monospace font:
- **JetBrains Mono** (closest to the precision of Braun's type)
- **IBM Plex Mono** (Rams would respect the system)
- **Input Mono** (customizable, functional)

### recommended settings

```json
{
  "editor.fontFamily": "'JetBrains Mono', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,
  "editor.letterSpacing": 0.3,
  "editor.renderWhitespace": "boundary",
  "editor.minimap.enabled": false,
  "editor.bracketPairColorization.enabled": false,
  "breadcrumbs.enabled": true,
  "editor.guides.bracketPairs": false
}
```

*bracket colorization is disabled in the recommended settings because Rams would never.*

---

## palette reference

colors sourced from Chad Ashley's documentation of Rams' product colors for Braun, the Rams Foundation archive, and direct product photography from the Braun collection.

---

## license

MIT
