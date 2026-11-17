# Cal.com — soft-edged useful machinery

## Overview

A light, near-monochrome software style with rounded geometric headlines, slender interface-like body text, and softly elevated white panels. Fine construction lines organize spacious sections while detailed product scenes make the promise tangible. Color belongs mainly to small app marks, people, and proof badges; a separate midnight-and-violet treatment gives specialist launches a more theatrical register.

### Essentials

- Headlines feel like friendly solid objects, not editorial typography: Cal Sans 600 at 64px/1.1 for the opening and 48px/1.1 for section leads, with normal tracking.
- The opening is a product showroom inside a white tray: a 1176px-wide, 12px-radius panel on #f4f4f4, a roughly 500px text column beside an oversized working interface, and 48px between them.
- Actions are compact beveled keys rather than pills: 36px high, 12px corners, 8px 12px padding, 14px light text, a small right chevron, and dark-to-darker or white-to-gray gradients.
- Neutral space does nearly all the work: #f4f4f4 canvas, white cards, #242424 headlines and #898989 supporting copy. Saturation stays in small logos, portraits and proof marks, not ordinary section backgrounds; midnight violet is a specialist-launch variant.
- Product explanation is built from nested, softly outlined interfaces: 16px outer cards, 24px padding, 12px grid gaps, partial windows, tiny controls and bottom fades. Every new page needs a tangible product scene; use a simplified but legible task interface if polished media is unavailable.
- Construction lines and ghost keys are signature devices: 1px gray rails and cross-marked section junctions frame the page, while a field of pale rounded square keys sits behind a prominent conversion statement. Recreate the keys with CSS rather than replacing them with generic stock art.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Help link blue | `#0099ff` | `--color-help-blue` | link | Tiny footer support links; not a primary marketing fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline charcoal | `#242424` | `--color-ink` | text, action | Display text, selected pricing surface and dark action gradient endpoint. |
| Link black | `#111111` | `--color-link-ink` | link | Footer and other plain text links. |
| Raised charcoal | `#292929` | `--color-action-top` | text, action | Small dark labels and the upper stop of dark actions. |
| Supporting gray | `#898989` | `--color-muted` | text | Paragraphs and secondary explanatory copy. |
| Inset rule gray | `#d2d2d2` | `--color-rule-strong` | border | Visible result of rgba(20,20,20,0.15) on the gray canvas; short inset rules reinforce wider hairlines. |
| Fine edge | `#e1e2e3` | `--color-edge` | border | Card outlines, section rules and interface frames. |
| Number tile gray | `#e5e7eb` | `--color-number-tile` | surface | Small numbered setup markers. |
| Soft key bottom | `#eaeaeb` | `--color-key-bottom` | action | Lower stop of the gray secondary conversion key. |
| Page gray | `#f4f4f4` | `--color-canvas` | background | Default page canvas and footer. |
| Soft key top | `#f7f7f8` | `--color-key-top` | action | Upper stop of the gray secondary conversion key. |
| Comparison white | `#fcfcfc` | `--color-near-white` | surface | Subtle comparison rows and the top of secondary action gradients. |
| Panel white | `#ffffff` | `--color-white` | surface, text | Cards, large trays and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| specialist dark product launches | Violet edge | `#352f4b` | `--color-night-edge` | border | Dark panel edges and section rails. |
| specialist dark product launches | Midnight violet | `#0d0c27` | `--color-night` | background | Dark launch canvas and footer. |
| specialist dark product launches | Raised midnight | `#15142e` | `--color-night-panel` | surface | Dark hero, capability panels and closing tray. |
| specialist dark product launches | Electric violet | `#6349ea` | `--color-violet` | action, accent | Primary dark-launch action and gradient lettering start. |
| specialist dark product launches | Soft violet | `#875fe0` | `--color-violet-soft` | action, accent | Lower action gradient stop and restrained luminous edging. |
| specialist dark product launches | Headline lilac | `#c292ff` | `--color-lilac` | accent | Right endpoint of highlighted headline text and soft proof-card light. |

## Typography

- **Cal Sans** — Rounded, solid display headings. Broad geometric sans with rounded bowls, single-storey forms and tightly fitted shapes; visually weighty without an industrial feel. If unavailable, use **Cal Sans**. Use the freely available Cal Sans distribution; retain the measured headline metrics. Font stack: "Cal Sans", "Cal Sans", sans-serif.
- **Cal Sans UI** — Marketing body, labels, buttons, card titles and footer text. Light, compact geometric UI sans; creates a marked contrast with the solid headings. If unavailable, use **Manrope**. Use weight 300; tune line breaks to preserve the narrow, light body texture. Font stack: "Cal Sans UI", "Manrope", sans-serif.
- **Roboto Mono** — Two-digit setup markers. Compact technical monospace that adds a little equipment-like numbering. Font stack: "Roboto Mono", monospace.
- **Inter** (only for dark-launch actions and product demonstrations) — Dark-launch action labels and selected interface text. Neutral UI grotesk, more conventional than the main geometric headings. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Cal Sans | 600 | 64px | 1.1 | normal | Opening promise; wrap into a few broad, deliberate lines. |
| heading | Cal Sans | 600 | 48px | 1.1 | normal | Section lead and closing conversion statement. |
| card-title | Cal Sans UI | 300 | 18px | 1.3 | -0.011em | Feature and setup-card titles. |
| question | Cal Sans UI | 300 | 18px | 1.5 | -0.011em | Accordion questions. |
| body | Cal Sans UI | 300 | 16px | 1.5 | normal | Supporting paragraphs and plain footer links. |
| footer-heading | Cal Sans UI | 300 | 16px | 1.5 | -0.0125em | Footer link-group labels. |
| caption | Cal Sans UI | 300 | 14px | 1.5 | normal | Trust-strip introduction and small explanatory text. |
| action | Cal Sans UI | 300 | 14px | 20px | -0.014em | Default compact action labels. |
| step-number | Roboto Mono | 600 | 14px | 1 | normal | Two-digit setup numbering. |
| eyebrow | Cal Sans UI | 300 | 12px | 1 | normal | Sentence-case section chips and announcement labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| benefit chapters and pricing pages | chapter-heading | Cal Sans | 600 | 32px | 1.2 | normal | Alternating media-and-copy chapters and plan prices. |
| specialist dark product launches | launch-action | Inter | 500 | 14px | 1 | normal | Violet conversion-button labels. |

**Notes:**

- Size, weight and silhouette create hierarchy; display headings do not need negative tracking or uppercase styling.
- The light body face is an intentional counterweight to the dense rounded headline. Do not make all marketing copy semibold.
- Centered section headings use up to 960px while support paragraphs usually stop at 640px; the opening's left-aligned headline uses about 500px.
- The same display and heading recipes reverse to white in the dark launch treatment. One phrase receives violet-to-lilac clipped text, not the whole heading.

## Layout

**Density:** Airy at section scale and compact inside controls: large chapter breathing room surrounds closely packed interface objects.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action icon-to-label gap. |
| 12px | Card-grid gutters, headline-to-paragraph gap and paired-action spacing. |
| 16px | Eyebrow-to-heading and support-to-action spacing; footer link rhythm. |
| 24px | Standard card padding, footer cluster separation and closing heading-to-action gap. |
| 32px | Text-to-miniature-UI gap inside setup cards and outer footer side padding. |
| 48px | Major copy-to-media and section-header-to-card gaps. |
| 64px | Large panel interior side inset. |
| 80px | Footer top and bottom padding. |
| 96px | Major section top spacing and space from document start to opening tray. |

### Containers and grids

- **page-frame**: max width 1200px · side padding 12px. Centered page frame with faint vertical rails; at a 1440px viewport the rails sit around the 120px side margins and trays span 1176px.
- **panel-content**: max width 1048px · side padding 0px. Default inner content span inside the large tray, inset 64px from its edges.
- **section-heading**: max width 960px. Centered heading group; pair with a paragraph limited to 640px.
- **setup-grid**: 3 columns · gap 12px. Three equal illustrated setup cards, about 341px wide at desktop.
- **benefit-grid**: 2 columns · gap 12px. Two equal large interface cards, about 518px wide at desktop.
- **footer**: max width 1200px · gap 24px · side padding 32px. A 400px identity-and-utility column beside four 176px link columns.
- **pricing-grid** (only for pricing pages): 4 columns · gap 12px. Four equal plan cards with one dark featured plan.

## Corner radius

| Element | Radius |
| --- | --- |
| tray-and-actions | 12px |
| feature-card | 16px |
| number-marker | 8px |
| section-chip | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card-lift | `rgba(36, 36, 36, 0.7) 0px 1px 5px -4px, rgba(36, 36, 36, 0.05) 0px 4px 8px 0px` | Tiny crisp contact shadow plus a softer short drop under trays and cards. |
| dark-key-lip | `rgba(255, 255, 255, 0.15) 0px 2px 0px 0px inset` | Top lip inside charcoal action keys. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f4f4f4`

**Observed:** Fine vertical rails continue past large sections, crossing horizontal rules.

**Transfer:** Let the gray canvas remain visible between white trays.

#### White tray · level 1

**Use:** Opening, integration band, selected proof section and closing statement.

**CSS:** `background: #ffffff; border: 1px solid #e1e2e3; border-radius: 12px; box-shadow: rgba(36, 36, 36, 0.7) 0px 1px 5px -4px, rgba(36, 36, 36, 0.05) 0px 4px 8px 0px; overflow: hidden`

**Observed:** Wide but inset from the page rails, with very little perceived elevation.

**Transfer:** Use as a presentation tray rather than a modal floating far above the page.

#### Feature card · level 2

**Use:** Repeated illustrated capabilities and setup steps.

**CSS:** `background: #ffffff; border: 1px solid #e1e2e3; border-radius: 16px; padding: 24px; box-shadow: rgba(36, 36, 36, 0.7) 0px 1px 5px -4px, rgba(36, 36, 36, 0.05) 0px 4px 8px 0px; overflow: hidden`

**Observed:** Copy occupies the upper part and a carefully framed miniature interface fills the lower part.

**Transfer:** Put one task or benefit in each card; let interface fragments run into the lower clipping edge.

#### Night canvas · level 0

**Only for:** specialist dark product launches

**Use:** Alternative launch environment.

**CSS:** `background: #0d0c27; color: #ffffff`

**Observed:** The same rails, trays and heading hierarchy remain, but the chromatic base is violet-black rather than neutral black.

**Transfer:** Change the complete page environment rather than inserting isolated dark cards into an otherwise ordinary page.

#### Night panel · level 1

**Only for:** specialist dark product launches

**Use:** Hero, media chapters and dark conversion tray.

**CSS:** `background: #15142e; border: 1px solid #352f4b; border-radius: 12px`

**Observed:** Capability-card versions use 16px corners and 24px padding; body copy uses white at 70% opacity.

**Transfer:** Keep panel separation subtle; violet actions should be the brightest small objects.

## Components

### Floating navigation

**Use:** Persistent compact site navigation.

**CSS:** `background: rgba(255, 255, 255, 0.58); border-radius: 16px; padding: 0px 32px; height: 57px; max-width: 1152px; display: flex; justify-content: space-between; align-items: center`

**Observed:** Fixed near the top with identity at left, restrained menu groups in the middle and sign-in plus a Primary button at right. It reads more distinctly as a rounded bar over scrolled content.

**Transfer:** Use a compact identity and only a few menu groups; keep the central navigation visually lighter than the identity.

### Primary button

**Use:** Default main conversion action.

**CSS:** `background: linear-gradient(#292929 0%, #242424 100%); color: #ffffff; border-radius: 12px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; justify-content: center; gap: 8px; box-shadow: rgba(255, 255, 255, 0.15) 0px 2px 0px 0px inset`

**Text style:** `action` — Cal Sans UI 300 · 14px/20px · tracking -0.014em

**Observed:** A right chevron follows the label. Opening sign-up variants expand to 480px and stack; the provider version places its colored mark before the label.

**Transfer:** Keep one clear primary action per local group; preserve the compact key-like height.

### Secondary button

**Use:** Demo, sales and alternate paths paired with a main action.

**CSS:** `background: linear-gradient(#fcfcfc 0%, #ffffff 100%); color: #292929; border-radius: 12px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; justify-content: center; gap: 8px; border-left: 1px solid #e1e2e3; border-right: 1px solid #e1e2e3; box-shadow: #ffffff 0px 2px 0px 0px inset`

**Text style:** `action` — Cal Sans UI 300 · 14px/20px · tracking -0.014em

**Observed:** Uses the same chevron and silhouette as the primary. A filled-gray alternate uses a #f7f7f8 to #eaeaeb gradient for email signup and some secondary conversions.

### Section chip

**Use:** Small section-category marker above a heading.

**CSS:** `background: #ffffff; color: #292929; border-radius: 9999px; height: 24px; padding: 4px 12px 4px 8px; display: inline-flex; align-items: center; gap: 4px; border-left: 1px solid #e1e2e3; border-right: 1px solid #e1e2e3; box-shadow: rgba(34, 42, 53, 0.05) 0px 4px 8px 0px`

**Text style:** `eyebrow` — Cal Sans UI 300 · 12px/1

**Observed:** Tiny black category icon sits at the left; sentence-case label stays untracked. Announcement versions use a gray fill and sometimes a trailing chevron.

### Number marker

**Use:** Order markers in illustrated setup cards and alternating benefit chapters.

**CSS:** `background: #e5e7eb; color: rgba(20, 20, 20, 0.6); border-radius: 8px; width: 32px; height: 28px; display: flex; align-items: center; justify-content: center`

**Text style:** `step-number` — Roboto Mono 600 · 14px/1

**Observed:** A compact marker above the title, not a giant decorative number.

**Transfer:** Use leading zeroes for short process sequences.

### Illustrated feature card

**Use:** Explain a task with copy above a miniature product scene.

**CSS:** `background: #ffffff; border: 1px solid #e1e2e3; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; gap: 32px; overflow: hidden; box-shadow: rgba(36, 36, 36, 0.7) 0px 1px 5px -4px, rgba(36, 36, 36, 0.05) 0px 4px 8px 0px`

**Text style:** `card-title` — Cal Sans UI 300 · 18px/1.3 · tracking -0.011em

**Observed:** Number marker, title and short support text form the top group. The lower group is a mostly neutral working interface, often partly clipped. Larger two-column versions omit numbering.

**Transfer:** Preserve meaningful controls and content in the miniature, not a generic diagram.

### FAQ row

**Use:** Broad, low-density objection handling.

**CSS:** `padding: 24px 0px; border-bottom: 1px solid #e1e2e3; display: flex; flex-direction: column; gap: 12px`

**Text style:** `question` — Cal Sans UI 300 · 18px/1.5 · tracking -0.011em

**Observed:** Question spans most of the row, with a small plus at the far right; an open row reveals Body copy beneath and changes the control to a close mark. Closed rows are about 77px tall.

**Transfer:** Use full-width rows rather than individual floating cards.

### Footer text link

**Use:** Dense navigation columns without button chrome.

**CSS:** `color: #111111; text-decoration: none`

**Text style:** `body` — Cal Sans UI 300 · 16px/1.5

**Observed:** Link groups use 16px vertical gaps and a Footer-heading label; four columns balance a wider identity and utility area.

**States:** Declared: hover color rgba(17,17,17,0.5), no underline; focus-visible not specified.

### Plan card

**Only for:** pricing pages

**Use:** Present a small set of comparable commercial tiers.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 16px; display: flex; flex-direction: column; gap: 24px; box-shadow: rgba(36, 36, 36, 0.7) 0px 1px 5px -4px, rgba(36, 36, 36, 0.05) 0px 4px 8px 0px`

**Text style:** `card-title` — Cal Sans UI 300 · 18px/1.3 · tracking -0.011em

**Observed:** Plan title, 32px price, compact description and full-width action precede a checklist. The highlighted tier is charcoal with white text and a light action, not a bright accent-colored plan.

**Transfer:** Align title, price and actions across columns; save detailed comparison for a separate matrix.

### Violet launch button

**Only for:** specialist dark product launches

**Use:** Chromatic main action in the dark environment.

**CSS:** `background: linear-gradient(#6349ea 0%, #875fe0 100%); color: #ffffff; border-radius: 12px; padding: 12px 16px; height: 38px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `launch-action` — Inter 500 · 14px/1

**Observed:** A separate violet-gradient backing slightly exceeds the face and uses nested dark-violet rings, making a luminous key edge rather than a diffuse neon cloud.

**Transfer:** Add the backing as a pseudo-element; keep the label clear and the light close to the edge.

## Imagery and graphics

### Working interface scenes

**Use:** Primary opening object and feature-card illustrations.

**Observed:** Bright, near-white scheduling windows contain real text, calendar cells, switches, avatars and small app marks. The opening object is deliberately larger than its available right-hand area and clipped at the tray edge. Smaller scenes are isolated on pale panels with thin outlines and short shadows; edge fades keep their density subordinate to the headline.

**Transfer:** Render the new product's key task with a title, a few recognizable controls and one active state. A small handcrafted HTML interface is preferable to stock device photography.

### Ghost key field

**Use:** Signature conversion backdrop and a recurring subtle tiled motif.

**Observed:** Rounded square keycaps form a shallow staggered field, almost white on white. Edges and tiny lower shadows reveal the keys; a broad white fade dissolves the perimeter. In the dark launch variant the same field becomes dim violet.

**Transfer:** Include the tiled field behind a strong promise or conversion statement. Keep text and buttons visually in front; the keys provide texture, not content.

**Build:** Create staggered rows of roughly 64px square divs with 8px corners, a 1px rgba(20,20,20,0.04) outline and 0px 2px 3px rgba(20,20,20,0.03) shadow. Place the field behind the content and apply a radial white mask that dissolves its outer rows. For the night variant use #15142e keys with rgba(135,95,224,0.08) highlights and a dark radial veil.

### Proof and integrations

**Use:** Narrow trust strips, integration bands and the closing tray.

**Observed:** Customer logos are mostly monochrome and aligned on a low band. Integration marks retain their native colors inside a fine-lined grid. Small stars, review marks, laurels and certification seals add localized color and credibility without recoloring the page.

**Transfer:** Use genuine partner marks, actual review evidence or a few text-based proof statements. Keep them secondary to the product scene.

### Spotlit testimonial

**Use:** Editorial customer proof between capability chapters.

**Observed:** One sharp white quote card sits centrally while neighboring cards are clipped and faded. Large bold quote text dominates; a small avatar, name and role sit along the lower edge. Fine rails and cross marks turn the quote into a framed object.

**Transfer:** Feature one short, concrete quote at a time; make surrounding proof visually quieter rather than creating a uniform grid of equally loud quotes.

### Portrait key mosaic

**Only for:** team-oriented landing pages

**Use:** Human-scale proof beneath a centered opening.

**Observed:** A wide field of the same pale rounded keys contains scattered square portraits in color and monochrome. Some people sit crisply at the center while top, bottom and side rows dissolve into white. It occupies the lower portion of the hero rather than becoming a photo banner.

**Transfer:** Use real user or collaborator portraits in sparse positions, with a consistent square framing and a soft perimeter fade.

**Build:** Use the Ghost key field grid, replace a minority of cells with object-fit cover portraits, and apply a radial transparent-to-white overlay around the full field. Mix portrait positions rather than filling a complete row.

### Developer customization scene

**Only for:** developer product pages

**Use:** Demonstrate control and extensibility.

**Observed:** A wide pale outlined panel places numbered code at left and a vividly recolored live interface at right, clipped by the panel boundary. The intentionally loud demo color contrasts with the neutral surrounding marketing surface.

**Transfer:** Show a short configuration beside the interface it changes. Keep vivid theming inside the demonstration, not in page-wide styling.

### Violet value card

**Only for:** specialist dark product launches

**Use:** Spotlight a single price or quantified value alongside explanatory copy.

**Observed:** A 500px by 400px rounded card carries a bright white 48px value over a soft violet, lavender and pinkish light field. A 32px benefit heading and supporting paragraph sit to the right against the night canvas.

**Transfer:** Feature one verified number, unit or short value proposition; preserve the simple white-on-luminous treatment.

**Build:** Start with a violet-to-lilac linear gradient, overlay broad translucent lilac ellipses across the center and upper edge, blur those light layers by about 60px, and clip to a 12px rounded rectangle. Center the white Heading recipe; match the soft glow rather than relying on exact gradient stops.

### Icons

**Observed:** Small black functional glyphs and chevrons are integrated with labels: 14px icons in section chips, about 14px trailing action arrows, and 16px to 24px capability symbols. Some feature tiles mount a dark symbol in a softly raised gray square with tiny corner details.

**Transfer:** Use simple monochrome functional icons with consistent apparent weight. Reserve multicolor for genuine app or provider marks; do not make every capability icon a colored badge.

## Section recipes

How recurring sections are built.

### First screen: Product showroom opening

**Observed:** A fixed Floating navigation sits above a White tray beginning 96px down the page and spanning 1176px within the rails. The tray is about 700px tall. A roughly 500px left column holds an announcement chip, a 64px Display headline wrapping into three broad lines, muted Body copy and stacked 480px-wide conversion keys, followed by a small reassurance. A large bright working interface sits to the right across a 48px gap; it deliberately runs beyond the tray edge, with small review marks below. Layers are gray canvas and rails, white tray, copy and interface, then compact actions and proof. Within the first 900px the navigation, full headline, support, actions, main object and the beginning of a trust strip are visible; capability grids begin below.

**Transfer:** Give a different product an equally concrete task interface in the right-hand stage, even if built from plain HTML. Keep the rounded headline and compact stacked conversion area as the default. Team-oriented variants center the promise above a portrait-key field; developer variants center it above a wide browser scene. Pricing variants place the promise directly on the gray canvas above plans. Dark launches keep the split composition but replace the white scene with a dark device or conversation interface and highlight one phrase in violet.

**Avoid:** Do not center the default opening above a tiny isolated illustration or stretch a generic dashboard edge-to-edge behind the headline. Do not let a decorative photo replace the legible product task.

**Text style:** `display` — Cal Sans 600 · 64px/1.1

### Section heading cluster

**Observed:** Section chip, 16px gap, centered Heading, 12px gap to Body support, then 16px to paired actions. The group is up to 960px wide, with support up to 640px. Large chapters usually start 96px below their boundary and leave 48px before the next object.

**Transfer:** Reuse the cluster for capability, proof or objection chapters; shorten copy to fit the same compact vertical hierarchy.

**Text style:** `heading` — Cal Sans 600 · 48px/1.1

### Numbered setup and benefit grids

**Observed:** Three Illustrated feature cards use Number markers and a 12px gutter for short setup sequences. Deeper capability sections switch to two wider columns with larger interface scenes. A compact additional-feature treatment uses small icon-led cards without full illustrations.

**Transfer:** Choose the number of cards by explanation needs, not by matching a fixed page sequence. Keep each card focused on one action or result.

### Integration tray

**Observed:** A White tray carries a left-aligned Section chip, 48px Heading, short Body paragraph and paired actions. A compact app-logo matrix sits on the right with fine horizontal and vertical separators.

**Transfer:** Show ecosystem compatibility through a restrained mark grid or equivalent connected-product symbols rather than a list of colored pills.

### Social proof gallery

**Observed:** A centered Section heading cluster introduces a Spotlit testimonial; other proof appears as a three-column masonry wall of short user posts with avatars. The featured quote gets stronger contrast than neighboring material.

**Transfer:** Use authentic short outcomes and named attribution. Vary proof density while keeping the central quote visually dominant.

### Objection ledger

**Observed:** Section heading cluster sits above a full inner-width list of FAQ rows. Questions stay at 18px, not headline size. The light version lives directly on the canvas; the dark variant groups rows inside one rounded Night panel.

**Transfer:** Answer practical setup, compatibility, cost and control questions in direct language.

### Ghost-key conversion and utility footer

**Observed:** A White tray approximately 390px tall centers a 48px Heading over the Ghost key field, with 24px before paired actions and small review or award proof underneath. Team variants shorten the tray; developer variants add a supporting line; dark variants use Night panel and the Violet launch button. A 32px rule interval separates it from a roomy gray footer with 80px vertical padding: broad identity, legal, seals, mission, language/status, download keys, review badges and help area on the left; four dense link columns on the right. The dark variant retains this structure with reversed text and a night canvas.

**Transfer:** Carry the ghost-key promise device into the new page and finish with useful navigation and trust details. Use only the utility groups the new product actually needs.

**Text style:** `heading` — Cal Sans 600 · 48px/1.1

### Alternating benefit chapters

**Only for:** team-oriented and developer landing pages

**Observed:** About 500px by 400px framed product art alternates left and right beside a Number marker, 32px Chapter-heading and Body paragraph. Media and copy are separated by 48px; the final 96px of a chapter restores breathing room.

**Transfer:** Use this for capabilities that require more than a short card caption, keeping a consistent image language across the alternation.

**Text style:** `chapter-heading` — Cal Sans 600 · 32px/1.2

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Left-aligned Display promise leads directly to four Plan cards with 12px gaps. A separate broad matrix has a white header, compact tier summaries and #fcfcfc feature rows divided by 1px edges. Category bands are slightly darker and the header stays present while comparing deeper rows.

**Transfer:** Separate quick commercial choice from detailed inspection; use one charcoal emphasis tier rather than colorful plan columns.

## Page flow

**Storyline:** Promise → tangible product demonstration → credible adoption → setup or benefit chapters → ecosystem and social proof → objections or comparison → renewed promise and useful navigation.

### Broad product landing page

1. **promise** — Split white showroom with large rounded claim, signup keys and oversized interface.
2. **product demonstration** — Numbered setup cards lead into a two-column capability grid and compact icon tiles.
3. **social proof** — Featured quote, integration tray and denser user-post wall.
4. **objection handling** — Full-width question ledger.
5. **closing call** — Trust strip, ghost-key conversion tray and multi-column utility footer.

**Transfer:** Move from a single easy-to-grasp promise to proof that the product can handle deeper needs.

### Collaborative or audience-specific landing page

1. **promise** — Centered hero above a portrait-key mosaic.
2. **capability chapters** — Alternating framed interface illustrations and numbered benefit copy.
3. **capability breadth** — A large typographic capability list fades at the top and bottom, followed by compact feature cards and audience use cases.
4. **social proof** — Integration tray and spotlight quote.
5. **closing call** — Shorter ghost-key conversion tray followed by the shared utility footer.

**Transfer:** Show how one product resolves several roles' problems without changing the core visual system.

### Commercial choice and detailed comparison

1. **promise** — Left-aligned value statement above four compact plan cards.
2. **social proof** — Narrow adoption-logo strip.
3. **comparison** — Long feature matrix with persistent tier summaries, checkmarks and category bands.
4. **closing call** — Shared ghost-key conversion tray and full utility footer.

**Transfer:** Let visitors choose quickly, then inspect details without losing the commercial context.

### Technical capability landing page

1. **promise** — Centered explanatory headline above a large browser-framed working example.
2. **setup** — Three numbered cards explain a short implementation process.
3. **capability chapters** — Format-choice grid, code-to-interface customization scene and alternating benefit chapters.
4. **product demonstration** — Additional-feature grid and wide video demonstration.
5. **objection handling** — Integration tray, FAQ and customer proof.
6. **closing call** — Trust strip and longer ghost-key promise with support text, then the utility footer.

**Transfer:** Combine understandable outcomes with implementation detail, keeping technical color inside the demo.

### Specialist product launch with a dark identity

1. **promise** — Split night tray with white headline, violet highlighted phrase and dark conversation device.
2. **product demonstration** — Large video stage followed by three setup cards.
3. **capability chapters** — Alternating dark UI scenes, transcripts, workflow objects and a luminous quantified-value card.
4. **capability breadth** — Dark benefit grid followed by a two-plus-three capability arrangement.
5. **objection handling** — Questions grouped inside a dark rounded panel.
6. **closing call** — Violet ghost-key conversion tray and reversed version of the shared utility footer.

**Transfer:** Retain the brand's geometry and information hierarchy while reserving violet light for the central innovation and conversion.

## Writing

Direct, approachable software language with an optimistic, practical bias. The promise is ambitious but the explanation quickly turns to recognizable tasks, controls and outcomes.

**Do not copy:** Do not reuse the brand name, logos, branded artwork, named customers, quotes, awards, adoption counts, prices, certifications or product claims as facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for helpful reassurance and the product name when naming a capability.
- **Rhythm:** Headlines are compact outcome statements, sometimes a conversational fragment. Support copy is usually one or two sentences; cards pair a short task title with a concrete explanation. Occasional contractions and playful lines soften technical subjects.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar activity made better or simpler; use plain comparative language. | 5–10 words | “The better way to schedule your meetings”<br>“Simple scheduling for teams” |
| Section lead | Name a broad benefit in conversational language rather than an abstract category. | 5–12 words | “Your all-purpose scheduling app”<br>“Designed for maximum efficiency” |
| Card title | Verb plus a task or unwanted problem. | 3–8 words | “Connect your calendar”<br>“Avoid meeting overload” |
| Supporting explanation | State the practical work handled, then reassure the reader. | One or two short sentences | “We'll handle all the cross-referencing, so you don't have to worry about double bookings.” |
| Primary action | Short action verb with low-friction next step. | 2–4 words | “Get started”<br>“Book a demo” |
| Closing statement | Condense the original outcome into a memorable simpler promise. | 3–10 words | “Smarter, simpler scheduling” |

**Words and phrasing to use:** simple; your; connect; customize; get started; no more; built for; set up; without; we'll handle

**Avoid:** synergize; paradigm shift; revolutionary ecosystem; unprecedented disruption; luxury; exclusive access

**Rules:**

- Translate a feature into the user's avoided work or gained control before explaining implementation.
- Use contractions and everyday verbs; technical terms belong next to concrete examples.
- Keep category chips short and sentence case, not promotional slogans.
- Actions describe what happens next, not a vague emotional reward.

## Do's and Don'ts

### Do

- Keep the default canvas #f4f4f4 and stage major scenes in white trays with 12px corners.
- Use 64px/1.1 opening type and 48px/1.1 section type with normal tracking.
- Keep default conversion keys 36px high with 12px corners and 14px light labels.
- Use 12px grid gaps and 24px feature-card padding so illustrated panels read as a related system.
- Keep 1px #e1e2e3 edges visible even when the white-on-gray contrast is subtle.
- Give small interface scenes real controls, an active state and carefully clipped boundaries.
- Use 96px chapter spacing to counterbalance the density of miniature UI.
- Keep the Ghost key field low contrast while the conversion statement stays crisp.

### Don't

- Do not turn ordinary primary buttons into 9999px-radius capsules; that silhouette belongs to the small section chips.
- Do not set body copy in the heavy display face or promote all 18px card titles to 32px.
- Do not use pure black as the whole page background for the dark variant; its base is violet-black.
- Do not introduce a broad bright accent band into the default neutral landing treatment.
- Do not replace the short contact shadows with long, high-opacity floating-card shadows.
- Do not recolor all customer logos or integration icons into a single marketing accent; the two proof treatments intentionally differ.
- Do not convert the footer into another giant display headline; it is a practical 16px link directory with an 80px vertical inset.
- Do not enlarge the step markers into decorative background numerals; keep their 32px by 28px badge scale.

## Motion and responsive

### Motion

**Observed:**

- Plain footer links declare a hover color change from #111111 to 50% opacity without underlining. Specific button transitions and animation durations are not established.

**Transfer:**

- Keep miniature interface scenes intelligible as still compositions; their clipped windows and layered controls must explain the task without relying on motion.

**Unknown:**

- Action transition timing, specific animation sequences and interactive carousel behavior are not established.

### Responsive

**Observed:**

- Desktop layouts use a 1200px outer frame; declared width thresholds include 810px and 1200px, with additional 640px, 768px and 1024px rules in the main implementation.

**Transfer:**

- On narrower layouts, stack the showroom copy above its task interface and let the copy remain fully readable before the scene is clipped.
- Reduce card-grid columns while preserving 12px gutters and the rounded scene framing. Keep ghost keys subordinate to the conversion text as the available width narrows.

**Unknown:**

- Exact mobile headline sizes, navigation transformation, ordering and padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
