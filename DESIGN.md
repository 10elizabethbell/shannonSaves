---
name: ShannonSaves
description: Afternoon sun in a clean room. A one-person home cleaner's page in her flyer's navy, lime and cream.
colors:
  navy: "#0e3b66"
  navy-deep: "#0a2c4f"
  navy-ink: "#0b2a49"
  cream: "#f7f0d9"
  cream-soft: "#fbf7ea"
  lime: "#a6ec6c"
  lime-hi: "#c2f593"
  focus-blue: "#2b78d8"
  muted-on-cream: "#3d5672"
  muted-on-navy: "#c4d2e2"
  line: "rgba(11, 42, 73, .14)"
  paper-white: "#ffffff"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.3rem, 10.6vw, 5.4rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8.6vw, 3.5rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 26px)"
    fontWeight: 800
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.4vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.01em"
  hint:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
  wordmark:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
rounded:
  pill: "999px"
  card: "18px"
  field: "14px"
  focus: "6px"
  circle: "50%"
spacing:
  gutter-phone: "20px"
  gutter-wide: "32px"
  stack-sm: "12px"
  stack-md: "20px"
  stack-lg: "26px"
  section-phone: "64px"
  section-desk: "104px"
  touch-min: "44px"
components:
  button-lime:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.navy-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-lime-hover:
    backgroundColor: "{colors.lime-hi}"
    textColor: "{colors.navy-ink}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-navy:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-navy-hover:
    backgroundColor: "{colors.navy-deep}"
    textColor: "{colors.cream}"
  button-facebook:
    backgroundColor: "rgba(247,240,217,.08)"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-facebook-hover:
    backgroundColor: "{colors.lime}"
    textColor: "{colors.navy-ink}"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.navy-ink}"
    typography: "{typography.title}"
    padding: "14px 0"
    height: "76px"
  service-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.navy}"
    rounded: "{rounded.circle}"
    size: "46px"
  service-arrow-hover:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.lime}"
    rounded: "{rounded.circle}"
    size: "46px"
  step-number:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.lime}"
    rounded: "{rounded.circle}"
    size: "46px"
  input:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.navy-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "54px"
  chip:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.navy-ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.cream}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  portrait:
    backgroundColor: "{colors.navy}"
    rounded: "{rounded.circle}"
    size: "176px"
  notice-card:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.navy-ink}"
    rounded: "{rounded.card}"
    padding: "18px"
---

# Design System: ShannonSaves

## Overview

**Creative North Star: "Afternoon Sun in a Clean Room"**

The page is a quiet navy room with low afternoon sun coming through a four-pane window, the moment a house feels clean. Everything comes from the owner's own flyer: its navy ground is the room, its cream ring is the window light, its lime lettering is the type and the call to action, and its pale dots became dust drifting in the sunbeam. Visitors can wave a finger or mouse through the light to wipe the dust out of it, and it slowly drifts back in. That is the reason bi-weekly upkeep exists, told without a word of copy.

The system alternates two kinds of room. Navy "rooms" carry the sunbeam and its dust. Cream "clean rooms" hold the practical content (services, steps, the quote form) and have no dust at all. Density is low and phone-first: one column, big tap targets, heavy uppercase headlines, and plain sentence-case body in the owner's first-person voice. Depth comes from light falling across the room, not from stacked cards.

Type is the platform's own system sans throughout. This is a deliberate house rule, not a gap: the page opens inside Facebook's in-app browser on a phone and has to paint instantly with zero font requests.

**Key Characteristics:**
- Two materials only: navy rooms with light, cream clean rooms without dust.
- Lime is the voice of the brand and appears only on navy ground.
- 900-weight uppercase display set tight, against relaxed 17px sentence-case body.
- Pills for every action, circles for every badge, 14px corners for fields.
- One signature motion: a canvas sunbeam with dust the pointer stirs and wipes.

## Colors

The flyer's three colors, navy, lime and cream, sampled directly and used at full strength, plus one utility blue that exists only for form focus on cream.

### Primary
- **Flyer Navy** (navy): the room. Ground of every lit section (hero, meet, close), the fill of selected chips, step numbers, hovered service arrows and the form's submit button. Lit rooms layer it as a vertical gradient into Night Navy with a faint lighter-blue glow (#164a7c) at the upper right where the window sits.
- **Night Navy** (navy-deep): the floor of the room gradient, and the hover state of the navy button.
- **Ink Navy** (navy-ink): all body text on cream, and the text on lime buttons.

### Secondary
- **Soap Lime** (lime): the flyer's lettering. The wordmark, the lime half of each headline, the primary button, the Facebook button border, icons in the header and footer, step numbers and checkmarks on navy chips. Also the text-selection highlight.
- **Bright Lime** (lime-hi): hover state of the lime button only.

### Tertiary
- **Window Blue** (focus-blue): the focus and hover accent on cream. Field borders on hover and focus (with a 4px 18% halo), chip hover and focus borders, focus outlines inside cream sections, the text caret. Lime does not read on cream, so this blue does the job there.

### Neutral
- **Window Cream** (cream): the flyer's ring. Text and outline-button strokes on navy, the outer portrait ring, selected-chip text.
- **Clean-Room Cream** (cream-soft): ground of the cream sections and the page body.
- **Paper White** (paper-white): fields, chips at rest, and the copy-fallback notice card on cream.
- **Dust-Line** (line): 1px rules between service rows, and the notice card's border.
- **Slate on Cream** (muted-on-cream): secondary text on cream (step descriptions, lede, hints, "(optional)").
- **Haze on Navy** (muted-on-navy): secondary text on navy (hero promise, meet paragraph, footer tagline).
- **Error Red** (error-red): validation messages and the border of an invalid field. Nothing else.

The sunbeam and dust are painted in warm sunlight tones (rgba(255,214,150) to rgba(255,244,214) at low alpha) that live only in the canvas, never in CSS surfaces.

### Named Rules
**The Lime-on-Navy Rule.** Lime only ever sits on navy. Inside cream sections it appears only within a navy shape (step number, hovered arrow, selected-chip checkmark), never as text, border or fill directly on cream.

**The Blue-Is-for-Cream Rule.** Window Blue marks focus and hover on cream fields and chips. On navy, the focus outline is lime.

## Typography

**Display Font:** System sans (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** The same system sans

**Character:** One family pushed to its extremes. Black-weight uppercase headlines set tight like the flyer's lettering, and roomy regular-weight sentences in between that read as a person talking.

### Hierarchy
- **Display** (900, clamp(2.3rem, 10.6vw, 5.4rem), 0.98, uppercase, -0.02em): the hero headline only. The second phrase is lime.
- **Headline** (900, clamp(2rem, 8.6vw, 3.5rem), 0.98, uppercase, -0.02em): section heads. Navy on cream, cream on navy, with a lime phrase allowed on navy.
- **Title** (800, clamp(20px, 5.4vw, 26px), -0.01em): service row names. Step headings use 800 at 20px with 1.25 line-height.
- **Body** (400, 17px, 1.55; 18px from 1024px): paragraphs, capped around 34 to 36em. The hero promise steps up to clamp(17px, 4.4vw, 20px) at 1.5.
- **Label** (800, 17px): buttons (0.01em tracking, line-height 1), field labels and legends. Phone numbers use tabular numerals.
- **Hint** (400 to 600, 15px): form hints and errors.
- **Wordmark** (900, 22px; 19px under 375px, 26px from 1024px; 24px in the footer): "$hannon$aves" in lime, the dollar signs at 800.

### Named Rules
**The System Stack Rule.** Every text role uses the system font stack. No web fonts get loaded; the hierarchy comes from weight (400, 700, 800, 900), case and size. The wordmark is the one place a drawn form may replace it: an SVG traced from the flyer's own slab-serif lettering.

**The Shout-Then-Talk Rule.** Only display and headline are uppercase. Everything else is sentence case in the owner's first-person voice.

## Layout

Phone-first, single column, centered in a 1180px container with 20px side gutters (32px from 640px). Breakpoints are 640px and 1024px, plus a 374px squeeze for the header on the narrowest phones.

- **Below 640px:** everything stacks. Hero actions stack as full-width pills 12px apart; the form's submit button runs full width.
- **From 640px:** hero actions sit side by side, left aligned; the submit button sizes to its content.
- **From 1024px:** body text steps to 18px and the header to 80px tall. Services and How it works go side by side (1.1fr / 1fr, 96px gap). The portrait sits beside the meet copy (240px). The quote section splits into a sticky heading column and a two-column form (1fr / 1.75fr, 72px gap; fields in two columns with full-width rows for services, notes and the submit area). The footer splits into wordmark left and links right.

The vertical rhythm is generous. Cream sections pad 64px (104px desktop); the meet room 72px (120px desktop); the close starts at 84px (130px desktop). Inside a section, stacks step through 12, 20 and 26 to 28px. The hero fills the screen (clamp(620px, 100svh, 980px)) and keeps an empty, touchable floor at least 190px tall below the buttons on phones (120px on desktop), where the light lands and the dust is thickest. The header floats over the hero, honouring safe-area insets. Every interactive target is at least 44px tall, and primary buttons are 56px.

## Elevation & Depth

Flat surfaces, with depth carried by light. Rooms read as deep because a sunbeam crosses them, not because anything is lifted. Shadows are rare, soft and downward, and belong to two objects only.

### Shadow Vocabulary
- **Button settle** (`box-shadow: 0 10px 24px -14px rgba(10,44,79,.8)`): under the navy submit button on cream, so the one action on the form sits slightly forward.
- **Portrait hang** (`0 22px 40px -16px rgba(0,0,0,.55)`, after the two rings): under the portrait in the meet room.
- **Field halo** (`box-shadow: 0 0 0 4px rgba(43,120,216,.18)`): a focus state, not elevation. On focused fields and keyboard-focused chips.

### Named Rules
**The Light-Not-Lift Rule.** Depth comes from the sunbeam and the navy gradient. Cards don't float, and no new shadow gets added without a physical reason (hanging the portrait, settling the action).

## Shapes

Round and soft-edged, like the flyer's ring. Every action is a full pill (999px). Every badge is a circle: step numbers, service arrows, the portrait. Fields get gently rounded 14px corners and the one notice card gets 18px. Focus outlines are 3px with a 3px offset and a 6px radius. Borders are 2px on interactive shapes (buttons, arrows, fields, chips) and 1px for rules. The portrait wears a double ring made with box-shadow: 7px of navy, then 6px of cream.

## Components

### Buttons
Big, round and confident; easy to tap with a thumb.
- **Shape:** full pill (999px), 56px tall, 26px side padding, 2px border, 800-weight 17px label.
- **Lime (primary, on navy):** lime fill and border, ink-navy text. Hover goes to Bright Lime. Used for "Get a free quote" and the close's text CTA.
- **Line (secondary, on navy):** transparent with a 75% cream border and cream text. Hover adds a 10% cream wash and a full-cream border. Used for "Text me".
- **Navy (on cream):** navy fill, cream text, with the button-settle shadow. Hover goes to Night Navy.
- **Press:** every button nudges down 1px and to 99% scale. All transitions are 0.18s ease-out on color, background, border and transform.
- **Focus:** a 3px lime outline on navy, or Window Blue on cream.

### Facebook Button
A softer cousin of the primary, used only in the meet room: a pill 56px tall with 24px padding, a faint 8% cream fill, a 2px lime border, cream text and a 22px lime Facebook glyph (inline SVG). On hover the whole pill floods lime and both text and glyph turn ink navy.

### Service Rows
A quiet list where only the arrow responds.
- **Structure:** full-width rows at least 76px tall, separated by 1px Dust-Line rules (top rule on the list, bottom rule on each row). Title-weight name on the left, a 46px circular arrow on the right.
- **Rest:** the arrow has a 2px 22% ink-navy ring and a navy glyph.
- **Hover / Focus:** the row itself doesn't change (no background, no outline, no shadow). Only the arrow fills navy with a lime glyph. Keyboard focus also puts a 3px Window Blue outline around the arrow.
- **Behavior:** on phones each row opens a text naming that service. On a computer it jumps to the quote form with that service ticked.

### Steps
A numbered list with 46px navy circles holding a lime 900-weight 19px numeral, a 20px 800 heading aligned to the circle's centre, and slate-on-cream description text.

### Chips
- **Style:** pill (999px), 48px tall, 18px side padding, Paper White fill, 2px 22% ink-navy border, 700-weight label. The native checkbox is visually hidden.
- **Hover:** border turns Window Blue.
- **Focus:** Window Blue border plus the 4px field halo.
- **Selected:** fills navy with cream text and shows a 16px lime checkmark. Hover keeps the blue border.

### Inputs / Fields
- **Style:** Paper White, 2px 20% ink-navy border, 14px radius, 54px minimum height, 14px/16px padding, 17px body text. The textarea starts at 110px and resizes vertically.
- **Labels:** 800-weight 17px above the field, 8px gap. "(optional)" sits inline at 500 weight in slate.
- **Hover:** border goes Window Blue.
- **Focus:** Window Blue border plus the 4px 18% blue halo. The native outline is removed and the caret is blue.
- **Error:** border and a 15px 600-weight message in Error Red, shown under the field.

### Notice Card
The only card in the system: the copy-fallback notice after the form. Paper White, a 2px Dust-Line border, 18px radius and 18px padding. It holds the composed message in body type and a smaller pill copy button (48px, white with a 30% ink border).

### Navigation
There is no menu. The header floats over the hero: the lime wordmark on the left, the tap-to-call number on the right in cream 700-weight tabular numerals, with a lime phone glyph. Hovering the number turns it white. The footer repeats the wordmark, the tagline in Haze on Navy, and phone, email and Facebook links with lime glyphs, which underline on hover.

### Portrait
A circular photo (176px phone, 240px desktop) scaled 1.06 inside its frame, with the double ring (7px navy, then 6px cream) and the portrait-hang shadow. It is the cream ring from the flyer.

### Sunbeam and Dust (signature)
Each navy room has two full-bleed canvases behind its content: a beam canvas and a dust canvas. Every value lives in two tunable objects at the top of the script.

- **The beam (`BEAMS`).** Per room (hero, meet, close) and per form factor (phone under 760px room width, desk otherwise), two quads in fractions of the room: `win`, the window opening, often off-canvas above, and `floor`, where the light lands. The window is drawn as a 2x2 grid of panes split by cross-bar gaps (5%). Each pane casts a soft-edged shaft (warm gradient from 30% to 5% alpha, blurred) and lands as a crisp 42% patch on the floor, with a radial hot core where the sun lands. It renders at quarter resolution and is blurred 1.5px in CSS. The beam is cut out (destination-out) behind every element marked as needing a clear pool, so text never sits in the light. Clear text also gets a soft navy pool behind it.
- **The dust (`DUST`).** Hero: 420 motes on phones, 750 on desktop. Other rooms get 60% of that. Motes are warm soft sprites in five sizes, two of them bokeh. A mote's brightness reads from the beam's intensity map, so dust only shows in the light, exactly like real dust. Motes near text, buttons and the portrait drop to 10%.
- **Air.** Ambient drift is layered sine currents (`AIR_SPEED` 0.32, `SWIRL` 0.0042, `DRAG` 0.07). The pointer stirs a small fluid grid (28 columns) within a 70px radius on phones or 110px on desktop (`PUSH` 0.55). Swirls diffuse to neighbouring cells and fade (`WAKE_DECAY` 0.955), so a gesture trails and spreads.
- **Wiping.** A pointer moving faster than `CATCH_SPEED` (2.2 px/frame) catches motes within `CATCH_R` (26px), pulls them into the hand and removes them. Wiped motes regrow (`REGROW` 0.0035 chance per frame) somewhere in the room and fade back in.
- **Idle.** After `IDLE_RESUME` (4500ms) without input, the room's own breeze wanders through the light at reduced strength.
- **Breathing.** Beam opacity slowly dims by up to `BEAM_BREATHE` (12%), as if clouds pass.
- **Performance and access.** Device pixel ratio is capped at `DPR_MAX` 1.5. Rooms only animate while on screen. Under reduced motion a single static frame paints. Before the canvas is ready, a CSS diagonal gradient stands in for the beam and fades out over 0.8s. The hero floor is touch-action none on phones so the finger can play.

### Named Rules
**The Clean-Room Rule.** Dust lives only in navy rooms. Cream sections are the cleaned rooms and stay free of particles, canvases and beams.

**The Arrow-Only Rule.** In a service row, only the arrow reacts to hover and focus. The row stays still.

**The Tunables Rule.** Beam geometry and dust behavior change only through `BEAMS` and `DUST`. A new navy room gets its own `BEAMS` entry with phone and desk geometry.

## Do's and Don'ts

### Do:
- **Do** alternate navy rooms (beam and dust) with cream clean rooms, and put new lit content in a navy room with its own `BEAMS` entry.
- **Do** keep lime on navy, and use Window Blue (#2b78d8) for focus and hover on cream.
- **Do** set headlines in 900 uppercase at 0.98 line-height and -0.02em, with an optional lime phrase on navy.
- **Do** make every action a 56px pill and every target at least 44px.
- **Do** cut the beam out behind text and soften the dust around controls so copy always reads on a calm ground.
- **Do** keep the system font stack for every role.
- **Do** honour reduced motion with a single static frame, and pause rooms that are off screen.

### Don't:
- **Don't** put dust, beams or canvases in cream sections.
- **Don't** use lime as text, border or fill directly on cream.
- **Don't** load web fonts for any text role. The flyer's slab-serif lettering may return only as an SVG wordmark traced from her flyer, never as a font.
- **Don't** add background, outline or shadow changes to a whole service row on hover; only the arrow changes.
- **Don't** float content on shadowed cards; the notice card is the only card, and it is flat.
- **Don't** paint the sunbeam's warm tones into CSS surfaces; sunlight belongs to the canvas.
