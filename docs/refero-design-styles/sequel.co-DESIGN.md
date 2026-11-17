# Sequel — cinematic ambition, editorial poise

## Overview

A cinematic, almost black visual world with the warmth of lived experience rather than futuristic spectacle. White grotesk typography is interrupted by expressive italic serif words, while documentary photography and intimate portrait films carry the emotional weight. The composition is sparse and expansive, suited to premium services, relationship-led products and ambitious long-term propositions.

### Essentials

- Editorial emphasis happens inside the sentence: medium grotesk headings use tight negative tracking, with a few meaningful words in an italic serif; the main opening is 57.6px/1 with -0.05em tracking, while ordinary section leads are 32px/1 with -0.03em tracking.
- The default opening is a film, not a centered pitch deck: edge-to-edge human footage fills a 900px desktop stage, a short headline sits bottom left with 80px side clearance, and a 320px support-and-film-action column sits bottom right.
- Actions look like small objects on a film still: off-white solid pills are 45px high with 24px horizontal padding; secondary controls and labels use translucent gray glass, 1px white-at-20% edges and blur(20px).
- Color belongs to the footage, not the interface: black and charcoal occupy nearly all structural surfaces, white carries text, and off-white is reserved for conversion pills. Natural brown, cream and muted green imagery supplies warmth; the product-feature variant confines sage gradients to individual demonstration panels.
- Proof is staged rather than packed: lightweight 54.1px numbers sit low in tall cells separated by fine vertical rules, tiny uppercase glass labels sit above, and monochrome partner marks form a low, widely spaced strip. Include a measured proof treatment using genuine results, scale or capabilities.
- A monumental typographic sign-off is part of the identity: a short outcome statement stretches across the dark footer at 128px/1, weight 500, -0.025em tracking, with its emotional word in italic serif; the utility links and small clock sculptures sit far below it.
- Human texture is a recurring device: full-bleed documentary scenes, close-up craft footage and rounded portrait tiles break up black chapters. When original film is unavailable, use a carefully art-directed still of real work with the same warm light and dark text-safe framing.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-text` | text, link | Headlines, navigation, icons and strongest foreground text. |
| Warm off-white | `#f5f5f0` | `--color-action` | action | Solid conversion pills; the only broad light interface fill. |
| Soft white | `#f0f0f0` | `--color-support` | text | Support text rendered as white at 94% over black. |
| Pressed ivory | `#e5e5e0` | `--color-action-hover` | action | Hover fill for solid conversion pills. |
| Secondary gray | `#999999` | `--color-secondary` | text | Small location metadata and supporting labels; white at 60% over black. |
| Muted gray | `#666666` | `--color-muted` | text | Low-priority utility and regulatory copy; white at 40% over black. |
| Glass edge | `#333333` | `--color-edge` | border | White at 20% over black for glass outlines and fine separators. |
| Closing seam | `#2c2c2c` | `--color-footer-edge` | border | Subtle 2px inset top seam of the closing field. |
| Charcoal | `#202020` | `--color-card` | surface | Quote tiles, portrait backing and stacked editorial cards. |
| Media edge | `#1a1a1a` | `--color-media-edge` | border | White at 10% over black for fine photographic card outlines. |
| Glass on black | `#141414` | `--color-glass` | surface | Visible result of rgba(200,200,200,0.1) over black; over photography this same material inherits the scene. |
| Near-black closing field | `#0d0d0d` | `--color-footer` | background | Full-width closing surface, subtly lifted from the black page. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Default page field and dark text on light action pills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product and service feature chapters | Product charcoal | `#282828` | `--color-demo-panel` | surface | Feature demonstration cards and paired service panels. |
| product and service feature chapters | Sage | `#86948f` | `--color-sage` | surface | Top of the restrained sage-to-olive feature-panel gradient. |
| product and service feature chapters | Gray olive | `#9b9e86` | `--color-olive` | surface | Bottom of the sage demonstration-panel gradient. |

## Typography

- **VisueltPro** — Headlines, paragraphs, numerals, labels and controls. Clean contemporary grotesk with soft round forms; medium headings contrast with light large numerals. If unavailable, use **Inter**. Use 300, 400 and 500; retain tight heading tracking. Font stack: "VisueltPro", "Inter", system-ui, sans-serif.
- **Bradford** — Italic words embedded within grotesk headlines and occasional editorial numerals. Expressive old-style serif italic with flowing joins, angled stress and long expressive strokes. If unavailable, use **Libre Caslon Text**. Use italic at 400–500 and tune the width of emphasized phrases. Font stack: "Bradford", "Libre Caslon Text", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-display | VisueltPro | 500 | 128px | 1 | -0.025em | fixed | Monumental one-line closing statement. |
| closing-italic | Bradford | 500 italic | 128px | 1 | -0.025em | fixed | One expressive word within the closing statement. |
| display | VisueltPro | 500 | 57.6px | 1 | -0.05em | fixed | Short bottom-aligned headline over the opening film. |
| stat | VisueltPro | 300 | 54.1px | 1.2 | normal | fixed | Large proof numerals and attached symbols. |
| heading | VisueltPro | 500 | 32px | 1 | -0.03em | fixed | Default centered section statements; keep them visually smaller than the opening. |
| editorial-line | VisueltPro | 500 | 32px | 1.2 | -0.03em | size clamp(32px, 2.2vw, 67.2px) | Centered lines in an immersive belief or manifesto scene. |
| editorial-italic | Bradford | 500 italic | 32px | 1.2 | -0.05em | fixed | Emotional phrase within an editorial line. |
| location | VisueltPro | 300 | 30px | 1.2 | -0.025em | fixed | City names below sculptural clocks in the footer. |
| card-heading | VisueltPro | 500 | 21.6px | 1.2 | -0.02em | size clamp(19.2px, 1.5vw, 32px) | Titles anchored near the bottom of audience or capability photo cards. |
| portrait-name | VisueltPro | 500 | 20px | 1.5 | normal | size clamp(16px, 1.5vw, 20px) | Name at the bottom of a portrait film. |
| body-lead | VisueltPro | 400 | 17.6px | 1.4 | normal | size clamp(17.6px, 1.62vw, 17.3px) | Concise introductory support beside the opening headline. |
| navigation | VisueltPro | 500 | 16px | 1.5 | normal | fixed | Top navigation. |
| footer-link | VisueltPro | 400 | 16px | 1.5 | normal | fixed | Footer utility links and contact address. |
| quote | VisueltPro | 500 | 16px | 1.4 | normal | size clamp(14px, 1.2vw, 16px) | Direct testimonial excerpts. |
| eyebrow | VisueltPro | 500 | 15.8px | 1.2 | 0.07em, uppercase | size clamp(14.4px, 1.1vw, 17.6px) | Small centered introductory marking in immersive editorial scenes. |
| button | VisueltPro | 500 | 15px | 1.5 | normal | fixed | Main conversion and manifesto actions. |
| button-small | VisueltPro | 500 | 14px | 1.5 | normal | fixed | Film action and audience card actions. |
| card-support | VisueltPro | 400 | 13px | 1.4 | normal | size clamp(12.8px, 0.9vw, 16px) | Short support under photographic card titles. |
| portrait-caption | VisueltPro | 400 | 12px | 1.5 | 0.05em, uppercase | size clamp(10px, 0.9vw, 12px) | Role beneath a portrait name. |
| badge | VisueltPro | 500 | 11.2px | 1.5 | 0.05em, uppercase | size clamp(10px, 0.8vw, 11.2px) | Glass capsule labels marking audiences, categories and proof. |
| micro-label | VisueltPro | 400 | 10px | 1.5 | 0.08em, uppercase | fixed | Footer group labels and location metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| access-led service pages | centered-display | VisueltPro | 500 | 56px | 1.2 | -0.03em | fixed | Centered membership-style opening and invitation closing. |
| application pages | application-display | VisueltPro | 500 | 56px | 1 | -0.03em | size clamp(32px, 4vw, 56px) | Long centered application proposition. |
| application pages | application-italic | Bradford | 500 italic | 56px | 1 | -0.05em | fixed | Expressive phrase in the application proposition. |
| recruiting pages | mission-display | VisueltPro | 500 | 43.2px | 1 | -0.02em | fixed | Compact centered mission headline on an otherwise black opening. |
| application pages | capability-heading | VisueltPro | 500 | 38.9px | 1 | -0.03em | fixed | Centered capability leads and final contact invitation. |
| capability and culture chapters | body | VisueltPro | 400 | 16px | 1.4 | normal | size clamp(13.6px, 1.4vw, 16px) | Paragraphs inside stacked editorial cards. |
| application and recruiting pages | text-action | VisueltPro | 500 | 15px | 1.5 | 0.05em, uppercase | size clamp(12.8px, 1.07vw, 15px) | Underlined application, showreel and recruitment links. |
| recruiting pages | listing-label | VisueltPro | 400 | 14.4px | 1.5 | 0.0556em, uppercase | size clamp(11.5px, 1vw, 14.4px) | Role titles and metadata inside job rows. |
| long-form operating-proof chapters | stat-caption | VisueltPro | 400 | 12.8px | 1.4 | 0.03em, uppercase | size clamp(11.2px, 0.96vw, 12.8px) | Narrow centered descriptions under vertically spaced proof numbers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Grotesk headings are medium, not bold; the drama comes from tight tracking and surrounding emptiness. Italic emphasis replaces individual words rather than creating a second stacked headline.
- For photo openings, match the serif emphasis to the surrounding 57.6px headline; the closing uses matching 128px sans and serif recipes.
- The support formula has a minimum larger than its maximum; retain its 17.6px effective minimum rather than treating it as an expansive responsive scale.
- Uppercase belongs to labels and small links, not to the main proposition. Numerals are lighter than headlines.

## Layout

**Density:** Airy at chapter scale, compact inside objects: long black intervals separate short statements, while labels, quote tiles and controls remain closely assembled.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Small text and label gaps. | fixed |
| 12px | Quote tile content gap. | fixed |
| 16px | Portrait and demonstration gutters, footer link gaps and media overlay padding. | fixed |
| 20px | Quote tile padding. | fixed |
| 24px | Common vertical text-stack gap and primary-button side padding. | fixed |
| 28.8px | Photo-card grid gutter and stacked editorial card padding. | clamp(25.6px, 2.4vw, 28.8px) |
| 32px | Navigation link gap and general chapter side padding. | fixed |
| 40px | Desktop navigation padding. | fixed |
| 48px | Gap below stacked cards before their controls. | fixed |
| 80px | Opening content side clearance. | fixed |
| 90px | Feature chapter padding and space before proof groups. | fixed |
| 96px | Closing-field padding and clock-column separation. | fixed |
| 160px | Closing-field vertical separation between major rows. | fixed |
| 180px | Centered service openings and deep chapter padding. | fixed |
| 270px | Default large black chapter top padding. | fixed |

### Containers and grids

- **wide-stage**: max width 1440px. Full-width film and immersive editorial stages; the main opening occupies 900px height at desktop.
- **opening-content**: gap 24px · side padding 80px. Bottom-aligned split: headline takes most of the width and right-hand support is limited to 320px.
- **statement**: max width 800px · side padding 32px. Centered compact section statements, usually two or three lines.
- **photo-pair**: max width 1200px · 2 columns · gap 28.8px. Two square photographic cards, each limited to 550px width.
- **portrait-grid**: 3 columns · gap 16px · side padding 32px. Centered 400px portrait columns with alternating video and quote tiles; use two columns for a lighter proof chapter.
- **closing-grid**: gap 64px · side padding 96px. Two link groups at left, three clock/location blocks at right; the latter use 96px column gaps.
- **feature-grid** (only for product and service feature chapters): max width 1200px · 3 columns · gap 16px · side padding 32px. Bento grid with one double-width lead panel and smaller companion panels.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | photo-and-quote-tiles | 10px |
|  | avatars-and-controls | 50% |
| capability and culture chapters | stacked-cards | 12px |
| recruiting pages | glass-rows | 8px |
| product and service feature chapters | feature-panels | 15px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | glass | `0px 10px 30px rgba(0, 0, 0, 0.35), inset 0px 1px 0px rgba(255, 255, 255, 0.08)` | Shared glass badge, control and listing treatment. |
|  | solid-action | `0px 4px 20px rgba(0, 0, 0, 0.15)` | Soft depth under off-white pills. |
| capability and culture chapters | card-stack | `0px 10px 30px rgba(0, 0, 0, 0.3), 0px 4px 8px rgba(0, 0, 0, 0.2)` | Separate overlapping charcoal cards. |

### Surfaces

#### Black stage · level 0

**Use:** Default page and negative-space chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Media and short white statements interrupt a continuous black field.

**Transfer:** Keep the structure dark even when photography supplies a warm scene.

#### Glass · level 2

**Use:** Badges, secondary controls and small content markings.

**CSS:** `background: rgba(200, 200, 200, 0.1); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 9999px; box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.35), inset 0px 1px 0px rgba(255, 255, 255, 0.08); backdrop-filter: blur(20px) saturate(1.4)`

**Observed:** The same material reads charcoal on black and warm translucent gray over film.

**Transfer:** Use on small floating objects, not as a full-page frosted overlay.

#### Photographic veil · level 1

**Use:** Maintain text contrast on photographic cards and portrait films.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0) 30%, rgba(0, 0, 0, 0) 60%, rgba(0, 0, 0, 0.6))`

**Observed:** A transparent center preserves faces; the darker bottom supports names and captions. Audience cards use a stronger progressive darkening toward the bottom.

**Transfer:** Apply the veil above media and below white text.

#### Charcoal tile · level 1

**Use:** Quote blocks and portrait backing.

**CSS:** `background: #202020; border-radius: 10px`

**Observed:** Solid dark gray offsets human footage without a bright outline.

**Transfer:** Let content and a capsule label supply hierarchy.

#### Closing field · level 0

**Use:** Monumental sign-off and complete utility footer.

**CSS:** `background: #0d0d0d; box-shadow: inset 0px 2px 0px #2c2c2c; padding: 96px 0px`

**Observed:** A barely lighter end field, divided by a fine seam rather than a large color change.

**Transfer:** Repeat this material on every page type.

#### Sage feature panel · level 1

**Only for:** product and service feature chapters

**Use:** Lead product demonstration in an otherwise charcoal grid.

**CSS:** `background: linear-gradient(#86948f, #9b9e86); border-radius: 15px; overflow: hidden`

**Observed:** One double-width panel contrasts with charcoal and photographic neighbors.

**Transfer:** Keep the soft gray-green contained within the feature demonstration.

#### Product panel · level 1

**Only for:** product and service feature chapters

**Use:** Companion feature demonstrations and paired service panels.

**CSS:** `background: #282828; border-radius: 15px; overflow: hidden`

**Observed:** Large dark panels frame small conversations, diagrams and devices.

**Transfer:** Make the illustration legible without reproducing an entire application.

## Components

### Navigation

**Use:** Persistent brand, chapter links and conversion action.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; z-index: 60; padding: 40px; color: rgba(255, 255, 255, 0.9)`

**Text style:** `navigation` — VisueltPro 500 · 16px/1.5

**Observed:** Logo left, three short links centered with 32px gaps, off-white Primary button right. A separate 128px dark-to-transparent veil supports contrast over imagery; central links recede during deeper chapters.

**States:** Declared: hover color #ffffff.

**Transfer:** Keep the same three-part balance with a different product identity.

### Primary button

**Use:** Main persistent conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 7px; height: 45px; padding: 0px 24px; background: #f5f5f0; color: #000000; border-radius: 9999px; box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.15)`

**Text style:** `button` — VisueltPro 500 · 15px/1.5

**Observed:** Short verb phrase followed by a small right arrow. Inside photo cards the compact variant is 42px high, uses 20px side padding and button-small text.

**States:** Declared: hover background #e5e5e0; box-shadow 0px 4px 20px rgba(0,0,0,0.25); transform translateY(-2px).

### Film button

**Use:** Secondary media action on the opening scene.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 20px; background: rgba(200, 200, 200, 0.1); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 9999px; color: #ffffff; backdrop-filter: blur(20px) saturate(1.4); box-shadow: 0px 10px 30px rgba(0,0,0,0.35), inset 0px 1px 0px rgba(255,255,255,0.08)`

**Text style:** `button-small` — VisueltPro 500 · 14px/1.5

**Observed:** Outlined play symbol before the label; the 42px inner button is wrapped in Glass. The wider editorial action uses button text, 45px inner height, 24px side padding and a right arrow.

**States:** Declared: hover background rgba(255,255,255,0.1).

### Capsule badge

**Use:** Small audience, category and proof markers.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 8px 16px; background: rgba(200, 200, 200, 0.1); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 9999px; color: #ffffff; backdrop-filter: blur(20px) saturate(1.4); box-shadow: 0px 10px 30px rgba(0,0,0,0.35), inset 0px 1px 0px rgba(255,255,255,0.08)`

**Text style:** `badge` — VisueltPro 500 · 11.2px/1.5 · tracking 0.05em · uppercase

**Observed:** A compact uppercase capsule sits at an upper corner of a media tile or at the top of a stat cell.

### Audience photo card

**Use:** Route readers into two complementary propositions.

**CSS:** `position: relative; display: flex; flex-direction: column; justify-content: space-between; width: 550px; height: 550px; padding: 16px; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 10px; overflow: hidden; color: #ffffff`

**Text style:** `card-heading` — VisueltPro 500 · 21.6px/1.2 · tracking -0.02em

**Observed:** Full-cover human image under a dark veil; Capsule badge high at the right, then title, short card-support text and compact Primary button near the bottom.

**Transfer:** Use two genuinely distinct audiences or jobs, each represented by a scene rather than an icon.

### Testimonial tile

**Use:** Human proof mixed with portrait film tiles.

**CSS:** `display: flex; flex-direction: column; gap: 12px; width: 400px; padding: 20px; background: #202020; border-radius: 10px; color: #ffffff`

**Text style:** `quote` — VisueltPro 500 · 16px/1.4

**Observed:** Capsule badge, direct quote, then a small uppercase attribution. A neighboring portrait tile is taller and carries a name and role at its bottom; columns alternate the quote above or below the video.

**Transfer:** Use a few substantial real comments rather than rows of stars.

### Stat cell

**Use:** Spacious quantified proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; width: 283px; height: 283px; padding: 19.2px; gap: 16px; border-left: 1px solid rgba(255, 255, 255, 0.15); color: #ffffff`

**Text style:** `stat` — VisueltPro 300 · 54.1px/1.2

**Observed:** Capsule badge at top, light numeral near bottom with its suffix on the same baseline; optional small uppercase descriptor below. Multiple cells sit in one row without filled backgrounds.

**Transfer:** Use verified metrics; keep each label short enough to remain a capsule.

### Footer link

**Use:** Quiet utility navigation beneath the oversized sign-off.

**CSS:** `display: inline-block; position: relative; color: #ffffff`

**Text style:** `footer-link` — VisueltPro 400 · 16px/1.5

**Observed:** Two vertical groups with 16px gaps; tiny uppercase group labels sit above.

**States:** Declared: hover opacity 0.6.

### Fanned editorial card

**Only for:** capability and culture chapters

**Use:** A focused browsable deck of values or capabilities.

**CSS:** `position: relative; width: 350px; height: 480px; padding: 28.8px; background: #202020; border-radius: 12px; overflow: hidden; box-shadow: 0px 10px 30px rgba(0,0,0,0.3), 0px 4px 8px rgba(0,0,0,0.2)`

**Text style:** `body` — VisueltPro 400 · 16px/1.4

**Observed:** One upright active card, others staggered and rotated clockwise behind it. Culture cards begin with a Capsule badge and paragraphs; capability cards place an image above the label and paragraph. Two 48px circular arrow controls sit below the deck.

**Transfer:** Use a compact collection that rewards browsing, not a dense visible grid.

### Text action

**Only for:** application and recruiting pages

**Use:** Low-chrome application and recruitment conversion.

**CSS:** `color: #ffffff; text-transform: uppercase; text-decoration: underline`

**Text style:** `text-action` — VisueltPro 500 · 15px/1.5 · tracking 0.05em · uppercase

**Observed:** A single centered underlined line below the proposition; showreel variant adds a small play control.

**States:** Declared: hover opacity 0.7; focus-visible outline 2px solid #ffffff; outline-offset 4px; box-shadow 0px 0px 0px 6px rgba(255,255,255,0.18).

### Opportunity row

**Only for:** recruiting pages

**Use:** Open-role listings grouped under department headings.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) minmax(110px, 140px) minmax(110px, 140px) 56px; align-items: center; gap: 16px; padding: 16px 24px; background: rgba(200, 200, 200, 0.1); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 8px; backdrop-filter: blur(20px) saturate(1.4); box-shadow: 0px 10px 30px rgba(0,0,0,0.35), inset 0px 1px 0px rgba(255,255,255,0.08)`

**Text style:** `listing-label` — VisueltPro 400 · 14.4px/1.5 · tracking 0.0556em · uppercase

**Observed:** Wide title column, employment type, location, then circular arrow action. Rows are separated by 20px. Benefits use the same glass material in smaller 72px-high rounded rectangles with icons.

## Imagery and graphics

### Documentary film stage

**Use:** Dominant opening and recurring immersive editorial pause.

**Observed:** Warm natural-light footage shows people absorbed in craft: a silhouetted pianist against sheer curtains, writing hands and a close-up climbing grip. The lens is intimate, texture-rich and subdued in saturation; a scene can occupy the entire screen with relatively little type. No bright digital glow is applied.

**Transfer:** Film actual work, concentration or use in an architectural setting. Minimum acceptable version is a high-quality still with strong subject silhouette, material detail and free space for the lower text.

### Portrait proof

**Use:** Portrait films in testimonial columns.

**Observed:** Tall, close, informal face-to-camera footage with everyday interiors, rounded 10px corners and dark top/bottom veils. Names sit at the bottom while small category capsules sit above. These feel credible and personal, not like studio headshots.

**Transfer:** Use honest customer or practitioner portraits, paired with a solid charcoal quote tile; preserve different tile heights.

### Monochrome credentials

**Use:** Low horizontal proof strip beneath statements or numbers.

**Observed:** White partner and professional-organization marks on black; an eight-mark strip uses roughly 96px-wide items with very wide separation. Shapes retain their own proportions rather than being forced into equal boxes.

**Transfer:** Use relevant authorized customer, ecosystem or certification marks, monochromized and optically balanced.

### Clock sculptures

**Use:** Distinctive small graphic above footer location names.

**Observed:** Minimal white clock hands with no dial or numerals; three clocks hover above city names in 188px location blocks. They read as abstract line sculptures rather than dashboard widgets.

**Transfer:** Include minimal hand-only local-time graphics for relevant operating locations; if locations are not meaningful, use the same hand-only motif beside service availability.

**Build:** Create a 48px square SVG per location with two or three white lines sharing an off-center-looking visual hub, stroke widths around 1px–3px and round caps. Rotate the hands around the shared center to show different times. Omit the clock face, ticks and bounding circle; place each above a light 30px location label and a fine horizontal rule.

### Sage demonstration tableau

**Only for:** product and service feature chapters

**Use:** Visual explanation inside a lead feature panel.

**Observed:** Soft sage-to-gray-olive backing contains scattered circular human avatars and a small translucent horizontal interface object. Companion panels mix intimate lifestyle photography, charcoal message bubbles and a partially visible tilted phone. White labels are small relative to the panel.

**Transfer:** Show one recognizable interaction, not a full interface. A minimal equivalent is a rounded horizontal task object surrounded by a few human avatars on a muted gradient.

**Build:** Use a 15px rounded clipped panel with a vertical gradient from #86948f to #9b9e86. Set a translucent rounded horizontal object in its right half; add several 36px circular portraits at staggered heights around it and a compact white two-line label in the left third. Keep outlines thin and the entire arrangement low contrast.

### Floating proof clippings

**Only for:** long-form operating-proof chapters

**Use:** Editorial depth around a vertical sequence of outcomes.

**Observed:** Dark rectangular news clippings with inset photography, a short heading and date capsule drift at alternating sides of centered numerals. Each is gently rotated; the surrounding field remains overwhelmingly black.

**Transfer:** Use actual milestones, releases or independent coverage around a central proof axis.

**Build:** Create dark charcoal rounded article cards with a date capsule and a cropped photographic lower half. Place alternating cards left and right of the centered stat column, vary their rotation by about 10deg as design guidance, and reduce contrast so they frame rather than compete with the numerals.

### Culture filmstrip

**Only for:** recruiting pages

**Use:** Transition from team proposition to working principles.

**Observed:** A horizontally overflowing strip of candid team, travel and shared-activity photographs uses mixed aspect ratios at a common 350px height.

**Transfer:** Use candid work and shared experience rather than identical corporate portraits; preserve the off-edge continuation.

### Icons

**Observed:** Action arrows are simple 15px–20px monochrome strokes, generally 2px with round caps. Play actions use a small outlined circle and triangle; social marks are filled 16px silhouettes. Carousel arrows sit inside 48px glass circles.

**Transfer:** Use restrained white or black line arrows matched to the action's contrast; reserve pictograms for benefits and functional controls.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px full-width human film stage forms the entire first screen. From back to front: warm documentary scene, subtle dark contrast veils, fixed Navigation, then bottom-aligned white content. The silhouetted person fills much of the left half, a piano occupies the middle, and light curtains and timber supply the warm background. The short display headline sits bottom left, occupying about two thirds of the available content region; its key noun is italic serif. A narrow 320px column at lower right contains Film button above a three-line support statement, separated by 28px. Both columns share a lower baseline with 63px bottom breathing room and 80px side clearance. The logo, central links, Primary button, headline, support and film action all fit within the first 900px; the next proposition begins below the fold.

**Transfer:** For a new landing page, choose one engrossing real-world scene and a short outcome-led sentence, not a giant product dashboard. With no film, use a warm, textural still and retain the asymmetrical lower text. Access-led services can open on black with centered 56px text and a two-row photo mosaic below; application pages use a centered multiline 56px proposition with immediate portrait proof; recruiting pages use a centered 43.2px mission statement with an underlined action.

**Avoid:** Do not replace this opening with a centered huge headline above a floating software window, or put every action and paragraph into the left column.

**Text style:** `display` — VisueltPro 500 · 57.6px/1 · tracking -0.05em

### Statement and audience pair

**Observed:** A centered heading in the statement container follows a long black interval, with 270px chapter top padding. After about 135px, two Audience photo cards sit in photo-pair; their photographic imagery carries the color and their lower text remains compact.

**Transfer:** Use a concise shared promise followed by two distinct paths into the product.

**Text style:** `heading` — VisueltPro 500 · 32px/1 · tracking -0.03em

### Immersive belief pause

**Observed:** An image-led sticky 900px stage begins as an inset media rectangle and expands to fill the view. A centered eyebrow sits above short editorial lines, one prominent at a time, with italic phrase emphasis. A glass editorial action sits beneath; footage shows hands and physical effort rather than interface decoration.

**Transfer:** Write a small set of beliefs about the user's ambition and back them with tactile craft imagery. Maintain the device as an immersive emotional pause rather than adding more feature tiles.

**Text style:** `editorial-line` — VisueltPro 500 · 32px/1.2 · tracking -0.03em

### Human proof columns

**Observed:** Centered heading and concise support introduce portrait-grid. Portrait footage and Testimonial tiles alternate vertically, separated by 16px, with varied overall heights; badges, names and role captions give a consistent small-scale hierarchy.

**Transfer:** Show the people who experience the product's outcome, paired with direct, specific testimony.

**Text style:** `heading` — VisueltPro 500 · 32px/1 · tracking -0.03em

### Proof and credential field

**Observed:** A compact centered statement sits above a horizontal group of Stat cells with vertical hairlines and low-aligned numerals. A widely spaced monochrome credential strip follows, with black breathing room between proof layers.

**Transfer:** Use a small number of meaningful metrics and relevant marks. Keep the light numeral weight and the tall-cell alignment.

**Text style:** `stat` — VisueltPro 300 · 54.1px/1.2

### Closing invitation and monumental footer

**Observed:** A restrained final proposition precedes Closing field: access-led services use a centered invitation statement, application pages use a short contact line, and recruiting pages conclude their opportunities before the footer. The footer starts with closing-display and closing-italic, then a 160px gap before two link groups and three Clock sculptures. A final widely separated row carries contact, copyright and small social marks, followed by muted regulatory copy. The footer has 96px outer side padding and the same near-black material across all page types.

**Transfer:** Give the product its own short outcome sign-off in mixed sans and serif, then preserve the unusually spacious utility footer and hand-only clock motif. The lead-in invitation can vary with page purpose.

**Text style:** `closing-display` — VisueltPro 500 · 128px/1 · tracking -0.025em

### Focused card deck

**Only for:** capability and culture chapters

**Observed:** A centered heading introduces one active Fanned editorial card; multiple offset cards peek out behind to the right. Imagery can occupy the upper half of a capability card, while culture cards use paragraphs. Circular Previous and Next controls sit 48px below.

**Transfer:** Convert a list of principles, capabilities or learning formats into a tangible browsable deck, with one idea per card.

**Text style:** `body` — VisueltPro 400 · 16px/1.4

### Service feature tableau

**Only for:** product and service feature chapters

**Observed:** Centered mixed-type heading and a short support line precede feature-grid. A two-column Sage feature panel anchors the first row beside Product panel. Further cards mix real photographs, messages and a partial device. A subsequent chapter uses two equal charcoal panels for a diagram and a short conversation, with explanatory text anchored low.

**Transfer:** Use a bento only when explaining an actual product or service interaction; make each card a composed scene rather than a colored text box.

### Recruiting utility chapter

**Only for:** recruiting pages

**Observed:** A centered mixed-type section title precedes two overflowing horizontal rows of glass benefits, with occasional activity photos layered among them. Open roles follow in department groups using Opportunity row; an italic invitation addresses readers who do not find a fit.

**Transfer:** Use the horizontal benefits material for concrete support offerings, then switch to stable scannable rows for actionable opportunities.

### Vertical operating proof

**Only for:** long-form operating-proof chapters

**Observed:** A narrow centered heading and support introduce a tall central sequence of stat numerals and uppercase captions limited to 200px width. Floating proof clippings flank alternating sides, leaving the central axis clear. Generous black intervals make this a slow credibility chapter.

**Transfer:** Use several verified milestones with contextual artifacts. Keep meaningful final numbers visible rather than leaving the story dependent on counting animation.

**Text style:** `stat` — VisueltPro 300 · 54.1px/1.2

## Page flow

**Storyline:** Emotional promise → clear proposition → human or institutional proof → focused capability chapters → credible scale → restrained invitation → monumental sign-off and utilities.

### Broad brand and product landing page

1. **Promise** — Full-screen documentary opening with lower split headline and support.
2. **Audience routing** — Centered shared proposition followed by two square photo cards.
3. **Belief** — Immersive craft-footage chapter with sequential editorial statements.
4. **Human proof** — Portrait films and compact quote tiles.
5. **Quantified and institutional proof** — Tall stat cells and a monochrome mark strip.
6. **Closing call** — Short long-term promise leading into the monumental footer.

**Transfer:** Let emotional imagery establish the stakes, then explain paths and prove outcomes before the last invitation.

### Access-led service or membership proposition

1. **Promise** — Centered mixed-type opening, support and access qualifier above two photo-tile strips.
2. **Credibility** — Short access proposition, institutional marks and four tall stat cells.
3. **Product demonstration** — Sage and charcoal feature bento with restrained interaction scenes.
4. **Supporting capability** — Paired dark panels explain collaboration and administration.
5. **Closing call** — A spare invitation-only statement, then the shared monumental footer.

**Transfer:** Replace exclusivity with the new service's real access model, and use composed demonstrations to explain value.

### Recruiting and culture page

1. **Mission** — Small centered mixed-type proposition on a full black screen with underlined role link.
2. **Emotional context** — Impact statement and candid horizontally overflowing photo strip.
3. **Culture proof** — Fanned deck of working principles.
4. **Practical value** — Two horizontal rows of icon-led glass benefit rectangles.
5. **Conversion** — Grouped job rows and a personal invitation for future candidates.
6. **Sign-off** — The same monumental closing field and utility system.

**Transfer:** Balance aspiration with readable practical information; do not make vacancies part of the cinematic media.

### Partner or application-focused landing page

1. **Promise** — Centered multiline proposition with an inline media thumbnail and underlined application action.
2. **Human proof** — Immediate three-column portrait and quote composition.
3. **Qualification** — Partner marks and two dark square commitment cards.
4. **Capability chapters** — Content-led fanned card deck and a spacious measurable-impact section.
5. **Operating proof** — Vertical light numerals surrounded by floating milestone clippings.
6. **Closing call** — Compact contact invitation above the shared monumental footer.

**Transfer:** Move proof closer to the application promise; use scoped decks and long-form metrics to explain depth rather than multiplying CTAs.

## Writing

Assured, aspirational and relationship-led. The voice pairs emotional ideas about lasting impact with short, concrete descriptions of what the service actually does.

**Do not copy:** Do not reuse Sequel's name, wordmark, distinctive slogans, customer names, partner marks, exact investment claims, financial figures, invitation policy or testimonial quotations as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Headlines alternate between direct 'your' outcomes and collective 'we' commitments. The organization speaks as people and partners rather than as an impersonal platform.
- **Rhythm:** Short headline clauses, often three to eight words, followed by one compact support sentence. Longer application propositions can run over two or three centered lines; paragraphs appear primarily inside browsable cards.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a personal lasting outcome, with one emotionally charged word singled out in italic. | 3–8 words | “Your legacy, made.”<br>“Invest with the best”<br>“Join our mission.” |
| Supporting line | Explain audience, mechanism and purpose in one sentence, without diluting the promise. | 15–25 words | “A digital family office for athletes, artists, and entrepreneurs backing companies that advance humanity.” |
| Section lead | Make a confident proposition, then follow it with an immediately understandable explanation. | 4–12 words | “We co-invest with top tier funds.”<br>“Real operating expertise.” |
| Action | Use a plain verb and the object or desired outcome, with no sales punctuation. | 2–4 words | “Build the future”<br>“Watch the film”<br>“View open roles” |
| Proof label | Use a compact factual noun phrase rather than an adjectival boast. | 1–5 words | “World champions”<br>“Companies started within sequel team.” |

**Words and phrasing to use:** lasting; build; back; partner; ambitious; impact; craft; network; expertise; long-term

**Avoid:** growth hacks; disrupt everything; 10x your life; limited-time deal; magic-powered; crush it

**Rules:**

- Use an emotional headline and a concrete support line as separate layers.
- Italicize the meaningful noun or phrase, not random decorative words.
- Support statements of scale with real attributable results.
- Keep eligibility language clear and factual rather than using manufactured urgency.
- Let direct customer language remain human; keep surrounding editorial copy controlled.

## Do's and Don'ts

### Do

- Keep standard section statements at 32px, weight 500 and -0.03em tracking.
- Retain the 128px mixed-type closing statement as a recognizably larger tier than the opening.
- Use 10px corners for photo and quote tiles and 9999px for control capsules.
- Keep the default structural palette black, charcoal and white; let photographic light carry warmth.
- Use the same 1px white-at-20% edge and blur(20px) material across glass controls and labels.
- Anchor 54.1px lightweight proof numerals low in tall ruled cells.
- Keep wide scene-level intervals of 90px, 180px and 270px separate from compact 8px–24px object spacing.
- Preserve the tiny 10px uppercase footer metadata and the light 30px location names.

### Don't

- Do not turn every heading bold: weight 500 headlines and weight 300 numerals create the hierarchy.
- Do not introduce saturated brand-color buttons or a page-wide sage canvas.
- Do not replace translucent capsules with square outlined buttons.
- Do not turn portrait proof into uniform circular headshots; its tall film tiles and charcoal quote blocks matter.
- Do not shrink the footer into a dense utility strip; keep the 160px separation between its main rows.
- Do not use the 15px product-panel radius as a universal radius for photographic tiles.
- Do not put boxed backgrounds behind every metric; fine left rules are the default proof construction.
- Do not use uppercase for the main emotional headline or add a monospace technical voice to the labels.

## Motion and responsive

### Motion

**Observed:**

- Solid action pills declare a 0.3s transition and a -2px hover lift; top navigation declares a 0.2s color transition with cubic-bezier(.4, 0, .2, 1).
- Application links declare opacity 0.2s; opportunity rows declare background, border-color and transform transitions at 0.2s.
- The closing field declares an all 1s cubic-bezier(0, 0, .2, 1) transition. The belief scene uses a sticky stage and perspective/blur changes on text.
- Horizontal photo and benefit strips, fanned card decks, hand-only clocks and changing numeric proof are part of the moving visual language.

**Transfer:**

- Keep movement concentrated in film, the immersive text chapter, browsable decks and subtle controls; preserve readable static end states.
- Retain the short lift of solid pills and opacity-based behavior of quieter text links.

**Unknown:**

- Full choreography, counter completion timing and video playback behavior are not established.
- No precise timing is established for carousel movement, clock hands or horizontal strips.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 648px, 768px, 1024px, 1108px, 1280px and 1536px, with additional very wide-screen breakpoints.
- Navigation uses 24px base padding and 40px desktop padding; central links and the persistent conversion action are desktop-only in the layout declarations.
- Footer side padding progresses through 24px, 48px and 96px. The three-location clock grid is desktop-only in the layout declarations.

**Transfer:**

- On narrow screens, stack the opening headline and 320px support column without losing the dominant human scene; preserve a text-safe area within the image.
- Reduce portrait and photo-pair columns instead of compressing text into narrow tiles. Keep the small capsule controls and distinct mixed-type emphasis.
- Maintain a strong closing typographic tier while wrapping the outcome line and compacting footer groups; do not force the desktop clock grid into tiny columns.

**Unknown:**

- Narrow-screen compositions, mobile menu behavior and exact mobile headline sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
