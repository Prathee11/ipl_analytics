# Design System

## Philosophy

The IPL Analytics Dashboard uses a **cinematic dark theme** inspired by broadcast sports graphics — deep navy backgrounds, IPL orange and gold accents, with neon highlights for data emphasis.

---

## Color Palette

```css
:root {
  /* Backgrounds */
  --navy-deep:   #060f2a;   /* Page background */
  --navy-mid:    #0d1e45;   /* Section backgrounds */
  --navy-card:   #111f4a;   /* Card backgrounds */
  --navy-hover:  #162455;   /* Hover state */

  /* Brand Accents */
  --orange:      #ff6b35;   /* Primary accent — IPL orange */
  --gold:        #ffd700;   /* Secondary accent — trophy gold */
  --cyan:        #00d9ff;   /* Data highlight — cool */
  --green:       #00ff88;   /* Positive metric / growth */
  --red:         #ff3366;   /* Alert / negative metric */

  /* Typography */
  --text-bright: #f0f4ff;   /* Headings, important values */
  --text-mid:    #c8d4ee;   /* Body text, descriptions */
  --text-muted:  #7a90bb;   /* Labels, metadata */

  /* Borders */
  --border:      rgba(255,107,53,0.22);   /* Standard border */
  --border-light: rgba(255,107,53,0.10);  /* Subtle divider */
  --grid-color:  rgba(139,157,195,0.12);  /* Chart gridlines */
}
```

---

## Typography

| Role | Font | Weight | Usage |
|---|---|---|---|
| Display / Hero | Orbitron | 700, 900 | Page titles, KPI numbers |
| Body | Rajdhani | 400–700 | All body text, descriptions |
| Mono / Labels | JetBrains Mono | 400, 700 | Eyebrows, chips, data labels |

```html
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&family=Rajdhani:wght@400;500;600;700&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet"/>
```

---

## Components

### KPI Card
- Background: `--navy-card`
- Top accent bar: 3px gradient (orange → gold)
- Value: Orbitron 700, `--gold`
- Label: JetBrains Mono, `--text-muted`, letter-spacing 2px

### Chart Container
- Background: `--navy-mid` with `--border` outline
- Title: Rajdhani 700, `--text-bright`, with coloured dot indicator
- Plot area: Transparent bg, `--grid-color` gridlines

### Section Divider
- `border-top: 1px solid var(--border-light)`
- Section title: Orbitron 700, 18px, uppercase

---

## Plotly Theme Config

```javascript
const plotlyLayout = {
  paper_bgcolor: 'transparent',
  plot_bgcolor:  'transparent',
  font: { family: 'Rajdhani, sans-serif', color: '#c8d4ee' },
  xaxis: { gridcolor: 'rgba(139,157,195,0.12)', linecolor: 'rgba(139,157,195,0.2)' },
  yaxis: { gridcolor: 'rgba(139,157,195,0.12)', linecolor: 'rgba(139,157,195,0.2)' },
  margin: { t: 20, r: 20, b: 40, l: 50 }
};
```

---

## Noise Texture Overlay

Applied to `body::before` for cinematic depth:

```css
body::before {
  content: '';
  position: fixed; inset: 0;
  background-image: url("data:image/svg+xml,...fractalNoise...");
  opacity: 0.035;
  pointer-events: none;
  z-index: 0;
}
```
