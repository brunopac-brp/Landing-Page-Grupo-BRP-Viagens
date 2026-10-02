---
name: Oceanic Nautical Modern
colors:
  surface: '#f6f9ff'
  surface-dim: '#c8ddf0'
  surface-bright: '#f6f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ebf5ff'
  surface-container: '#e0f0ff'
  surface-container-high: '#d6ebff'
  surface-container-highest: '#d0e5f9'
  on-surface: '#071d2c'
  on-surface-variant: '#414751'
  inverse-surface: '#1e3241'
  inverse-on-surface: '#e6f2ff'
  outline: '#717782'
  outline-variant: '#c1c7d3'
  surface-tint: '#0060a8'
  primary: '#004c87'
  on-primary: '#ffffff'
  primary-container: '#0464ae'
  on-primary-container: '#cce0ff'
  inverse-primary: '#a2c9ff'
  secondary: '#3e6187'
  on-secondary: '#ffffff'
  secondary-container: '#afd2fe'
  on-secondary-container: '#375a80'
  tertiary: '#783900'
  on-tertiary: '#ffffff'
  tertiary-container: '#9c4c01'
  on-tertiary-container: '#ffd7bf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e4ff'
  primary-fixed-dim: '#a2c9ff'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#004881'
  secondary-fixed: '#d1e4ff'
  secondary-fixed-dim: '#a6c9f5'
  on-secondary-fixed: '#001d36'
  on-secondary-fixed-variant: '#24496e'
  tertiary-fixed: '#ffdcc7'
  tertiary-fixed-dim: '#ffb787'
  on-tertiary-fixed: '#311300'
  on-tertiary-fixed-variant: '#723600'
  background: '#f6f9ff'
  on-background: '#071d2c'
  surface-variant: '#d0e5f9'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4rem
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a maritime, trustworthy, and modern atmosphere tailored for leisure and corporate travel planning. Rooted in deep naval blues and vibrant sky tones, it balances institutional security with wanderlust and approachability.

The visual aesthetic follows a **Corporate / Modern** direction refined with clean, breezy editorial pacing. Visual hierarchy is achieved through crisp card layouts, generous whitespace, pristine high-contrast photography framing, and structured typographic scales. The interface feels dependable, crisp, and effortless—eliminating friction in vacation browsing and booking flows.

## Colors

The palette is anchored by maritime tones that convey reliability and high-seas exploration:

- **Primary (`#0464AE`)**: A vibrant azure blue representing open skies and tropical waters, used for primary calls to action, focus rings, and highlighted navigational markers.
- **Secondary (`#023054`)**: A deep navy blue anchoring top-level typography, structural headers, footers, and institutional elements.
- **Neutral (`#5A6E7F`)**: A slate-blue gray utilized to construct body copy, secondary metadata, borders, and sub-labels without harsh chromatic clashing.
- **Surface Foundations**: Crisp white backgrounds complemented by soft naval-tinted slate containers (`#F4F7FA` to `#E8EEF4`) for card backdrops and search modules.

## Typography

Typography relies on **Plus Jakarta Sans** across all levels, replacing unstandardized web geometric sans-serifs with a contemporary, high-clarity alternative designed for digital booking interfaces and legibility.

- **Headlines & Titles**: Rendered in Semibold to ExtraBold weights with slight negative letter tracking to produce a punchy, confident editorial stance on destination showcases.
- **Body & Captions**: Maintained at regular weight with open line spacing (`1.5` to `1.6`) for rapid scanning of itineraries, flight tables, and hotel inclusions.
- **Accents**: For promotional badges, tags, and pricing micro-copy, use uppercase `label-sm` with widened letter-spacing (`0.04em`) to ensure distinct visual separation from descriptive body text.

## Layout & Spacing

The layout is structured on a 12-column responsive fluid grid designed to manage heavy search filters, package catalogs, and destination imagery:

- **Desktop (>= 1024px)**: 12 columns with `gutter: 1.5rem` and outer page margins capped within a maximum container width of `1280px` (`margin: 2rem`).
- **Tablet (768px - 1023px)**: 8 columns with `gutter: 1.25rem` and outer margins of `1.5rem`.
- **Mobile (< 768px)**: 4 columns with `gutter-mobile: 1rem` and compact canvas boundaries with `margin-mobile: 1rem`.

Component padding strictly aligns with the 8pt rhythm scale: `space-xs` (4px) for badge and chip insets, `space-sm` (8px) for input padding and compact lists, `space-md` (16px) for standard button and field insets, `space-lg` (24px) for card body padding, and `space-xl` (40px) for section tiering.

## Elevation & Depth

Visual hierarchy uses **tonal surfaces paired with ambient nautical shadows** to create an airy, float-above feeling without visual noise:

- **Level 0 (Base)**: Flat canvas `#FFFFFF` or soft cool tint `#F8FAFC`.
- **Level 1 (Card & Module Resting)**: Elevated via a subtle 1px border (`rgba(2, 48, 84, 0.08)`) and an ultra-soft ambient drop: `0px 4px 16px -2px rgba(2, 48, 84, 0.06)`.
- **Level 2 (Interactive Hover & Package Cards)**: `0px 12px 28px -4px rgba(2, 48, 84, 0.12)`, signaling elevation when hovering over trip itineraries or booking summaries.
- **Level 3 (Search Drawers, Dropdowns, Datepickers)**: `0px 18px 36px -6px rgba(2, 48, 84, 0.18)` with crisp border definition.
- **Level 4 (Modals & Overlays)**: `0px 24px 48px -12px rgba(2, 48, 84, 0.25)` atop a darkened naval veil (`rgba(2, 48, 84, 0.45)`).

## Shapes

The interface adopts a **Rounded (Level 2)** geometric rhythm:

- **Standard Elements (0.5rem / 8px)**: Applied to text input fields, search filter boxes, buttons, itinerary timeline badges, and modal window borders.
- **Containers & Cards (`rounded-lg`, 1rem / 16px)**: Applied to trip showcase cards, hero search panels, package overview banners, and review testimonials.
- **Pill Shapes (Full Round)**: Exclusively reserved for status chips (e.g., "Passagens Inclusas", "Últimas Vagas"), interactive filter toggles, and floating WhatsApp/support triggers.

## Components

### Buttons
- **Primary**: Solid Azure Blue (`#0464AE`) background with pure white text, 8px border radius, font-weight 600. Active states drop to a darkened tone (`#034E89`).
- **Secondary**: Navy Blue outline (`#023054`) with transparent background, shifting to solid `#023054` with white text on hover.
- **Ghost/Tertiary**: Clean `#023054` text on transparent fill, light background tint on hover (`rgba(4, 100, 174, 0.06)`).

### Cards & Trip Packages
- Destination cards feature high-resolution imagery clipped to top border radius (`16px`), accompanied by a floating pill tag for package status or discount rate.
- Body area contains clear destination hierarchy: location in secondary navy, price emphasized in primary azure blue, and duration meta in neutral gray with light iconography.

### Form Inputs & Search Module
- Search bars (destination, check-in, check-out, guests) sit within an elevated container (`Level 2`) with an 8px border radius.
- Input boxes use light backgrounds (`#F4F7FA`), subtle borders (`1px solid rgba(2, 48, 84, 0.12)`), transitioning to a vibrant primary azure focus ring (`2px solid #0464AE`) without harsh outlines.

### Chips & Filter Tags
- Multi-select filters (e.g., "Aéreo + Hotel", "Resorts", "Cruzeiros") utilize pill-shaped tags with light neutral-tinted outlines. Selected states flip to `#0464AE` fill with white text.

### Checkboxes & Radio Buttons
- Crisp 4px rounded corners for checkboxes and fully circular radio options. Filled with `#0464AE` when active, framed by `#023054` at 30% opacity when dormant.