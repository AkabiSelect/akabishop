# Akabi Select Boutique

A handcrafted fashion brand website for [Akabi Select Boutique](https://www.etsy.com/shop/AkabiSelectboutique), founded in 2012 by a Japanese-trained fashion designer from Takeo, Japan.

## Live Links

- **Etsy Shop:** https://www.etsy.com/shop/AkabiSelectboutique
- **Instagram:** https://www.instagram.com/akabiselectboutique/
- **Email:** akabi27@gmail.com

## Tech Stack

- Static HTML + CSS (no frameworks)
- Google Fonts: [Syne](https://fonts.google.com/specimen/Syne) (display) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body)
- Responsive design (mobile 375px, tablet 768px, desktop 1280px+)

## Color Palette — Sunset Blaze

| Role | Color | Hex |
|------|-------|-----|
| Primary (hero) | Firebrick red | `#B22222` |
| Hero text | Light pink | `#FFB6C1` |
| Accent 1 | Orange/amber | `#FF9505` |
| Accent 2 | Deep plum | `#8E3557` |
| Neutral warm | Tan/camel | `#D2B48C` |
| Neutral light | Peach | `#FFE5B4` |
| Background | Cream | `#FFF8EE` |
| Dark | Charcoal | `#1A1A1A` |

## Site Sections

1. **Nav** — Fixed dark bar with logo, About/Shop/Contact links, and scrolling marquee banner
2. **Hero** — Full-viewport firebrick red with oversized pink "AKABI SELECT" and dark "BOUTIQUE" typography
3. **The Story Behind Every Stitch** — Plum background, personal story about learning to sew from grandmother in Takeo, Japan, with sewing studio photo
4. **The Birth of Akabi Select Boutique** — Tan background, Fukuoka fashion school photo + founding story (2012), thank-you message with crafting workspace photo
5. **From the Studio** — Cream background, product showcase (handmade Jessie costume dress)
6. **Shop the Collection** — Orange background with CTA button linking to Etsy shop
7. **Billboard Quote** — Cream background with plum text: "Fashion is not just about what you wear — it's about how it's made."
8. **Let's Connect** — Peach background, contact links (email, Instagram, Etsy)
9. **Footer** — Dark background with brand name and copyright

## Changelog

### 2026-07-06 — Initial Build

- Created single-page responsive website with bold, section-based design inspired by flyingpapers.com
- Established typography system: Syne (800 weight display) + DM Sans (body)
- Built mobile hamburger menu with full-screen overlay
- Added scrolling marquee banner ("Internationally trained", "Handcrafted", etc.) integrated into fixed nav bar
- Wrote personal brand copy for "The Story Behind Every Stitch" (grandmother in Takeo) and "The Birth of Akabi Select Boutique" (Fukuoka training, 2012 founding)
- Added product showcase section with sample garment image (AVIF format)
- Applied Sunset Blaze color palette, iterated hero red from #FF2400 → #C21807 → #FF3030 → #B22222 (firebrick)
- Set hero "AKABI SELECT" text to light pink (#FFB6C1)
- Fixed hero text alignment/centering for all breakpoints
- Removed mix-blend-mode nav (caused cyan anti-pattern) in favor of dark translucent backdrop
- Split "Birth" section thank-you paragraph into its own row with about2 workspace photo
- Verified responsive layout at mobile (375px), tablet (768px), and desktop

## Project Structure

```
akabishop/
├── index.html          # Single-page site
├── styles.css          # All styles
├── README.md
├── images/
│   ├── studio.jpg      # Sewing studio workspace
│   ├── fukuoka.jpg     # Fukuoka Fashion School building
│   ├── sample1.avif    # Product photo (Jessie costume dress)
│   ├── about2.avif     # Crafting workspace with fabrics
│   └── ichigo.png      # Mascot illustration (unused)
└── colors/
    └── Red-Color-Palettes-Sunset-Blaze.jpg  # Color reference
```
