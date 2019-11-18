# Sketch TailwindCSS Design System

An atomic design system for TailwindCSS implemented in Sketch.

## Requirements

- Sketch 60 (or newer)
- [SF Pro fonts](https://developer.apple.com/fonts/) installed. Please read the
    license agreement. They are intended for development and mockup use only.
- Menlo font (should be installed in macOS).
- Georgia font (should be installed in macOS).

## (Planned) Features

### Styles

- [X] Color Styles
- Font Styles
  - [X] Font Family
  - [X] Font Sizes
  - [X] Font Styles
  - [X] Font Weights
  - [ ] Letter Spacing (? not yet sure if feasible)
  - [ ] Line Height (? not yet sure if feasible)
  - [ ] Text Align (? not yet sure if feasible)
  - [X] Text Color
  - [ ] Text Decoration (? not yet sure if feasible)
  - [ ] Text Transform (? not yet sure if feasible)
- [X] Box Shadow
- [ ] Opacity (? not yet sure if feasible)
- Border Styles
  - [X] Border Color
  - Border Styles
    - [X] Solid
    - [X] Double
    - [ ] Dashed
    - [ ] Dotted
  - [X] Border Width
- [X] Border Radius (implemented as cards)

### Symbols

- Spacing & Sizing Symbols (to be used as guides)
  - [X] Container
  - [X] Paddings, Margins, Widths, Heights
  - [ ] Max-Width
- [X] Basic Text Symbols
- [X] Spacing & Sizing Symbols
- [X] Card Symbols

### Examples

- [ ] Alerts
- [ ] Buttons
- [ ] Cards
- [ ] Grids (? not yet sure if feasible)
- [ ] Navigation
- [ ] Email Inbox
- [ ] Kanban Board
- [ ] Pricing Page

## Current Limitations

- Not all font weights (100 through 900) are represented. Instead, only the
    available weights the for the respctive fonts are created.

### Issues

The following are issues we are working on resolving. Until then, they are
    ommitted from the template in order to avoid confusion and keep things
    simple.

- Italics are currently not rendering correctly (instead rendering as Normal).
- Double borders render as single borders.
- Dotted borders render as single borders.
- Dashed borders render as single borders.

## Installation

1. Download the latest version.
2. Open in Sketch.
3. Set as a template: File > Save as Template ... > Set name to "TailwindCSS".
4. Start a new project: File > New From Template > TailwindCSS.

## Recommended Use

- Update elements in "Symbols" layer to match your project's branding.
- "Styles" layer should only be used to make corrections to styles, for example
  when Tailwind updates its styles, and not for branding purposes.
