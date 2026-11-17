# Made With Gsap — playful interaction laboratory

## Overview

An exhibition-like digital style that pairs a white gallery entrance with long, near-black stages and a bright white finale. Medium-weight grotesk lettering and tiny uppercase mono captions make expressive motion experiments feel catalogued rather than chaotic. Lime accents, pastel benefit cards, miniature photographic collages and framed website demonstrations suit creative tools and products whose value is best experienced visually. Text stays compact while the main objects have room to perform.

### Essentials

- The opening behaves like a gallery, not a billboard: a 900px white stage, a 504×284px central demonstration, and a 47.5px headline split into left and right phrases across its midpoint; supporting copy and a black action sit at the lower left.
- Type alternates between friendly speech and catalogue notation: LayGrotesk at weight 500, 48px/1.02 section headings with -0.02em tracking, and 11–13px uppercase PPNeueMontrealMono labels with normal tracking.
- Actions are small capsules against enormous breathing room: 50px height, 25px radius and 25px horizontal padding; lime is the conversion color, black is the action on white, and white or pale gray handles exploration.
- Most of the long-form page is near-black #0a0a0b; white is reserved for the entrance, selected proof or trial panels and the monumental ending. Lime #c9fe6e occupies small actions and a few featured cards, not a continuous page wash.
- Media is a specimen inside a specimen: 331×186px landscape demonstrations sit within 453px square cards with 20px corners, followed by tiny mono identifiers outside the card. Use a real product sequence or a composed mini-scene when footage is unavailable.
- Playful scale changes are a signature: include a fanned set of numbered pastel benefit cards with 120px numerals at 20% opacity, and an oversized two-line closing invitation at 140px/0.85 with -0.03em tracking. These devices can live wherever the new narrative needs them.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#c9fe6e` | `--color-lime` | action, surface, accent | Conversion capsules, count highlights and selected benefit or featured project cards. |
| Ice blue | `#bcefff` | `--color-ice` | surface | One of the pastel cards in the numbered benefit fan. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0a0a0b` | `--color-ink` | background, text, action | Main dark canvas, text on white and black action capsules. |
| Panel charcoal | `#232323` | `--color-panel` | surface, action, border | Testimonials, pricing shell, secondary dark actions and avatar edges. |
| Raised charcoal | `#323232` | `--color-edge` | surface, border | Hairline dividers; square project backings in portfolio galleries. |
| Caption gray | `#999999` | `--color-muted` | text, link | Descriptions on dark, metadata and quiet helper copy. |
| Specimen gray | `#f3f3f3` | `--color-pale` | surface, action | Light media cards, navigation capsule, secondary actions and email form. |
| Gallery white | `#ffffff` | `--color-white` | background, surface, text, action | Entrance, finale, trial and price panels; primary text on dark stages. |

## Typography

- **LayGrotesk** — Headlines, prose, prices and large numerals. A fluid, relatively compact grotesk with open forms and a medium visual weight. OpenType features: "cswh", "dlig", "hlig", "kern", "liga", "ss02". If unavailable, use **DM Sans**. Use 500 and preserve tight heading tracking. Font stack: "LayGrotesk", "DM Sans", Arial, sans-serif.
- **PPNeueMontrealMono** — Navigation, actions, specimen identifiers, author credits and utility labels. Compact mechanical monospace that gives expressive objects a catalogue frame. OpenType features: "cswh", "dlig", "hlig", "kern", "liga", "ss02". If unavailable, use **IBM Plex Mono**. Use 500; keep capitals and normal tracking. Font stack: "PPNeueMontrealMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing | LayGrotesk | 500 | 140px | 0.85 | -0.03em | Monumental two-line final invitation. |
| benefit-number | LayGrotesk | 500 | 120px | 1 | normal | Low-opacity central numeral on each benefit card. |
| heading-lg | LayGrotesk | 500 | 65px | 1.02 | -0.02em | Major conversion and proof headings; also the large price. |
| heading | LayGrotesk | 500 | 48px | 1.02 | -0.02em | Default centered section heading. |
| opening | LayGrotesk | 500 | 47.5px | 1.02 | -0.02em | Split single-line promise flanking the central demonstration. |
| heading-sm | LayGrotesk | 500 | 30px | 1.02 | -0.02em | Trial panel heading and newsletter invitation. |
| subheading | LayGrotesk | 500 | 22px | 1.2 | normal | Footer column headings and pricing period selector. |
| body | LayGrotesk | 500 | 18px | 1.4 | normal | Supporting paragraphs, quotes and feature titles. |
| action | PPNeueMontrealMono | 500 | 13px | 1.615 | normal, uppercase | Text inside navigation and action capsules. |
| label | PPNeueMontrealMono | 500 | 13px | 1.49 | normal, uppercase | Eyebrows, drag instructions and footer links. |
| helper | LayGrotesk | 500 | 12px | 1.4 | -0.02em | Compact reassurance beneath actions or forms. |
| caption | PPNeueMontrealMono | 500 | 11px | 1.39 | normal, uppercase | Specimen captions, testimonial credits and pricing feature-group labels. |
| badge | PPNeueMontrealMono | 500 | 11px | 3.18 | normal, uppercase | Dates and numeric references inside small white capsules. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| portfolio index pages | gallery-display | LayGrotesk | 500 | 120px | 0.95 | -0.02em | Left-aligned index title with a matching count at the opposite edge. |

**Notes:**

- Keep most lettering at weight 500; hierarchy comes from scale, color and placement rather than a bold-weight ladder.
- Headings through 65px use -0.02em tracking and 1.02 line height. The 140px closing line tightens to -0.03em and 0.85 line height.
- Mono text is uppercase and untracked: do not substitute widely letterspaced luxury-style labels.
- The small opening headline leaves the demonstration dominant; the largest type belongs to narrative statements and the ending.

## Layout

**Density:** Airy stages with compact cards: long dark pauses surround densely organized specimens and small utility text.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Inset around two-part trial and pricing panels; feature title to paragraph. |
| 15px | Card gutters, media-to-title spacing and grouped action gaps. |
| 20px | Opening paragraph to action. |
| 25px | Outer page margin and capsule horizontal padding. |
| 30px | Testimonial inner padding. |
| 50px | Heading to feature row, gallery row gaps and two-part panel interior gap. |
| 70px | Vertical grouping within the white pricing panel. |
| 150px | Major section lead-ins and separation around proof or trial blocks. |
| 200px | Large chapter separation and end of the workflow section. |
| 280px | Quiet space below footer columns before the final legal row. |

### Containers and grids

- **page grid**: max width 1440px · 12 columns · gap 15px · side padding 25px. Broad desktop composition with a persistent outer margin.
- **specimen grid**: 3 columns · gap 15px. Three equal square cards across the content width, 453px per card at desktop; 50px between rows.
- **conversion panel**: max width 896px · gap 50px. Centered two-part panel with a 440px media or price half and a narrower explanatory half.
- **section heading**: max width 580px. Centered default headline block; larger proof invitations can span 870px.
- **opening support**: max width 366px. Short paragraph and one action anchored low on the left.
- **horizontal rail**: gap 15px. Feature cards are 453px wide; testimonial cards are 385px wide. Both rails continue beyond the right edge instead of shrinking every card to fit.

## Corner radius

| Element | Radius |
| --- | --- |
| main capsules | 25px |
| specimen cards | 20px |
| quote and price cards | 12px |
| small badges | 18px |
| landscape media | 4px |
| avatars | 50% |

## Surfaces and depth

### Surfaces

#### Dark stage · level 0

**Use:** Default long-form canvas.

**CSS:** `background: #0a0a0b; color: #ffffff`

**Observed:** Broad, flat dark chapters with no texture or elevated shadow treatment.

**Transfer:** Let the objects and type supply spectacle rather than adding ambient gradients.

#### White gallery · level 0

**Use:** Opening stage and closing pavilion.

**CSS:** `background: #ffffff; color: #0a0a0b`

**Observed:** The entrance is edge-to-edge white. The final pavilion has rounded outside corners and a narrow dark surround.

**Transfer:** Use the inversion as an intentional change of scene.

#### Light specimen backing · level 1

**Use:** Demonstration cards.

**CSS:** `background: #f3f3f3; border-radius: 20px; box-shadow: none`

**Observed:** A generous square matte around a much smaller landscape image.

**Transfer:** Preserve the large backing-to-image ratio.

#### Charcoal panel · level 1

**Use:** Quote cards and grouped purchase content.

**CSS:** `background: #232323; border-radius: 12px; color: #ffffff`

**Observed:** Flat charcoal differentiates content without shadows. The larger pricing shell uses 20px corners.

**Transfer:** Use tonal separation rather than raised dashboard styling.

#### Bright trial panel · level 1

**Use:** An accessible first experience.

**CSS:** `background: #ffffff; color: #0a0a0b; border-radius: 20px; padding: 10px`

**Observed:** A framed media half sits beside a simple invitation and black action.

**Transfer:** Give one useful low-commitment action an unusually bright, tangible container.

#### Benefit lime · level 1

**Use:** Numbered benefit cards.

**CSS:** `background: #c9fe6e; color: #0a0a0b; border-radius: 20px; padding: 40px 0px`

**Observed:** Lime sits in a fan alongside mint, ice blue and pale neutral cards.

**Transfer:** Keep color concentrated in the physical-card moment rather than tinting all sections.

## Components

### Floating navigation

**Use:** Persistent compact wayfinding.

**CSS:** `display: flex; align-items: center; background: #f3f3f3; border-radius: 25px; height: 50px; padding: 0px 14px`

**Text style:** `action` — PPNeueMontrealMono 500 · 13px/1.615 · uppercase

**Observed:** Wordmark sits separately at left; the right cluster contains this navigation, a circular utility control and the lime Primary button. The header is fixed, 100px tall, with 25px padding. A small white numeric badge attaches to the collection label.

**Transfer:** Use a concise product mark and at most a handful of short navigation labels.

### Primary button

**Use:** Join, purchase or start action.

**CSS:** `background: #c9fe6e; color: #0a0a0b; border-radius: 25px; height: 50px; padding: 0px 25px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — PPNeueMontrealMono 500 · 13px/1.615 · uppercase

**Observed:** Short label followed by a tiny diagonal directional mark; label and icon are separated by 15px. Width follows content.

**Transfer:** Reserve lime for a clear conversion rather than every link.

### Dark button

**Use:** Exploration or trial on white.

**CSS:** `background: #0a0a0b; color: #ffffff; border-radius: 25px; height: 50px; padding: 0px 25px; display: flex; align-items: center`

**Text style:** `action` — PPNeueMontrealMono 500 · 13px/1.615 · uppercase

**Observed:** Same capsule construction as Primary button, with a directional glyph after the label. On dark stages exploration reverses to white.

### Secondary button

**Use:** Paired exploration beside a conversion.

**CSS:** `background: #f3f3f3; color: #0a0a0b; border-radius: 25px; height: 50px; padding: 0px 25px; display: flex; align-items: center`

**Text style:** `action` — PPNeueMontrealMono 500 · 13px/1.615 · uppercase

**Observed:** Pairs with the lime action in a 15px-gap row. Objection-handling links on dark can use charcoal with white lettering.

### Specimen badge

**Use:** Date, category reference or identifiers attached to media.

**CSS:** `background: #ffffff; color: #0a0a0b; border-radius: 18px; height: 35px; padding: 0px 18px; display: flex; align-items: center; gap: 10px`

**Text style:** `badge` — PPNeueMontrealMono 500 · 11px/3.18 · uppercase

**Observed:** Dates sit at the top-left of light specimens; numeric reference lists sit at the lower-left of portfolio specimens.

**Transfer:** Use useful compact metadata, not decorative fake serial numbers.

### Testimonial card

**Use:** Expert or practitioner endorsement.

**CSS:** `background: #232323; color: #ffffff; border-radius: 12px; padding: 30px; width: 385px`

**Text style:** `body` — LayGrotesk 500 · 18px/1.4

**Observed:** Quote comes first; a circular portrait, uppercase author and muted role sit at the bottom. One lead endorsement reverses to white with dark text; a logo can balance the attribution. The rail runs beyond the viewport.

**Transfer:** Keep quotes substantial enough to describe the experience, not just a two-word superlative.

### Pricing card

**Use:** A single all-inclusive offer.

**CSS:** `background: #ffffff; color: #0a0a0b; border-radius: 12px; width: 440px; display: flex; flex-direction: column; align-items: center; gap: 70px`

**Text style:** `heading-lg` — LayGrotesk 500 · 65px/1.02 · tracking -0.02em

**Observed:** A period selector sits above a large price, mono billing line and lime Primary button; quiet payment reassurance is below. This white half nests in a charcoal shell beside two feature groups with check icons and an avatar proof cluster.

**Transfer:** Keep the offer legible as one coherent product rather than a dense comparison table.

### Trial panel

**Use:** Low-friction product sampling.

**CSS:** `background: #ffffff; color: #0a0a0b; border-radius: 20px; padding: 10px; display: flex; align-items: center; gap: 50px; width: 896px`

**Text style:** `heading-sm` — LayGrotesk 500 · 30px/1.02 · tracking -0.02em

**Observed:** Left: 440px square demonstration. Right: heading, short support, Dark button and small reassurance. The media is inset by a narrow white frame.

**Transfer:** Offer an actual useful sample rather than another promotional download.

### Newsletter form

**Use:** Secondary conversion in the bright finale.

**CSS:** `background: #f3f3f3; border-radius: 25px; height: 50px; max-width: 370px; display: flex; justify-content: space-between; margin: 15px 0px`

**Text style:** `action` — PPNeueMontrealMono 500 · 13px/1.615 · uppercase

**Observed:** Email input occupies the left; a 35px white Submit capsule with 18px corners nests at right with 7.5px inset. A heading precedes the field and a compact explanatory line follows.

### Footer link

**Use:** Dense utility navigation without large button surfaces.

**CSS:** `color: #0a0a0b; text-decoration: none`

**Text style:** `label` — PPNeueMontrealMono 500 · 13px/1.49 · uppercase

**Observed:** Links stack directly under 22px column headings, with a separate dark download capsule in the contact group.

**States:** Declared: hover color #999999; focus-visible unspecified.

### Project specimen

**Only for:** portfolio index pages

**Use:** Repeated project proof.

**CSS:** `background: #323232; border-radius: 20px; display: grid; align-items: center; margin-bottom: 10px; position: relative`

**Text style:** `caption` — PPNeueMontrealMono 500 · 11px/1.39 · uppercase

**Observed:** A landscape website view is centered in a square; bottom-left reference badges and bottom-right award text sit inside the backing. Name and creator appear below, white over muted gray. Featured examples reverse the backing to lime.

**Transfer:** Use real outputs or case studies; preserve their original visual character inside a consistent frame.

## Imagery and graphics

### Miniature demonstration gallery

**Use:** Opening and repeated product specimens.

**Observed:** Black-backed landscape clips contain vivid miniature compositions: cropped portraits, flower heads, water, architecture and expressive typography. The hero has one large central clip with other clips partially entering from above and below; the page itself remains neutral.

**Transfer:** Use short visual demonstrations of the new product. Without footage, compose a still sequence of three to six real outputs against a near-black backing and give each a clear central motif.

**Build:** For a simple equivalent, place 10–12 rounded image tiles around an elliptical path inside a 504×284px dark rectangle; vary each tile from roughly 35px to 50px, leaving the middle clear for a small title. Use saturated photographic details against the flat dark field; clip to 4px outer corners.

### Pastel benefit fan

**Use:** Signature capability storytelling.

**Observed:** Tall pastel cards expand from a single centered card into an overlapping fan on the dark stage. Each has a slightly arched uppercase heading, a huge faint numeral and compact centered prose at the bottom. Mint, lime, ice blue and pale neutral make it feel like a playful physical deck.

**Transfer:** Give each card one practical benefit. Keep the physical fan even when the product has no visual output.

**Build:** Create four roughly 338×398px cards with 20px corners and 40px vertical padding. Stack them around their lower center with modest alternating rotations, then spread horizontally while retaining overlap. Use lime, ice blue, pale neutral and a mint companion. Put a 120px numeral in the center at opacity 0.2. Set two-line uppercase titles on shallow SVG arcs or slightly rotated line groups and body copy near the lower edge.

### Floating output constellation

**Use:** Visual proof chapter around a centered invitation.

**Observed:** Small landscape website views of different scales drift into an overlapping cluster on black. Pink, green, cream and burgundy are inside the outputs, not applied to the page background; the surrounding scene is unframed and spatial.

**Transfer:** Use a collection of genuine customer outputs or product results. A static collage with varied scale and overlap is the minimum equivalent.

**Build:** Place 7–10 landscape image planes in an approximately 800×500px stage with ample dark margins. Vary width from 80px to 280px, overlap central planes and place the smallest toward the outer edges. Preserve image colors, add no enclosing card or glow.

### Workflow mini-scenes

**Use:** Feature rail and trial media.

**Observed:** Pale gray feature tiles show isolated copy controls, floating app symbols and a small tutorial sheet with generous empty backing. The trial scene reverses to black with floating photographic cards and a compact white action menu layered in front.

**Transfer:** Illustrate a concrete workflow action, not a full unreadable interface. Keep the controls large enough to recognize while surrounding them with space.

### Attribution photography

**Use:** Human proof alongside quotes and maker notes.

**Observed:** Small circular portraits accompany mono credits. The maker note uses one small casual rectangular photograph rather than a studio portrait hero.

**Transfer:** Keep human imagery incidental and candid; do not let portraits replace the product exhibition.

### Icons

**Observed:** Tiny monochrome directional marks around 9×9px follow action labels. Utility symbols fit a 14×14px scale inside a 50px circular control; check marks are quiet and compact. App symbols appear as colorful objects only inside workflow scenes.

**Transfer:** Choose simple monochrome arrows, checks and utility marks, preserving the small scale and 10–15px separation from text rather than introducing large line-icon feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Split gallery opening

**Observed:** A 900px white viewport stage sits behind Floating navigation. A central 504×284px black-backed demonstration occupies about one third of the width near mid-height. The 47.5px opening promise splits into a left phrase and a right phrase that flank the object, both aligned through its center. Lower left holds a three-line, 366px-wide paragraph and Dark button; lower right holds a muted mono drag hint. Additional 360×203px demonstrations are partially visible at the top and bottom, suggesting a vertical collection. All of this is visible within the first 900px; the first dark benefit introduction begins below.

**Transfer:** Split a compact product promise into balanced phrases and put an unmistakable product demonstration between them. If media is unavailable, use the Miniature demonstration gallery construction rather than enlarging the headline. Purchase-focused pages instead open on a dark centered offer; portfolio indexes open on a dark oversized title-and-count row.

**Avoid:** Do not turn the opening into a centered giant headline above a full-width dashboard, or collapse it into a conventional left-copy/right-image split.

**Text style:** `opening` — LayGrotesk 500 · 47.5px/1.02 · tracking -0.02em

### Centered introduction and specimens

**Observed:** On Dark stage, a 580px-wide centered heading uses the heading recipe, then a short supporting paragraph. A three-column row of Light specimen backing cards follows; dates sit at the top-left, demonstrations are centered and mono captions live below. An exploration capsule centers under the row.

**Transfer:** Introduce a few tangible results before explaining implementation details.

**Text style:** `heading` — LayGrotesk 500 · 48px/1.02 · tracking -0.02em

### Trust strip

**Observed:** A compact overlapping avatar cluster ends in a lime count capsule. A centered one-line adoption statement sits beneath it, followed by a thin charcoal rule and two rows of small monochrome logos.

**Transfer:** Use verified adoption evidence and a compact logo strip as a pause between demonstrations and the larger narrative.

### Full-stage statement and fan

**Observed:** A large centered two-line white statement fills a sparse dark stage. The next visual idea is the Pastel benefit fan, growing from a single object into a group while the dark surround remains dominant.

**Transfer:** State one memorable product advantage, then convert its practical consequences into numbered physical cards. The device need not occupy the same narrative position.

### Workflow rail

**Observed:** A centered heading introduces four 453px-wide feature specimens in an overflowing rail with 15px gutters. Each has a pale mini-scene, 18px title, muted paragraph and a small mono preview link. A download-oriented horizontal strip and thin rule finish the chapter.

**Transfer:** Show the product meeting several working contexts, with one concrete action or artifact per card.

**Text style:** `heading` — LayGrotesk 500 · 48px/1.02 · tracking -0.02em

### Single offer and reassurance

**Observed:** A two-line 65px centered heading precedes the Pricing card within a 896px charcoal shell. The right half has two clearly separated feature groups. Below the shell, a short question and dark secondary capsule address remaining uncertainty. The purchase-focused variant gives the opening more top breathing room.

**Transfer:** For a simple product, keep one offer primary and make support details subordinate rather than filling the stage with competing plans.

**Text style:** `heading-lg` — LayGrotesk 500 · 65px/1.02 · tracking -0.02em

### Endorsement rail and maker note

**Observed:** Testimonial card repeats horizontally with 15px gaps, one white card leading a charcoal series. Small partner marks can sit above. A later maker note pairs muted prose with highlighted names and one small candid photo, finishing with a thin rule.

**Transfer:** Use practitioner testimony for lived benefits and a brief human authorship note for credibility; keep both visually smaller than the demonstration stages.

### Low-friction sample

**Observed:** Trial panel centers on Dark stage with 150px preceding space and about 145px following space. Its white shell is a small island, not a full-width band.

**Transfer:** Place a useful sample or test drive near decision points, including after a long catalogue.

**Text style:** `heading-sm` — LayGrotesk 500 · 30px/1.02 · tracking -0.02em

### Monumental closing pavilion

**Observed:** A bright white rounded pavilion closes every page. A small centered mono invitation leads into a 720px-wide, two-line 140px closing statement and paired lime and pale actions. About 170px separates the action row from the newsletter and link area: a broad left half holds Newsletter form while the right half divides into three 219px columns. A large quiet area of 280px separates these columns from the bottom copyright, legal links and small maker mark. The entire closing composition is roughly 1155px tall.

**Transfer:** End with a short action-oriented line large enough to feel like an object, then a practical directory and a genuinely secondary subscription. Maintain the dramatic white inversion and roomy final baseline.

**Text style:** `closing` — LayGrotesk 500 · 140px/0.85 · tracking -0.03em

### Objection invitation

**Only for:** purchase-focused pages

**Observed:** An uppercase mono eyebrow introduces a centered 65px statement, mostly gray with its key permission phrase white. Two capsules underneath lead to detailed terms and questions.

**Transfer:** Make one key reassurance legible at headline scale, then route the reader to precise details.

**Text style:** `heading-lg` — LayGrotesk 500 · 65px/1.02 · tracking -0.02em

### Portfolio index

**Only for:** portfolio index pages

**Observed:** After 250px top space, a 120px title and matching count align to opposite ends of a row with a 1px charcoal bottom rule. A short introduction and submission link precede a three-column Project specimen grid. Cards have 15px horizontal gutters and 50px row separation.

**Transfer:** Treat the index as a curated catalogue, not a masonry wall of edge-to-edge thumbnails.

**Text style:** `gallery-display` — LayGrotesk 500 · 120px/0.95 · tracking -0.02em

## Page flow

**Storyline:** Tangible visual promise → curated examples → practical benefits and workflow → confidence and commitment → low-friction experience → monumental final invitation.

### Expressive product landing page

1. **promise** — White split-headline gallery with a central demonstration and a small exploration action.
2. **product demonstration** — Dark introduction with three catalogued examples.
3. **social proof** — Avatar count and compact monochrome logo strip.
4. **capability chapters** — Full-stage statement, pastel benefit fan and workflow mini-scenes.
5. **pricing** — One centered two-part offer.
6. **credibility** — Endorsement rail and short maker note.
7. **outcome proof** — Large centered invitation and floating output constellation.
8. **low-friction conversion** — White sample panel on dark.
9. **closing call** — White monumental invitation, newsletter, directory and bottom legal row.

**Transfer:** Alternate vivid demonstrations with plainspoken practical details, using dark space to make each object distinct; shorten or reorder chapters without losing the gallery, fan and monumental closing devices.

### Purchase decision page

1. **pricing** — Dark opening with a centered all-inclusive offer and period selector.
2. **social proof** — Expert and practitioner quote rail.
3. **objection handling** — Large muted-and-white permissions invitation with detail links.
4. **closing call** — The same bright pavilion with large invitation, newsletter, directory and legal baseline.

**Transfer:** Lead with the commercial decision, then answer trust and permissions concerns before the shared ending.

### Output catalogue and inspiration index

1. **orientation** — Oversized title and count, rule, short introduction and contribution link.
2. **outcome proof** — Three-column square-backed project catalogue with reference capsules and attribution.
3. **low-friction conversion** — Bright sample panel after the catalogue.
4. **closing call** — Shared white invitation and complete utility footer.

**Transfer:** Let the repeated work carry the story, using featured lime cards sparingly and retaining the same trial and closing language.

## Writing

Confident, practical and friendly, with a maker's enthusiasm for well-crafted experiences. Claims connect creative ambition to saved effort, clear implementation and immediate use.

**Do not copy:** Do not reuse the brand name, wordmark, partner marks, named people, customer quotations, proprietary artwork, prices, counts or award claims. Replace them with truthful material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your; use we and our for the people making the product. Product descriptions are direct and concrete.
- **Rhythm:** Headlines commonly run 4–9 words, sometimes in two balanced lines. Support copy is a short explanatory sentence; actions use 2–3 words, while helper text quietly removes a specific worry.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a distinctive output, then signal immediate usability. | 5–8 words | “Unique JS effects ready to use” |
| Benefit heading | Pair a desirable result with reduced effort or a natural fit. | 5–9 words | “Better websites, without the extra work”<br>“Made to fit your workflow” |
| Offer heading | Two clipped statements make the purchase feel simple. | 4–6 words | “One Plan. Everything included.” |
| Support | Explain what the reader gets using tangible formats or working contexts. | 15–25 words | “A growing collection of 124+ GSAP effects, each with AI prompts, Webflow components, source code and tutorials.” |
| Action | An active verb plus its object or a short start invitation. | 2–3 words | “Explore collection”<br>“Try it now” |
| Reassurance | Remove one concrete barrier using a short factual statement. | 5–12 words | “No credit card or account required. Free for everyone.” |
| Closing | Invite the reader into the product's central activity. | 4–6 words | “Get ready to animate” |

**Words and phrasing to use:** well-crafted; ready-to-use; standout; workflow; get started; explore; step-by-step; free for everyone

**Avoid:** revolutionary ecosystem; disruptive synergy; enterprise transformation; unlock limitless potential; hyperbolic urgency

**Rules:**

- Tie each creative promise to a practical mechanism in its supporting paragraph.
- Make utility labels concise enough to work in uppercase mono.
- Use helper copy for billing, access and account requirements rather than repeating the headline.
- Keep the final invitation energetic and verb-led, without adding a slogan paragraph.

## Do's and Don'ts

### Do

- Keep the opening promise at 47.5px and let the central 504×284px object be its equal.
- Use the 25px outer margin and 15px card gutters as the desktop frame.
- Center landscape demonstrations at 331×186px within 453px square matte backings.
- Use 20px corners for specimen panels and 12px for quote or inset price cards.
- Keep conversion capsules 50px tall with 25px horizontal padding.
- Set descriptive prose at 18px/1.4 and secondary copy in #999999.
- Use a low-opacity 120px numeral to anchor each pastel benefit card.
- Give the ending its 140px/0.85 statement and a distinct white pavilion.

### Don't

- Do not replace the small mono navigation with a full-width dark toolbar; it should remain a separate pale capsule.
- Do not give all cards the same radius: 20px specimens and 12px quotes have different material roles.
- Do not introduce drop shadows to separate flat charcoal cards; #232323 against #0a0a0b already does that work.
- Do not expand lime into a full-page theme; it is a conversion and featured-card accent.
- Do not stretch specimen imagery edge-to-edge within square backings; the wide matte is part of the presentation.
- Do not make the 11px credits as visually strong as the 18px quotes.
- Do not shrink every horizontal rail item to fit all content in one viewport; preserve the substantial card widths.
- Do not turn every 48px heading into bold weight 700; medium-weight letterforms and tight tracking carry the hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Media galleries, a pinned full-stage statement, a progressively spreading benefit fan and a floating output collage provide the major motion vocabulary.
- Declared action and surface transitions include opacity 0.2s, background-color 0.15s and background-color 0.3s with a 0.1s delay.
- The button construction contains clipped duplicate label layers for rolling text. Footer text links declare a gray hover color.

**Transfer:**

- Animate the fan as a physical group emerging from one card into an overlapping spread; do not make each benefit an unrelated entrance.
- Keep motion inside specimens or isolated dark stages so the surrounding mono navigation remains a stable catalogue frame.
- Use a settled static fan and output collage as the fallback, keeping the same composition and content.

**Unknown:**

- Exact scroll progress mappings, motion sequencing and per-component easing assignments are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 500px, 550px, 768px, 900px, 1024px, 1100px, 1300px, 1310px and 1920px.

**Transfer:**

- On narrow layouts, preserve the central specimen and arrange the two promise fragments around it in reading order rather than reducing them into illegible slivers.
- Keep rail cards substantial and horizontally explorable; stack the trial and pricing halves when their content no longer fits.
- Reduce the closing statement proportionally while preserving its tight two-line object-like treatment and clear action row.

**Unknown:**

- Narrow-screen typography, exact breakpoint behaviors and touch-gallery mechanics are not established; the adaptations above are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
