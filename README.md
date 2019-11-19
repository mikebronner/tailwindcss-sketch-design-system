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
Items marked as blocked are not yet implemented in the style generator plugin.

- [X] Color Styles
- Font Styles
  - [X] Font Family
  - [X] Font Sizes
  - [X] Font Styles
  - [X] Font Weights
  - [ ] Letter Spacing (ommitted, should be set when creating symbols)
  - [X] Line Height
  - [ ] Text Align (ommitted, should be set when creating symbols)
  - [ ] Text Color (ommitted, should be achieved in symbols using masks)
  - [ ] Text Decoration (ommitted, should be set when creating symbols)
  - [ ] Text Transform (ommitted, should be set when creating symbols)
- [X] Box Shadow
- [ ] Opacity (blocked)
- Border Styles
  - [X] Border Color
  - Border Styles
    - [X] Solid
    - [X] Double
    - [ ] Dashed (blocked)
    - [ ] Dotted (blocked)
  - [X] Border Width
- [ ] Border Radius (blocked, implemented as card symbols)

### Symbols

- Spacing & Sizing Symbols (to be used as guides)
  - [X] Container
  - [X] Paddings, Margins, Widths, Heights
  - [X] Max-Width
- [ ] Basic Text Symbols
- [X] Spacings & Sizings
- [X] Cards
- [X] Browser Window

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
- 100% border radii don't scale in Sketch 60.

## Installation

1. Download the latest version.
2. Open in Sketch.
3. Set as a template: File > Save as Template ... > Set name to "TailwindCSS".
4. Start a new project: File > New From Template > TailwindCSS.

## Recommended Use

- Update elements in "Symbols" layer to match your project's branding.
- "Styles" layer should only be used to make corrections to styles, for example
  when Tailwind updates its styles, and not for branding purposes.
