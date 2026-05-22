---
name: Rich Blox Aesthetic
colors:
  surface: '#121416'
  surface-dim: '#121416'
  surface-bright: '#37393b'
  surface-container-lowest: '#0c0e10'
  surface-container-low: '#1a1c1e'
  surface-container: '#1e2022'
  surface-container-high: '#282a2c'
  surface-container-highest: '#333537'
  on-surface: '#e2e2e5'
  on-surface-variant: '#e5bdb8'
  inverse-surface: '#e2e2e5'
  inverse-on-surface: '#2f3133'
  outline: '#ac8883'
  outline-variant: '#5c403c'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#ff5546'
  on-primary-container: '#5c0002'
  inverse-primary: '#bd1212'
  secondary: '#ffdb9d'
  on-secondary: '#412d00'
  secondary-container: '#feb700'
  on-secondary-container: '#6b4b00'
  tertiary: '#8bceff'
  on-tertiary: '#00344e'
  tertiary-container: '#0099dd'
  on-tertiary-container: '#002d44'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930006'
  secondary-fixed: '#ffdea8'
  secondary-fixed-dim: '#ffba20'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4200'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#8bceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004b6f'
  background: '#121416'
  on-background: '#e2e2e5'
  surface-variant: '#333537'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  container-max: 1200px
---

## Brand & Style

The brand personality of this design system is high-energy, playful, and aspirational. It is designed to resonate with a gaming audience that values both the fun of the platform and the prestige of "rich" status. The emotional response should be one of excitement and tactile satisfaction.

The design style is **Tactile / Skeuomorphic** mixed with **High-Contrast Bold**. It moves away from the flat trends of the web and embraces the "blocky" nature of the Roblox universe. Elements should feel like physical objects—buttons should look like they can be pressed down, and containers should look like extruded plastic slabs. This approach provides a sense of durability and fun, making the interface feel less like a document and more like a dashboard within a game engine.

## Colors

The color palette is built on a foundation of "Deep Space" grays to provide a high-contrast backdrop for vibrant highlights. 

- **Primary:** A bright, high-energy red used for critical actions and brand recognition.
- **Secondary (Gold):** Representing the "Rich" aspect of the brand, this gold is used for premium features, currency indicators, and highlights.
- **Neutral:** A range of dark grays (from #0E0F10 to #2B2D30) creates depth. Pure white is reserved for high-readability body text and icons.
- **Accents:** Vibrant blue is used sparingly for informational elements or secondary functional cues to maintain the "gamer" energy without cluttering the primary red/gold hierarchy.

## Typography

This design system utilizes **Plus Jakarta Sans** for its friendly yet geometric structure, which perfectly complements a blocky UI. 

Typography is characterized by heavy weights (700 and 800) for headlines to mimic the "chunky" feel of game menus. Letter spacing is slightly tightened on large headings to create a more compact, impactful look. For body text, a medium weight (500) is preferred over regular to ensure text doesn't feel "thin" compared to the heavy borders and shadows of the container elements. All interactive labels should be bold and occasionally uppercase to drive urgency and clarity.

## Layout & Spacing

The layout follows a **Fixed Grid** model to ensure that content feels structured and "contained," much like a game HUD (Heads-Up Display). 

The spacing rhythm is built on an 8px base unit. Large internal paddings (24px to 40px) are used within containers to prevent the UI from feeling cramped. The layout should prioritize "Cards" or "Modules" that sit on a background layer, with generous 20px gutters between them. Centered layouts are preferred for landing sections to create a focused, cinematic experience, while dashboard views utilize a standard 12-column grid.

## Elevation & Depth

Hierarchy is established through **Tactile 3D effects** rather than traditional soft ambient shadows. 

1.  **Chunky Shadows:** Use hard-edged, low-blur shadows with a significant vertical offset (4px to 8px). These should be slightly darker than the surface they sit on, creating a "block" effect.
2.  **Inner Bevels:** To make elements look "carved" or "embossed," use subtle top-light borders (1px, low opacity white) and bottom-dark borders.
3.  **Active States:** When a user interacts with a button or card, the element should "depress." This is achieved by reducing the shadow offset to 0 or 1px and applying a slight `translateY` transform, simulating a physical press.
4.  **Tonal Layers:** The background uses the darkest gray, while interactive containers use a secondary, lighter gray to pull them forward visually.

## Shapes

The shape language is "Rounded-Blocky." 

While the aesthetic is inspired by blocks, the design system uses a consistent **0.5rem (8px)** corner radius for standard elements like buttons and input fields to ensure they feel modern and touch-friendly. Larger containers and cards use **1rem (16px)** to soften the overall layout and make the site feel more approachable. Icons should follow this same logic, avoiding sharp points in favor of rounded terminals.

## Components

### Buttons
Buttons are the core of the tactile experience. They must have a bottom "rim" (a shadow that looks like the thickness of the button). 
- **Primary:** Red background, white text, dark red bottom border (3px).
- **Premium:** Gold background, dark gray text, dark gold bottom border (3px).
- **Hover:** Slight brightness increase.
- **Active:** Moves down 2px, shadow disappears.

### Cards
Cards act as 3D containers. They should have a dark gray surface (#232527) and a 1px border (#3A3D40) to separate them from the background. Every card must have a hard drop shadow (8px offset, #000000 opacity 40%).

### Input Fields
Inputs should look "sunken" into the UI. Use an inner shadow (inset) to create depth, with a dark background and a bright border highlight (Gold or Blue) when focused.

### Chips & Tags
Small, pill-shaped elements with high-contrast backgrounds. These use the `label-bold` typography and act as status indicators (e.g., "New," "Hot," "Rich").

### Lists
List items should be separated into individual blocks rather than a single flat list. Each item should behave like a mini-card, providing a satisfying hover effect.

### Progress Bars
Chunky, 20px tall bars with a rounded track. The progress fill should have a slight gradient and a "gloss" overlay to look like a physical plastic bar filling up.