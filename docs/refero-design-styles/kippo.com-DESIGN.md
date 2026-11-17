# Kippo — neon terminal playground

## Overview

A black, arcade-inflected style with widely spaced monospaced capitals, hot pink commands and floating product collages. Charcoal utility panels and faint outlines give the page a technical scaffold while colorful cards and human imagery keep it playful. It suits consumer apps and community-oriented products, with sparse copy inside large, theatrical product stages.

### Essentials

- Headlines feel like arcade commands: Source Code Pro 42px/50px, weight 700, uppercase with 5px tracking; one meaningful word turns #ee1f66 while the rest stays white.
- The opening is a framed product theater: a 1170px-wide, 662px-tall outlined stage with 15px corners, a left-hand promise and a roughly 363px-wide upright product object breaking the frame on the right.
- Commands are rounded rectangles, not capsules: hot pink buttons measure 265px by 45px with 10px corners, 12px bold capitals and 5px tracking, led by a small white circular download arrow.
- Black owns most of the page: #29292a is confined to navigation, compact tips and the closing directory; vivid yellow–pink and blue–mint gradients appear as small floating proof cards and product backing rather than full-width bands.
- Product evidence floats beyond its scaffold: overlapping interface cards, portrait mosaics and upright devices occupy about half a chapter, with slight perspective and saturated rounded backing plates. Recreate this with real interface panels if no device media exists.
- Technical annotations punctuate the theater: compact 265px charcoal panels use 10px/20px capitals with 4px tracking, prompt chevrons and numbered tips; bright testimonial cards provide a complementary human proof device.
- The ending becomes a charcoal directory: a 1170px panel with 15px corners, a 16px tracked heading, three equal link columns, a subdued brand mark and a lower action-and-legal row.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot pink command | `#ee1f66` | `--color-action` | text, action, accent | Single emphasized words, key numbers and primary button fills. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden proof | `#ffc400` | `--color-yellow` | surface, accent | Warm endpoint of small yellow-to-pink proof cards and colorful product backing. |
| Electric pink | `#ff33e0` | `--color-magenta` | surface, accent | Opposite endpoint of warm proof-card gradients. |
| Electric blue | `#33beff` | `--color-blue` | surface, accent | Left endpoint of blue-to-mint press cards and cool product backing. |
| Arcade mint | `#33ffb8` | `--color-mint` | surface, accent | Right endpoint of blue-to-mint press cards and cool product backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black canvas | `#000000` | `--color-canvas` | background, text | Dominant page background and dark text on bright proof cards. |
| Subtle stage edge | `#262626` | `--color-edge` | border | Visible result of white at 15% opacity over black; use rgba(255,255,255,0.15) for stage outlines. |
| Charcoal panel | `#29292a` | `--color-panel` | surface, background | Solid navigation, tip cards and closing directory. |
| Review silver | `#cfcfcf` | `--color-silver` | surface | Left endpoint of silver-to-white review cards. |
| White signal | `#ffffff` | `--color-text` | text, accent | Primary headings, annotations, navigation and action labels. |

## Typography

- **Source Code Pro** — All marketing headings, labels, navigation and prose. Square, readable monospace with a coding-terminal rhythm; bold capitals carry the hierarchy. OpenType features: "zero". Font stack: "Source Code Pro", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Source Code Pro | 700 | 42px | 50px | 5px, uppercase | Opening promise, feature chapter headings and quantified proof. |
| section-label | Source Code Pro | 700 | 16px | 30px | 5px, uppercase | Credibility line, press-strip heading and closing directory title. |
| action | Source Code Pro | 700 | 12px | 20px | 5px, uppercase | Primary action labels. |
| annotation | Source Code Pro | 400 | 10px | 2 | 4px, uppercase | Tip-card copy, prompt rows and footer directory links. |
| navigation | Source Code Pro | 600 | 10px | 2 | 5px, uppercase | Short top-level navigation links. |
| quote | Source Code Pro | 400 | 10px | 2 | 0.1em | Sentence-case testimonial and editorial quotes on bright cards. |

**Notes:**

- Use the same display recipe for the opening, feature chapters and large proof number; hierarchy comes from composition and pink emphasis rather than continually changing sizes.
- Tracking stays conspicuously positive even in large headings. Small utility text has 4–5px tracking, while long quotations tighten to 1px and retain sentence case.
- Enable the slashed-zero feature throughout. Limit uppercase support copy to short phrases because its tracking consumes substantial width.

## Layout

**Density:** Airy stages with compact technical islands: tall product chapters surround tiny labels and tightly grouped conversion panels.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Navigation gaps and compact internal separations. |
| 15px | Tip padding, action icon-to-label gap and spacing between store badges. |
| 20px | Horizontal padding on bright proof cards. |
| 25px | Heading-to-support spacing and tip-to-button separation. |
| 30px | Stage interior padding and directory side padding. |
| 35px | Directory vertical padding and title-to-links separation. |
| 50px | Headline-to-tip/action grouping and links-to-bottom-row separation. |
| 100px | Closing directory section top and bottom padding. |
| 150px | Feature chapter top padding and opening bottom padding. |
| 200px | Opening top padding before the outlined stage. |

### Containers and grids

- **stage-container**: max width 1170px · side padding 30px. Centered desktop stages and utility panels; at 1440px the outer margins are 135px.
- **feature-split**: 2 columns · gap 0px. Two equal 554px inner columns across a 1108px content row; one holds the product collage and one the left-aligned headline and compact conversion stack. Reverse the sides between chapters.
- **directory-columns**: 3 columns · gap 0px. Three equal 370px columns across the 1110px footer interior.
- **press-rail**: gap 30px. Full-width overflow rail of 150px by 98px logo cells, extending beyond the centered content edges.

## Corner radius

| Element | Radius |
| --- | --- |
| stage-and-directory | 15px |
| tips-buttons-proof-cards | 10px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** Continuous background through the entire narrative.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** No alternating light section bands; open black space separates outlined chapters.

**Transfer:** Keep the surrounding field uninterrupted so product objects and proof cards supply the visual variety.

#### Outlined stage · level 1

**Use:** Opening, feature demonstrations and the final proof chapter.

**CSS:** `border: 1px solid rgba(255,255,255,0.15); border-radius: 15px; padding: 30px; background: #000000`

**Observed:** The border is a faint enclosure rather than a raised card; media can extend beyond it.

**Transfer:** Use the enclosure to hold a single benefit and its visual demonstration.

#### Charcoal utility · level 1

**Use:** Navigation, compact tips and the directory.

**CSS:** `background: #29292a; border-radius: 10px; box-shadow: none`

**Observed:** Small tips use the default corners; navigation and the closing panel expand to 15px corners.

**Transfer:** Reserve solid charcoal for practical reading and navigation, not every feature backdrop.

#### Bright proof cards · level 2

**Use:** Floating testimonial and press quotations.

**CSS:** `background: linear-gradient(to right, #33beff, #33ffb8); color: #000000; border-radius: 10px; padding: 15px 20px`

**Observed:** Companion cards use yellow-to-electric-pink and silver-to-white gradients; cards overlap in a gently tilted cluster.

**Transfer:** Retain the mixed gradient family in small proof artifacts, with dark readable text.

## Components

### Floating navigation

**Use:** Persistent top-level navigation.

**CSS:** `background: #29292a; border-radius: 15px; max-width: 1170px; height: 60px; padding-left: 20px; padding-bottom: 10px`

**Observed:** A fixed shell sits 15px from the top, with a compact white wordmark at the left and a short right-aligned link group. The shell remains visible near the ending.

**Transfer:** Use a compact distinctive logotype and two or three utility destinations.

### Navigation link

**Use:** Top-level destinations.

**CSS:** `color: #ffffff; padding: 20px 10px 10px; background: transparent`

**Text style:** `navigation` — Source Code Pro 600 · 10px/2 · tracking 5px · uppercase

**Observed:** Text-only labels sit in a horizontal group with 10px gaps; the current link has slightly less bottom padding.

### Primary command

**Use:** Repeated chapter conversion.

**CSS:** `background: #ee1f66; color: #ffffff; border-radius: 10px; padding: 10px 15px; width: 265px; height: 45px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — Source Code Pro 700 · 12px/20px · tracking 5px · uppercase

**Observed:** A small filled circular down-arrow precedes the label with 15px separation. The command aligns to the tip card above it, forming one narrow conversion unit.

**Transfer:** Choose one brief conversion verb and repeat the same action across relevant chapters.

### Terminal tip

**Use:** Explain a feature beneath its headline.

**CSS:** `background: #29292a; border-radius: 10px; padding: 15px; width: 265px; margin-bottom: 25px`

**Text style:** `annotation` — Source Code Pro 400 · 10px/2 · tracking 4px · uppercase

**Observed:** A subdued numbered tip heading starts with a chevron; an empty prompt line separates it from the brighter explanation, also led by a chevron. Copy wraps into short stacked lines; panel height grows from 130px to 170px.

**Transfer:** Use a short practical note rather than a dense feature list.

### Feature stage

**Use:** Reusable two-sided product chapter.

**CSS:** `max-width: 1170px; height: 662px; padding: 30px; border: 1px solid rgba(255,255,255,0.15); border-radius: 15px; position: relative`

**Observed:** Equal text and media halves sit inside the frame. The illustration breaks its enclosure while the headline and narrow tip/action stack remain orderly.

**Transfer:** Show one capability per stage and alternate the visual side to establish rhythm.

### Proof quote card

**Use:** User and editorial credibility.

**CSS:** `background: linear-gradient(to right, #33beff, #33ffb8); color: #000000; border-radius: 10px; padding: 15px 20px; width: 366px`

**Text style:** `quote` — Source Code Pro 400 · 10px/2 · tracking 0.1em

**Observed:** Quote text sits above an attribution and publication mark. Smaller companion cards carry a user identity or star rating on warm and silver gradients; the cluster is not an equal-tile grid.

**Transfer:** Use genuine quotations, short author details and one compact logo or rating device.

### Store badge pair

**Use:** Direct platform acquisition in the opening and directory.

**CSS:** `display: flex; align-items: center; gap: 15px; height: 45px`

**Observed:** Two official marketplace artworks sit side by side at 137px and 153px wide. A white-on-black QR code sits below the opening pair, not in the directory.

**Transfer:** For a non-mobile product, use two equally compact destination or compatibility badges and a real scannable action where useful.

### Closing directory

**Use:** Final navigation, community links and acquisition.

**CSS:** `background: #29292a; border-radius: 15px; padding: 35px 30px; max-width: 1170px`

**Text style:** `annotation` — Source Code Pro 400 · 10px/2 · tracking 4px · uppercase

**Observed:** A tracked title and subdued logo lead three link columns, each link preceded by a prompt chevron. A lower row pairs store badges at left with a compact legal block at right; there is no email input.

**Transfer:** Group community channels, product destinations and practical policies into the same three-column directory.

## Imagery and graphics

### Hero device with chromatic plates

**Use:** Main opening visual and signature product theater.

**Observed:** A dark upright smartphone, approximately 363px by 710px, displays a four-photo profile interface and floats above two offset rounded chromatic silhouettes. The phone occupies the right third of the frame and slightly exceeds the stage vertically; a hand-pointer accent makes the demonstration feel interactive.

**Transfer:** Use the new product's actual interface in a dark device or upright panel. Without device artwork, frame one polished interface panel with a dark rim and layered colored backing; retain the dimensional silhouette.

**Build:** Place a roughly 350px-wide upright rounded product panel above two similarly proportioned plates. Offset one plate up and left and fill it with a yellow-to-pink vertical gradient; offset the second down and right and fill it with a blue-to-mint vertical gradient. Leave roughly 20–30px of each backing visible. Keep these shapes crisp, not blurred or luminous.

### Floating capability collage

**Use:** Demonstrate individual benefits inside the repeated stages.

**Observed:** Overlapping rounded portrait mosaics and game-image cards float in the first chapter, with slight perspective, crisp light edging and restrained local glow. Other chapters use a fan of profile cards, a matched-state phone with small floating graphic accents, and detached message bubbles alongside a GIF. The visual mass balances a half-width text block and often crosses the frame.

**Transfer:** Compose actual interface excerpts, content tiles and relevant human imagery into a small depth stack. Preserve natural photo color and vivid media tiles against black; the minimum version is two overlapping interface panels plus one small content tile.

**Build:** Create an absolutely positioned collage in a 554px-wide half-stage. Overlap two rounded content panels, one behind and slightly lower; apply a shallow perspective rotation and a thin white edge to the front panel. Add two or three smaller rounded content tiles below or to the side, keeping ample black negative space. Use perspective as an accent rather than tilting every text label.

### Floating proof sculpture

**Use:** Human evidence alongside a pink quantified headline.

**Observed:** Three different-sized rounded quotation cards overlap in depth: a warm gradient user card, a silver review card and a blue-to-mint press card. Dark prose contrasts with the bright fills; the overall group leans gently in perspective and extends beyond the stage's left boundary.

**Transfer:** Make the same visual sculpture from authentic quotes or compact proof artifacts. Retain at least one bright proof card even when only one testimonial is available.

**Build:** Use 276px, 327px and 366px-wide cards with 10px corners and 15px 20px padding. Stack them at staggered vertical positions, with the middle silver card forward. Apply a shared rotateX(10deg) rotateY(-10deg) treatment to the group; keep the adjacent headline level.

### Press logo rail

**Use:** Early third-party credibility.

**Observed:** Two repeated horizontal runs of publication marks appear on black, clipped at both viewport edges. Logos retain recognizable white and selective native colors rather than living inside cards.

**Transfer:** Use real partner or publication marks with balanced optical sizing in open 150px-wide cells; the repeated rail supplies breadth without extra copy.

### Icons

**Observed:** Filled white 12px circular download arrows accompany primary commands; black 14px stars support review cards. Text chevrons serve as prompt markers in tips and footer links.

**Transfer:** Prefer compact filled utility glyphs and typed prompt chevrons; avoid a large decorative outline-icon library.

## Section recipes

How recurring sections are built.

### First screen: Framed product opening

**Observed:** A fixed Floating navigation bar sits above a generous black interval. The Outlined stage begins after 200px of top padding, spans 1170px and stands 662px tall. In its left half, the 42px uppercase promise occupies about two lines, with the category word alone in pink; a 16px credibility line follows. The Store badge pair and a white QR code sit lower in that same column. In front of the black field and faint frame, the right-hand device rises above the top edge and runs almost to the bottom of the first 900px, with chromatic plates behind it. The headline, support, acquisition controls, QR and main object are all visible within the first screen; the press rail begins below it.

**Transfer:** Keep a concise category promise at left and one oversized real product object at right. If no phone demo exists, use an upright interface panel with the same colorful offset plates and frame-breaking scale. Other page purposes can replace the acquisition pair with one equally compact command while retaining the stage hierarchy.

**Avoid:** Do not replace the asymmetric upright object with a centered laptop under a giant headline, or add a full-bleed gradient behind the entire opening.

**Text style:** `display` — Source Code Pro 700 · 42px/50px · tracking 5px · uppercase

### Credibility rail

**Observed:** A 16px Section-label heading introduces the Press logo rail on the uninterrupted Black canvas. Logo cells have a 30px horizontal gap and overflow beyond the content width.

**Transfer:** Use a brief proof label and a wide rail of recognizable third-party marks rather than a paragraph of praise.

### Alternating capability stage

**Observed:** Each Feature stage follows 150px of top breathing room. A Floating capability collage fills one half; the opposite side carries a white display heading with one pink word, then a Terminal tip and Primary command. The text-to-conversion group is separated by 50px; tip and command are separated by 25px. Text and media swap sides across chapters.

**Transfer:** Select one visible capability and one outcome per chapter. Keep the artwork varied while reusing the same heading, tip and action construction.

**Text style:** `display` — Source Code Pro 700 · 42px/50px · tracking 5px · uppercase

### Quantified proof theater

**Observed:** A Floating proof sculpture occupies the left side of an Outlined stage. A white display statement at right embeds a pink multi-digit number, followed by the Terminal tip and Primary command. The statistic uses the same 42px recipe as feature headings, not a separate oversized numeral font.

**Transfer:** Pair a defensible metric with human evidence; adapt the metric type to the product instead of manufacturing scale.

**Text style:** `display` — Source Code Pro 700 · 42px/50px · tracking 5px · uppercase

### Directory ending

**Observed:** The final section has 100px top and bottom padding around Closing directory. Its 16px title and low-contrast mark precede three equal link columns. A 50px separation leads to the Store badge pair and compact legal block. The ending remains charcoal on black rather than turning into a large slogan or newsletter form.

**Transfer:** Close with useful destinations and a compact acquisition reminder. Preserve the substantial panel and prompt-led link treatment even for a shorter site.

**Text style:** `section-label` — Source Code Pro 700 · 16px/30px · tracking 5px · uppercase

## Page flow

**Storyline:** Audience promise → third-party recognition → visual capability chapters → quantified and human proof → practical directory and acquisition reminder.

### Consumer product landing page that explains fit, demonstrates the experience and converts interest

1. **Promise** — An outlined split stage combines a short audience-specific headline, a credibility line, compact acquisition controls and an oversized product object.
2. **Social proof** — An edge-clipped repeated rail of recognizable publication marks.
3. **Capability chapters** — Alternating framed demonstrations pair one benefit headline with a prompt-style tip and repeated command.
4. **Quantified proof** — A pink adoption figure balances a dimensional cluster of vivid user and press quotes.
5. **Closing navigation** — A rounded charcoal directory ends with community, product and policy links plus a smaller acquisition row.

**Transfer:** Use this as an adaptable progression from fit to experience to trust. Chapter count and placement can change; retain the framed theater, terminal annotations and floating proof devices.

## Writing

Confident, direct and friendly, with a gamer-terminal presentation rather than technical jargon. Headlines celebrate personal outcomes; supporting copy names simple actions the reader can take.

**Do not copy:** Do not reuse Kippo's name, logos, character or game artwork, quoted testimonials, publication endorsements, ranking claims or download figures. Replace them with original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Name concrete user actions; the product is a facilitator, not the narrator of a long company story.
- **Rhythm:** Short benefit headings, often 3–8 words, followed by one practical sentence. Capitals are a visual treatment; quotations retain natural sentence case. Repeat one short conversion label.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and the audience in one compact statement; emphasize the audience word. | 5–8 words | “The Dating App for Gamers” |
| Capability headline | Start with an action or outcome and make one verb or key noun the colored pivot. | 3–8 words | “Show off your unique personality”<br>“Make connections real” |
| Tip support | Explain how the capability works in one reader-centered sentence. | 10–20 words | “Match with people based on your favorite games & more”<br>“Customize your profile with our card deck system to show off your unique personality” |
| Primary action | A concrete action plus a low-friction qualifier. | 2–4 words | “Download for free” |
| Directory title | Plain invitation to remain connected. | 2–3 words | “Stay Updated” |

**Words and phrasing to use:** you; your; connect; share; show off; together; favorite; unique; for free

**Avoid:** synergize; enterprise-grade transformation; revolutionary ecosystem; long abstract manifesto language

**Rules:**

- Tie each pink headline word to the main benefit rather than coloring an arbitrary word.
- Keep prompt-panel copy concrete enough to explain the adjacent visual.
- Use rankings and scale only when supportable; let authentic quotes carry warmth.
- Use community language without overloading every sentence with gaming slang.

## Do's and Don'ts

### Do

- Keep display text at 42px/50px with 5px tracking and weight 700.
- Use one pink word or number against white within a major heading.
- Center the major frames at 1170px and keep 30px inner padding.
- Keep 265px tip cards and commands aligned as a single compact unit.
- Let the upright product object and floating cards cross the 15px-radius stage boundary.
- Include small vivid gradient proof cards with black text and 10px corners.
- End with a three-column charcoal directory and a compact lower acquisition row.

### Don't

- Do not replace Source Code Pro with a proportional geometric sans for marketing headlines.
- Do not tighten display tracking to the negative values typical of SaaS display type.
- Do not convert the 10px-radius commands into fully rounded pills.
- Do not fill every chapter with #29292a; the faint frame sits on black.
- Do not apply soft drop shadows to all utility panels; their separation comes from fill and outline.
- Do not enlarge the metric beyond the shared 42px heading scale merely because it is a number.
- Do not make testimonials a uniform white three-card grid; preserve staggered size and chromatic variety.
- Do not turn the closing directory into an email signup form or an oversized closing slogan.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
