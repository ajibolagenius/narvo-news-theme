# Narvo News Theme for VS Code

A Swiss-brutalist VS Code theme derived from the **Narvo News** design system — Africa's audio-first news platform. Sharp edges, mono-UI typography, and three distinctive palettes.

![Narvo Theme Preview](images/preview.png)

## Three Variants

### Narvo Nature (default)
Deep matte forest (`#1B211A`) with sand/beige accents (`#EBD5AB`) and sage green syntax. The signature Narvo experience — like coding in a moonlit forest.

### Narvo Sun
Warm parchment background (`#FCF6F0`) with deep green accents (`#166534`). Clean, readable, and distinctly editorial — like a Swiss-designed broadsheet.

### Narvo Moon
Deep navy void (`#0B0C14`) with soft purple accents (`#9B8DFF`). Vite-inspired, electric, and perfect for late-night deep work.

---

## Design System Origin

Every color maps directly to the Narvo Design System's semantic tokens:

| Role | Nature | Sun | Moon |
|------|--------|-----|------|
| **Background** | `#1B211A` Forest | `#FCF6F0` Parchment | `#0B0C14` Navy |
| **Surface** | `#242B23` | `#F5F0E8` | `#1A1D2E` |
| **Border** | `#628141` Forest Green | `#646260` Warm Gray | `#2A2D3A` Slate |
| **Accent** | `#EBD5AB` Sand | `#166534` Green-800 | `#9B8DFF` Purple |
| **Keywords** | Sand `#EBD5AB` | Green `#166534` | Purple `#9B8DFF` |
| **Functions** | Sage `#8BAE66` | Blue `#1E64B4` | Blue `#93C5FD` |
| **Strings** | Health `#4ADE80` | Green `#15803D` | Green `#4ADE80` |
| **Types** | Tech `#D8B4FE` | Purple `#7E3EBE` | Purple `#D8B4FE` |
| **Numbers** | Science `#5EEAD4` | Teal `#0D8A78` | Teal `#5EEAD4` |
| **Constants** | Lime `#D4FF00` | Amber `#B45309` | Indigo `#646CFF` |
| **Tags** | Urgent `#FCA5A5` | Red `#C81E1E` | Red `#FCA5A5` |
| **Params** | Politics `#FDBA74` | Amber `#B45309` | Amber `#FDBA74` |

Category colors from the design system (finance, environ, tech, urgent, politics, science, culture, sports, health, security) are woven into syntax highlighting for a uniquely editorial feel.

---

## Design Philosophy

The Narvo Design System follows **Swiss design principles**: sharp edges (`border-radius: 0`), mono-UI typography, 8pt spacing grid, and deliberate structural borders. This theme carries those principles into VS Code — you'll notice crisp tab borders, decisive accent colors, and zero-radius visual language throughout.

---

## Installation

1. Open **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for `Narvo News Theme`
3. Click **Install**
4. `Ctrl+Shift+P` → `Preferences: Color Theme` → Select **Narvo Nature**, **Narvo Sun**, or **Narvo Moon**

---

## Recommended Settings

Match the Narvo stack with Space Grotesk + JetBrains Mono:

```json
{
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 13,
  "editor.lineHeight": 1.6,
  "editor.letterSpacing": 0.3,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.renderLineHighlight": "gutter",
  "workbench.colorTheme": "Narvo Nature"
}
```

---

## License

MIT — See [LICENSE](LICENSE)

---

<p align="center">
  <em>Built for <a href="https://github.com/ajibolagenius/narvo_news">Narvo News</a> — The Local Pulse, Refined.</em>
</p>
