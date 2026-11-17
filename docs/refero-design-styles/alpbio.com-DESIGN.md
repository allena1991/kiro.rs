# Alpine Bio — tactile science, dotted machinery

## Overview

An airy, materially grounded style for technical products that need to feel both useful and sensorial. Pale gray space, butter-yellow closing bands and small sky-blue actions surround tightly set grotesk typography and utilitarian mono labels. Oversized photography of pours, powders and finished objects lends warmth, while dot-built symbols supply a machine-readable counterpoint.

### Essentials

- Headlines feel compressed rather than heavy: regular Switzer at 76px/1.1 with -0.05em tracking; smaller headings retain the same tight spacing.
- The opening is a photographic immersion, not a product card: a 900px-tall edge-to-edge material scene with centered white two-line type, a narrow support paragraph and one blue action; faint vertical guides run through the scene.
- Actions are two touching pieces: a 40px-high blue text capsule with 22px corners and a separate 38px circular northeast-arrow companion.
- Color is rationed by function: #f5f5f5 dominates reading sections, #e9e9e9 groups the offering, #8ec7e2 marks actions and a full-width #f7ca50 ending delivers the strongest flat color.
- Physical texture and digital dots coexist: use tightly framed material photography alongside black dot-matrix symbols about 75px square; when no physical product exists, photograph an analogous material or build a softly lit abstract object rather than replacing the scene with UI tiles.
- The ending is a designed destination: a centered cream contact field leads into a 481px yellow footer, with a compact invitation at upper left, pale link columns at right and an enlarged dot-built identity at lower left. Carry the dotted identity device into every new page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#f7ca50` | `--color-closing` | background | Full-width closing footer, the largest flat chromatic area. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#8ec7e2` | `--color-action` | action, surface | Text capsules and their circular arrow companions, not whole reading sections. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical black | `#000000` | `--color-black` | text, accent | Headings, action text, mono labels and dotted graphics. |
| Paragraph ink | `#1e1e1f` | `--color-ink` | text | Body paragraphs and dark editorial display text. |
| Plus control gray | `#c9c9c9` | `--color-control` | surface | Small circular plus controls on offering cards. |
| Equipment gray | `#e9e9e9` | `--color-card` | surface, background | Offering cards, navigation plate and carousel controls. |
| Warm cream | `#f8f4e6` | `--color-cream` | surface, background, text | Small section-label backing, contact field and pale footer links. |
| Pale gray canvas | `#f5f5f5` | `--color-canvas` | background, text | Default reading canvas and light text on selected image-led openings. |
| Photographic white | `#ffffff` | `--color-white` | text, surface | Primary hero lettering and image captions; white inset explanatory panels. |

## Typography

- **Switzer** — Hero headings, section headings and offering titles. Neutral grotesk, clean open forms and tightly packed regular-weight display lines. If unavailable, use **Inter**. Use 400 and 500 with the same negative tracking; check line wraps. Font stack: "Switzer", "Inter", Arial, sans-serif.
- **Geist** — Editorial statements, body copy, buttons and footer links. Compact contemporary grotesk with a pragmatic technical tone. Font stack: "Geist", Arial, sans-serif.
- **PT Mono** — Navigation, technical eyebrows and small directional labels. Monospaced uppercase markings, unusually tight rather than widely letterspaced. Font stack: "PT Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Switzer | 400 | 76px | 1.1 | -0.05em | Primary opening headline; centered over photography by default. |
| heading-lg | Switzer | 400 | 48px | 1.1 | -0.05em | Major showcase and process headings. |
| statement | Geist | 400 | 42.1px | 1.2 | -0.05em | Large editorial introduction, laid out as a readable paragraph rather than a slogan. |
| heading | Switzer | 400 | 32px | 1.2 | -0.05em | Compact section heading above an offering grid. |
| lead | Geist | 500 | 22.1px | 1.2 | -0.05em | Footer invitation, offering-list names, process-step titles and emphatic editorial paragraphs. |
| card-title | Switzer | 500 | 20px | 1.2 | -0.05em | Centered offering-card names. |
| link-lg | Geist | 400 | 18.2px | 1.35 | -0.03em | Footer links; also longer explanatory paragraphs in the institutional variant. |
| body | Geist | 400 | 15px | 1.35 | -0.03em | Descriptions, action labels and short white captions inside photographs. |
| eyebrow | PT Mono | 400 | 13px | 1.2 | -0.04em, uppercase | Navigation, section labels and small directional headings. |

**Notes:**

- Use regular-weight display type; scale and tight tracking carry emphasis instead of boldness.
- Display, statement and lead roles share -0.05em tracking; body and link roles loosen to -0.03em. Mono labels stay compact at -0.04em.
- Keep each recipe intact rather than borrowing a heading size with a body line height. The introduction label is a sentence-case body recipe on cream; technical labels use the uppercase eyebrow recipe.

## Layout

**Density:** Airy at section scale and compact inside controls: long pauses surround tightly joined text, icons and images.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Offering-grid gutters and cream-label padding. |
| 10px | Common internal flex gap and action vertical padding. |
| 16px | Default page edge and action horizontal padding. |
| 24px | Navigation link separation and footer side padding. |
| 32px | Introduction stack, heading support groups and offering-card internal spacing. |
| 48px | Heading-to-grid separation. |
| 64px | Gallery cell inset and process-column separation. |
| 80px | Footer top padding and institutional panel padding. |
| 110px | Introduction vertical padding and footer separation between upper links and lower identity. |
| 150px | Default offering and showcase section vertical padding. |
| 160px | Catalog section vertical padding and deeper editorial image margins. |

### Containers and grids

- **Marketing container**: max width 1800px · side padding 16px. Broad centered content; at desktop the reading field uses almost the full viewport.
- **Offering grid**: 3 columns · gap 8px. Three equal 464px-wide cards at a 1440px viewport; compact gutters contrast with airy section padding.
- **Introduction measure**: max width 986px. Large left-aligned statement occupies roughly seven tenths of the desktop width, leaving the right side open.
- **Process grid** (only for process explanations): 3 columns · gap 64px · side padding 32px. Three equal text columns below a left-aligned heading.
- **Gallery grid** (only for use-case galleries): 2 columns · gap 0px · side padding 64px. Edge-to-edge two-column structural grid; each 720px cell contains a 592px-wide image with a 64px inset.
- **Institutional inset** (only for company and platform explanations): max width 1280px · side padding 80px. Inset editorial field with alternating text and square photography.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Action capsules | 22px |
|  | Navigation plate | 4px |
|  | Plus controls | 18px |
|  | Carousel controls | 3px |
| company and platform explanations | Editorial photos | 20px |

## Surfaces and depth

### Surfaces

#### Reading canvas · level 0

**Use:** Default background for text, grids and editorial pauses.

**CSS:** `background: #f5f5f5`

**Observed:** Flat, borderless and unshadowed; the pale neutral continues across multiple sections.

**Transfer:** Let white space, not raised panels, separate the narrative.

#### Offering slab · level 1

**Use:** Grouped offering choices.

**CSS:** `background: #e9e9e9; box-shadow: none`

**Observed:** Square-edged gray cards without an outline or elevation.

**Transfer:** Use a slightly darker gray than the canvas so a compact grid remains legible without decorative borders.

#### Contact field · level 0

**Use:** Centered closing invitation.

**CSS:** `background: #f8f4e6`

**Observed:** A broad warm cream band with a small black contact label, two-line dark heading and blue action centered within substantial empty space.

**Transfer:** Keep this distinct from the brighter footer; use one clear next step.

#### Yellow ending · level 0

**Use:** Conversion and site-directory footer.

**CSS:** `background: #f7ca50; padding: 80px 24px 8px`

**Observed:** Full bleed, flat and warm, carrying black invitation copy and pale navigation links.

**Transfer:** Concentrate saturated flat color here instead of distributing colored panels through the whole page.

#### White editorial inset · level 1

**Only for:** company and platform explanations

**Use:** Longer explanations with alternating photographs.

**CSS:** `background: #ffffff; padding: 80px 20px; box-shadow: none`

**Observed:** A large square-edged white field inside the pale gray page; rounding belongs to its photos, not the outer panel.

**Transfer:** Reserve this white-on-gray distinction for deeper process or institutional content.

## Components

### Navigation plate

**Use:** Persistent compact site navigation at upper left.

**CSS:** `background: #e9e9e9; border-radius: 4px; padding: 2px; height: 54px; width: 571px`

**Text style:** `eyebrow` — PT Mono 400 · 13px/1.2 · tracking -0.04em · uppercase

**Observed:** A fixed plate sits 16px from the top and left, combining a black identity with a compact horizontal link row. The contact action floats independently at upper right. Links are separated by 24px; one category has a small downward chevron.

**Transfer:** Keep the identity and a few top-level destinations in a single compact plate rather than stretching a navigation bar across the page.

### Capsule action

**Use:** Primary and secondary navigation actions, differentiated by wording rather than a second button color.

**CSS:** `background: #8ec7e2; color: #000000; border-radius: 22px; padding: 10px 16px; height: 40px; display: flex; align-items: center; justify-content: center`

**Text style:** `body` — Geist 400 · 15px/1.35 · tracking -0.03em

**Observed:** The text capsule touches a separate Arrow companion. Together they form one link, with a subtle backdrop blur on the wrapper; some conversion capsules also use a 5px backdrop blur.

**Transfer:** Use the same blue construction for conversion, exploration and contact, with concise verb-led labels.

### Arrow companion

**Use:** The second piece of every capsule action.

**CSS:** `background: #8ec7e2; border-radius: 22px; width: 38px; height: 38px; display: flex; align-items: center; justify-content: center`

**Observed:** A small black northeast arrow is centered in the circle, aligned vertically with the text capsule; the two shapes remain visibly separate.

**Transfer:** Treat both pieces as one accessible link, not two separate targets.

### Offering card

**Use:** A compact collection of products or capabilities.

**CSS:** `background: #e9e9e9; height: 300px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 32px; position: relative; overflow: hidden`

**Text style:** `card-title` — Switzer 500 · 20px/1.2 · tracking -0.05em

**Observed:** Each card centers a black dot-built symbol over its name. A Plus control is pinned to the upper right, inset 16px. The whole card is a link.

**Transfer:** Give each offering a related but distinct dotted symbol rather than a colorful stock illustration.

### Plus control

**Use:** Small exploration cue on offering cards.

**CSS:** `background: #c9c9c9; border-radius: 18px; width: 36px; height: 36px; display: flex; align-items: center; justify-content: center`

**Observed:** A thin black plus sits inside a gray circle at the card corner; it is secondary to the central dotted symbol.

**Transfer:** Keep it a small affordance, not a large floating primary button.

### Section label

**Use:** A small introductory marker above editorial text.

**CSS:** `background: #f8f4e6; padding: 8px; display: flex; align-items: center; justify-content: center`

**Text style:** `body` — Geist 400 · 15px/1.35 · tracking -0.03em

**Observed:** A flat cream rectangle with no pill rounding. The default introduction label uses sentence case; technical chapters use the eyebrow recipe on the same backing.

**Transfer:** Use for orientation, not as a colorful badge collection.

### Carousel controls

**Use:** Navigate a horizontally overflowing photographic showcase.

**CSS:** `background: #e9e9e9; border-radius: 3px; width: 42px; height: 42px; overflow: hidden`

**Observed:** Two square controls with black left and right chevrons are grouped at the heading's right edge, separated by 6px. Small centered dots below the images mark the current position.

**Transfer:** Retain compact square controls even though primary actions are rounded.

### Footer link column

**Use:** Small directory groups on the yellow ending.

**CSS:** `display: flex; flex-direction: column; gap: 4px; color: #f8f4e6`

**Text style:** `link-lg` — Geist 400 · 18.2px/1.35 · tracking -0.03em

**Observed:** Each directory has a black uppercase mono label with a bent arrow to its left, followed by a vertical list of pale links. Two groups sit toward the right side of the footer.

**Transfer:** Separate navigation from conversion: directory at right, invitation at left.

### Footer invitation

**Use:** Compact conversion message in the yellow ending.

**CSS:** `max-width: 400px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `lead` — Geist 500 · 22.1px/1.2 · tracking -0.05em

**Observed:** Two short lines of black invitation copy sit over a Capsule action. The block anchors the upper left, counterbalancing the directory columns.

**Transfer:** Pair a reader-centered next step with a concrete offer of help, documentation or a trial.

## Imagery and graphics

### Immersive material photography

**Use:** Default opening scene and major visual bridges.

**Observed:** An extreme close-up of cream-colored liquid pouring into clear glass fills the viewport, with edges extending out of frame. Warm beige and soft gray dominate, visible bubbles and glass rims provide texture, and a dark neutral veil lets white lettering sit clearly over the scene. Fine vertical lines divide the image into broad bays.

**Transfer:** Use a close, tactile view of the new product in action, or photograph a material that expresses its effect. Minimum acceptable replacement is one carefully lit macro still with a large central object, not a collage.

**Build:** Place an object-fit:cover image at the back of a full-height section. Add an rgba(0,0,0,0.4) veil, tuning it for readable white text. Overlay 1px vertical rules in rgba(255,255,255,0.08) at the outer margins and roughly quarter-width intervals. Keep the image warm and the rules subordinate.

### Dotted equipment symbols

**Use:** Offering cards, catalog rows and the enlarged closing identity.

**Observed:** Black circular dots assemble segmented discs, a many-sided outline and small internal marks. Symbols are about 75px square in cards. The same dot-built construction turns the footer identity into an enlarged graphic rather than ordinary typeset text.

**Transfer:** Create an original dotted symbol family and a dotted rendering of the new identity. Carry the dot construction through both small symbols and the closing graphic.

**Build:** Use SVG circles on a regular lattice: approximately 3px dot diameter with 4px center spacing in a 75px symbol viewBox. Mask the lattice into a geometric disc, segmented wheel or polygon; vary internal cutouts while retaining the same dot density. For the identity, render original lettering as paths and sample it onto the same dot lattice, scaling the finished art into a roughly 382px-wide closing slot.

### Photographic use-case panels

**Use:** Showcase carousel and dedicated gallery.

**Observed:** Cropped pours, bars, capsules, yogurt and bubbling clear liquid fill rectangular frames. Subjects are enlarged, neutrally backed and directional shadows remain visible. A restrained dark veil unifies the photographs; a small white caption sits inside the lower-left corner. The carousel shows large neighboring panels; the gallery gives each photo a generous cell inset.

**Transfer:** Show tangible outcomes or real contexts, one per image. Keep the caption short and inside the frame rather than adding a separate card body.

### High-key material diptych

**Only for:** catalog and material-detail pages

**Use:** An image-only pause between technical listing and process information.

**Observed:** Two 510px by 654px photographs show clear liquid pouring into a glass and a close-up of fine white powder. The right image starts 100px higher; nearly white backings, crisp texture and cool gray shadows make the images feel laboratory-clean.

**Transfer:** Pair two complementary material states with the same high-key treatment. Keep their outer frames square and stagger their top edges.

### Institutional editorial photography

**Only for:** company and platform explanations

**Use:** Story, production and method explanations.

**Observed:** A silver product pouch is presented on a pale neutral field; later, warm backlit plant photography alternates with monochrome industrial imagery. Method photos are roughly 480px square with 20px corners inside a large white inset.

**Transfer:** Combine one isolated real artifact with photographs of the process or people behind it. Preserve the warm-natural versus monochrome-industrial contrast without making it a decorative collage.

### Icons

**Observed:** Small solid black SVG arrows and plus signs, generally 16px, with an 11px by 6px navigation chevron. Carousel chevrons occupy 42px control images. Dotted offering symbols are a distinct graphic family, not conventional UI icons.

**Transfer:** Choose simple black directional shapes, center them optically and reserve the dot-built treatment for identity and offering symbols.

## Section recipes

How recurring sections are built.

### First screen: Immersive opening

**Observed:** A 900px full-viewport photographic scene sits behind a neutral veil and faint vertical guides. Navigation plate floats at upper left and a Capsule action at upper right. Centered white display type occupies two lines across roughly half the viewport width in the upper-middle of the scene; a narrow three-line support paragraph sits below, then a Capsule action with Arrow companion. The main glass and pour extend well beyond the text block and out of frame. A small mono scroll cue sits at the bottom. Within the first 900px, the entire promise, support, main action and material scene are visible; the editorial introduction begins below.

**Transfer:** Make a centered benefit statement against one oversized tactile subject. Without product media, art-direct a macro material or simple physical object whose behavior expresses the benefit. Catalog openings instead use a shorter image-led band with a bottom-left headline; use-case openings use dark display text at left with an eyebrow and support at right; institutional openings pair a small explanatory block at left with a compact multiline heading at right before a large image.

**Avoid:** Do not turn this into a left-text/right-dashboard split, add a row of competing hero buttons or place the main object in a rounded card.

**Text style:** `display` — Switzer 400 · 76px/1.1 · tracking -0.05em

### Editorial statement

**Observed:** Reading canvas with 110px vertical padding and 16px edges; Section label precedes a large left-aligned statement about 986px wide. The statement uses the statement recipe and a Capsule action follows with 32px separation.

**Transfer:** Explain what the product does, how it differs and whom it serves in a single substantial paragraph. Retain the open right side rather than filling it with decorative media.

**Text style:** `statement` — Geist 400 · 42.1px/1.2 · tracking -0.05em

### Offering overview

**Observed:** A heading row places a 32px heading at left and exploration action at right. After 48px, three Offering cards form a tight 8px-gutter grid. Section padding is 150px vertically and 16px horizontally.

**Transfer:** Group a small set of capabilities, product families or benefits, each with a dotted symbol and succinct name.

**Text style:** `heading` — Switzer 400 · 32px/1.2 · tracking -0.05em

### Photographic showcase

**Observed:** A 48px heading pairs with Carousel controls above an overflowing strip of large landscape images. In-image captions sit low and left; position dots sit below the strip and a view-all Capsule action is left aligned beneath it.

**Transfer:** Use visual outcomes as proof. Let neighboring frames remain partly visible to communicate a larger collection.

**Text style:** `heading-lg` — Switzer 400 · 48px/1.1 · tracking -0.05em

### Contact and yellow ending

**Observed:** Contact field centers a small black label with pale mono text, a regular two-line heading and one Capsule action in an expansive cream band. Yellow ending then fills a 481px-high field. Footer invitation is upper left, two Footer link columns occupy the upper right, and the dotted identity anchors the bottom left in a roughly 382px-wide slot. Small black mono legal text aligns along the bottom right. All page types share this ending.

**Transfer:** Use the cream field for one direct invitation and the yellow field for a compact offer of help and site navigation. Preserve the enlarged dotted identity and asymmetrical footer balance; the exact wording and link count can change.

**Text style:** `lead` — Geist 500 · 22.1px/1.2 · tracking -0.05em

### Technical catalog rows

**Only for:** catalog pages

**Observed:** After a small section marker and concise lead, full-width rows are separated by faint neutral rules. Names sit in the left quarter, dotted symbols in the next quarter and compact descriptions in the right half, with descriptions limited to 500px. Rows are 136px tall with 64px gaps.

**Transfer:** Use each row to connect a named offering with its material identity and functional benefit. Keep specification prose more compact than the name-and-symbol field.

**Text style:** `lead` — Geist 500 · 22.1px/1.2 · tracking -0.05em

### Process columns

**Only for:** process explanations

**Observed:** A mono label, 48px heading and short support line introduce three text columns separated by 64px. A faint top rule marks each column, followed by a 22.1px title and a short 15px description. Outer padding is 128px vertically and 32px horizontally.

**Transfer:** Explain the reader's path from initial need to working result using concise noun-like step titles.

**Text style:** `heading-lg` — Switzer 400 · 48px/1.1 · tracking -0.05em

### Framed outcome gallery

**Only for:** use-case galleries

**Observed:** A two-column structural grid uses fine vertical and horizontal separators. Each cell surrounds a 592px by 466px photograph with 64px of space. Short white captions are embedded at lower left; the page opens with an asymmetrical text-only heading and support pair.

**Transfer:** Give each outcome a full photograph and compact label, without feature bullets or nested rounded cards.

**Text style:** `body` — Geist 400 · 15px/1.35 · tracking -0.03em

### Alternating institutional explanation

**Only for:** company and platform explanations

**Observed:** Story text uses 22.1px medium paragraphs in a 600px measure alongside an isolated artifact photo. The deeper method chapter places alternating 320px text blocks and roughly 480px square rounded photos within White editorial inset. Small cream mono labels orient each chapter. A short centered recruitment invitation follows before the common contact field.

**Transfer:** Use the variant to explain origin, approach and people, retaining alternation and the artifact-to-process progression.

**Text style:** `lead` — Geist 500 · 22.1px/1.2 · tracking -0.05em

## Page flow

**Storyline:** Material promise → plain-language explanation → offerings or outcomes → practical path or method → direct invitation → bright directory ending.

### Flagship marketing landing page

1. **Promise** — Full-height tactile photographic opening with centered two-line benefit and one action.
2. **Positioning** — Large editorial statement on pale gray.
3. **Capability overview** — Tight three-card offering grid with dotted symbols.
4. **Outcome proof** — Wide photographic showcase with captions and compact carousel controls.
5. **Closing call** — Centered cream contact field, then yellow invitation and directory footer.

**Transfer:** Balance one immersive opening with a few spacious explanations and tangible outcome images; use the same closing devices without fixing the number of middle sections.

### Offering catalog and commercial enablement

1. **Promise** — Shorter photographic hero with large lower-left white heading.
2. **Offering detail** — Ruled rows connect names, dotted symbols and concise functional descriptions.
3. **Material demonstration** — Staggered high-key photo pair.
4. **Practical path** — Three process columns below a heading and support line.
5. **Closing call** — Cream contact invitation and shared yellow footer.

**Transfer:** Move from what is available to how it can be evaluated and supplied; adapt the steps to the new product's buying process.

### Demonstrate use cases through outcomes

1. **Orientation** — Dark large title at left, small category label and explanatory support at right.
2. **Outcome collection** — Two-column ruled photographic gallery with labels inside images.
3. **Closing call** — Cream contact field and shared yellow footer.

**Transfer:** Let a visual collection do most of the explaining; supply just enough copy to connect outcomes to the product.

### Institutional story and production credibility

1. **Positioning** — Asymmetrical text introduction, then an oversized warm material image.
2. **Origin and rationale** — Medium-weight story paragraphs beside an isolated product artifact.
3. **Method explanation** — White inset alternates text with warm natural and monochrome process images.
4. **Participation** — Small centered recruitment invitation and dark action.
5. **Closing call** — Shared cream contact invitation and yellow footer.

**Transfer:** Explain why the organization exists and how it works; keep institutional depth scoped rather than importing it into every landing page.

## Writing

Confident, practical and technically literate, with a little sensory warmth. Benefits are expressed through concrete functionality and removed trade-offs rather than hype.

**Do not copy:** Do not reuse Alpine Bio's name, logo, proprietary offering names, technical claims, purity figures, performance multipliers or source sentences as new-product claims. Examples below illustrate voice only.

- **Addressing the reader:** Use we for the maker and your for the reader's work or desired result. Refer to the product directly rather than personifying it.
- **Rhythm:** Headings are short declarative phrases, often split into two balanced lines. Support mixes one explanatory sentence with clipped benefit fragments; descriptions stay compact even when technical.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the useful category, then express the low-friction benefit. | 4–8 words across two lines | “Functional Ingredients Invisible in Formulations” |
| Technical description | Describe function and then remove familiar compromises in short fragments. | 25–45 words | “Fractionated soy protein isolate with over 90% purity, neutral flavor, and complete solubility. No gums, no maskers, no off-notes. The blank slate protein.” |
| Section headline | Plain noun phrase or a compact from-to journey. | 2–5 words | “From Sample to Scale”<br>“Applications Showcase” |
| Supporting line | Explain the direct practical outcome in a single sentence. | 8–16 words | “A direct line from formulation challenge to commercial supply.” |
| Primary action | Verb plus a concrete next step. | 2–4 words | “Request a Sample”<br>“Get In Touch” |
| Closing invitation | Reader-centered starting point followed by tangible assistance. | 10–18 words | “Your next formulation starts here. Get samples, specs, and technical support.” |

**Words and phrasing to use:** functional; designed for; neutral; performance; purity; support; from … to …; without the trade-offs; your next

**Avoid:** revolutionary magic; game-changing; world's best; effortlessly amazing; excessive exclamation marks

**Rules:**

- Translate a technical mechanism into a practical benefit before adding specifications.
- Name the reader's actual work, not an abstract lifestyle aspiration.
- Use quantified claims only when independently supported for the new product.
- Keep photo captions to recognizable category names.
- Use short verbs for actions and nouns for process steps.

## Do's and Don'ts

### Do

- Keep primary display type at weight 400 with -0.05em tracking.
- Use 16px outer edges for broad marketing sections and 24px sides in the footer.
- Pair 40px blue capsules with separate 38px arrow circles.
- Keep the three-card overview tight with 8px gutters and 300px-tall gray cards.
- Use 150px vertical pauses around core offering and showcase chapters.
- Place short white photo captions inside the lower-left image edge.
- Maintain black dot-built symbols and an enlarged dotted identity in the ending.
- Use cream as the transition into the strong yellow footer.

### Don't

- Do not use bold oversized headings throughout; the primary display is weight 400.
- Do not spread the blue action color over large reading panels.
- Do not round every container to 20px; that rounding is reserved for institutional photos, while offering slabs stay square.
- Do not add drop shadows to the gray cards or white inset panels.
- Do not make all navigation links normal sans text; the compact top plate uses 13px-class uppercase mono.
- Do not use widely tracked technical labels; PT Mono is set at -0.04em.
- Do not replace the yellow footer with a conventional dark multicolumn footer.
- Do not turn photo captions into large titles outside the frames.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transition declarations were matched. The visible showcase includes previous/next controls and position dots.

**Transfer:**

- Preserve the sideways continuation of the showcase and use its controls to expose additional outcomes; keep text readable independent of animation.

**Unknown:**

- Hero media playback behavior, scroll-animation sequencing and interaction timing are not established. No specific duration or easing is prescribed.

### Responsive

**Observed:**

- Declared width breakpoints cluster around 810px and 1200px.

**Transfer:**

- At narrow widths, preserve the headline-over-material composition while reducing line length and keeping the main subject behind the text.
- Stack offering cards, process columns and gallery cells when their text or imagery can no longer retain its intended measure; keep the arrow companion joined to its capsule.
- Reflow the footer directory below the invitation while retaining the dotted identity as a distinct lower anchor.

**Unknown:**

- Exact mobile typography, navigation replacement, section heights and grid-collapse behavior are not established. The narrow-screen rules are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
