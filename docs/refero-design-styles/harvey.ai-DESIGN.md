# Harvey — institutional ink and pigment

## Overview

An institutional editorial style that pairs a literary serif with a direct, contemporary sans. Warm paper and near-black bands give dense professional software a composed, credible setting, while smoky pigment textures soften the machinery. Large interface views, restrained portraits and ruled lists make this suited to complex business products with tangible workflows and substantiated outcomes.

### Essentials

- Authority comes from book-like display type rather than bold tech lettering: serif headlines and numbers use 72px/1.05, weight 400, -0.0125em tracking; functional section heads switch to 32px/1.1 medium sans.
- The opening reads as an editorial spread above a product plate: two 680px columns separated by 16px, headline on the left, 20px support and a 48px action on the right, then a 1376px-wide image after 64px.
- Controls are small rectangles, not soft capsules: 4px corners, 48px primary actions with 20px side padding, and 32px outlined secondary actions with 12px side padding.
- Color lives in the artwork, not the marketing chrome: paper #fafaf9 and ink #0f0e0d occupy nearly all structural surfaces; muted teal, olive, aubergine and dusty rose appear as low-intensity pigment behind white interface plates.
- Software is staged as a physical plate against rubbed pigment: use an 8px-clipped stage with an enlarged, sharply legible interface inset or intentionally cut off at an edge. Include this material device even without finished software, using a truthful simplified workflow plate.
- Proof reads like a ledger: 2px horizontal rules, 32px vertical row padding and 72px serif figures, with captions spatially separated rather than boxed into colorful statistic cards.
- The finish is understated but complete: a textured charcoal assurance band leads to a 24px serif invitation, an inverse rectangular action, a 1px divider and a compact five-column link directory beside a small monogram.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm ink | `#0f0e0d` | `--color-ink` | text, background, action | Primary light-theme text, dark canvas and filled light-theme actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pigment charcoal | `#1f1d1a` | `--color-charcoal` | background, surface | Backing for the textured assurance band. |
| Reading charcoal | `#33312c` | `--color-text-secondary` | text, border | Body text on paper and dark-theme ledger rules. |
| Deep warm gray | `#706d66` | `--color-muted-light-theme` | text | Inactive labels on light accordion sections. |
| Warm gray | `#8f8b85` | `--color-muted` | text, action, border | Footer headings, subdued labels and button hover fills. |
| Pale rule | `#cccac6` | `--color-rule-light` | border, text | Rules on light surfaces, secondary prose on dark surfaces and inverse-button active fill. |
| Pale stone | `#f2f1f0` | `--color-stone` | surface, background | Light proof bands and inset product spotlights. |
| Ivory paper | `#fafaf9` | `--color-paper` | background, text, border, action | Default opening canvas, reverse text and outline controls; inverse filled actions. |
| Clear white | `#ffffff` | `--color-white` | text | Closing invitation text. |

## Typography

- **HarveySerifFont** — Editorial display, feature names, large figures and closing invitation. A literary, relatively compact serif with prominent thick-thin contrast and gently expressive terminals. OpenType features: "calt", "liga". If unavailable, use **Libre Caslon Display**. Use weight 400 and preserve tight tracking; check headline wrapping. Font stack: "HarveySerifFont", "Libre Caslon Display", Georgia, serif.
- **HarveySansFont** — Functional headings, body copy, navigation and actions. A clean, open contemporary sans with moderate width and a matter-of-fact medium cut. If unavailable, use **Inter**. Use 400 and 500, not semibold as the default. Font stack: "HarveySansFont", "Inter", -apple-system, system-ui, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | HarveySerifFont | 400 | 72px | 1.05 | -0.0125em, features "calt", "liga" | Opening headline and oversized ledger figures. |
| heading-editorial | HarveySerifFont | 400 | 48px | 1.05 | -0.01em, features "calt", "liga" | Centered editorial section titles and dark capability chapter names. |
| heading-functional | HarveySansFont | 500 | 32px | 1.1 | -0.01em, features "calt", "liga" | Left-aligned capability, proof and assurance section headings. |
| card-editorial | HarveySerifFont | 400 | 32px | 1.05 | -0.01em, features "calt", "liga" | Audience-route card titles and compact social-proof heading. |
| item-heading | HarveySansFont | 500 | 24px | 1.3 | -0.01em, features "calt", "liga" | Accordion labels and benefit-card titles. |
| closing-line | HarveySerifFont | 400 | 24px | 1.05 | -0.01em, features "calt", "liga" | Single-line invitation at the top of the footer. |
| body | HarveySansFont | 400 | 20px | 1.3 | normal | Opening support, chapter descriptions and statistic captions. |
| body-compact | HarveySansFont | 400 | 16px | 1.3 | normal | Card descriptions and expanded accordion explanations. |
| action | HarveySansFont | 500 | 16px | 1.5 | normal | Primary actions on light sections. |
| action-inverse | HarveySansFont | 500 | 16px | 1 | normal | Inverse action in the closing strip. |
| action-secondary | HarveySansFont | 400 | 14px | 20px | normal | Small outline actions. |
| navigation | HarveySansFont | 500 | 14px | 1.3 | normal | Navigation and footer links. |
| footer-heading | HarveySansFont | 500 | 14px | 1.3 | -0.01em, features "calt", "liga" | Muted directory column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product overview and feature-detail openings | eyebrow | HarveySansFont | 500 | 16px | 1.3 | normal | Breadcrumbs and introductory product labels. |
| feature-detail chapters | detail-label | HarveySansFont | 500 | 16px | 1.3 | -0.01em, features "calt", "liga" | Ruled feature specifications beside large interface art. |

**Notes:**

- Display and editorial serif recipes stay at weight 400; hierarchy comes from scale and placement, not weight escalation.
- Large serif figures share the opening headline recipe. Keep the minus tracking paired with the short 1.05 line height.
- Sans headings use weight 500 with -0.01em tracking; paragraphs use weight 400 and normal tracking.
- Use the functional heading for explanation and the serif for promises, chapter names and human testimony. Preserve this division rather than rendering every heading in serif.

## Layout

**Density:** Airy at the section level, compact inside functional lists; broad pauses frame dense interface imagery.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small item heading to explanation. |
| 16px | Core grid gutters, heading-to-support gaps and footer link rhythm. |
| 20px | Primary action side padding and three-column benefit gutters. |
| 32px | Desktop page gutters, primary support-to-action gaps and ledger row padding. |
| 44px | Gap above testimonial progress rails. |
| 64px | Opening top inset, gap before major media and footer strip spacing. |
| 128px | Proof and assurance section padding. |
| 160px | Major light capability section top padding. |

### Containers and grids

- **page-grid**: max width 1728px · 6 columns · gap 16px · side padding 32px. Centered desktop grid; at 1440px the usable width is 1376px. Most compositions divide it into two 680px halves.
- **benefit-grid**: 3 columns · gap 20px. Three equal benefit columns, each with a 445px square visual above unboxed copy.
- **centered-introduction**: max width 560px. Centered launch copy and actions above full-width media.
- **footer-directory**: 5 columns · gap 16px. Five link groups occupy the right side; an independent identity and copyright column occupies the left.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 4px |
| media-stages | 8px |
| play-control | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| oversized-interface-plate | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | Oversized software plates inside audience-route artwork; not a default card effect. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing opening and early explanatory sections.

**CSS:** `background: #fafaf9; color: #0f0e0d`

**Observed:** A continuous paper field rather than separate floating content cards.

**Transfer:** Keep the first impression light even when later proof chapters become dark.

#### Ink canvas · level 0

**Use:** Late proof, capability and closing regions.

**CSS:** `background: #0f0e0d; color: #fafaf9`

**Observed:** Full-width bands run directly into one another; content remains aligned with the light grid.

**Transfer:** Use a sustained dark chapter, not a checkerboard of alternating section backgrounds.

#### Stone proof band · level 0

**Use:** Testimony and light quantified proof.

**CSS:** `background: #f2f1f0; color: #0f0e0d`

**Observed:** Slightly warmer and darker than the primary paper; visual separation without a heavy boundary.

**Transfer:** Reserve for a clear change from explanation to proof.

#### Pigment stage · level 1

**Use:** Framing white interface plates and benefit illustrations.

**CSS:** `background: #1f1d1a; border-radius: 8px; overflow: hidden`

**Observed:** Smoky, rubbed, granular pigment sweeps in subdued teal, olive, violet or rose across a near-black backing. The texture remains subordinate to the interface.

**Transfer:** Add the rubbed-pigment artwork described in imagery; use the flat charcoal only as its backing.

#### Assurance material · level 0

**Use:** Full-width reassurance band before the footer.

**CSS:** `background: #1f1d1a; color: #fafaf9`

**Observed:** Nearly black, low-contrast grain and broad shadowy streaks, not a luminous gradient.

**Transfer:** Keep the grain barely visible behind text and ruled verification rows.

#### Adaptive navigation glass · level 2

**Use:** Fixed navigation over scrolling sections.

**CSS:** `background: rgba(15,14,13,0.6); backdrop-filter: blur(16px)`

**Observed:** The navigation reverses with the section: paper-toned and dark text above light content, ink-toned with pale text above dark content. The main bar is 72px high beneath a 34px announcement strip.

**Transfer:** Preserve legibility while allowing a trace of the content behind the bar.

## Components

### Primary button

**Use:** Main conversion action on paper.

**CSS:** `background: #0f0e0d; color: #fafaf9; border-radius: 4px; padding: 0px 20px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — HarveySansFont 500 · 16px/1.5

**Observed:** A content-width rectangle, generally 158px wide for this label, placed below support copy rather than paired with several competing actions.

**States:** Declared: hover background-color #8f8b85.

**Transfer:** Use one clear enterprise conversion verb phrase.

### Inverse button

**Use:** Conversion action on the dark closing strip.

**CSS:** `background: #fafaf9; color: #0f0e0d; border-radius: 4px; padding: 0px 20px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `action-inverse` — HarveySansFont 500 · 16px/1

**Observed:** The light action anchors the far right of a horizontal invitation. A compact 32px version appears in navigation.

**States:** Declared: hover background-color #8f8b85; active background-color #cccac6.

### Outline action

**Use:** Secondary actions on dark sections or artwork.

**CSS:** `color: #fafaf9; border: 1px solid #fafaf9; border-radius: 4px; padding: 0px 12px; height: 32px; display: flex; align-items: center; justify-content: center`

**Text style:** `action-secondary` — HarveySansFont 400 · 14px/20px

**Observed:** No fill; used below descriptions and opposite section headings. A light-section version uses dark text and edge.

**States:** Declared: hover border-color #8f8b85 and color #8f8b85.

### Navigation shell

**Use:** Persistent orientation and compact conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; z-index: 100; backdrop-filter: blur(16px)`

**Text style:** `navigation` — HarveySansFont 500 · 14px/1.3

**Observed:** Small serif wordmark at left, horizontal text menu beside it, outlined login and filled conversion action at right. A slim announcement sits above; total header height is 106px. Uses Adaptive navigation glass.

**Transfer:** Keep the announcement short and the main menu visibly secondary to page content.

### Capability accordion

**Use:** A compact choice of capabilities beside one large interface stage.

**CSS:** `border-top: 2px solid #cccac6; padding-bottom: 24px; position: relative`

**Text style:** `item-heading` — HarveySansFont 500 · 24px/1.3 · tracking -0.01em

**Observed:** Left-hand list occupies about 550px within half the page. Label buttons have 20px top and 12px bottom padding; the open item reveals compact prose and a text link. Inactive light-theme labels use deep warm gray; the active label is ink. A small progress segment marks auto-advance. A dark use-case variant uses dark rules, pale active text and warm gray inactive text.

**Transfer:** Pair each label with a materially different interface view, not a decorative icon.

### Ledger row

**Use:** Large quantified outcomes on the dark proof chapter.

**CSS:** `border-top: 2px solid #33312c; padding: 32px 0px; display: grid; grid-template-columns: 1fr 1fr; gap: 16px; align-items: center`

**Text style:** `display` — HarveySerifFont 400 · 72px/1.05 · tracking -0.0125em

**Observed:** A body-sized descriptive label sits in the left half and a serif figure begins at the center line. Rows extend across the page. In the light product-proof variant, the section heading fills the left half and ruled figures with captions stack in the right half.

**Transfer:** Use substantiated outcome figures; keep units and plus signs on the same baseline.

### Verification row

**Use:** Scannable assurance or standards directory.

**CSS:** `border-bottom: 1px solid #33312c`

**Observed:** Each 680px-wide, 89px-high row puts a 48px monochrome seal at left, a 20px medium label beside it and a subdued 20px Details link at the far right. Rows are transparent over Assurance material.

**Transfer:** Use actual verification, controls or support commitments appropriate to the new product.

### Footer directory

**Use:** Full navigation at the page ending.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); gap: 16px`

**Text style:** `navigation` — HarveySansFont 500 · 14px/1.3

**Observed:** Muted small headings over pale links with 16px vertical gaps. A separate small monogram sits left; copyright is beneath it. The directory begins 64px below the invitation divider.

**States:** Declared: hover link color #cccac6.

**Transfer:** Maintain five useful groups where the information architecture supports them; let content determine group length.

### Progress rails

**Use:** Testimonial carousel position and time indication.

**CSS:** `background: #cccac6; height: 2px; position: relative`

**Observed:** Equal-width line segments separated by 16px, with a dark fill progressing along the current segment. The interactive target is 24px tall rather than only the painted line.

**Transfer:** Retain the fine segmented rule rather than replacing it with dots.

### Closing invitation

**Use:** Small, deliberate final call above the directory.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding-bottom: 64px; border-bottom: 1px solid #33312c`

**Text style:** `closing-line` — HarveySerifFont 400 · 24px/1.05 · tracking -0.01em

**Observed:** A short serif sentence at left and Inverse button at right; the strip is inset 64px from the footer top. It is not a giant headline or isolated splash screen.

**Transfer:** Make the last line an organizational invitation, with the same conversion action used earlier.

## Imagery and graphics

### Rubbed pigment and interface plates

**Use:** Signature material for the opening product scene, audience cards and feature imagery.

**Observed:** Broad charcoal brush-like fields with coarse sprayed grain, soft uneven edges and muted teal, olive, aubergine or dusty rose. White software plates sit above them, usually front-facing without perspective. The opening spans 1376px with a dashboard inset about 116px from each side; secondary views use roughly half-page stages and can deliberately clip an oversized plate.

**Transfer:** Stage a real interface or a simplified faithful output on the same granular backing. Without software, use a credible document, workflow or analytical plate; preserve the large light rectangle against pigment.

**Build:** Create an 8px-clipped wrapper on charcoal. Layer two oversized irregular SVG paths or soft polygon masks crossing at shallow diagonal angles, one translucent muted pigment and one near-black. Add SVG feTurbulence fractalNoise, desaturate it, and blend it softly into those masks to break the edges into sprayed grain. Keep the pigment dark and low-saturation; do not illuminate the center like a glow. Place a front-facing light interface plate above, inset on the hero and oversized toward the bottom-right on cards.

### Professional testimony portraits

**Use:** Human proof in light quote carousels.

**Observed:** A large nearly square portrait occupies one half of the spread with 8px corners. Images alternate between composed studio portraits against subdued violet and candid workplace photography with shallow depth of field. On the opposite side are a large serif quotation, compact name and role, and a small customer mark; Progress rails run below.

**Transfer:** Commission or choose credible, naturally lit portraits of real users. Keep the photographic subject at human scale and the quote in an open field rather than inside a speech bubble.

### Documentary video panels

**Use:** Customer-story carousel on the dark proof chapter.

**Observed:** Wide architectural and workplace footage is darkened so pale serif story text and a circular play control remain readable. A centered main panel is flanked by partial neighboring panels, with customer marks below.

**Transfer:** Use real environments associated with the product's users, graded down toward charcoal. Keep footage documentary rather than glossy lifestyle stock.

### Assurance grain

**Use:** Subtle atmospheric material in the full-width assurance band.

**Observed:** Very dark brown-charcoal texture with broad, soft vertical and diagonal pigment traces. It is barely distinguishable from a flat dark field and does not interfere with the foreground list.

**Transfer:** Use a static noise and pigment texture when an animated material is unavailable.

**Build:** On charcoal, place a full-size desaturated SVG noise layer at low opacity. Add two broad near-black irregular paths with softly feathered edges. Keep contrast low enough that pale body text and 1px rules dominate.

### Analog launch collage

**Only for:** major product launches

**Use:** Large video poster below a centered announcement.

**Observed:** A pale, mottled paper collage with scattered geometric fragments, scanned marks, charcoal swatches and a central faceted dark cube; sparse muted violet accents. Rounded rectangular framing and a centered 72px frosted circular play control.

**Transfer:** Create a new abstract object related to the product's transformation rather than a software montage. A minimum version uses textured paper, a few cut geometric fragments and one shaded faceted object.

**Build:** Use a pale stone base, monochrome SVG noise at low opacity, and asymmetric rectangular paper fragments around the perimeter. Draw a central three-face cube in SVG using three gray values and a subtle grain mask. Add thin angular line fragments and one muted violet block; leave broad empty areas around the object.

### Icons

**Observed:** Small navigation chevrons and arrows are 16px outlines, commonly 2px with round caps; compact close glyphs use 1.5px strokes. Assurance seals are larger 48px monochrome marks. Video controls use a filled light triangle.

**Transfer:** Choose restrained outline arrows and functional symbols, with larger monochrome marks only for genuine verification. Keep colorful application icons inside integration or product contexts.

## Section recipes

How recurring sections are built.

### First screen: Editorial product opening

**Observed:** Paper canvas beneath a fixed 106px header, with a small gap before the section. The first content begins 64px into the opening. A two-line 72px serif promise occupies the left half; a short 20px support paragraph starts near its top on the right, followed after 32px by Primary button. Below the heading row, a 64px pause leads to a 1376px-wide, 750px-high Pigment stage containing a front-facing white dashboard inset within the textured art. At 900px viewport height the header, full headline, support, action and upper majority of the dashboard are visible; the remainder of the plate and subsequent proof continue below the fold. Layers are paper, dark grainy pigment artwork, then a crisp light interface plate; there is no floating decorative object over the headline.

**Transfer:** Use a short promise that can naturally fill two lines in half the spread, paired with a concrete support sentence. Recreate the pigment-backed plate with a genuine workflow or output if no complete interface exists. Product overview and feature-detail openings retain the split headline/support composition but add a 16px breadcrumb 32px above the title; the overview can substitute a full-width film poster for the interface stage.

**Avoid:** Do not center the whole hero, squeeze the media into a small right-hand mockup, or use a giant slogan with no visible product before the fold.

**Text style:** `display` — HarveySerifFont 400 · 72px/1.05 · tracking -0.0125em

### Centered editorial introduction

**Observed:** A 48px serif heading, support text separated by 16px and a 64px gap before full-width content. Launch versions use a 560px copy measure, a centered action after 32px and an Analog launch collage beneath.

**Transfer:** Use for a major proposition or announcement, keeping copy short enough to preserve the surrounding paper field.

**Text style:** `heading-editorial` — HarveySerifFont 400 · 48px/1.05 · tracking -0.01em

### Audience route spread

**Observed:** Two equal 680px-wide Pigment stage cards separated by 16px. Each places a 32px serif heading, compact support and Outline action at the upper left with 32px insets, above an oversized interface plate spilling toward the lower and right edges.

**Transfer:** Present two meaningful audience or workflow entry points with different outputs; let the art carry most of the card weight.

**Text style:** `card-editorial` — HarveySerifFont 400 · 32px/1.05 · tracking -0.01em

### Capability selector

**Observed:** A 32px functional heading above a two-half composition after 64px. Capability accordion occupies about four fifths of the left half; a roughly 688px by 517px interface stage fills the right. Only the selected item reveals its support. Dark use-case sections reverse labels and rules without changing the construction.

**Transfer:** Use concise capability names and make each selected image show the specific promise in operation.

**Text style:** `heading-functional` — HarveySansFont 500 · 32px/1.1 · tracking -0.01em

### Human proof spread

**Observed:** Stone proof band with 128px top and 64px bottom padding. A large portrait sits left, a serif quote and attribution right, vertically balanced near the portrait center. Progress rails sit below with a 44px gap.

**Transfer:** Pair one real customer voice with one portrait and restrained attribution, using the same quiet editorial hierarchy.

### Ruled outcome proof

**Observed:** Default dark proof uses a 32px heading followed by full-width Ledger rows. Light product sections instead place the heading left and stack large serif figures with short captions in a ruled right-hand column over Stone proof band.

**Transfer:** Choose the full-width ledger for a broad organizational story; use the half-width variant within a product-detail narrative.

**Text style:** `display` — HarveySerifFont 400 · 72px/1.05 · tracking -0.0125em

### Assurance and footer finish

**Observed:** Assurance material spans the page with 128px vertical padding. A 448px text column on the left contains a functional heading, 20px secondary paragraph and Outline action; the right half holds Verification rows. Ink canvas continues into the footer, where Closing invitation precedes Footer directory and a small monogram/copyright column. The final action remains a 48px pale rectangle, not an oversized promotional panel.

**Transfer:** Use concrete evidence to resolve the product's principal buying objection, then finish with a concise invitation and useful navigation.

**Text style:** `closing-line` — HarveySerifFont 400 · 24px/1.05 · tracking -0.01em

### Alternating capability chapters

**Only for:** product overview pages

**Observed:** Ink canvas carries repeated two-half rows: 680px by 511px interface stages alternate sides with a 48px serif name, one short 20px paragraph and Outline action. Text is inset toward the interior of its half; 64px gaps separate rows.

**Transfer:** Give a complex product a series of focused chapters rather than compressing all modules into tiny feature cards.

**Text style:** `heading-editorial` — HarveySerifFont 400 · 48px/1.05 · tracking -0.01em

### Ruled detail chapters

**Only for:** feature-detail pages

**Observed:** Paper canvas chapters start with a 1px rule and a split 32px heading/support row. After roughly 48px–64px, a 688px by 516px interface stage sits left and a compact list of ruled feature explanations sits right. Chapters have 128px spacing and can stack with sticky headings. An inset Stone proof band spotlight pairs square imagery with a centered 48px serif name and brief explanation.

**Transfer:** Organize deeper explanations around work outcomes, with a short list of mechanisms proving each outcome.

**Text style:** `heading-functional` — HarveySansFont 500 · 32px/1.1 · tracking -0.01em

### Integration directory

**Only for:** product ecosystem sections

**Observed:** On Ink canvas, a 32px heading occupies the left half. Right-hand groups begin with a 2px pale rule and a small medium subheading, followed by application-icon rows with 1px dark rules, 16px top padding and 24px medium names.

**Transfer:** Show actual connected tools or sources as a usable directory, keeping their brand colors confined to small icons.

## Page flow

**Storyline:** organizational promise → tangible product stage → credibility and routes → capability explanation → human and quantified proof → assurance → restrained final invitation

### Broad organizational landing page

1. **Promise** — Split editorial opening over a large pigment-backed dashboard.
2. **Social proof** — Centered serif trust line above a six-column field of monochrome organization marks.
3. **Audience orientation** — Centered introduction and two large artwork-backed route cards.
4. **Product momentum** — Centered launch announcement and abstract film poster.
5. **Capability explanation** — Ruled accordion paired with changing interface imagery.
6. **Human proof** — Portrait/quote spread, then a dark documentary story carousel.
7. **Quantified proof** — Full-width dark ledger of serif figures.
8. **Objection handling** — Textured assurance band with verification rows.
9. **Closing call** — Small serif invitation, inverse action, monogram and five-column directory.

**Transfer:** Let the breadth of the product determine which narrative blocks need room; retain the editorial plate, ledger proof and understated close without treating every block as required.

### Product-family overview

1. **Promise** — Breadcrumb and split serif headline above a broad video stage.
2. **Benefits** — Three square pigment-backed benefit illustrations over unboxed text.
3. **Quantified proof** — Light half-width figure ledger opposite a functional heading.
4. **Human proof** — Portrait and quote carousel with segmented rails.
5. **Capability chapters** — Sustained dark sequence of alternating media/text rows.
6. **Compatibility** — Right-column directory of connected applications and context sources.
7. **Objection handling** — Shared assurance material and verification list.
8. **Closing call** — Shared small invitation and directory footer.

**Transfer:** Use this expanded chapter structure when a product has distinct modules and integrations; retain the light-to-dark change as a narrative shift.

### Single-feature detail and workflow explanation

1. **Promise** — Breadcrumb and split headline above a large interface plate.
2. **Capability explanation** — Introductory statement with muted and dark emphasis, followed by sticky ruled outcome chapters.
3. **Differentiation** — Inset pale spotlight with square document art and centered serif feature name.
4. **Quantified proof** — Light half-width ledger.
5. **Human proof** — Compact testimonial carousel with five progress rails.
6. **Use cases** — Dark accordion and output stage.
7. **Objection handling** — Shared assurance list.
8. **Closing call** — Shared invitation strip and full directory.

**Transfer:** For a narrow product, replace broad audience routing with detailed outcome chapters and authentic outputs while retaining the same materials and ending.

## Writing

Assured, professional and outcome-led, with a literary headline register and plain explanatory prose. Confidence comes from showing concrete work and evidence rather than exuberance.

**Do not copy:** Do not reuse Harvey's name, monogram, customer marks, quotations, proprietary product names, funding announcements, security certifications or numerical claims. Examples illustrate voice only; replace them with accurate statements and owned assets.

- **Addressing the reader:** Address the reader through your team, your work and your organization; refer to the product by name when describing what it does. We appears sparingly in institutional assurance prose.
- **Rhythm:** Headlines are short declarative promises, often two balanced clauses. Support usually consists of one or two concise sentences; feature labels are compact noun phrases. No exclamatory sales patter.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with an imperative or a compact contrast between delegated effort and retained agency. | 5–9 words | “Build a Frontier Legal Organization”<br>“Delegate the Work. Own the Judgment.” |
| Support | Name a concrete action and the usable result it returns. | 12–25 words | “[Brand] handles the work end to end and returns cited, review-ready output.” |
| Capability heading | State the benefit in everyday professional language. | 4–7 words | “Move fast, stay sharp”<br>“Control the Quality of Work” |
| Primary action | A direct, low-drama next step. | 2–4 words | “Request a Demo” |
| Proof heading | Introduce measurable usefulness without a superlative. | 4–10 words | “Delivering value at scale” |
| Closing invitation | Invite an organization-level change in a single serif line. | 7–10 words | “Unlock Professional Class AI for Your Organization” |

**Words and phrasing to use:** review-ready; your team; work; control; trusted; securely; collaborate; context; deliver; built to your standard

**Avoid:** magic; game-changing; 10x everything; crush it; revolutionary!!!; effortless perfection

**Rules:**

- Make the headline about the reader's professional agency rather than an abstract technology.
- Follow the promise with the actual operation and deliverable.
- Keep feature descriptions close to work: what starts, what happens and what the user receives.
- Use numerical proof only with clear units and a concise caption.
- Keep assurance prose factual and specific; avoid unsupported absolutes.

## Do's and Don'ts

### Do

- Keep opening serif type at 72px/1.05, weight 400, with -0.0125em tracking.
- Maintain the 32px page gutters and 16px split-layout gap at desktop.
- Give major images 8px corners and keep their interface plates front-facing.
- Use 48px filled actions for conversion and 32px outlined actions for exploration.
- Let 128px–160px section pauses coexist with compact 16px list rhythms.
- Use 2px ledger rules and large serif figures to give proof an editorial presence.
- Carry the dark proof chapter through assurance into a concise 24px serif closing line.
- Keep color embedded in subdued pigment artwork and small contextual application marks.

### Don't

- Do not substitute heavy 700-weight grotesk headlines for the light serif display.
- Do not turn 4px button corners into pill-shaped CTAs.
- Do not spread saturated accent fills across the paper canvas or marketing headings.
- Do not give every benefit a raised white card with a heavy shadow; benefit text remains unboxed.
- Do not turn ledger rows into a dashboard of colorful statistic badges.
- Do not add isometric laptop frames or tilted devices around the front-facing interface art.
- Do not replace fine segmented progress rails with oversized carousel dots.
- Do not inflate the final invitation into a 72px promotional billboard; reserve that scale for the opening and figures.

## Motion and responsive

### Motion

**Observed:**

- Primary and outline actions declare 0.3s color transitions with cubic-bezier(0,.7,.3,1); footer links declare 0.3s with cubic-bezier(.7,0,.3,1).
- Navigation glass and the inverse closing action declare 0.3s color transitions with cubic-bezier(.3,.3,.3,1).
- Capability and use-case lists have auto-advance, visible progress and a pause control; progress animation is linear.
- Feature-detail chapters use sticky positioning beneath the header.

**Transfer:**

- Keep accordion selection, progress and paired media synchronized, with a visible pause affordance.
- Use restrained tonal hover changes rather than scaling or bouncing the rectangular controls.

**Unknown:**

- Auto-advance duration and full scroll-animation choreography are unspecified.
- Focus-visible appearance is not established for every action.

### Responsive

**Observed:**

- Declared width breakpoints include 431px, 640px, 768px, 1025px, 1100px, 1106px, 1445px, 1536px and 1730px.
- Grid classes include two-, six- and twelve-column variants; footer classes include two-, three- and five-column arrangements.

**Transfer:**

- On narrow screens, recommended adaptation is headline, support/action, then full-width pigment plate; keep the interface focus legible rather than shrinking a whole desktop plate to unreadable text.
- Stack paired media/copy chapters while preserving their ruled grouping and material contrast. Reflow the directory into fewer columns before reducing type size.

**Unknown:**

- Exact mobile typography, navigation behavior, breakpoint-to-layout mapping and narrow-screen image framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
