
## 📁 File

```
nihaal_portfolio.html
```

No build tools, no dependencies, no frameworks. Open the file in any modern browser and it works.

---

## 

## ✨ Features & Animations

### Background
| Effect | Description |
|---|---|
| Particle network | 60+ glowing dots float upward; nearby dots are connected by faint lines |
| Mouse repulsion | Particle nodes drift away from your cursor in real time |
| Morphing blobs | 4 large colour blobs (teal, indigo, pink, amber) slowly breathe and drift |
| Grid overlay | Subtle dot grid that fades toward the edges |

### Cursor
| Effect | Description |
|---|---|
| Custom dot cursor | Replaces the default cursor with a glowing accent dot |
| Trailing ring | A soft ring lags behind the cursor for depth |
| Hover expansion | Cursor grows and turns pink over links and buttons |

### Cards & Interactions
| Effect | Description |
|---|---|
| 3D tilt | Project and skill cards tilt in perspective as you move the mouse over them |
| Spotlight | A radial glow inside skill cards follows your exact cursor position |
| Glow blob | Project cards have a colour blob that tracks mouse position |
| Accent line | A gradient line sweeps across the top of skill cards on hover |
| Edu card reveal | Education cards slide right and grow an accent bar on hover |

### Scroll & Entry
| Effect | Description |
|---|---|
| Scroll reveal | Every section fades and rises into view with staggered delays |
| Count-up stats | Numbers in the About section count up when scrolled into view |
| Typewriter | Hero subtitle types out character by character on load |
| Scroll beam | The scroll indicator has an animated light beam travelling downward |
| Active nav | Nav links highlight and underline as you scroll through each section |

---

## 🎨 Customisation

All key values are CSS variables at the top of the `<style>` block:

```css
:root {
  --bg: #06060f;         /* page background */
  --accent: #5eead4;     /* primary accent (teal) */
  --accent2: #818cf8;    /* secondary accent (indigo) */
  --accent3: #f472b6;    /* tertiary accent (pink) */
  --accent4: #fbbf24;    /* quaternary accent (amber) */
  --text: #eeeef5;       /* body text */
  --muted: #7878a0;      /* secondary text */
}
```

### Update your details
Search the file for the following and replace:

| Placeholder | Where to update |
|---|---|
| `Nihaal S Suresh` | `<title>`, hero `<h1>`, footer |
| `nihaalsuresh@gmail.com` | Contact section + mailto links |
| `+91 8197402425` | Contact section + tel link |
| `Mangaluru, Karnataka` | Hero sub, contact section |
| Section content | Each `<section>` block is clearly labelled with a comment |

### Add/remove sections
Each section is wrapped in `<section id="...">` with a matching nav link in `<nav>`. To remove a section, delete both the `<section>` block and its `<li>` in the nav. To add one, copy an existing block and update the `id` and nav link.

---

## 🗂 Section Structure

```
#hero        — Name, role, tags, CTA buttons
#about       — Bio text + animated stat grid
#skills      — 6 skill cards with spotlight effects
#experience  — 3 internships with bullet points and tech tags
#projects    — 4 project cards with glow and 3D tilt
#education   — 3 institutions with animated accent bars
#contact     — Email, phone, location + CTA
```

---

## 🌐 Browser Support

Works in all modern browsers. Custom cursor and canvas effects require JavaScript to be enabled.

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile browsers | ✅ Responsive (custom cursor disabled on touch) |

---

## 📄 License

Free to use and modify for personal portfolio purposes.

---

*Built for Nihaal S Suresh — AI/ML Engineer, Mangaluru*
