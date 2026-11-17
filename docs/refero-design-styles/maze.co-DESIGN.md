# Maze — human signal, digital texture

## Overview

A light, expressive technology style that puts very thin, tightly spaced grotesk headlines beside human faces and colorful interface fragments. Warm paper and charcoal carry most of the reading, while acid lime, lilac and blue make the product feel active and curious. It suits platforms that need to explain sophisticated workflows without losing their human purpose; the overall density is spacious, with compact controls and information-rich demonstrations.

### Essentials

- Headlines feel stretched across the room rather than emboldened: Phonic at weight 300, 90px/1 with -0.07em tracking for major promises and 130px/1 with -0.09em for monumental statements.
- The opening is a typeset promise interlocked with a product collage: 40px outer gutters, a headline spanning roughly three fifths of the width, small paired 40px actions below the supporting copy, and staggered human and interface tiles filling the right and lower edges.
- Conversion controls deliberately mix silhouettes: charcoal primary buttons use 8px corners while outlined secondary actions are pills, both with 17px regular text and 8px 16px padding; closing actions expand to 80px high with 28px light text.
- Color arrives as concentrated stages, not a rainbow of reading surfaces: #f5f4f0 and white dominate; one vivid lime statement field, blue or purple media backings, and the #dbf570 social strip punctuate the neutral page.
- Human photographs and digital halftones belong together: warm candid faces and work scenes sit inside 12–16px rounded tiles, often repeated behind themselves as a tinted dot or square field. Recreate this pairing with original photography and simple interface fragments when elaborate product art is unavailable.
- The page has both a moving vocabulary and a monumental sign-off: two edge-faded rows of white capability chips use 46px light type, and the footer carries a roughly 920px-wide wordmark treatment below its link columns. A new brand uses its own capability language and oversized typographic identity.
- Proof is presented as a lived outcome: three 387px-wide translucent cards over a warm full-bleed photograph, with 46px light claims, small outlined uppercase labels and bottom-aligned logos; a text attribution can replace a logo.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal lime | `#dbf570` | `--color-lime` | surface, accent | Social strip, quote marker and the acid-lime family of editorial color fields; media can push this hue toward a brighter yellow-green. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Report mint | `#adeeda` | `--color-mint` | surface | Wide editorial report card backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#1c1c1c` | `--color-ink` | text, action, background | Headlines, body text and primary actions; also the inverse media-band ground. |
| Black | `#000000` | `--color-black` | background, action | Announcement strip and pressed primary actions. |
| Soft charcoal | `#3c3c3c` | `--color-hover` | action, text | Primary-button hover and small category text. |
| Warm gray | `#706f6c` | `--color-muted` | text, border | Supporting copy, inactive large tabs and outlined labels or secondary actions. |
| Input edge | `#9e9b94` | `--color-input-edge` | border | Email field outline and large play-control edge. |
| Paper rule | `#d2cec6` | `--color-rule` | border | Footer, accordion and table separators. |
| Warm stone | `#eae6e1` | `--color-stone` | surface, border | Selected tabs, small footer category chips, alternating comparison rows and navigation edge. |
| Warm paper | `#f5f4f0` | `--color-canvas` | background, surface | Default page canvas and inset neutral stages. |
| White | `#ffffff` | `--color-white` | surface, text, background | Cards, navigation and text on dark or photographic grounds; white at 50% is used for photographic glass and at 70% for secondary controls. |

## Typography

- **Phonic** — All marketing typography, from enormous promises to compact navigation. A light contemporary grotesk with open counters, plain forms and strongly tightened display spacing. If unavailable, use **Inter**. Use 300 and 400; retain tight tracking and check line breaks against the intended width. Font stack: "Phonic", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Phonic | 300 | 130px | 1 | -0.09em | size clamp(3.25rem, -0.5203rem + 9.6059vw, 8.125rem) | Monumental closing promises and the scale of the collage-opening headline. |
| hero | Phonic | 300 | 90px | 1 | -0.07em | size clamp(2.75rem, 6.25vw, 5.625rem) | Centered promises, feature-page openings and oversized horizontal chapter tabs. |
| heading | Phonic | 300 | 58px | 1.1 | -0.06em | size clamp(2rem, 1.4623rem + 2.403vw, 3.625rem) | Main section headings and large editorial statements. |
| heading-small | Phonic | 300 | 46px | 1.15 | -0.05em | size clamp(1.5rem, -0.1525rem + 3.3639vw, 2.875rem) | Feature headings, outcome claims and moving vocabulary chips. |
| card-heading | Phonic | 300 | 28px | 1.3 | -0.04em | size clamp(1.25rem, 0.8846rem + 0.9615vw, 1.75rem) | Quotes, FAQ questions, card headings and newsletter title. |
| action-large | Phonic | 300 | 28px | 1.05 | -0.02em | size clamp(1.25rem, 0.8846rem + 0.9615vw, 1.75rem) | Large closing-call actions. |
| body-large | Phonic | 300 | 22px | 1.4 | -0.03em | fixed | Hero supporting copy, large informational card text and social-strip title. |
| body | Phonic | 400 | 17px | 24px | -0.02em | size clamp(0.9375rem, 0.8456rem + 0.241vw, 1.0625rem) | Body paragraphs, footer links and supporting explanations. |
| action | Phonic | 400 | 17px | 1 | -0.02em | size clamp(0.9375rem, 0.8456rem + 0.241vw, 1.0625rem) | Compact action buttons and arrow links. |
| navigation | Phonic | 400 | 14px | 1.05 | 0.03em, uppercase | fixed | Navigation categories and vertical capability-tab labels. |
| eyebrow | Phonic | 400 | 14px | 1 | 0.03em, uppercase | fixed | Outlined section markers. |
| label-small | Phonic | 400 | 12px | 1 | 0.03em, uppercase | fixed | Outlined proof and informational-card markers. |
| caption | Phonic | 400 | 12px | 1.05 | 0.03em, uppercase | fixed | Quote attributions and filled footer category chips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | comparison | Phonic | 400 | 15px | 1.4 | -0.02em | size clamp(0.8125rem, 0.7206rem + 0.241vw, 0.9375rem) | Feature lists and dense comparison cells. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display hierarchy is made through size and negative tracking, not bold weight. Tracking tightens from -0.02em in body and controls to -0.09em at the largest scale.
- Uppercase labels reverse the tracking logic with +0.03em spacing; keep them regular and small beside the light headings.
- Use a 520px maximum for centered supporting copy, around 800px for centered opening headings and 400–600px for feature prose.

## Layout

**Density:** Airy at section scale, compact inside controls and information cards; oversized words and media provide the density rather than crowded prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action pairs, small icon gaps and footer-link rhythm. |
| 12px | Small list and form gaps. |
| 16px | Card padding and heading-to-paragraph gaps in compact content. |
| 20px | Three-column card gaps and larger card padding. |
| 24px | Hero heading-to-copy and copy-to-action spacing. |
| 32px | Closing heading-to-action and FAQ-row spacing. |
| 40px | Outer desktop gutter and major internal chapter gaps. |
| 64px | Footer vertical padding. |
| 80px | Default major section padding or inter-section breathing room. |
| 112px | Inset assurance-stage vertical padding. |
| 120px | Editorial statement and centered opening vertical breathing room. |
| 208px | Monumental closing section vertical padding. |

### Containers and grids

- **section grid**: max width 1440px · gap 40px · side padding 40px. Centered desktop section framework; at 1440px each underlying column is 40px. Main inset panels span 1360px.
- **reading column**: max width 800px · gap 24px · side padding 40px. Centered opening text and mission statements; supporting paragraphs narrow to 520px.
- **proof grid**: max width 1200px · 3 columns · gap 20px · side padding 40px. Three equal informational or outcome cards; six-card variants continue into a second row.
- **feature split**: max width 1360px · 2 columns · gap 80px · side padding 40px. A 640px square media tile balanced by a narrower copy column; reverse the media side between chapters.
- **capability stage**: max width 1360px · 2 columns · gap 80px · side padding 40px. A 280px vertical selector beside the main 880px-wide media stage; heading and explanation sit above that stage.
- **plan grid** (only for pricing pages): max width 1360px · 2 columns · gap 20px · side padding 40px. Two equally weighted plan panels, each with a text half and a 260px-wide graphic.

## Corner radius

| Element | Radius |
| --- | --- |
| primary controls | 8px |
| secondary controls | 9999px (pill) |
| labels | 4px |
| content cards | 12px |
| media and closing panels | 16px |
| wide chapter panel | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation | `0px 4px 30px 0px rgba(0, 0, 0, 0.04)` | A faint separation under the white fixed navigation; flat content cards do not borrow it. |

### Surfaces

#### Paper canvas · level 0

**Use:** The default ground.

**CSS:** `background: #f5f4f0; color: #1c1c1c`

#### White panel · level 1

**Use:** Wide editorial, product and conversion stages.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: none`

**Observed:** Large white islands sit on paper without heavy outlines. The wide horizontal chapter panel increases its radius to 20px.

**Transfer:** Let the shape group a whole argument or demonstration, not every paragraph.

#### Photo glass · level 1

**Use:** Outcome proof over full-width photography.

**CSS:** `background: rgba(255, 255, 255, 0.5); border-radius: 12px; backdrop-filter: blur(40px); color: #ffffff`

**Observed:** The photographic colors show through a milky, strongly blurred material; the typography and attribution remain white.

**Transfer:** Use a warm photograph with dark enough local values for the white claims.

#### Mint editorial panel · level 1

**Use:** A report or editorial resource promoted beside an image.

**CSS:** `background: #adeeda; border-radius: 16px`

**Observed:** Text occupies one half; large editorial artwork occupies the other half.

**Transfer:** Reserve this secondary hue for one distinct resource rather than all feature cards.

#### Signal field · level 0

**Use:** A vivid statement and moving vocabulary interlude.

**CSS:** `background: #dbf570; color: #1c1c1c; overflow: hidden`

**Observed:** The lime field contrasts strongly with paper; two white-chip rows fade into the colored ground at their edges.

**Transfer:** Use a bright yellow-green within this family and match the visual punch; exact animated color stops are not essential.

#### Inverse media band · level 0

**Only for:** feature announcements with video

**Use:** A theatrical interruption around a large demonstration film.

**CSS:** `background: #1c1c1c; color: #ffffff`

**Observed:** A light heading and compact paragraph lead into an almost full-width rounded video poster.

**Transfer:** Keep inverse sections concentrated around the demonstration rather than switching the entire site to dark.

## Components

### Navigation bar

**Use:** Fixed site orientation and conversion.

**CSS:** `background: #ffffff; height: 81px; border-bottom: 1px solid #eae6e1; box-shadow: 0px 4px 30px 0px rgba(0, 0, 0, 0.04)`

**Text style:** `navigation` — Phonic 400 · 14px/1.05 · tracking 0.03em · uppercase

**Observed:** Logo left, uppercase menu groups with small carets across the middle, login and a mixed-shape action pair at right. A separate black announcement strip can sit above it.

### Primary button

**Use:** Main compact conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #1c1c1c; color: #ffffff; border-radius: 8px; padding: 8px 16px; min-height: 40px; gap: 8px`

**Text style:** `action` — Phonic 400 · 17px/1 · tracking -0.02em

**Observed:** Text-only filled rectangle with soft corners; width follows the label rather than a uniform long pill.

**States:** Declared: hover background-color #3c3c3c; focus-visible outline 2px with 2px offset; active background-color #000000 and outline-width 0px.

### Secondary button

**Use:** Self-serve or alternate action beside a filled button.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(255, 255, 255, 0.7); color: #1c1c1c; border: 1px solid #706f6c; border-radius: 9999px; padding: 8px 16px; min-height: 40px; backdrop-filter: blur(2px)`

**Text style:** `action` — Phonic 400 · 17px/1 · tracking -0.02em

**Observed:** A thin outlined pill, deliberately rounder than the primary action. Circular 40px carousel arrows use the same material.

**States:** Declared: hover border-color #1c1c1c and background-color #ffffff; focus-visible outline 2px with 2px offset; active outline-width 0px.

### Closing button

**Use:** High-emphasis action under a monumental promise.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background: #1c1c1c; color: #ffffff; height: 80px; min-width: 240px; padding: 4px 16px; border-radius: 16px`

**Text style:** `action-large` — Phonic 300 · 28px/1.05 · tracking -0.02em

**Observed:** The action grows with the headline; an outlined pill companion can be placed alongside it.

### Outlined marker

**Use:** Section eyebrow or proof-card topic.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; border: 1px solid #706f6c; border-radius: 4px; padding: 8px 12px`

**Text style:** `eyebrow` — Phonic 400 · 14px/1 · tracking 0.03em · uppercase

**Observed:** A tiny 8px square precedes the uppercase label. Informational cards use the smaller label-small recipe; photographic proof uses white borders, square and text.

### Information card

**Use:** Compact assurance, principle or capability explanation.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 16px; display: grid`

**Text style:** `body-large` — Phonic 300 · 22px/1.4 · tracking -0.03em

**Observed:** An outlined marker or small line icon starts the card, followed by short left-aligned copy. Cards align in equal columns; illustrated variants place the artwork first and use body-sized copy.

**Transfer:** Use marker plus one clear explanation; for values-like cards add a card-heading title between icon and body copy.

### Outcome card

**Use:** A quantified result attributed to a real customer.

**CSS:** `background: rgba(255, 255, 255, 0.5); border-radius: 12px; backdrop-filter: blur(40px); padding: 20px; display: flex; flex-direction: column; justify-content: space-between; gap: 16px; color: #ffffff`

**Text style:** `heading-small` — Phonic 300 · 46px/1.15 · tracking -0.05em

**Observed:** Outlined marker at top, large sentence-form result beneath, customer logo anchored at the bottom. Three cards remain the same height even when line counts vary.

### Capability selector

**Use:** Switch between product workflows or audiences.

**CSS:** `display: inline-flex; align-items: center; background: #eae6e1; border-bottom: 1px solid #d2cec6; border-radius: 8px 8px 0px 0px; width: 280px; min-height: 46px; padding: 8px 16px; gap: 12px`

**Text style:** `navigation` — Phonic 400 · 14px/1.05 · tracking 0.03em · uppercase

**Observed:** Selected tab carries a small dark square. Inactive rows are transparent with only a bottom rule. The selector is left of an oversized product stage with a neighboring preview partly visible.

### FAQ row

**Use:** Objection handling on feature and integration pages.

**CSS:** `border-bottom: 1px solid #d2cec6; padding-bottom: 24px; max-width: 600px`

**Text style:** `card-heading` — Phonic 300 · 28px/1.3 · tracking -0.04em

**Observed:** Question and a small down-caret share the top line. Expanded answers use body text below; the large section heading lives in a separate left column.

### Email input

**Use:** Newsletter conversion within the footer card.

**CSS:** `background: #ffffff; border: 1px solid #9e9b94; border-radius: 8px; height: 40px; padding: 0px 8px`

**Observed:** Input and compact dark Subscribe action share a row under the newsletter heading.

### Footer

**Use:** Deep site navigation and a recognizable final visual.

**CSS:** `background: #f5f4f0; border-top: 1px solid #d2cec6; padding: 64px 0px`

**Text style:** `body` — Phonic 400 · 17px/24px · tracking -0.02em

**Observed:** Four link columns occupy the left, a 360px newsletter card and lime social strip the right. Category headings are small stone chips. Below them sits a monumental 920px-wide identity mark, then a tiny muted legal line.

**Transfer:** Preserve the oversized identity treatment even for a short brand name; use a custom typeset wordmark if no symbol exists.

### Plan panel

**Only for:** pricing pages

**Use:** Present two contrasting levels without a conventional crowded price-card stack.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 20px; display: grid; gap: 40px`

**Text style:** `heading` — Phonic 300 · 58px/1.1 · tracking -0.06em

**Observed:** Small stone package label above a light plan name, 22px audience description and dark action; a tall tinted halftone image occupies the adjacent half. A rule separates the upper composition from feature lists.

## Imagery and graphics

### Interlocking human-product collage

**Use:** Signature opening scene.

**Observed:** An asymmetrical constellation of white product panels, a blue pixel-texture square, warm interview faces and a lime-backed analysis fragment. The tallest panel anchors the upper right; shorter portrait and interface tiles form a lower shelf. Rounded corners are crisp, with very little shadow.

**Transfer:** Combine one primary product interaction, one human portrait and one visualized result. Minimum version: build two simplified interface cards, one warm portrait and one tinted dot-field tile rather than a single giant browser mockup.

**Build:** Create a desktop grid with staggered top alignment: one tall white card at upper right, a small blue square to its left, and three lower tiles of unequal width. Use 12–16px radii and 20px gaps. Back the result tile in vivid yellow-green and overlay a white response card plus a simple stepped chart; keep chart color within product-ui rather than adding marketing text colors.

### Halftone image stages

**Use:** Signature media backing across demonstrations, portraits and editorial tiles.

**Observed:** Blue, lilac, yellow or pink grounds carry a coarse square-and-dot rendering of a photographic subject. A smaller natural-color photo or clean white interface floats in front. The texture is digital and blocky rather than grainy or hand drawn.

**Transfer:** Repeat an original photo behind itself as a tinted halftone; leave the foreground natural and legible. A regular SVG dot field with a few larger pixel clusters is the minimum acceptable substitute.

**Build:** Place a tinted photo over a saturated rectangular backing with 16px corners. Mask a same-hue darker overlay using a 4–6px repeating SVG grid of 1–3px squares or circles; vary dot size from a grayscale version of the photo. Center a foreground image about two thirds of the backing width, with an 8–12px radius. Allow texture to remain visible on every side.

### Warm documentary proof

**Use:** Full-bleed outcome sections and humanizing support imagery.

**Observed:** Candid close-ups of hands, conversation, laptops, books and people at work; warm brown, olive and cream, soft natural light and shallow depth of field. Wide images cover an entire band behind white headings and Photo glass cards.

**Transfer:** Photograph the human context of the new product, not a sterile device on a gradient. If no photography is available, commission a single warm contextual scene rather than substituting abstract neon art.

### Quote portrait tile

**Use:** Testimonial carousel.

**Observed:** A white 880px-wide horizontal card pairs a roughly 320px portrait stage with 28px quote text. The portrait sits over a lime halftone enlargement of itself; a small lime quote marker and low-key attribution complete it. Adjacent cards are blurred and clipped beyond the stage.

**Transfer:** Use authentic customer portraits and short quotations, with one central sharp card and peripheral softened cards.

**Build:** Use a white 16px-radius horizontal panel. Put a square lime halftone portrait stage on the left and a smaller natural portrait centered inside it. On the right stack a small quote-square, quote, name and uppercase role. Position duplicate neighboring panels outside the container and blur them by 8px; keep the active panel sharp.

### Orbiting photographic close

**Use:** Closing conversion stages.

**Observed:** Small floating photographic rectangles of different sizes surround a sharp central heading and button on white or paper. Some photographs are sharp; others are heavily softened, cropped at panel edges or almost out of frame.

**Transfer:** Use original human-context photos and keep a clean text clearing. For a product without people photography, use tangible output or work-context details, not random decorative avatars.

**Build:** Use a 16px-radius overflow-hidden stage. Arrange 6–10 absolute image tiles, approximately 64–320px wide, around its edges; give them 12px corners. Mix sharp images with 4–20px blur, with smaller tiles farther from the central headline. Keep all tiles behind the text and away from action targets.

### Violet dot atmosphere

**Only for:** integration-page openings

**Use:** A centered technical promise with a softer ambient illustration.

**Observed:** Two diffuse purple halftone mounds rise from the lower sides of a paper hero while the middle stays clear for a centered headline, support copy and dark button.

**Transfer:** Use a low-contrast dot atmosphere around the text rather than the full collage used for a general landing page.

**Build:** Place two elliptical violet radial-gradient layers near the lower left and right, blur them by about 40px and apply a fine SVG dot mask. Fade to transparent toward the headline and outer edges; match the soft glow rather than exact stops.

### Portrait directory

**Only for:** company and culture pages

**Use:** Leadership or contributor profiles.

**Observed:** Four-column white cards with landscape headshots on olive studio backgrounds, then small outlined role labels and names.

**Transfer:** Use consistent original portrait framing and lighting; keep the directory separate from marketing capability grids.

### Icons

**Observed:** Simple SVG outlines at 16px and 24px, with 1.5px round-ended strokes; charcoal or warm gray. Carets sit beside nav labels, arrows finish inline actions, and tiny square bullets mark active tabs and labels.

**Transfer:** Use a consistent rounded outline set, not filled multicolor badges. Keep the square bullet as a distinct marker rather than replacing it with a checkmark everywhere.

## Section recipes

How recurring sections are built.

### First screen: Collage promise opening

**Observed:** A paper first screen sits below the white navigation and a separate black announcement strip. The two-line, left-aligned headline has display-scale thin black lettering and spans about three fifths of the width; the collage interlocks into the remaining right side and the lower middle. Layers run from paper and faint colored texture to blue/lime backing tiles, white interface cards and warm human photos, then the headline and controls. A narrower gray support paragraph and the Secondary button plus Primary button sit below the headline at left. Within 900px the whole promise, support, action pair and principal collage objects are visible, together with a centered small scroll cue at the bottom. Further chapters and the centered follow-up promise belong below this first screen.

**Transfer:** Write a two-part promise short enough to stay at monumental scale and build the interlocking collage around the words rather than shrinking the type. Without rich product artwork use the minimum Interlocking human-product collage recipe. Feature pages use a 90px left headline beside a single product scene; integration pages use a centered 90px promise and Violet dot atmosphere; pricing uses a centered 90px title above plan panels; company pages open with a centered 58px mission statement and a large video below.

**Avoid:** Do not replace the opening with a centered headline over a generic browser window, or let a wide paragraph push all imagery below the fold.

**Text style:** `display` — Phonic 300 · 130px/1 · tracking -0.09em

### Section heading and support

**Observed:** Heading at 58px light weight, a 24px gap to supporting copy, and another 24px gap to a compact action when present. Centered versions constrain prose to 520px; split versions align text left and can begin with an Outlined marker.

**Transfer:** Use one clear promise per chapter, followed by a practical explanation rather than a second headline.

**Text style:** `heading` — Phonic 300 · 58px/1.1 · tracking -0.06em

### Horizontal chapter island

**Observed:** A White panel with 20px corners and 40px internal breathing room holds three 90px chapter tabs across its top. Active tab is charcoal on stone; others are warm gray. Beneath, a 400px-wide text column with 46px heading sits beside a large purple-backed interface stage.

**Transfer:** Group three simple stages of the new product's story in this oversized selector, keeping the selected tab visually integrated into the panel.

**Text style:** `hero` — Phonic 300 · 90px/1 · tracking -0.07em

### Capability rail and demonstration

**Observed:** Capability selector rows stack at left. The 46px heading and compact support copy form two columns above the main media. An 880px-wide blue or violet Halftone image stage dominates the section; a softened neighboring stage peeks past the right boundary. Typical vertical breathing room is 80px.

**Transfer:** Use this for related capabilities or role-specific benefits; keep each selected scene a focused interaction rather than a complete application dashboard.

**Text style:** `heading-small` — Phonic 300 · 46px/1.15 · tracking -0.05em

### Statement and vocabulary field

**Observed:** A vivid Signal field holds a large 58px paragraph across roughly 1080px, with 120px section breathing room. After an 80px pause, two horizontal rows of white rounded chips carry 46px light capability names, with 16px between rows and faded outer edges.

**Transfer:** Include this expressive vocabulary device using the new product's actual methods, outputs or capabilities. It may appear at any suitable point in the story; preserve the oversized text and edge-faded motion.

**Text style:** `heading` — Phonic 300 · 58px/1.1 · tracking -0.06em

### Assurance grid

**Observed:** A centered heading and Primary button lead into a three-column, two-row Information card grid with 20px gaps and 112px stage padding. Small outlined labels introduce 22px explanatory copy.

**Transfer:** Use for compact practical assurances, constraints or reasons to trust; keep all card claims similar in length.

**Text style:** `body-large` — Phonic 300 · 22px/1.4 · tracking -0.03em

### Alternating human-context chapter

**Observed:** A 640px square Halftone image stage sits opposite a restrained copy block with Outlined marker, 58px question heading, body paragraph and arrow link. Chapters alternate media side and use 80px top and bottom breathing room.

**Transfer:** Ask a question the reader actually faces, then show the work context or output that resolves it.

**Text style:** `heading` — Phonic 300 · 58px/1.1 · tracking -0.06em

### Photographic outcomes

**Observed:** Warm documentary proof fills a broad band. A white 58px heading sits above three equal Outcome cards with 20px gaps. Their 46px claims are sentence-like, not isolated oversized numerals; white logos finish the cards.

**Transfer:** Make this a human proof moment, with substantiated outcomes integrated into readable statements.

**Text style:** `heading-small` — Phonic 300 · 46px/1.15 · tracking -0.05em

### Testimonial stage

**Observed:** One central sharp Quote portrait tile is flanked by clipped blurred cards. Square pagination dots sit below at left and two circular outlined arrows at right; an optional centered 58px heading introduces the stage.

**Transfer:** Preserve the portrait/quote balance and peripheral depth rather than presenting a conventional grid of quotation boxes.

**Text style:** `card-heading` — Phonic 300 · 28px/1.3 · tracking -0.04em

### Monumental closing invitation

**Observed:** A centered 130px promise spans two lines above Closing button and an outlined companion, with 32px between heading and actions. The default paper treatment leaves very generous 208px vertical breathing room; alternate white stages use Orbiting photographic close. Feature announcements can align this promise left. Smaller company and integration closes use 58px or 90px headings and compact actions.

**Transfer:** Include a monumental closing line and a clear next step; the photo orbit can move to another suitable proof or conversion stage. Keep the central message readable regardless of the surrounding imagery.

**Text style:** `display` — Phonic 300 · 130px/1 · tracking -0.09em

### Questions and final directory

**Observed:** FAQ row items occupy a 600px right column beside a large left heading, with 32px between rows. A Footer then returns to paper: four link columns, newsletter card and lime social bar, followed by a giant identity mark and understated legal text.

**Transfer:** Use FAQs where real objections exist, and preserve the footer's large identity gesture even when the link directory is shorter.

**Text style:** `card-heading` — Phonic 300 · 28px/1.3 · tracking -0.04em

### Comparison ledger

**Only for:** pricing pages

**Observed:** Two Plan panels follow the centered opening. A capability rail precedes the full comparison ledger: three aligned columns, 64px rows, alternating stone fills with 8px corners, uppercase group labels and 15px cell text. Checkmarks sit in small lime circles.

**Transfer:** Keep package choice broad and calm, then let the ledger handle detailed distinctions. Do not force a numeric monthly price into a custom-sales plan.

**Text style:** `comparison` — Phonic 400 · 15px/1.4 · tracking -0.02em

### Company proof and principles

**Only for:** company and culture pages

**Observed:** The centered mission leads to a wide rounded video with a large pill Play control. A three-card scale summary, Portrait directory and investor logos give way to a three-by-two principle grid using 28px titles and 17px copy.

**Transfer:** Tell the organization's story through real people and specific working principles, not through generic product-feature cards.

**Text style:** `card-heading` — Phonic 300 · 28px/1.3 · tracking -0.04em

## Page flow

**Storyline:** promise → tangible demonstration → credibility → capability chapters → human outcomes → decisive invitation → useful final directory

### Broad platform marketing

1. **Promise** — Monumental collage opening and a centered follow-up promise.
2. **Product demonstration** — Large horizontal chapter island, logo strip and editorial product panel.
3. **Capability breadth** — Signal field and moving vocabulary, followed by assurance grid.
4. **Social proof** — Portrait quotes, mint editorial resource and photographic outcome cards.
5. **Closing call** — Monumental invitation with paired actions.
6. **Final directory** — Newsletter, social strip, link columns and giant identity.

**Transfer:** Use breadth and contrast to communicate a platform; alternate expressive devices with concrete explanations rather than copying a fixed section sequence.

### Company narrative and hiring

1. **Mission** — Centered editorial mission over a wide video.
2. **Credibility** — Compact organization facts, portrait directory and investor strip.
3. **Principles** — Six simple icon-led cards.
4. **Product connection** — Horizontal chapter island and photographic outcomes reconnect culture to the product.
5. **Closing call** — Human-photo invitation to join, then the shared footer.

**Transfer:** Substitute authentic people, operating beliefs and a relevant next step; keep the human photography coherent.

### Flagship feature explanation

1. **Promise** — Split 90px headline and purple-backed interface scene with paired actions.
2. **Product demonstration** — Logo proof and vertical capability rail, then an inverse announcement film.
3. **Use cases** — Alternating photo-backed question chapters.
4. **Social proof** — Large demonstration and portrait testimonial carousel.
5. **Closing call** — Left-aligned monumental conversion stage with floating photographs.
6. **Objection handling** — Two-column FAQ before the shared footer.

**Transfer:** Explain one feature through realistic decisions and outputs, maintaining media scale and practical language.

### Integration or technical capability marketing

1. **Promise** — Centered headline with violet dotted atmosphere and compatible-tool strip.
2. **Problem framing** — One human-context split chapter.
3. **Capability explanation** — Centered introduction over three illustrated cards, followed by role-based capability tabs.
4. **Objection handling** — Concise FAQ.
5. **Closing call** — A centered judgment-oriented invitation and shared footer.

**Transfer:** Keep the opening calmer than the platform collage; prioritize context, interoperability and practical uses.

### Package selection and detailed comparison

1. **Orientation** — Centered title and concise value-oriented support copy.
2. **Pricing** — Two wide plan panels with tall tinted image inserts and feature lists.
3. **Product demonstration** — Capability rail explains what the plans enable.
4. **Comparison** — Long grouped ledger with alternating rows and restrained checks.
5. **Closing call** — Centered monumental invitation in a photographic orbit, then shared footer.

**Transfer:** Separate high-level package decisions from detailed entitlement comparison; use expressive media to prevent the page from becoming only a spreadsheet.

## Writing

Confident, curious and practical. The language balances speed with thoughtfulness and uses concrete consequences to explain sophisticated technology.

**Do not copy:** Do not reuse Maze names, logos, proprietary product imagery, customer identities, quotes, participant counts, performance statistics or market claims. Replace every claim and example with substantiated information for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your team. The product is named as an active helper; we is used for the organization and its beliefs, not as a constant sales refrain.
- **Rhythm:** Short, often two-part headlines; conversational questions introduce use cases. Supporting prose usually takes one to three sentences, with em dashes and contrasts doing more work than exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Pair a desired pace or outcome with a reassuring counterweight. | 5–10 words | “AI speed, meet research rigor”<br>“Insights where you work” |
| Supporting line | Explain what changes in the reader's existing workflow and why that matters. | 20–40 words | “[Brand] MCP brings research findings into your AI tools, so decisions are made with real insights in context.” |
| Section heading | Name an everyday friction or ask the decision the reader needs to resolve. | 5–12 words | “The research was already done. Nobody found it.”<br>“Is this the right problem to solve?” |
| Primary action | Use a familiar verb and an explicit destination or activity. | 2–4 words | “Get a demo”<br>“Read the report” |
| Outcome claim | Embed a measured result in a readable benefit sentence. | 5–10 words | “Source user feedback in 1-2 days, not weeks” |
| Closing line | Make the reader's future advantage feel immediate and achievable. | 4–7 words | “Make learning your advantage”<br>“Scale your impact now” |

**Words and phrasing to use:** what matters; your team; in context; built for; without the overhead; ready to act on; thoughtfully; confidence

**Avoid:** revolutionary; disruptive; unleash the power; magic; 10x everything; best-in-class without support

**Rules:**

- Lead with the user's decision or result, then explain the mechanism.
- Use a specific contrast such as speed versus rigor or existing work versus missing visibility.
- Let one short label categorize a chapter; do not duplicate the headline in the eyebrow.
- Keep capability names concrete enough to work as short moving vocabulary chips.
- Use questions to open a use case, not to undermine confidence in the main promise.

## Do's and Don'ts

### Do

- Set large headings at weight 300 and preserve the tighter tracking as size increases.
- Keep desktop content within the 1440px framework and use 40px outer gutters.
- Pair an 8px-radius dark primary action with a fully rounded outlined secondary.
- Use 20px gaps for equal proof cards and 16px inner padding for compact information cards.
- Give product media a colored halftone backing and leave visible texture around the foreground image.
- Include both an edge-faded vocabulary device and the giant final identity treatment.
- Let full-width photography support large sentence-form outcomes rather than disconnected number counters.
- Keep supporting copy around 520px wide in centered compositions.

### Don't

- Do not use heavy bold weights to compensate for smaller headlines; the scale and weight-300 contrast are essential.
- Do not turn all actions into the same pill shape; filled and outlined controls have different silhouettes.
- Do not cover every section in saturated gradients; paper and white remain the reading grounds.
- Do not apply heavy elevation to ordinary cards; reserve the faint 4px/30px shadow for navigation.
- Do not replace the square label bullet with colored pictograms or ubiquitous checkmarks.
- Do not make every media panel a whole browser screenshot; isolate product interactions and mix them with people.
- Do not use cold stock-business portraits for the photographic outcome band; warm, tactile context carries the proof.
- Do not shrink the footer identity to a small repeated header logo or put the giant mark above all navigation links.

## Motion and responsive

### Motion

**Observed:**

- Compact actions declare color transitions of .15s cubic-bezier(.4,0,.2,1).
- The page background declares 0.7s color transitions with cubic-bezier(0,0,.2,1); colored editorial fields can change with section context.
- Scroll animations declare 32s linear and 60s linear infinite variants, including a reverse direction.
- Photo glass cards declare all-property transitions of 0.5s cubic-bezier(.4,0,.2,1).

**Transfer:**

- Keep the two vocabulary rows moving in opposing directions with faded edges.
- Use background-color shifts to emphasize an expressive chapter rather than animating every paragraph.
- Maintain one sharp active testimonial and soften peripheral cards to communicate carousel depth.

**Unknown:**

- Exact trigger positions, sequencing and duration of the opening collage transition.
- Full timing of photographic-orbit depth changes and reduced-motion behavior.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1440px among several finer adjustments.
- Typography uses the clamp formulas provided with each recipe.
- Capability selectors switch from full-width vertical rows to horizontally scrolling snap layouts below the desktop variant.
- Card grids declare a single-column base and three-column desktop variant; the footer directory declares two columns before four.

**Transfer:**

- On narrow screens keep the large promise first, then support and actions, followed by a compact collage with fewer simultaneous tiles.
- Keep colored media backing visible rather than reducing every graphic to an unframed image.
- Use horizontal snapping for capability and outcome sequences, preserving the square active marker.
- Let the footer directory stack above its newsletter and retain a viewport-spanning identity treatment.

**Unknown:**

- Exact rendered mobile compositions and spacing at each breakpoint.
- Touch behavior of the opening scroll scene.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
