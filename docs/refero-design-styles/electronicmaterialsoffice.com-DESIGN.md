# Electronic Materials Office — occult hardware in the dark

## Overview

A pitch-black, product-worship launch page for a piece of precision hardware: near-black bands and charcoal squircle cards hold glossy studio renders, with one hot signal red used like an indicator LED. Type pairs a hairline-light high-contrast serif for names and monumental statements with a wide, tightly tracked grotesk for sentence headlines and a light mono for uppercase labels and spec tables. It suits flagship product, pre-order and device launch pages; density is low and cinematic, with full-width renders and video carrying most of the page and text arriving in short, confident bursts.

### Essentials

- Headlines are two-tone sentences: a white claim followed immediately by a grey explanation in the same size and line — 65px wide grotesk, weight 400, 63.7px line height, -4px tracking, white #ffffff then grey #6d6d6d.
- Names and big statements switch to a light display serif with crushing negative tracking: 83px/0.8 at -6px for the product name, 124px/1 at -0.1em for a stacked centered word list, 200px/0.9 at -0.08em for a single monumental line.
- Labels read like panel markings: 21px light mono, uppercase, 25.2px line height, in signal red #ff3300, set top-left of a section above its headline (or centered above centered statements).
- Everything sits on black: canvas #000000 alternating with #111111 bands; content lives in #1b1b1b cards with 20px squircle corners and 24px gaps, 24px from the window edges; no borders, no shadows on cards.
- Red is a light source, not a fill: a 12px glowing red dot logo, a glowing red Reserve button, red mono labels, and one red-tinted 'night mode' section in dark ember #7c1f00 — red never covers more than a button or a monitor-glow in the imagery, except the giant closing button.
- Imagery is glossy black-on-black studio renders and loops cropped edge to edge inside cards (macro keys, exploded parts, side profiles); when there is no render, use tight macro crops of the product material lit with a single soft top light on #000000.
- The page closes on a white card that flips the palette: black-and-grey heading pair and two 216px-tall full-width buttons (solid red, then outlined) set at 64px.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#ff3300` | `--color-signal` | accent, action, text | Mono section labels, the glowing logo dot, Reserve buttons, text selection; display-p3 red-orange (1, 0.2, 0). |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Void | `#000000` | `--color-canvas` | background, text | Page canvas and alternate bands; also text on the white closing card. |
| Graphite band | `#111111` | `--color-band` | background | Alternating full-width section bands that hold card rows. |
| Charcoal card | `#1b1b1b` | `--color-card` | surface | Squircle media and feature cards on both black and graphite bands. |
| Smoked glass | `#2b2b2b` | `--color-glass` | surface | Visible tone of the blurred header bar and hero price card (90% grey gradient over the page). |
| Smoke grey | `#6d6d6d` | `--color-muted` | text, border | Second half of two-tone headlines, captions, spec labels, hairline rules, badge and chip outlines. |
| Ash | `#cacaca` | `--color-soft` | text | Light grey for a centered oversized statement headline. |
| White | `#ffffff` | `--color-ink` | text, background | Lead half of headlines, names, stats, nav and footer links; fill of the closing card. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| a red-lit low-light feature section | Ember | `#7c1f00` | `--color-ember` | text, accent | Dim red text and dot grid of the night-light variant section; also used at 50% alpha for its dot pattern. |

## Typography

- **Tobias-Web** — Product name, monumental statements, stacked feature-name list, nav and footer links. High-contrast light text serif with sharp wedge serifs, set very tight so letters nearly touch. If unavailable, use **Newsreader**. weight 300; keep the heavy negative tracking. Font stack: "Tobias-Web", "Newsreader", Georgia, serif.
- **GT Flexa** — Sentence headlines, stats, giant CTA labels. Wide, slightly extended grotesk with round geometric bowls; tight negative tracking at display sizes. If unavailable, use **Unbounded**. weights 300–500; reduce tracking slightly since it is wider. Font stack: "GT Flexa", "Unbounded", system-ui, sans-serif.
- **GT Flexa Text** — Body captions, taglines, footnotes, text links. Text cut of the same wide grotesk, open spacing, normal tracking. If unavailable, use **Manrope**. Font stack: "GT Flexa Text", "Manrope", system-ui, sans-serif.
- **GT Flexa Mono** — Uppercase section labels, badges, spec table. Light, wide monospace with an engineering-drawing feel. If unavailable, use **Space Mono**. weight 400 is the lightest; set slightly smaller. Font stack: "GT Flexa Mono", "Space Mono", "SF Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Tobias-Web | 300 | 200px | 0.9 | -0.08em | One centered monumental line per page. |
| word-list | Tobias-Web | 300 | 124px | 1 | -0.1em | Stacked, centered list of feature names near the end of the page, one per line. |
| heading-xl | GT Flexa | 400 | 108px | 0.85 | -0.07em | Centered short statement headline in Ash grey. |
| display-name | Tobias-Web | 300 | 83px | 0.8 | -6px | Product name in the opening, bottom-left. |
| stat | GT Flexa | 550 | 67px | 1 | -0.1em | Big numbers inside dotted stat cards. |
| heading | GT Flexa | 400 | 65px | 0.98 | -4px | Two-tone section headline: white claim plus grey continuation in one block, usually right 8 of 12 columns. |
| cta-giant | GT Flexa | 400 | 64px | 1 | -0.1em | Labels of the giant closing buttons. |
| lead | GT Flexa | 400 | 51px | 0.95 | -3px | Intro statement under the opening; grey then white. |
| value | GT Flexa | 500 | 42px | 1 | -2px | Measured values in comparison cards. |
| footer-link | Tobias-Web | 300 | 32px | 1.2 | -2px | Footer link columns and legal line. |
| nav-link | Tobias-Web | 300 | 31px | 1.2 | -0.04em | Top-right nav link and hero Reserve label. |
| tagline | GT Flexa Text | 400 | 30px | 1.2 | normal | Grey tagline under the product name, text links, stat lead-ins. |
| body | GT Flexa Text | 400 | 21px | 1 | normal | Card captions: white bold-feeling lead phrase then grey sentence. |
| eyebrow | GT Flexa Mono | 300 | 21px | 1.2 | normal, uppercase | Red section labels and badges. |
| spec | GT Flexa Mono | 300 | 21px | 0.82 | normal, uppercase | Spec-table labels (grey) and values (white). |

**Notes:**

- Tracking tightens hard with size: -2px at 32–42px, -4px at 65px, about -0.1em at 64–124px; text cuts and mono stay at normal tracking.
- Line height drops below 1 for display (0.8–0.98) and is exactly 1 for 21px captions.
- Serif = names and monuments; wide grotesk = sentences; mono = labels and data. Never swap roles.
- Trademark marks are set as small superscripts in the same color as the word they follow.

## Layout

**Density:** airy — few words per screen, huge type and full-bleed media, but tight 24px gutters between cards.

### Spacing

**Spacing system:**

- **grid** 12px — Declared steps 6/12/24/48/96px; all layout spacing is a multiple of 12px (6px for tight label gaps).

| Value | Use |
| --- | --- |
| 6px | Label to value inside cards. |
| 12px | Card media to caption; between stacked giant buttons. |
| 24px | Window side padding, card gutters, section top padding. |
| 48px | Section bottom padding; inner padding of comparison cards. |
| 96px | Large section top padding and footer top padding; gap between footer columns. |

### Containers and grids

- **full-bleed frame**: max width 1392px · side padding 24px. No centered container: content runs edge to edge with 24px side padding at 1440px.
- **12-column grid**: 12 columns · gap 24px. Heading pairs put the mono label in the first 4 columns and the headline in the last 8; card rows mix widths (920+448, 566+448+920, 684+684, 4×330) and may overflow off the right edge as a horizontal strip.

## Corner radius

| Element | Radius |
| --- | --- |
| cards | 20px |
| badges | 6px |
| chips | 9999px (pill) |
| round controls | 50% |
| glass bar and red buttons | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| red glow | `0 0 21px #ff3300, 0 0 7px #ff3300` | Logo dot and Reserve buttons: the red emits light. |
| white glow | `0 0 7px #ffffff, 0 0 20px #ffffff` | Active sound toggle button. |

### Surfaces

#### Void canvas · level 0

**Use:** Page background.

**CSS:** `background: #000000`

#### Graphite band · level 0

**Use:** Alternating full-width bands.

**CSS:** `background: #111111; padding: 24px 0 48px`

**Observed:** Alternates with black every one or two sections; edges are hard cuts.

#### Squircle card · level 1

**Use:** Media and feature cards.

**CSS:** `background: #1b1b1b; border-radius: 20px; overflow: hidden`

**Observed:** Corners are a smooth squircle (20px) drawn by a border-image overlay; media fills the card edge to edge.

**Transfer:** Use for every image, video and feature tile; captions sit outside, 12px below.

#### Dot-grid card · level 1

**Use:** Stat cards and an audio feature panel.

**CSS:** `background-color: #1b1b1b; background-image: radial-gradient(circle, rgba(255,255,255,0.1) 1px, rgba(0,0,0,0) 1px); background-size: 12px 12px; border-radius: 20px; padding: 24px`

**Observed:** A faint 12px dot matrix like perforated metal; the red-lit variant uses rgba(124,31,0,0.5) dots on black.

#### Smoked glass · level 2

**Use:** Fixed header bar and hero price card.

**CSS:** `background: linear-gradient(90deg, rgba(47,47,47,0.9) 0%, rgba(38,38,38,0.9) 100%); backdrop-filter: blur(7px); border-radius: 12px`

#### White closing card · level 1

**Use:** Final reservation call.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 22px 21px`

**Observed:** The only white surface on the page; inverts text to black and grey.

## Components

### Header glass bar

**Use:** Fixed navigation after the first screen.

**CSS:** `background: linear-gradient(90deg, rgba(47,47,47,0.9) 0%, rgba(38,38,38,0.9) 100%); backdrop-filter: blur(7px); border-radius: 12px; height: 52px; padding: 0 8px 0 12px`

**Text style:** `nav-link` — Tobias-Web 300 · 31px/1.2 · tracking -0.04em

**Observed:** Floats 24px from the sides; left: glowing red dot plus serif wordmark with ®; right: small glowing red Reserve button. On the first screen only the dot and a serif About link show, no bar.

### Glowing reserve button

**Use:** Primary purchase action in header and hero card.

**CSS:** `background: #ff3300; color: #ffffff; border-radius: 12px; height: 48px; padding: 0 12px; box-shadow: 0 0 21px #ff3300, 0 0 7px #ff3300`

**Text style:** `nav-link` — Tobias-Web 300 · 31px/1.2 · tracking -0.04em

**Observed:** Serif label, light weight, on a red that glows into its surroundings; header version is 36px tall with 22px label.

**States:** Declared: hover transform scale(1.05); active scale(0.98); transform 0.2s.

### Hero price card

**Use:** Offer summary in the first screen, bottom-right.

**CSS:** `background: linear-gradient(90deg, rgba(47,47,47,0.9) 0%, rgba(38,38,38,0.9) 100%); backdrop-filter: blur(7px); border-radius: 12px; width: 448px; height: 96px; padding: 0 12px`

**Text style:** `body` — GT Flexa Text 400 · 21px/1

**Observed:** Left: struck-through grey old price, white new price, grey offer line below; right: glowing reserve button.

### Media card with caption

**Use:** Feature rows of images or loops.

**CSS:** `background: #1b1b1b; border-radius: 20px; overflow: hidden`

**Text style:** `body` — GT Flexa Text 400 · 21px/1

**Observed:** Card 480–681px tall; caption 12px below: white lead phrase ending in a period, then grey sentence in the same 21px line.

**Transfer:** Mix one wide card with one or two narrow ones per row.

### Round media control

**Use:** Play/pause/replay on video cards.

**CSS:** `width: 48px; height: 48px; border: 3px solid #6d6d6d; border-radius: 50%; background: transparent`

**Observed:** Bottom-right inside the video card with a thin round-capped glyph; ember outline in the red-lit section.

**States:** Declared: hover scale(1.05); active scale(0.95).

### Mono badge

**Use:** Classification tag in comparison cards.

**CSS:** `border: 1px solid #6d6d6d; border-radius: 6px; padding: 8px 12px; color: #6d6d6d`

**Text style:** `eyebrow` — GT Flexa Mono 300 · 21px/1.2 · uppercase

**Observed:** Sits under the measured value in a comparison card; red-label variant for the hero item, grey outline and grey text for competitors.

### Outline chip

**Use:** Small sample/trigger buttons in a row.

**CSS:** `border: 2px solid #6d6d6d; border-radius: 9999px; padding: 0 10px; height: 36px; color: #6d6d6d`

**Observed:** Grotesk 21px label, -0.8px tracking; chips sit in a row with 6px gaps under a caption.

**States:** Declared: hover scale(1.05); active scale(0.95).

### Spec row

**Use:** Technical specification and credits table.

**CSS:** `border-bottom: 1px solid #6d6d6d; padding: 11px 0; display: flex`

**Text style:** `spec` — GT Flexa Mono 300 · 21px/0.82 · uppercase

**Observed:** Grey uppercase mono label in the first quarter, white uppercase mono value after; external links get a small arrow.

### Giant closing buttons

**Use:** Final call inside the white card.

**CSS:** `background: #ff3300; color: #ffffff; height: 216px; width: 100%; border-radius: 20px`

**Text style:** `cta-giant` — GT Flexa 400 · 64px/1 · tracking -0.1em

**Observed:** Stacked 12px apart: solid red primary, then an outlined secondary with a thick black squircle outline and black label; a grey sentence with an underlined link follows.

**States:** Declared: hover scale(1.02); active scale(0.99).

### Footer link columns

**Use:** Site footer.

**CSS:** `color: #ffffff; padding: 96px 24px 48px`

**Text style:** `footer-link` — Tobias-Web 300 · 32px/1.2 · tracking -2px

**Observed:** Legal line in serif at left, two columns of seven serif links to the right; no icons, no dividers.

**States:** Declared: hover opacity 0.7; opacity 0.2s.

## Imagery and graphics

### Black-on-black product renders

**Use:** Nearly every section; full-bleed in the opening and inside every card.

**Observed:** Glossy black hardware rendered on pure black with a single soft top light; extreme macro crops, exploded parts, side profiles; the only color is a red-orange accent part. Imagery fills 60–80% of every screen.

**Transfer:** Render or photograph the new product in matte/gloss black on #000000, single key light, crop past the frame edges; one saturated accent element at most.

### Red-glow lifestyle and UI scenes

**Use:** Context shots and app screenshots.

**Observed:** A dark desk scene lit by red monitors, and app windows floating over a grainy red-orange gradient wallpaper.

**Transfer:** Stage any software screens over a dark-to-red grainy gradient so they feel lit by the brand red.

**Build:** background: radial-gradient(120% 90% at 70% 40%, #ff3300 0%, #7c1f00 45%, #000000 85%); add a 3–4% noise overlay.

### Line-drawing inventory

**Use:** What's-in-the-box card.

**Observed:** Thin white outline drawings of each item on a charcoal card, labelled with circled letters.

**Transfer:** Draw contents as 1.5px white strokes, no fills, with circled-letter keys referenced in the text.

**Build:** SVG, stroke #ffffff 1.5px, fill none, round joins; circled letters 26px in mono.

### Red waveform

**Use:** An audio demo panel.

**Observed:** Many overlapping thin red-orange oscillating lines on black.

**Transfer:** For any data/sound proof, plot many 1px #ff3300 lines at mixed opacity on black.

**Build:** SVG polylines, stroke #ff3300 1px, opacity 0.4–1, stacked 12–20 lines.

### Icons

**Observed:** Very few icons: thin round-capped 3px-stroke playback glyphs in grey or red inside 48px circles, small arrow on external links.

**Transfer:** Use minimal stroke glyphs only for controls; never decorate copy with icons.

## Section recipes

How recurring sections are built.

### First screen: Render stage opening

**Observed:** Back to front: pure black canvas; a full-bleed product render/video 1440×900 with the product floating in the upper half; bottom-left the serif product name (83px, white) with a grey 30px tagline directly under; bottom-right the smoked-glass price card with the glowing red Reserve button; top-left a 12px glowing red dot, top-right a serif About link. All within the first 900px; the first row of charcoal cards peeks in at the bottom edge.

**Transfer:** Put the new product, lit alone on black, across the upper two thirds; anchor name and offer to the bottom corners; keep text under 10 words above the fold. Without a render, use a macro crop of the material with one top light.

**Avoid:** No centered hero headline, no gradients behind text, no multiple buttons, no white or colored backgrounds.

**Text style:** `display-name` — Tobias-Web 300 · 83px/0.8 · tracking -6px

### Two-tone heading pair

**Observed:** Red mono label at left (columns 1–4) and 65px headline at right (columns 5–12): white claim sentence then grey explanation, followed 16–24px below by a full-width 681px video card.

**Transfer:** Write a 2–5 word white claim and a one-sentence grey continuation.

### Mixed-width card strip

**Observed:** Graphite band, row of Media cards with captions, widths mixed and sometimes overflowing the right edge, 24px gaps.

**Transfer:** 2–4 cards per row; one wide plus narrow ones.

### Monumental serif statement

**Observed:** Red mono label centered, then a 200px serif line over an app or product image.

**Transfer:** Use once per page for the defining claim, ending with a period.

### Stat cards

**Observed:** Two dotted cards side by side: grey 30px lead-in, white 67px stat, grey 30px unit line; footnote with dagger below.

**Transfer:** Use for 2 quantified claims; keep footnotes honest.

### Feature name litany

**Observed:** Centered stacked list of feature names in 124px serif with superscript ™, red mono label above, ending in the product name over a top-down render.

**Transfer:** List 6–10 feature names, one per line, as a rhythmic recap before the close.

### White reservation close

**Observed:** White card: red mono label, black+grey heading pair, Giant closing buttons, small grey subscribe line. Then black Footer link columns.

**Transfer:** Invert to white only here; keep two giant buttons.

## Page flow

**Storyline:** product reveal → intro statement → capability chapters with video → quantified comparison → craft details → specs and credits → feature litany → reservation close

### Launch and pre-order a single hardware product

1. **Promise** — Render stage opening with name, price and reserve.
2. **Product demonstration** — Heading pairs plus full-width video cards per capability.
3. **Quantified proof** — Comparison cards with measured values and badges; stat cards.
4. **Capability chapters** — Mixed-width card strips with captions; a red-lit variant section.
5. **Specification** — Spec rows and credits table.
6. **Recap** — Feature name litany in serif.
7. **Closing call** — White reservation close and footer.

**Transfer:** Give each capability one heading pair, one hero video card and one card strip; finish with recap and inverted close.

## Writing

Deadpan, reverent and slightly mischievous: sacred and devilish puns paired with precise engineering facts.

**Do not copy:** Do not reuse the brand's product names (Altar, M-Dial, NiteLite, Harmonic Synthesiser etc.), prices, measurements, headlines or trademarks. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal and product-as-subject; 'you' only for benefits; the company is rarely named.
- **Rhythm:** Two-to-five word headline claims ending in a period, followed by one longer explanatory sentence; captions start with a two-word label.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section headline | Short idiomatic claim + period, then explanation | 2–5 words + 1 sentence | “Feels like an epiphany.”<br>“Sounds divine.” |
| Caption | Label phrase + benefit sentence | 12–25 words | “Durable design. Steel construction means an incredibly durable mechanism with long operating life.” |
| Primary action | Single verb | 1–2 words | “Reserve”<br>“Get updates” |

**Words and phrasing to use:** miracle; divine; sacred; precise; tactile; understated; period-ended claims

**Avoid:** exclamation marks; revolutionary; game-changing; emoji

**Rules:**

- End headlines with a period.
- Use exact numbers with units.
- Use British spelling consistently.
- Mark claims with footnote daggers when qualified.

## Do's and Don'ts

### Do

- Set every section headline as a 65px two-tone pair, white then #6d6d6d.
- Keep 24px side padding and 24px card gutters throughout.
- Use 21px uppercase mono red labels above sections.
- Wrap all media in #1b1b1b 20px-radius cards with captions outside.
- Give red buttons and the logo dot a red glow (0 0 21px + 0 0 7px).
- Use the light serif for product names and one 200px statement.
- Alternate #000000 and #111111 bands.
- Close with an inverted white card and two 216px-tall buttons.

### Don't

- Don't use bold serif — keep it at weight 300.
- Don't add borders or drop shadows to cards.
- Don't use red for body text or large backgrounds outside the final button.
- Don't track the grotesk loosely; display needs -4px to -0.1em.
- Don't introduce a second accent hue.
- Don't center section headlines except the statement and litany moments.
- Don't use light-gray or white sections before the close.

## Motion and responsive

### Motion

**Observed:**

- Buttons: transform 0.2s, hover scale(1.05), active scale(0.95–0.98); giant buttons scale(1.02).
- Links: opacity 0.2s ease to 0.7 on hover; text link color to white on hover.

**Transfer:**

- Keep interactions as small physical scale presses, like hardware buttons.

**Unknown:**

- Scroll-triggered animation timing and video behaviours.

### Responsive

**Observed:**

- Breakpoint at 768px; some wide cards hide on mobile.

**Transfer:**

- Stack heading pairs label above headline; card strips become horizontal swipes.

**Unknown:**

- Mobile type sizes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
