# Restaurante Peak

A multi-page fictitious restaurant website built with semantic HTML5 and vanilla CSS3. No frameworks, no JavaScript dependencies.

## Pages

| Page | File | Key Features |
|------|------|-------------|
| Home | `index.html` | Hero, featured dishes grid, why choose us |
| Menu | `menu.html` | Definition lists, 2-col CSS grid |
| About | `about.html` | Story grid, chef section, awards |
| Gallery | `gallery.html` | 4-col image grid, hover overlays |
| Contact | `contact.html` | Reservation form, hours table, map |

## Tech

- **HTML5** — semantic elements (`header`, `nav`, `address`, `figure`, `dl`, `fieldset`)
- **CSS3** — custom properties, CSS Grid, Flexbox, media queries
- **Fonts** — Playfair Display + Lato via Google Fonts
- **No JavaScript** — hamburger menu uses the checkbox hack

## CSS Architecture

```
css/
├── style.css   # Global reset, CSS variables, typography
├── nav.css     # Shared sticky header & footer
├── index.css   # Home page
├── menu.css    # Menu page
├── about.css   # About page
├── gallery.css # Gallery page
└── contact.css # Contact page
```

## Team Roles

| Member | Responsibility |
|---|---|
| Gabriel Njoku (https://github.com/gabrielnjoku) | Page structure, style.css, nav.css, index.css, index.html, about.css, about.html, gallery.css, gallery.html |
| Juliet Aneke (https://github.com/Juliet-Aneke) | contact.css, contact.html |
| Victoria Echebima (https://github.com/Victoria-Echebima) | menu.css, menu.html |

## Getting Started

Clone the repo, drop your images into the `images/` folder, and open `index.html` in a browser. No build step required.

```bash
git clone https://github.com/gabrielnjoku/restaurante-peak.git
cd restaurante-peak
```

## Responsive Breakpoints

| Breakpoint | Target |
|------------|--------|
| `1024px+` | Desktop |
| `≤ 768px` | Tablet |
| `≤ 480px` | Mobile |

## Credits

Built as part of the **Enugu Turing Tech Program** CSS Group Project — Turing Tech LLC.  
Images sourced from [Unsplash](https://unsplash.com) and [Pexels](https://pexels.com).
