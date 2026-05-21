---
name: Lionia
description: AI training and custom agents for French SMEs. Cream-paper authority for an AI advisory.
colors:
  parchment-cream: "#faf9f5"
  stone-linen: "#f0ede4"
  plain-white: "#ffffff"
  ink: "#1a1a1a"
  soft-ink: "#3d3935"
  stone: "#6b6561"
  pale-stone: "#9a9590"
  burnt-amber: "#c47a3a"
  light-amber: "#d4935e"
  hairline: "rgba(26, 26, 26, 0.08)"
  hairline-strong: "rgba(26, 26, 26, 0.12)"
  amber-wash: "rgba(196, 122, 58, 0.08)"
  amber-glow: "rgba(196, 122, 58, 0.15)"
typography:
  display:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "clamp(2.5rem, 2rem + 2.5vw, 4.5rem)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "clamp(2rem, 1.6rem + 2vw, 3.25rem)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  title:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "clamp(1.25rem, 1.1rem + 0.75vw, 1.75rem)"
    fontWeight: 500
    lineHeight: 1.15
    letterSpacing: "normal"
  subtitle:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "clamp(1.1rem, 1rem + 0.5vw, 1.35rem)"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  body:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "clamp(1rem, 0.95rem + 0.25vw, 1.125rem)"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  label:
    fontFamily: "'Space Grotesk', Arial, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "0.12em"
  mono:
    fontFamily: "'Space Mono', ui-monospace, Menlo, monospace"
    fontSize: "1.125rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0"
rounded:
  flat: "4px"
  soft: "8px"
  card: "12px"
  pill: "100px"
  circle: "50%"
spacing:
  xs: "0.5rem"
  sm: "0.75rem"
  md: "1rem"
  lg: "1.5rem"
  xl: "2rem"
  xxl: "clamp(4rem, 3rem + 5vw, 8rem)"
  gutter: "clamp(1rem, 0.5rem + 2vw, 2rem)"
components:
  button-primary:
    backgroundColor: "{colors.burnt-amber}"
    textColor: "{colors.plain-white}"
    typography: "{typography.body}"
    rounded: "{rounded.flat}"
    padding: "clamp(0.75rem, 0.5rem + 0.5vw, 1rem) clamp(1.25rem, 1rem + 1vw, 2rem)"
  button-primary-hover:
    backgroundColor: "{colors.light-amber}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.flat}"
    padding: "0.75rem 1.5rem"
  button-outline-hover:
    backgroundColor: "{colors.parchment-cream}"
    textColor: "{colors.ink}"
  card-soft:
    backgroundColor: "{colors.plain-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "2rem"
  card-offer:
    backgroundColor: "{colors.parchment-cream}"
    textColor: "{colors.ink}"
    rounded: "{rounded.soft}"
    padding: "clamp(1.5rem, 1rem + 2vw, 2.5rem)"
  tag-eyebrow:
    backgroundColor: "{colors.amber-wash}"
    textColor: "{colors.burnt-amber}"
    typography: "{typography.label}"
    rounded: "{rounded.flat}"
    padding: "0.25rem 0.75rem"
  section-label:
    backgroundColor: "transparent"
    textColor: "{colors.burnt-amber}"
    typography: "{typography.label}"
    padding: "0"
---

# Design System: Lionia

## 1. Overview

**Creative North Star: "Le studio méthodique"**

Lionia is built like a methodical studio: precision applied to warmth, not warmth applied to precision. The surface is parchment cream, not screen white. The text is ink, not pure black. The accent is burnt amber, not optimistic orange. Everything has been picked to read as "considered" before it reads as "designed". A French SME director arriving from a LinkedIn link should feel they've opened a careful document, not a tech-startup landing page.

The system commits to a single hue family (warm earth tones across the entire surface) and lets typography carry hierarchy. Heading weight contrast, generous line-height, and uppercase tracked labels do the structural work. Shadows are broad and ambient, never tight or theatrical. Hovers move 2px, not 8. Buttons translate, never bounce.

What this system explicitly rejects: gradient-on-black AI startup aesthetics, navy-and-gold cabinet de conseil rigidity, infopreneur neon highlights and oversized CTAs. None of those vocabularies appear here. The page must read like the deliverable a Lionia client would actually receive.

**Key Characteristics:**
- Parchment cream surface (`#faf9f5`) as the canvas; near-black ink (`#1a1a1a`) for text; burnt amber (`#c47a3a`) as the singular accent
- Space Grotesk across the entire system (weights 400–700), Space Mono reserved for the logo and key meta moments
- Sharp small radii: `4px` on buttons, `8px` on offer cards, `12px` on signature cards. No `border-radius: 1rem` softness.
- Broad ambient shadows, low opacity (0.04–0.08). Amber-tinted shadows reserved for amber elements (`rgba(196, 122, 58, 0.25)` under the CTA).
- Uppercase tracked labels (`0.12em` letter-spacing) on section eyebrows; never as decoration, always to mark a structural break.
- Hover language: `translateY(-2px)` on buttons, `translateY(-4px)` on offer cards, `translateX(3px)` on inline arrow icons. Quiet, consistent, predictable.

## 2. Colors

A single hue family carried across the entire system: warm earth tones with one committed accent. Restraint with conviction, not absence.

### Primary
- **Burnt Amber** (`#c47a3a`): The only accent. Used on primary CTAs, section eyebrow labels, key inline emphasis, hover state revelations on offer cards, and amber-tinted shadows under amber elements. The accent rate is low by design.
- **Light Amber** (`#d4935e`): Hover state for primary buttons only.

### Neutral
- **Parchment Cream** (`#faf9f5`): The page surface. The canvas on which everything else sits. Used as the default `body` background and on offer cards (which sit on a white section to invert).
- **Stone Linen** (`#f0ede4`): Secondary cream for layered surfaces when one cream is not enough. Used sparingly.
- **Plain White** (`#ffffff`): Reserved for elevated cards (hero card, founder card, format cards) that need to lift off the cream surface. White is a tool here, not the default.
- **Ink** (`#1a1a1a`): Primary text. Near-black with a faint warm tilt that keeps it from feeling clinical against the cream.
- **Soft Ink** (`#3d3935`): Body emphasis, slightly relaxed from full ink.
- **Stone** (`#6b6561`): Muted body text, subtitles, nav links at rest.
- **Pale Stone** (`#9a9590`): Quietest text, captions, meta.
- **Hairline** (`rgba(26, 26, 26, 0.08)`): Default borders on cards and inputs.
- **Hairline Strong** (`rgba(26, 26, 26, 0.12)`): Borders on interactive outline elements.

### Tints
- **Amber Wash** (`rgba(196, 122, 58, 0.08)`): Background for eyebrow tags and quiet amber moments.
- **Amber Glow** (`rgba(196, 122, 58, 0.15)`): Selection background; faint amber halos.

### Named Rules

**The One Hue Rule.** Lionia commits to a single warm hue family across the entire surface. No secondary accent color is introduced. Status colors (success green, error red) appear only when a real status exists, never as decoration. Prohibited: introducing blue, purple, teal, or any color outside the cream/ink/amber family for visual variety.

**The Sparse Amber Rule.** Burnt amber is the only accent and must cover ≤10% of any given screen. Its rarity is the point. Prohibited: full-amber sections, amber backgrounds on large surfaces, amber as anything other than ink emphasis or CTA fill.

**The No-Pure-Black Rule.** Text is ink (`#1a1a1a`), not `#000`. The faint warmth keeps the page coherent with the cream surface. Pure black breaks the warmth and reads as sharper than this system wants to read.

## 3. Typography

**Display Font:** Space Grotesk (with Arial fallback)
**Body Font:** Space Grotesk (single-family commitment)
**Mono Font:** Space Mono (with `ui-monospace`, Menlo fallback). Reserved for the logo and rare meta moments.

**Character:** A single sans across the entire system, treated like a typeface specimen would treat one face: weight contrast and size contrast do the work. Space Grotesk earns its place through its geometric clarity at display sizes and its readable warmth at body sizes. Space Mono appears once in the logo and stays mostly out of sight; when it does appear, it functions as a typographic margin annotation, not as decoration.

### Hierarchy

- **Display** (weight 600, `clamp(2.5rem, 2rem + 2.5vw, 4.5rem)`, line-height 1.15, letter-spacing -0.03em): The hero headline. One per page, used to deliver the proposition de valeur. Tight negative letter-spacing tightens the form at large sizes.
- **Headline** (weight 600, `clamp(2rem, 1.6rem + 2vw, 3.25rem)`, line-height 1.15, letter-spacing -0.02em): Section openings. Marks structural breaks in the page narrative.
- **Title** (weight 500, `clamp(1.25rem, 1.1rem + 0.75vw, 1.75rem)`, line-height 1.15): Offer card headings, sub-section titles. Lighter weight than display/headline to signal a step down in hierarchy.
- **Subtitle** (weight 400, `clamp(1.1rem, 1rem + 0.5vw, 1.35rem)`, line-height 1.6, color stone): The supporting line that follows a headline. Sits in stone (`#6b6561`) to recede from the ink heading above.
- **Body** (weight 400, `clamp(1rem, 0.95rem + 0.25vw, 1.125rem)`, line-height 1.65): Prose. Capped at 65–75ch for readability. Line-height is generous (1.65) to feel like paper, not screen.
- **Label** (weight 600, `0.8125rem`, letter-spacing 0.12em, uppercase, color burnt amber): The section eyebrow. Marks the structural break of a new section. The amber color signals "Lionia voice" without taking up visual mass.

### Named Rules

**The Single-Family Rule.** Space Grotesk carries the entire system. No serif display face, no secondary sans. Voice comes from weight contrast (500/600 vs. 400) and size contrast (≥1.25 step), not from family mixing. Space Mono is permitted only on the logo and on rare mono-marked metadata; it is not a body-text alternative.

**The Eyebrow Rule.** Uppercase tracked labels mark the start of a new section once, in burnt amber, at `0.8125rem` and `0.12em` letter-spacing. They are not decoration. They are not repeated within a section. They are not used in body copy.

**The Tight-Display Rule.** Display and headline type carry negative letter-spacing (`-0.02em` to `-0.03em`). Body and subtitle type do not. Tight tracking at scale, normal tracking at reading size.

## 4. Elevation

Lionia is a lifted-ambient system: surfaces never feel pressed against the page, but the lift is diffuse and almost dreamlike, never theatrical. Shadows are always broad, always low-opacity (0.04–0.08), always cast straight down. There are no tight 4px-blur drop shadows. Depth reads as light falling on cream paper, not as elements floating above a UI canvas.

Amber-tinted shadows are reserved for amber elements (the primary CTA, accent moments). Black shadows are for everything else. Mixing them breaks the system.

### Shadow Vocabulary

- **Ambient Soft** (`box-shadow: 0 8px 32px rgba(0, 0, 0, 0.04)`): Default lift for cards on a cream section. Diffuse, barely perceptible.
- **Ambient Medium** (`box-shadow: 0 16px 64px rgba(0, 0, 0, 0.06)`): Standard card elevation. The default for offer cards and feature cards.
- **Ambient High** (`box-shadow: 0 24px 80px rgba(0, 0, 0, 0.06)`): Hero card and founder card. Broadest cast, deepest reach, still under 10% opacity.
- **Amber CTA Rest** (`box-shadow: 0 4px 20px rgba(196, 122, 58, 0.25)`): The default shadow under the primary amber button. Tinted amber, not black.
- **Amber CTA Hover** (`box-shadow: 0 6px 30px rgba(196, 122, 58, 0.35)`): Lifts on hover. Slightly deeper, slightly wider, slightly more saturated.
- **Amber Reveal** (`box-shadow: 0 16px 64px rgba(196, 122, 58, 0.08)`): Cast on offer cards when they're hovered. The amber `::before` top-bar scales in, the amber-tinted shadow blooms.
- **Nav Hairline** (`box-shadow: 0 1px 0 rgba(26, 26, 26, 0.08)`): A single-pixel divider under the scrolled nav. Functionally a border, written as a shadow for the layout reason.

### Named Rules

**The Broad-Diffuse Rule.** Every shadow is wider than it is tall (typical: 64–80px blur for 16–24px y-offset). Tight 4px-blur drop shadows are prohibited; they read as 2014-era card UI, not 2026 considered surface.

**The Tinted-Shadow Rule.** Amber-tinted shadows appear only under amber elements. Cards, surfaces, and neutral elements always cast neutral shadows. Mixing breaks the "ambient light on paper" mental model.

## 5. Components

### Buttons

**Character:** Quietly confident, never decorative. Buttons declare action through color, weight, and a single 2px translate on hover. No bounces, no scales, no rotations.

- **Primary (`.btn-primary`):** Burnt amber (`#c47a3a`) fill, white text, `4px` radius, `clamp(0.75rem, 0.5rem + 0.5vw, 1rem) clamp(1.25rem, 1rem + 1vw, 2rem)` padding, weight 500, amber-tinted shadow at rest. Inline-flex with an arrow SVG that nudges `translateX(3px)` on hover.
- **Primary Hover:** Background shifts to Light Amber (`#d4935e`), button lifts `translateY(-2px)`, shadow deepens to `0 6px 30px rgba(196, 122, 58, 0.35)`.
- **Outline (`.btn-outline`):** Transparent fill, `1.5px solid rgba(26, 26, 26, 0.12)` border, ink text, `4px` radius, weight 500. Used when the primary CTA is also on screen and an outline alternative is needed.
- **Outline Hover:** Background fills to parchment cream, border tightens to soft ink.
- **Final CTA Variant:** The hero CTA and footer CTA carry slightly larger padding (`clamp(0.875rem, 0.75rem + 0.5vw, 1.125rem)` × `clamp(1.5rem, 1.25rem + 1vw, 2.5rem)`) and a hair-larger font (`clamp(0.9375rem, 0.9rem + 0.2vw, 1.0625rem)`). Same shape, more presence.

### Cards

**Character:** Cards exist to group meaning, never as visual variety. Use them only when the content is genuinely a discrete unit (an offer, a founder bio, a format).

- **Soft Card (hero, founder):** Plain white background, `12px` radius (hero) or `10px` (founder), `1px solid hairline` border, `2rem` padding, Ambient High shadow.
- **Offer Card:** Parchment cream background (sits on a white section), `8px` radius, `1px solid hairline` border, `clamp(1.5rem, 1rem + 2vw, 2.5rem)` padding, no resting shadow.
  - **Offer Card Hover:** A `3px` amber `::before` bar scales in (`transform: scaleX(0) → scaleX(1)`) along the top edge, the card lifts `translateY(-4px)`, the border tints to `rgba(196, 122, 58, 0.2)`, and an Amber Reveal shadow blooms underneath.
- **Format / Feature Card:** Plain white background, `8px` radius, `1px solid hairline` border, `1.5rem`+ padding, Ambient Soft to Ambient Medium shadow depending on context.

### Tags and Eyebrows

- **Eyebrow Tag (`.offer-tag`):** Amber Wash (`rgba(196, 122, 58, 0.08)`) background, burnt amber text, `4px` radius, `0.25rem 0.75rem` padding, `0.75rem` font, weight 600, uppercase, `0.08em` letter-spacing. Sits on top of an offer card as a "Point de départ" / "Montée en compétence" / "Automatisation" label.
- **Section Label (`.section-label`):** Transparent background, burnt amber text, `0.8125rem`, weight 600, uppercase, `0.12em` letter-spacing. Appears once at the start of each section. Distinct from the eyebrow tag (which lives inside cards).

### Navigation

- **Style:** Fixed top, transparent at rest, transitions to `rgba(250, 249, 245, 0.85)` cream with `backdrop-filter: blur(20px)` on scroll. Single `1px` ink-hairline divider under the scrolled state.
- **Logo:** Space Mono, weight 700, `1.125rem`, uppercase, ink color with a burnt amber span on the brand mark.
- **Links:** `0.875rem`, stone color at rest, ink on hover (`transition: color 0.2s ease`).
- **Mobile:** Mega-menu opens; primary CTAs in the nav stretch to full width.

### Hero Pattern

The hero is not a card but a typographic event: large display headline (clamp up to 4.5rem), stone subtitle below, a single primary CTA with micro-copy ("Gratuit · 30 min · Sans engagement"), and an optional eyebrow label above. No background image, no decorative SVG behind the text. The page surface (parchment cream) carries the weight; the type does the rest.

### Named Rules

**The Two-Pixel Rule.** Hover lifts are always `translateY(-2px)` on buttons, `translateY(-4px)` on cards. Never more. Never less. The consistency is the system.

**The One-CTA-Color Rule.** Only the burnt amber `.btn-primary` exists as a filled button. Outline buttons are the only other variant. Prohibited: secondary filled buttons in any other color, ghost buttons with colored borders, gradient fills.

## 6. Do's and Don'ts

### Do:

- **Do** use Parchment Cream (`#faf9f5`) as the default page surface. White (`#ffffff`) is reserved for elevated cards that need to lift.
- **Do** keep burnt amber rare. ≤10% of any screen. If more than one amber-filled element appears on screen at the same time, demote one to ink.
- **Do** use Space Grotesk across the entire system. Voice comes from weight contrast (400 vs. 500 vs. 600) and size contrast, never from family mixing.
- **Do** cast broad ambient shadows (64–80px blur, ≤8% opacity) under cards. Tinted amber shadows under amber elements only.
- **Do** hover with `translateY(-2px)` on buttons and `translateY(-4px)` on cards. Match the system, don't invent new physics.
- **Do** lead each section with a single uppercase tracked burnt amber label (`section-label`). Use it once, then don't repeat inside the section.
- **Do** keep body line length within 65–75ch. Use `container--narrow` (`min(800px, ...)`) for prose sections.
- **Do** write copy like the LANDING_PAGE.md voice guide: direct, confident, concrete. "30 jours", "2-3 jours d'audit", "rapport priorisé" beats "transformation digitale".

### Don't:

- **Don't** introduce a second accent color. No blue, no teal, no purple, no green for "variety". One hue family across the entire system. This rules out the **generic AI startup aesthetic** (gradient violet/cyan, neon-on-black, dark mode by default) called out in PRODUCT.md.
- **Don't** drop into the **cabinet de conseil français rigide** (PRODUCT.md anti-reference). No navy-and-gold. No serif corporate. No stock-photo handshake. Lionia is moderne, not vieille école.
- **Don't** ship **growth-hacker marketing** moves (PRODUCT.md anti-reference): no oversized neon CTAs, no urgency banners ("Plus que 2 places !"), no fluorescent highlights, no testimonial carousels.
- **Don't** use `#000` or `#fff` for text or background. Text is Ink (`#1a1a1a`); surfaces are Parchment Cream or Plain White, both tinted toward warm. Pure black breaks the warmth.
- **Don't** use border-radius greater than `12px` on functional elements. Lionia is sharp-soft, not pillowy.
- **Don't** use `border-left` greater than 1px as a colored stripe accent. Forbidden across the system. Use full borders, background tints, or numbered leaders instead.
- **Don't** use gradient text (`background-clip: text`). Emphasis comes from weight, size, or color, never from a gradient mask.
- **Don't** stack tight drop shadows (`0 2px 4px rgba(0,0,0,0.2)`). All shadows are broad and diffuse. Tight shadows read as 2014 card UI.
- **Don't** use Space Mono for body copy. It is the logo face and an occasional metadata mark. Never paragraphs.
- **Don't** repeat the uppercase tracked label inside a section as decoration. Once per section, at the start, then no more.
- **Don't** introduce additional shadow recipes. The vocabulary in §4 is closed; if a new use case appears, pick the nearest existing recipe rather than inventing.
- **Don't** wrap every section in a card. Most sections are typographic events on the open cream surface. Cards are reserved for offers, founder, and format groupings.
