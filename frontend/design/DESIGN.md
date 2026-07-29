---
name: Electric Pop
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4a4731'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#7c785f'
  outline-variant: '#ccc7aa'
  surface-tint: '#686000'
  primary: '#686000'
  on-primary: '#ffffff'
  primary-container: '#ffed00'
  on-primary-container: '#736a00'
  inverse-primary: '#d9c900'
  secondary: '#b60055'
  on-secondary: '#ffffff'
  secondary-container: '#e4006c'
  on-secondary-container: '#fffbff'
  tertiary: '#006877'
  on-tertiary: '#ffffff'
  tertiary-container: '#bdf2ff'
  on-tertiary-container: '#007384'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f7e600'
  primary-fixed-dim: '#d9c900'
  on-primary-fixed: '#1f1c00'
  on-primary-fixed-variant: '#4e4800'
  secondary-fixed: '#ffd9e0'
  secondary-fixed-dim: '#ffb1c3'
  on-secondary-fixed: '#3f0019'
  on-secondary-fixed-variant: '#8f0041'
  tertiary-fixed: '#a5eeff'
  tertiary-fixed-dim: '#00daf8'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5a'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 42px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  offset-shadow: 6px
---

## Brand & Style
The design system is built on an energetic, Neo-Brutalist foundation that prioritizes high-impact visual communication. The personality is unapologetically loud, youthful, and "funky," designed to feel like a living comic book or a collection of high-end stickers. 

Key stylistic pillars:
- **High-Contrast Borders:** Everything is contained within thick, consistent black strokes.
- **Offset Geometry:** Shadows and highlights are rarely centered; they are hard-edged and offset to create a "pop-out" 2.5D effect.
- **Sticker Aesthetic:** UI elements often feature thick white or black outlines that make them look like they’ve been slapped onto the canvas.
- **Movement-Ready:** Elements utilize "speed lines" or exaggerated hover states to suggest kinetic energy.

## Colors
The palette is hyper-saturated and high-contrast, designed to command attention. 
- **Primary (Electric Yellow):** Used for main actions and background "splashes" to provide maximum energy.
- **Secondary (Hot Pink):** Used for highlights, playful accents, and notification badges.
- **Tertiary (Electric Blue):** Used for interactive data, links, or secondary brand elements to provide a cool contrast to the warm primary/secondary tones.
- **Surface & Stroke:** Pure white surfaces are used for legibility, always bounded by a heavy "Black Ink" (#000000) stroke.

## Typography
The typography strategy pairs a quirky, expressive grotesque for display moments with a sharp, clean sans-serif for readability.
- **Display & Headlines:** Use Bricolage Grotesque. It should be set with tight leading and negative letter-spacing for a "chunky" look.
- **Body Text:** Hanken Grotesk provides a modern, neutral balance to the expressive headlines.
- **Labels & UI Metadata:** Space Grotesk is used for a technical, slightly futuristic "sticker label" feel. All labels should be uppercase to reinforce the bold aesthetic.

## Layout & Spacing
The layout follows a rigid 8px grid system but breaks the rules visually with "floating" elements. 
- **The Offset Rule:** All containers and interactive buttons feature a hard-edged shadow that is offset by exactly 6px (or 4px on mobile) to the bottom-right.
- **Padding:** Generous internal padding (24px+) ensures that the thick borders do not crowd the content.
- **Grid:** A 12-column fluid grid is used for desktop, but elements frequently "overhang" or overlap slightly to create a messy, high-energy collage feel.

## Elevation & Depth
Depth is not created through light and shadow, but through **Graphic Stacking**.
- **Hard Shadows:** Instead of blurs, use solid #000000 blocks offset from the parent container.
- **Layering:** Top-level elements (like modals) should have a thicker border (4pt) than base elements (2pt).
- **Parallax:** On scroll, different layers should move at slightly different speeds to enhance the "kinetic" vibe of the brand.

## Shapes
This design system uses a "Soft-Brutalist" approach to shapes. 
- **Corners:** Containers use a consistent 0.25rem (4px) radius. This prevents the design from feeling too sharp/aggressive while maintaining the structural integrity of the Neo-Brutalist style.
- **Strokes:** All shapes must have a minimum 2px black border. Main CTA buttons and "hero" cards should increase this to 3px or 4px.

## Components
- **Buttons:** Primary buttons use the Primary Color (Yellow) with a 3px black stroke and a 6px black offset shadow. On hover, the shadow disappears as the button "presses" down into the shadow's space.
- **Cards:** Cards are white with a 2px stroke. Use "Sticker" accents—small, high-contrast labels that overlap the top border of the card.
- **Input Fields:** Thick borders with a slight inner shadow (solid grey, not blurred) to suggest depth. Use the Primary Color for the active cursor/caret.
- **Chips/Badges:** Rounded-pill shapes with secondary or tertiary fills. These should look like individual physical stickers.
- **Checkboxes:** Square with hard corners and a "thick X" mark rather than a traditional checkmark.
- **Modals:** Use a heavy "backdrop blur" combined with a high-contrast black overlay at 40% opacity to keep focus on the pop-out window.