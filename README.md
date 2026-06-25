---
name: Structural Excellence
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#474550'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#787581'
  outline-variant: '#c8c5d1'
  surface-tint: '#5c5699'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#180f52'
  on-primary-container: '#827cc1'
  inverse-primary: '#c6bfff'
  secondary: '#b90a1b'
  on-secondary: '#ffffff'
  secondary-container: '#de2d30'
  on-secondary-container: '#fffbff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#370e00'
  on-tertiary-container: '#b77359'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c6bfff'
  on-primary-fixed: '#180f52'
  on-primary-fixed-variant: '#443e7f'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb3ad'
  on-secondary-fixed: '#410003'
  on-secondary-fixed-variant: '#930011'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#370e00'
  on-tertiary-fixed-variant: '#6e3822'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  slate-gray: '#64748B'
  ice-white: '#F8FAFC'
  silver-border: '#E2E8F0'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
  stack-sm: 8px
  stack-md: 16px
---

## Brand & Style

This design system embodies the strength and precision of high-end construction and engineering. It is crafted for an established South African firm that balances traditional reliability with modern innovation. The aesthetic is **Corporate / Modern**, emphasizing architectural clarity, structural integrity, and premium service delivery.

The visual narrative is built on:
- **Precision Engineering:** A strict adherence to grid systems and geometric forms.
- **Corporate Authority:** A confident, high-contrast palette that evokes trust and scale.
- **Architectural Breathing Room:** Generous use of white space to symbolize clarity and professional organization.
- **Industrial Sophistication:** Subtle use of depth and refined borders to suggest quality craftsmanship.

## Colors

The palette is rooted in a deep, authoritative **Navy Blue** (Primary), symbolizing institutional stability and engineering expertise. A **Professional Red** (Secondary) is used strategically for calls to action and critical highlights, reflecting energy and South African vibrancy.

- **Primary (Navy):** Used for headlines, navigation backgrounds, and primary action buttons.
- **Secondary (Red):** Reserved for emphasis, key accents, and state indicators.
- **Neutral (Charcoal):** Applied to body text and icons for high legibility.
- **Surface Strategy:** Layouts should primarily use White and Ice-White backgrounds to maintain a "blueprint-clean" feel. Silver-border is used for defining structural divisions without adding visual clutter.

## Typography

Typography is used as a structural element. **Montserrat** provides a geometric, bold foundation for headlines, echoing the permanence of steel and concrete. **Inter** is used for body copy to ensure maximum readability and a technical, utilitarian efficiency.

- **Headlines:** Use Montserrat Bold. Headlines should feel "anchored" to the grid.
- **Body:** Use Inter for all long-form content. 
- **Utility:** Small caps with tracking (letter spacing) are used for category labels and secondary headers to evoke the feel of architectural technical drawings.
- **Mobile Scaling:** Display titles should scale down to 32px for mobile, while body text remains at 16px to maintain professional accessibility.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (12 columns) and a fluid model on mobile (4 columns). 

- **The Grid:** All elements must align to a strict 8px baseline grid to maintain engineering precision.
- **Margins:** Generous section gaps (80px+) are encouraged to separate service offerings and project case studies, allowing the "premium" nature of the brand to breathe.
- **Consistency:** Use fixed gutters of 24px to provide clear "lanes" of information.
- **Reflow:** On tablet, the 12-column grid transitions to 8 columns; on mobile, elements stack vertically with 16px margins.

## Elevation & Depth

Visual hierarchy is achieved through a mix of **Tonal Layers** and **Ambient Shadows**.

- **Surfaces:** Use "Ice-White" for cards sitting on a "White" background to create a subtle contrast.
- **Shadows:** Avoid heavy, black shadows. Use extremely soft, diffused Navy-tinted shadows (e.g., `rgba(22, 12, 80, 0.05)`) with a large blur radius (20px+) to create a "lifted" effect for cards.
- **Outlines:** Use 1px "Silver-border" for input fields and static containers to define boundaries without the weight of shadows.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the "edge" off the industrial nature of the business, making the brand feel modern and approachable while retaining the rigidity of a professional engineering firm. 

- **Standard Elements:** Buttons and input fields use 4px (0.25rem) radius.
- **Cards:** Large containers and cards use 8px (0.5rem) to signify they are distinct layout blocks.
- **Iconography:** Icons should follow the reference style—contained within circular enclosures with thick, professional strokes and a mix of the primary navy and secondary red accents.

## Components

### Buttons
- **Primary:** Solid Navy background, White Montserrat Bold text, 4px radius. 
- **Secondary:** Transparent with 2px Red border and Red text.
- **Hover States:** Primary buttons shift to a slightly lighter navy; Secondary buttons fill with a light red tint (10% opacity).

### Cards
- Use for project showcases and service descriptions.
- White background, 1px Silver-border, and a 24px padding.
- Include a subtle Navy shadow on hover to indicate interactivity.

### Input Fields
- 1px Silver-border, 12px vertical padding. 
- Label should use "label-caps" typography style positioned above the field.
- Active state: Border changes to Primary Navy.

### Iconography Style
- Draw from the reference images: Icons should be multi-tone (Navy/Gray/Red).
- Encased in a light gray circular stroke.
- Illustrations should be "simplified-technical"—showing tools, lightbulbs, or building materials with clean, vector lines.

### Lists & Tables
- Used for project specifications. 
- Clean horizontal dividers in Silver-border. 
- Alternating row highlights using Ice-White for readability.
