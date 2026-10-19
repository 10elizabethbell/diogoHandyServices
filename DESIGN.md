---
name: Diogo's Handy Services
description: A one-person handyman's navy wall, scuffed and holed, getting a fresh coat of his own logo blue.
colors:
  navy: "#0d2152"
  navy-deep: "#0a1a44"
  wall-old: "#15295a"
  royal: "#1d46b3"
  bright: "#2a7bff"
  gold: "#ffc21a"
  gold-deep: "#e0a400"
  gold-lift: "#ffd04d"
  primer: "#eef2fb"
  primer-ink: "#0d2152"
  primer-soft: "#3a4c7a"
  white: "#f5f8ff"
  paper: "#ffffff"
  mist: "#c9d5f2"
  line: "#7d8db5"
  roller-wire: "#c3cbdb"
  error: "#b3261e"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.75rem, 11.6vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8vw, 3.5rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  numeral:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "4.5rem"
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: "-0.04em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  row:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.1875rem"
    fontWeight: 800
    lineHeight: 1.3
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1
rounded:
  focus: "6px"
  field: "10px"
  button: "12px"
  panel: "14px"
  card: "18px"
  round: "50%"
spacing:
  gutter: "clamp(16px, 5vw, 64px)"
  band-top: "64px"
  band-bot: "84px"
  max: "1160px"
  chip-gap: "8px"
  action-gap: "12px"
  field-gap: "22px"
  block: "28px"
components:
  button-gold:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.navy}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "56px"
  button-gold-hover:
    backgroundColor: "{colors.gold-lift}"
    textColor: "{colors.navy}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "56px"
  button-plain:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.primer-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "48px"
  service-row:
    backgroundColor: "{colors.royal}"
    textColor: "{colors.white}"
    typography: "{typography.row}"
    padding: "10px 0"
    height: "64px"
  service-arrow-hover:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.navy}"
    rounded: "{rounded.round}"
    size: "44px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.primer-ink}"
    rounded: "{rounded.field}"
    padding: "8px 14px"
    height: "44px"
  chip-checked:
    backgroundColor: "{colors.royal}"
    textColor: "{colors.paper}"
  input-text:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.primer-ink}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  facebook-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.navy}"
    rounded: "{rounded.card}"
    padding: "18px 20px 18px 18px"
    height: "96px"
---

# Design System: Diogo's Handy Services

## Overview

**Creative North Star: "The Wall He's Fixing"**

The whole page is one wall in Diogo's logo colors, and you watch it get fixed. The hero is a scuffed old navy coat (hairline cracks, nail holes, low rub marks, one doorknob hole torn through the drywall), and a paint roller with a gold grip lays fresh royal blue over it. The fresh coat then turns into the page itself: each section is a solid band of paint, and the bands meet at ragged roller edges that a small roller lays left to right as you scroll to them. The colors come from his logo and flyer and nowhere else: navy ground, royal coat, primer white, logo gold.

Type is heavy, uppercase and tight, like the block caps in his logo. Everything is set in the system sans stack at weights 800 to 900. The page is built for a phone first: one column, thumb-sized targets (44px or more, 56px for primary actions), and the main action is always a text message with a photo attached. Elevation stays low. The real objects (the roller, the gold button, the Facebook card) cast soft shadows, and the bands are flat paint.

Motion means work being done. The roller paints, drips run down, the hole gets spackled over, and the old coat slowly shows through again so there is always something left to fix. Nothing moves just to look nice.

**Key Characteristics:**
- Full-bleed bands of solid color, in the order navy wall, royal, primer, navy, primer, navy-deep.
- Ragged roller-edge dividers with spatter dots, never straight lines or waves.
- Heavy uppercase system sans headings (900, line-height 0.98, negative tracking).
- Gold is the one action color. Bright blue marks interaction on primer surfaces.
- A canvas hero that is a real paint job: autoplay W strokes, visitor takeover, drips, a patch, fade-back.

## Colors

A cyclorama of the logo's own blues, with gold kept for the hand that works and the button you press.

### Primary
- **Logo Window Gold** (gold): the primary button fill, the roller grip, the call-icon tint, the second line of the hero headline, the closing promise line, the focus ring on dark bands, the selection highlight, and the hover state of service arrows. It always means "the thing you act with".
- **Grip Shadow Gold** (gold-deep): the darker under-stroke of the roller grip. Used only for depth on painted gold objects.
- **Lit Gold** (gold-lift): the hover fill of gold buttons.

### Secondary
- **Fresh Coat Royal** (royal): the paint the roller lays in the hero, and the background of the services band directly below it, so the paint becomes the section. Also the step numerals and step arrows on primer, the checked chip fill and the text caret.
- **Logo Bright Blue** (bright): the interaction color on light surfaces. Form controls get a bright border plus an outline on hover and focus, and focus rings on primer bands use it in place of gold.

### Neutral
- **Logo Navy** (navy): the ground of the logo. Used for the "See my work" band, ink on gold and white, and the hero text-shadow glow.
- **Deep Navy** (navy-deep): the page canvas, the closing band, the footer and the scrollbar track.
- **Old Wall Navy** (wall-old): the scuffed wall before it is painted. Used only for the hero wall and as the color under the first edge.
- **Primer White** (primer): the fresh white wall behind "How it works" and the quote form. It is also the surface for the composed message preview.
- **Primer Ink** (primer-ink) / **Primer Soft** (primer-soft): primary and secondary text on primer.
- **Cool White** (white): primary text on every blue band, and the Facebook card surface.
- **Paper** (paper): pure white for the inside of fields, chips, plain buttons and the sent panel, so controls sit a step brighter than the primer around them.
- **Mist** (mist): secondary text on blue (ledes, area line, footer).
- **Control Line** (line): the 2px resting border on fields, chips and the sent panel (3.3:1 on white).
- **Roller Wire** (roller-wire): the steel frame of every painted roller, in the canvas and in the edge rollers.
- **Error Red** (error): validation messages and the borders of invalid controls. Nothing else.

### Named Rules
**The Logo Palette Rule.** Every brand color comes from the logo or flyer: navy, royal, bright blue, gold, white. Add a new hue only when it is a material in the wall's world (gypsum, spackle, steel).

**The Gold Hand Rule.** Gold goes on the action and on the tool doing the work. It is never a band background or a decorative fill.

**The Paint Becomes Page Rule.** A band's color is the coat the roller just laid. Section backgrounds are flat, full-bleed tokens from the palette, and each one is introduced by an edge in its own color.

## Typography

**Display Font:** system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** a single family carries the whole page through weight alone. Headings at 900, uppercase, set tight like the logo's block caps, sit over plain 400 body copy.

### Hierarchy
- **Display** (900, clamp(2.75rem, 11.6vw, 6rem), 0.98, -0.03em, uppercase): the hero headline only. Its second line breaks onto its own line in gold.
- **Headline** (900, clamp(2rem, 8vw, 3.5rem), 0.98, -0.02em, uppercase, balanced wrap): section heads. The closing "Your home. My care." scales up to clamp(2.4rem, 10vw, 4.5rem).
- **Numeral** (900, 4.5rem, 0.8, -0.04em, royal): the big step numbers in "How it works".
- **Title** (900, 1.375rem, 1.1, -0.01em, uppercase): step titles.
- **Row** (800, 1.1875rem, 1.3): service list rows and the Facebook card line (900, up to 1.625rem there).
- **Body** (400, 17px, 1.55): running copy. Ledes are capped at 34em and the hero promise at 30em, at clamp(1.0625rem, 4.4vw, 1.25rem).
- **Label** (800, 1.0625rem, 1): buttons, form legends and labels, and the header phone number. "(optional)" drops to 500 in primer-soft.

### Named Rules
**The Weight Not Face Rule.** Hierarchy comes from weight (900, 800, 700, 400), case and size. Every role uses the same system stack.

**The Uppercase Is For Heads Rule.** Uppercase applies to h1, h2 and h3 only. Body, labels, buttons and rows stay in sentence case.

## Layout

The page is a stack of full-bleed bands. Content sits in a centered wrap (max 1160px plus side gutters of clamp(16px, 5vw, 64px)). Each band pads 64px at the top and 84px at the bottom. The extra 20px at the bottom leaves room for the next roller edge, which overlaps the band by 29px.

- **Phone (base):** one column. Hero actions are two full-width buttons (flex 1 1 220px, gap 12px). Steps run vertically with a 72px numeral column, joined by downward arrows. The hero wall reserves at least 170px of open wall under the copy for the roller.
- **700px:** the logo grows from 64px to 76px. Services split into two columns (gap 40px). Town and name fields sit side by side.
- **1024px:** the hero copy caps at 600px and the canvas painter works in the open area to its right. Steps lay out in one row of five tracks (step, arrow, step, arrow, step). "See my work" becomes a 1fr / 1.4fr split with the card beside the heading. The quote section becomes heading-left (sticky at 32px) and form-right (max 700px, gap 64px).
- **Short landscape (max-height 500px):** the display size drops to clamp(2.25rem, 12svh, 3.5rem) and the open wall shrinks to 80px.
- Vertical rhythm inside bands: 12px between heading and lede, 22px between form fields, 28px before a block (form, list, card), 8px between chips.

## Elevation & Depth

The bands are flat paint, and depth comes from the color order. Shadows belong only to physical things that would cast one on a wall: the roller, the gold button and the Facebook card. They are soft, dropped downward, navy-black, and never hard-offset. On the wall, a dark navy glow behind the hero copy keeps cracks and scuffs from cutting through the letters. It is a legibility device for the canvas, not decoration.

### Shadow Vocabulary
- **Button drop** (`box-shadow: 0 6px 16px -6px rgba(2,8,24,.5)`): gold buttons on dark bands. Removed on the in-form submit, which sits on primer.
- **Card lift** (`box-shadow: 0 14px 32px -16px rgba(0,0,0,.55)`): the Facebook card on navy.
- **Wall glow** (`text-shadow: 0 2px 22px #0d2152, 0 1px 4px rgba(13,33,82,.6)`): hero copy over the canvas only. The header phone number uses `0 2px 12px` navy.
- **Tool shadow** (canvas: blur 10 to 12, offsetY 5 to 6, rgba(2,8,24,.45 to .5)): the painted roller's frame and cover.

### Named Rules
**The Only Objects Cast Rule.** Something casts a shadow only if it would cast one in the real room. Bands, rows, chips and fields stay flat.

## Shapes

Corners are softly rounded, and the radius gets larger as the object gets bigger: 6px for focus rings, 10px for fields and chips, 12px for buttons and the Facebook icon tile, 14px for the sent panel, 18px for the Facebook card. Arrow buttons are full circles (44px). Controls rest on 2px borders. Dividers inside bands are 1px hairlines at 18% white, and the footer rule is 12% white.

The signature silhouette is the **roller edge**. It is a 30px SVG band in the next section's color. Its top is a jittery line (random walk between 9 and 21px, 3px steps, occasional spikes) with a scatter of 0.5 to 1.9px spatter dots above it. It is seeded per edge so it stays stable on resize. Straight section joins do not exist in this system.

## Components

### Buttons
Big, blunt and thumb-first.
- **Shape:** gently rounded (12px), 56px tall, 22px side padding, 2px border, a 22px icon with a 0.55em gap.
- **Gold (primary):** gold fill, navy label, button drop on dark bands. Hover lifts to Lit Gold. Press nudges down 1px. Inside the form it goes full width with no shadow, and hover or focus adds a 3px bright outline.
- **Line (secondary, dark bands):** transparent with an 85% white border and white label. Hover adds a 10% white wash and a full white border.
- **Plain (secondary, light surfaces):** paper fill, primer-ink label, line border. Hover and focus give a bright border plus a 3px bright outline. 48px tall in the sent panel.
- Transitions run 0.18s on color and border, 0.12s on the press transform.

### Service Rows
Each row texts Diogo about that one job.
- Full-width link, 64px minimum, 800 weight at 1.1875rem, between 1px hairlines (18% white), with a 44px circular arrow at the right end (14% white fill).
- **Hover / focus:** only the arrow changes. It fills gold with a navy glyph, and on focus a 3px gold ring sits around the arrow. The row gets no background, outline or shadow.

### Chips (job picker)
- **Style:** paper, 2px line border, 10px radius, 44px tall, 700 weight at 0.9688rem. The check glyph is hidden at rest.
- **Checked:** royal paint rolls across the chip left to right (background-size 0 to 100%, 0.28s cubic-bezier(.22,.8,.3,1)), the border goes royal, the text goes white, and a check appears.
- **Hover:** bright border plus a 2px bright outline. **Focus:** a 3px bright outline at a 2px offset.
- **Error:** the border turns error red.

### Inputs / Fields
- **Style:** paper fill, 2px line border, 10px radius, 13px by 14px padding, 52px minimum (textarea 110px, vertical resize), 500 weight at 1.0625rem, royal caret, placeholder #5d6b8f.
- **Hover:** bright border plus a 2px bright outline. **Focus:** bright border plus a 3px bright outline.
- **Error:** a red border with a 700-weight red message below.
- Labels are 800 weight at 1.0625rem, sitting 10px above the field.

### Facebook Card
The single route to his work, placed under "See my work".
- White surface, 18px radius, card lift, 96px minimum (120px on desktop). It holds a 56px Facebook-blue icon tile (12px radius, Facebook's own mark color), a 900-weight line with a 600-weight primer-soft subline, and a primer circle arrow.
- **Hover:** lifts 2px (0.15s) and the arrow fills gold.

### Navigation
There is no menu. The header is the logo at the left (64px, 76px from 700px) and the phone number at the right (800 weight, gold phone icon, 48px target, underline on hover). It scrolls away with the wall. The footer repeats the phone number and Facebook as 700-weight white links (44px targets) next to the copyright, in mist.

### The Wall (signature canvas)
The hero background is a 2D canvas, seeded so it looks the same on every load.
- **Old coat:** wall-old with 70 soft light and dark blotches, per-pixel noise, branching hairline cracks (a dark stroke with a lit edge), low rub-mark scuffs, nail holes, and one doorknob hole (jagged gypsum break, dark cavity, torn paper flaps, crumbs and dust). All of it keeps clear of the header and hero copy, with a 14px margin.
- **Fresh coat:** royal with gentle stipple, revealed through a mask built from roller stamps (alpha 0.5 per pass, so coats build up, with ragged nap ends and a thinner stamp once the roller runs dry).
- **Painter:** autoplay starts almost at once. It rolls a W over the hole, then vertical fill strokes, with smoothstep stroke ends and a springy wrist (spring 38, damp 6.5). Speed is 300px/s on phones and 430px/s on desktop. The roller stays nearly level (within about 0.45rad), then rests at the side for 4s between patches.
- **Takeover:** mouse hover rolls on desktop (it hands back after 2.6s of rest), and a finger drag on open wall rolls on phones. Touches that start on the copy or controls scroll as usual.
- **Patch:** once the paint covers the hole past 30%, the hole crossfades to dried spackle (#2c4580, putty-knife drag lines, a knife ridge) under the coat.
- **Drips:** only a loaded roller drips (up to 14 at a time). Drips slow down and end in a bead.
- **Fade-back:** after 5s idle, while the painter is resting, the old coat shows through again in uneven blotches (never as an even dissolve). The hole comes back once the cover drops below 12%.
- **The roller:** a roller-wire frame, a gold grip with a gold-deep under-stroke, and a royal nap cylinder (gradient #3d68d6 to #122f80) whose stipple turns as it rolls. Cover length is 74px on phones and 104px on desktop.
- **Budget:** DPR is capped at 1.25 on coarse pointers and 1.5 elsewhere. The loop pauses off screen. Resizes that keep the same size are ignored, so the paint survives the phone address bar moving.

### Roller Edges (section dividers)
- Each edge is an SVG ragged band in the color of the section below it, revealed by `clip-path` from left to right over 1.25s with cubic-bezier(.22,.8,.3,1) once it is 12% into the viewport, one time only.
- A small SVG roller (wire, gold grip, cover in the edge's color) rides along the paint front. Where the browser supports `@property`, it is tied to the paint front through a registered `--p`. Otherwise it runs a matching keyframe. It fades out at the right edge.

## Do's and Don'ts

### Do:
- **Do** keep the system font stack for every role. This is a house rule: no webfonts.
- **Do** put the phone number only at the top right of the header (and repeat it in the footer). It scrolls away with the page.
- **Do** keep the Facebook link under "See my work" as the single route to his work, with the footer link as the only repeat.
- **Do** change only the arrow (gold fill, navy glyph) when a service row is hovered or focused.
- **Do** outline form controls (fields, chips, plain and in-form buttons) in bright on hover and focus: a 2px outline on hover and 3px on focus, plus a bright border.
- **Do** join every pair of bands with a roller edge in the incoming band's color, laid left to right as it scrolls into view.
- **Do** make gold mean action: the primary text button, the arrow you are about to tap, the grip of the tool.
- **Do** keep tap targets at 44px or more, and 56px for primary buttons.
- **Do** honor reduced motion: no transitions or animations, edges shown already painted with no roller, and a still wall that only paints under the visitor's own hand.

### Don't:
- **Don't** add a sticky or fixed contact bar, or a floating call button.
- **Don't** add an email address or a mailto link anywhere.
- **Don't** give service rows a hover background, row outline, underline or shadow.
- **Don't** use straight rules, waves or diagonal cuts between bands.
- **Don't** use gold as a band background or a large decorative fill.
- **Don't** put hard offset shadows or shadows on flat elements (bands, rows, chips, fields).
- **Don't** add motion that is not a paint or repair action happening on the wall.
- **Don't** set body, labels or buttons in uppercase.
