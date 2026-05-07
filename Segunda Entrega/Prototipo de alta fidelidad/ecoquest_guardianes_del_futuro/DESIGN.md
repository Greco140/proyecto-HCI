---
name: 'EcoQuest: Guardianes del Futuro'
colors:
  surface: '#f7faf7'
  surface-dim: '#d7dbd8'
  surface-bright: '#f7faf7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f1'
  surface-container: '#ebefec'
  surface-container-high: '#e6e9e6'
  surface-container-highest: '#e0e3e0'
  on-surface: '#181c1b'
  on-surface-variant: '#404751'
  inverse-surface: '#2d3130'
  inverse-on-surface: '#eef1ef'
  outline: '#707882'
  outline-variant: '#c0c7d2'
  surface-tint: '#00629e'
  primary: '#005e97'
  on-primary: '#ffffff'
  primary-container: '#0077be'
  on-primary-container: '#f7f9ff'
  inverse-primary: '#9acbff'
  secondary: '#006e1c'
  on-secondary: '#ffffff'
  secondary-container: '#91f78e'
  on-secondary-container: '#00731e'
  tertiary: '#695f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#bdad00'
  on-tertiary-container: '#474000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#9acbff'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#004a79'
  secondary-fixed: '#94f990'
  secondary-fixed-dim: '#78dc77'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#005313'
  tertiary-fixed: '#f9e534'
  tertiary-fixed-dim: '#dbc90a'
  on-tertiary-fixed: '#201c00'
  on-tertiary-fixed-variant: '#4f4800'
  background: '#f7faf7'
  on-background: '#181c1b'
  surface-variant: '#e0e3e0'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  body-lg:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 30px
  body-md:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  label-bold:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 20px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  touch-target-min: 64px
  margin-landscape: 48px
  gutter: 24px
  card-padding: 24px
---

## Brand & Style
The brand personality is heroic and adventurous, designed to make children feel like "Guardians of the Future." The visual language balances educational authority with the high-energy excitement of a cartoon world. 

This design system utilizes a **Tactile / Skeuomorphic** style adapted for a modern, flat-plus-depth aesthetic. The UI focuses on "squishy" physical metaphors, making every interaction feel responsive and rewarding. The environment is vibrant and friendly, using high-saturation colors to maintain engagement while emphasizing an eco-friendly narrative through nature-inspired motifs.

## Colors
The palette is inspired by the natural biomes children are tasked to protect. 
- **Ocean Blue (#0077BE):** Used for navigation, high-level headers, and core "Hero" interactions.
- **Leaf Green (#4CAF50):** The primary action color for "Positive" progress, growth-related tasks, and success states.
- **Sun Yellow (#FFEB3B):** Used for highlights, collectibles, and drawing attention to specific educational facts.
- **Alert Red (#F44336):** Reserved for environmental "threats" within the game or critical errors.

Backgrounds should remain off-white or very light mint (#F8FBF8) to ensure the vibrant components pop without causing eye fatigue during horizontal gameplay.

## Typography
This design system prioritizes legibility for young readers. **Plus Jakarta Sans** is used for headlines to provide a friendly, rounded, and "bubbly" appearance. **Lexend** is utilized for all body text and instructional labels, as its specific character spacing is optimized for reading fluency and accessibility in educational contexts. All text should maintain high contrast against backgrounds to ensure focus.

## Layout & Spacing
The layout is strictly **Landscape**. This horizontal orientation mimics a cinematic or console gaming experience. 
- **Grid:** A 12-column fluid grid is used, but with significantly wider side margins (48px) to account for thumb placement on mobile devices.
- **Touch Targets:** Minimum touch targets are oversized (64px) to accommodate developing motor skills. 
- **Safe Zones:** UI elements must avoid the extreme corners to prevent interference with hardware-level gestures or rounded device displays.

## Elevation & Depth
Depth is not communicated through realism, but through **3D Cartoon Effects**. 
- **The "Pressable" Effect:** Interactive elements use a thick bottom border (4px to 6px) that is 20% darker than the surface color, creating a "block" look.
- **Shadows:** Soft, diffused ambient shadows are used for floating containers (Cards), while buttons use a "pressed" state where the bottom border disappears and the element shifts 4px downward on the Y-axis.
- **Layers:** Use tonal layering for backgrounds—light sky blues or soft earth tones to distinguish the play area from the UI overlay.

## Shapes
The design system employs a highly rounded, organic shape language. There are no sharp corners. 
- **Buttons and Containers:** Use "Pill-shaped" or high-radius corners to evoke a sense of safety and friendliness.
- **Iconography:** Icons should be enclosed in circular or squircle frames with thick strokes. 
- **Modals:** Use a heavy border-radius (32px+) to make large UI panels feel less intrusive.

## Components
- **Action Buttons:** Oversized, colorful blocks with a 3D "raised" effect. The primary action (e.g., "Go!") should always be Leaf Green. 
- **Progress Bars:** Thick, rounded bars. The "track" is a darker shade of the background, and the "fill" is a vibrant Sun Yellow with a subtle "shimmer" animation to indicate active growth.
- **Achievement Chips:** Small, pill-shaped badges with icons. They use Sun Yellow backgrounds and bold Lexend labels.
- **Dialogue Cards:** Large, white rounded containers with a thick Blue or Green stroke. They always appear centered or bottom-aligned in the landscape view.
- **Hero Character HUD:** A fixed top-left component showing the player's "Guardian Level," encased in an Ocean Blue rounded frame.
- **Checkboxes:** Large, square boxes with rounded corners (12px). When checked, they fill with Leaf Green and a thick white checkmark.