---
name: Clinical Vitality
colors:
  surface: '#f7f9ff'
  surface-dim: '#c4ddf6'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ecf4ff'
  surface-container: '#e2efff'
  surface-container-high: '#d7eaff'
  surface-container-highest: '#cde5ff'
  on-surface: '#021d30'
  on-surface-variant: '#3f4851'
  inverse-surface: '#1a3246'
  inverse-on-surface: '#e7f2ff'
  outline: '#6f7882'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bba'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#006e2d'
  on-secondary: '#ffffff'
  secondary-container: '#7cf994'
  on-secondary-container: '#007230'
  tertiary: '#006194'
  on-tertiary: '#ffffff'
  tertiary-container: '#007bb9'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#7ffc97'
  secondary-fixed-dim: '#62df7d'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005320'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f7f9ff'
  on-background: '#021d30'
  surface-variant: '#cde5ff'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an environment of clinical precision, accessibility, and reassuring care for everyday healthcare commerce. Balancing institutional medical authority with patient-first warmth, the interface communicates reliability, cleanliness, and swift access to vital medications and wellness services. 

The aesthetic is Modern Clinical Minimalist with functional tactile elements. It relies on pristine slate surfaces, luminous cyan and vital green accents derived from pharmacy cross and botanical motifs, and crystal-clear typographic hierarchy. Surfaces convey sterility without coldness, employing balanced whitespace and soft borders that inspire immediate confidence during critical prescription and health transactions.

## Colors

The palette directly reflects modern clinical trust, vitality, and regulatory clarity:

- **Primary (`#0090D9`)**: Azure medical cyan, used for core calls-to-action, navigation anchors, active state highlights, and digital prescription workflows.
- **Secondary (`#16A34A`)**: Vital leaf green, signaling safety, authentic pharmacy verification badges, positive stock statuses, discounts, and preventive wellness.
- **Tertiary (`#0284C7`)**: Deep clinical azure, utilized for interactive hover layers, information ribbons, and focused component framing.
- **Neutral (`#0B2538`)**: Deep slate navy, replacing harsh blacks with a dignified, high-legibility tone for headlines, body copy, and structured container outlines.

Surface backgrounds prioritize optical hygiene: pure white (`#FFFFFF`) for elevated cards and prescription slips, grounded over clinical slate tint (`#F8FAFC` to `#F1F5F9`) for main page backdrops. Error states employ `#DC2626` (clinical red), while warning tags use `#D97706` (amber).

## Typography

The design system standardizes on **Plus Jakarta Sans** across all levels. Its balanced geometric proportions and friendly, sculpted terminals provide human warmth while preserving strict typographic readability needed for medical dosages, active ingredients, and regulatory warnings.

- **Headlines**: Set in Bold (`700`) and Extra Bold (`800`) to anchor pharmacy departments, store locations, and service hubs.
- **Body**: Regular (`400`) with generous line-heights for strain-free reading of contraindications, usage directions, and patient instructions.
- **Labels & Badges**: SemiBold (`600`) and Bold (`700`) with slight tabular alignment when showing prices, milligrams, and prescription statuses (e.g., `Rx REQUIRED`).

## Layout & Spacing

A 12-column responsive fluid grid governs page composition on desktop screens, collapsing to 8 columns on tablet devices and 4 columns on mobile viewports.

- **Desktop (1024px+)**: Page margins set at `2rem`, gutters at `1.25rem`. Content container max width is constrained to `1280px` to maintain optimal optical scan paths for multi-column medicine listings.
- **Tablet (768px - 1023px)**: Gutters scale to `1rem`, page margins reduce to `1.5rem`.
- **Mobile (<768px)**: Fast thumb zones dictate interactions. Canvas margins contract to `1rem`, gutters tighten to `0.75rem`. Critical interactions (Upload Prescription, Refill Rx, Call Pharmacist) lock to fixed bottom-docked application bars.
- **Vertical Rhythm**: Built upon a strict 4px / 8px incremental scale ensuring consistent baseline alignment between dosage microcopy, counter steppers, and pill card containers.

## Elevation & Depth

Visual hierarchy adopts a layered clinical surface approach utilizing low-contrast borders combined with ultra-diffuse ambient shadows:

- **Level 0 (Flat / Canvas)**: Baseline surface `#F8FAFC`. Zero elevation, seamlessly integrating neutral divider lines (`#E2E8F0`).
- **Level 1 (Card & Tile Default)**: Pure white `#FFFFFF` surface bordered with a 1px crisp outline in `#E2E8F0` and an ambient shadow `0 1px 3px rgba(11, 37, 56, 0.04), 0 1px 2px rgba(11, 37, 56, 0.02)`.
- **Level 2 (Active Dropdowns & Interactive Cards)**: Elevated white surface with `0 4px 12px rgba(11, 37, 56, 0.08)`. Used for medicine search auto-suggest, cart flyouts, and floating prescription status chips.
- **Level 3 (Modals & Prescription Review Sheets)**: Elevated surface with `0 20px 32px -4px rgba(11, 37, 56, 0.16)`. Accompanied by a 30% deep slate navy backdrop blur (`rgba(11, 37, 56, 0.45)` with `backdrop-filter: blur(4px)`).

## Shapes

The system implements a balanced `Rounded` (Level 2) geometry:

- **Standard Elements (0.5rem / 8px)**: Applied to product cards, text inputs, prescription file dropzones, and table containers, reflecting structural hygiene.
- **Large Containers (1rem / 16px)**: Applied to banner modules, consultation booking cards, and modal dialogs.
- **Capsule / Pill Radii (`9999px`)**: Reserved exclusively for medical metadata chips, stock indicators (`In Stock`), dosage tags (`500 mg`), search query pills, and primary prescription action buttons. This reinforces the physical pill metaphor native to pharmacy branding.

## Components

### Buttons
- **Primary Prescription Button**: Solid medical cyan (`#0090D9`) background, `#FFFFFF` text, `font-weight: 600`, pill-shaped or `0.5rem` rounded corners. Hover transitions to tertiary `#0284C7`. Contains an optional leading pharmacy cross or upload icon.
- **Secondary / Refill Action**: Tinted background (`rgba(0, 144, 217, 0.08)`), text `#0090D9`, with an active border in `#0090D9`.
- **Success / Verified Consultation**: Solid healthcare green (`#16A34A`) background with white typography for verified orders and WhatsApp/Pharmacist connect actions.

### Pharmacy Badges & Health Service Tags
- **Rx Prescription Required**: Bordered capsule pill with light red background (`#FEF2F2`), red text (`#B91C1C`), and a bold `Rx` symbol prefix.
- **Authenticity Verified**: High-visibility soft green badge (`#DCFCE7`) with deep green text (`#15803D`) and a checkmark shield icon.
- **Health Category Tags**: Soft azure background (`#E0F2FE`), text `#0369A1`, padding `4px 12px`, uppercase font weight 700 at 10px.

### Cards & Product Listings
- **Medicine Item Card**: White surface, 1px border `#E2E8F0`, rounded-lg corners. Header displays medicine strength, generic formula name in muted slate, retail price with savings tag, and an instant "Add / Upload Rx" pill button.
- **Service Banner Card**: Cyan to navy subtle radial background gradient with high-contrast white text for diagnostic lab tests and home delivery guarantees.

### Inputs & Prescription Uploaders
- **Text Inputs**: Crisp `#FFFFFF` surface with `#CBD5E1` border, 0.5rem radius, and navy `#0B2538` typography. Focus state elevates with a 2px ring in primary cyan `#0090D9`.
- **File Drag & Drop (Rx Slip)**: Dashed 2px cyan border (`#0090D9`) over a delicate `#F0F9FF` surface, with instant file-type preview badges (PDF, JPG, Camera capture).

### Selection Controls
- **Checkboxes & Radios**: Primary cyan fill on active selection with an internal white medical check. Unchecked state presents a clean 1.5px `#94A3B8` border over a `#FFFFFF` fill.