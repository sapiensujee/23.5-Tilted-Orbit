# 23.5° Tilted Orbit 🌏✨

> *A soft pastel VS Code theme inspired by the Thai GL show **23.5** (23.5 องศาที่โลกเอียง) — school-romcom warmth, sunlight, Earth tones, and cosmic blue.*

Just as Earth's 23.5° axial tilt gives us our seasons, this theme tilts your editor into a softer, warmer orbit — where night-blue skies meet sunlight gold, garden greens meet romantic pinks, and lavender space meets sky-blue clarity.

---

## 🎨 Color Palette

| Role               | Color     | Swatch | Meaning                          |
|---------------------|-----------|--------|----------------------------------|
| Editor background   | `#101722` | 🟦     | Soft night-blue, not harsh black |
| Sidebar background  | `#151E2B` | 🟦     | Muted school-uniform blue        |
| Foreground          | `#DDE7F0` | ⬜     | Chalky off-white                 |
| Comments            | `#7F9AA8` | 🩶     | Faded chalk / shy inner thoughts |
| Keywords            | `#FFB86B` | 🟧     | Sun warmth                       |
| Strings             | `#A7E8BD` | 🟩     | Earth / garden green             |
| Functions           | `#8FD3FF` | 🩵     | Clear sky blue                   |
| Variables           | `#F7D6E0` | 🩷     | Soft romantic pink               |
| Classes / Types     | `#CDB4FF` | 🟪     | Luna / space lavender            |
| Constants           | `#FFE66D` | 🟨     | Sunlight                         |
| Properties          | `#9BE7FF` | 🩵     | Cyan shimmer                     |
| Tags (HTML/JSX)     | `#FF9FB2` | 🩷     | Warm blush                       |
| Errors              | `#FF7A90` | 🔴     | Romcom panic moment              |
| Cursor              | `#FFE66D` | 🟨     | Little Sun beam                  |

---

## ✨ Features

### 🎨 Comprehensive UI Theming
Every corner of VS Code is styled — not just the editor, but the entire workspace:

- **Editor** — background, line highlight, selection, word highlight, find match, fold regions
- **Sidebar & Activity Bar** — backgrounds, badges, section headers
- **Tabs** — active/inactive states, hover effects, top border accent
- **Status Bar** — normal, debugging, no-folder, and remote states
- **Terminal** — full 16-color ANSI palette (normal + bright variants)
- **Breadcrumbs** — navigation trail with themed focus/active colors
- **Minimap** — find matches, selection, error/warning highlights
- **Peek View** — border, background, match highlights
- **Diff Editor** — inserted/removed text and line backgrounds
- **Merge Conflicts** — current/incoming header and content colors
- **Debug Toolbar** — breakpoints, start, pause, stop, step icons
- **Git Decorations** — added, modified, deleted, renamed, untracked files
- **Scrollbar** — subtle sky-blue slider with hover/active states
- **Settings, Notifications, Welcome Page** — all themed consistently

### 🖋️ Rich Syntax Highlighting
Token colors for all major language scopes:

- **JavaScript / TypeScript** — keywords, functions, variables, classes, template literals, decorators
- **HTML / JSX** — tags, attributes, embedded expressions
- **CSS** — property names, values, selectors, pseudo-classes, units
- **JSON** — keys with distinct coloring
- **Markdown** — headings, bold, italic, inline code, links
- **Python, Rust, Go** — full scope coverage via universal token scopes
- **Regex** — distinct warm blush coloring

### 🧠 Semantic Highlighting
Modern LSP-aware token coloring for precise syntax differentiation:

- Class/interface **declarations** get bold styling
- **Parameters** and **interfaces** are italicized
- **Readonly** variables and properties map to sunlight gold `#FFE66D`
- **Decorators** use warm italic styling
- Distinct colors for `enum`, `struct`, `namespace`, `typeParameter`

### 🌈 Bracket Pair Colorization
Six themed bracket colors using the full palette:

1. `#FFB86B` — Sun warmth (orange)
2. `#CDB4FF` — Space lavender
3. `#A7E8BD` — Garden green
4. `#8FD3FF` — Sky blue
5. `#F7D6E0` — Romantic pink
6. `#FFE66D` — Sunlight gold

---

## 🌟 Bonus: Starfield & Celestial Doodles

This theme includes an **optional** starfield background and floating celestial doodles that bring the cosmic romance of 23.5 right into your editor.

### What's Included

| Element | Description |
|---------|-------------|
| ⭐ **Starfield** | ~35 scattered stars using CSS radial gradients in gold, sky-blue, lavender, pink, and chalk colors — with varying sizes and soft glow halos |
| ✨ **Twinkle Animation** | 10 select stars gently pulse with a 4-second twinkle cycle |
| 🌌 **Constellations** | The Big Dipper and Cassiopeia drawn with dashed lines in the top-left area |
| 💖 **Sparkling Hearts** | 6 scattered hearts (🩷 and 💚) with staggered sparkle animations across the editor |
| 🌞 **Sun Doodle** | Floating in the center-right of the editor |
| 🌍 **Earth Doodle** | Floating near the Sun, offset slightly |
| 🌙 **Moon Doodle** | Bottom-right corner with lavender glow |
| 🛸 **UFO Doodle** | Bottom-right corner, floating near the Moon |
| 🌈 **Rainbow Doodle** | Top-right area with a bouncy "peek-a-boo" bloom animation |

Each celestial doodle is rendered beautifully at `50px` and has its own unique **floating/blooming animation** with different timing for a natural, dreamy feel.

### Setup (Optional)

The starfield and doodles require the **Custom CSS and JS Loader** extension:

1. **Install the extension:**
   ```bash
   code --install-extension be5invis.vscode-custom-css
   ```

2. **Add to your `settings.json`** (`Ctrl+Shift+P` → "Preferences: Open User Settings (JSON)"):
   ```json
   "vscode_custom_css.imports": [
     "file:///c:/path/to/extension/stars.css"
   ]
   ```
   > Replace the path with the actual path to your `stars.css` file.

3. **Enable Custom CSS:**
   `Ctrl+Shift+P` → **"Enable Custom CSS and JS"**

4. **Restart VS Code** when prompted.

> ⚠️ **Note:** VS Code will show a "Your Code installation appears to be corrupt" warning. This is **normal and harmless** — the Custom CSS loader modifies VS Code's internal files to inject the styling. Click the ⚙️ gear icon → **"Don't Show Again"** to dismiss it.

### Disabling the Starfield

To remove the starfield and doodles:
1. `Ctrl+Shift+P` → **"Disable Custom CSS and JS"**
2. Restart VS Code

---

## 🚀 Installation

### From Source (Development)

1. Clone or copy this repository into your VS Code extensions folder:
   ```bash
   # Windows
   xcopy /E /I <source-path> %USERPROFILE%\.vscode\extensions\tilted-orbit

   # macOS / Linux
   cp -r <source-path> ~/.vscode/extensions/tilted-orbit
   ```

2. Restart VS Code.

3. Open **Settings** → **Color Theme** (`Ctrl+K Ctrl+T`) → Select **23.5° Tilted Orbit**.

### From VSIX

1. Package the extension:
   ```bash
   npx @vscode/vsce package
   ```

2. Install the `.vsix` file:
   ```bash
   code --install-extension tilted-orbit-0.1.0.vsix
   ```

### Development / Testing

1. Open the extension folder in VS Code.
2. Press **F5** to launch the Extension Development Host.
3. In the new window, `Ctrl+K Ctrl+T` → Select **23.5° Tilted Orbit**.

---

## 📁 Extension Structure

```
tilted-orbit/
├── .vscode/
│   └── launch.json          # Extension dev host launch config
├── themes/
│   └── tilted-orbit-color-theme.json  # The theme definition
├── stars.css                 # Optional starfield & doodles
├── icon.png                  # Extension icon
├── package.json              # Extension manifest
├── README.md                 # This file
├── CHANGELOG.md              # Version history
├── LICENSE                   # MIT license
├── .gitignore
└── .vscodeignore
```

---

## 💜 Inspired By

**23.5** (23.5 องศาที่โลกเอียง) — the Thai GL series about Sun and Ongsa, where a 23.5° tilt of the Earth brings two people together. This theme captures the warmth, softness, and cosmic wonder of that story.

| Theme Element | Show Connection |
|---------------|-----------------|
| Night-blue background | Evening scenes, stargazing |
| Sunlight gold keywords | Sun (ซัน) — warmth and brightness |
| Garden green strings | Earth tones, school gardens |
| Sky-blue functions | Clear skies, new beginnings |
| Romantic pink variables | Soft feelings, growing affection |
| Space lavender types | Luna, cosmic wonder, astronomy club |
| Chalk-grey comments | Shy inner thoughts, unsaid words |
| Panic-red errors | Romcom panic moments 💕 |

---

## 📝 License

MIT
