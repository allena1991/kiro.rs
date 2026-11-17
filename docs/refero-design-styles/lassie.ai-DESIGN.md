# Lassie — human work in bloom

## Overview

A humane, sunlit alternative to technological spectacle, suited to services that give people time and attention back. Warm ivory and white carry literary serif headlines, understated sans-serif explanations and tiny monospaced annotations. Candid workplace film, shallow-focus flowers and small interface fragments make the experience feel lived-in rather than diagrammatic, with sparse text and expansive visual stages.

### Essentials

- Headlines speak in paired human statements: abcMarist at 86.5px, weight 350, 0.95 line height and -0.02em tracking, with the second line italic rather than heavier.
- The opening is a film still, not a software dashboard: a full-width 900px-tall human close-up, centered white two-line headline, 17px support and a compact email action anchored 16px above the bottom.
- Controls resemble little joined cushions: white 40px navigation segments with 12px corners inside a 16px translucent frame; conversion buttons are 42px tall, not full pills.
- Color lives mainly in the world being photographed: ivory #f9f8f5 dominates the reading canvas, orange #ff740a is restricted to the small navigation conversion tab, and pale cyan appears beneath the closing white panel.
- Proof floats around an empty center: rounded candid photos and cream interface fragments orbit a serif claim; include a human-and-work collage with a central outcome rather than a conventional stat grid.
- Nature and monumental lettering complete the atmosphere: include a sunlit shallow-focus photographic band and a near-edge-to-edge white wordmark on a pale cyan gradient beneath a footer with 64px lower corners. When original media is unavailable, use a candid still, a licensed botanical photograph and live serif lettering of the new identity.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Demo orange | `#ff740a` | `--color-orange` | action | Small navigation conversion tab only; photographic orange is independent of this UI token. |
| Closing sky | `#c3eaf4` | `--color-sky` | background | Bottom stop of the closing gradient and text selection background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown black | `#120c08` | `--color-ink` | text, action | Controls, smaller headings and dark conversion buttons. |
| Headline black | `#000000` | `--color-black` | text | Editorial headings and quotations. |
| Soft gray | `#666666` | `--color-secondary` | text | Explanations, secondary labels and FAQ answers. |
| Stone glass | `#f0ede6` | `--color-nav-wash` | surface | Visible stone wash on ivory, made from rgba(227,221,207,0.4); navigation glass changes with its backdrop. |
| Light stone glass | `#f5f3ed` | `--color-form-wash` | surface | Visible 20% stone wash on ivory; rgba(227,221,207,0.2) over photographic forms takes on the underlying image colors. |
| Warm ivory | `#f9f8f5` | `--color-canvas` | background, surface | Dominant reading canvas and small inset labels. |
| Glass glint | `#faf9f6` | `--color-glass-edge` | border | Visible white 10% edge on ivory; use rgba(255,255,255,0.1) on translucent frames. |
| Paper white | `#ffffff` | `--color-white` | surface, text, action | Cards, navigation segments and footer; reversed headlines on photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruiting lists | Focus blue | `#42b5dc` | `--color-focus` | border | 2px focus-visible border on recruiting rows. |

## Typography

- **abcMarist** — Headlines, outcome claims, quotations and editorial passages. Literary serif with soft, substantial forms at a light intermediate weight; expressive true italic. If unavailable, use **Lora**. Use regular and italic near weight 400; preserve line breaks and tune width before increasing weight. Font stack: "abcMarist", "Lora", Georgia, serif.
- **dmSans** — Body copy, navigation, forms and actions. Friendly, open sans-serif; consistently regular rather than forcefully bold. If unavailable, use **DM Sans**. Font stack: "dmSans", "DM Sans", system-ui, sans-serif.
- **dmMono** — Compact attribution tags and recruiting action labels. Small, utilitarian monospace that punctuates the otherwise editorial typography. If unavailable, use **DM Mono**. Font stack: "dmMono", "DM Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | abcMarist | 350 | 86.5px | 0.95 | -0.02em | size clamp(7.69rem, 6.01vw, 10.4rem) | Centered opening headline in white. |
| display-italic | abcMarist | 350 italic | 86.5px | 0.95 | -0.02em | fixed | Contrasting second line within the opening headline. |
| heading | abcMarist | 350 | 58.3px | 1.05 | -0.01em | size clamp(5.18rem, 4.05vw, 7rem) | Section leads, central outcome statements and footer proposition. |
| heading-italic | abcMarist | 350 italic | 58.3px | 1.05 | -0.01em | fixed | Second line of the footer proposition. |
| faq-heading | abcMarist | 350 | 58.3px | 1 | -0.01em | size clamp(5.18rem, 4.05vw, 7rem) | Compact standalone question-section heading. |
| quote | abcMarist | 350 | 24.9px | 1.1 | -0.008em | size clamp(2.22rem, 1.73vw, 3rem) | Customer quotations and compact feature-side headlines. |
| feature-title | dmSans | 400 | 20px | 1.2 | 0.01em | fixed | Short titles below product illustrations. |
| body | dmSans | 400 | 17px | 24px | normal | fixed | Supporting explanations, customer names, questions and the opening support line. |
| small | dmSans | 400 | 15px | 20px | 0.005em | fixed | Conversion buttons, footer links and FAQ answers. |
| nav | dmSans | 400 | 14px | 1 | normal | fixed | Short labels in floating navigation segments. |
| attribution | dmMono | 400 | 10px | 1.54 | -0.01em | fixed | Small organization tags paired with customer names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company and mission pages | editorial-display | abcMarist | 350 | 86.5px | 0.95 | normal | size clamp(7.69rem, 6.01vw, 10.4rem) | Black centered mission headline on ivory. |
| company and mission pages | editorial-body | abcMarist | 350 | 33.3px | 1.1 | normal | size clamp(2.96rem, 2.31vw, 4rem) | Centered mission paragraphs and short opening afterthought. |
| recruiting lists | job-action | dmMono | 400 | 15px | 20px | 0.005em | fixed | Inset action at the right of a recruiting row. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep regular and italic at the same size and weight; contrast comes from the cut, not a jump to bold.
- Tracking tightens from -0.01em in section headings to -0.02em in the opening; body copy is neutral or very slightly open.
- Fluid formulas use a 10px rem basis. Preserve that basis for these formulas even if the surrounding application uses another root size.
- The monumental closing identity is vector lettering fitted to 96% of the viewport width, not another body heading. Use a width-fitted serif SVG or live text for a new identity.

## Layout

**Density:** Airy editorial stages with compact controls; large stretches of ivory separate short statements while cards keep practical 24px padding.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Primary vertical rhythm for section spacing and component gaps; local control details use finer increments.

| Value | Use |
| --- | --- |
| 8px | Question-to-answer spacing and small stacked details. |
| 16px | Opening form bottom inset and compact layout padding. |
| 24px | Card padding and feature-grid gaps. |
| 32px | Desktop page gutters and common flex gaps. |
| 40px | Opening headline-to-support gap. |
| 56px | Section heading-to-feature-stage separation. |
| 80px | Footer top padding. |
| 96px | Feature chapter bottom padding. |
| 160px | Question and institutional-proof section vertical padding. |
| 200px | Feature chapter top padding. |

### Containers and grids

- **wide-stage**: max width 2056px · side padding 32px. Near-full-width media and feature stages, centered on wide screens.
- **feature-grid**: 3 columns · gap 24px · side padding 32px. Equal-width square illustrations above short left-aligned captions; 443px image width at the desktop reference size.
- **question-column**: max width 540px. Narrow centered stack surrounded by much wider ivory space.
- **story-card**: max width 766px · 2 columns · gap 24px. Portrait at left and a quote with bottom-aligned attribution at right.
- **footer-shell**: max width 2120px · side padding 32px. Wide left proposition and action balanced against three compact link groups on the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 12px |
|  | cards-and-glass | 16px |
|  | attribution-tag | 4px |
|  | large-photo-and-footer | 64px |
| recruiting lists | job-inset | 18px |

## Surfaces and depth

### Surfaces

#### Ivory canvas · level 0

**Use:** Main reading ground.

**CSS:** `background: #f9f8f5; box-shadow: none`

#### White content card · level 1

**Use:** Quotes and question rows.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: none`

**Observed:** Separation is achieved through white against ivory, without a gray outline or elevation shadow.

**Transfer:** Let contrast of material carry grouping.

#### Navigation glass · level 2

**Use:** Frame around segmented navigation.

**CSS:** `background: rgba(227,221,207,0.4); border: 1px solid rgba(255,255,255,0.1); border-radius: 16px; backdrop-filter: blur(13px)`

**Observed:** A narrow translucent lip surrounds opaque white segments.

**Transfer:** Keep the frame closely fitted rather than creating a full-width glass header.

#### Email glass · level 2

**Use:** Compact conversion form over photography.

**CSS:** `background: rgba(227,221,207,0.2); border: 1px solid rgba(255,255,255,0.1); border-radius: 16px; backdrop-filter: blur(8px)`

#### Closing white shell · level 1

**Use:** Footer foreground over the closing identity.

**CSS:** `background: #ffffff; border-radius: 0px 0px 64px 64px`

**Observed:** The bottom corners reveal a separate pale-blue stage below.

**Transfer:** Keep footer content on white, not directly on the oversized lettering.

#### Closing sky gradient · level 0

**Use:** Backdrop behind the monumental white identity.

**CSS:** `background: linear-gradient(#ffffff 0%, #f9f8f5 30%, #c3eaf4 100%)`

**Observed:** A viewport-height backdrop sits behind the foreground footer; about 418px is revealed at the page end.

**Transfer:** Match the soft wash rather than making a saturated blue banner.

#### Ivory to white transition · level 0

**Use:** Bridge from late content into the white footer.

**CSS:** `background: linear-gradient(#f9f8f5 0%, #ffffff 100%)`

**Observed:** The company institutional-proof variant holds ivory until 80.8% before fading to white.

## Components

### Floating navigation

**Use:** Persistent compact orientation, with a separate utility cluster at the top right.

**CSS:** `display: flex; position: fixed; top: 16px; left: 50%; transform: translateX(-50%); height: 40px; z-index: 10`

**Text style:** `nav` — dmSans 400 · 14px/1

**Observed:** Identity and two short links form the centered cluster inside Navigation glass. Utility access and the orange conversion tab sit in a second cluster. The identity contracts to its symbol during the reading sequence.

**Transfer:** Use only a few destinations so the object remains small.

### Navigation segment

**Use:** Individual link inside either navigation cluster.

**CSS:** `background: #ffffff; color: #120c08; height: 40px; padding: 0px 12px; border-radius: 12px`

**Text style:** `nav` — dmSans 400 · 14px/1

**Observed:** Segments touch without divider lines. The conversion segment uses orange with white type.

**States:** Declared: hover removes text decoration.

### Primary button

**Use:** Compact conversion action on a light background.

**CSS:** `display: inline-flex; align-items: center; height: 42px; padding: 0px 14px; background: #120c08; color: #ffffff; border: 2px solid transparent; border-radius: 12px`

**Text style:** `small` — dmSans 400 · 15px/20px · tracking 0.005em

**Observed:** A small arrow can occupy a separate dark trailing segment. The default on ivory or white is dark; over photography the button is white with brown-black text.

### Photo button

**Use:** Conversion action inside a photographic email form.

**CSS:** `display: flex; align-items: center; height: 42px; padding: 0px 14px; background: #ffffff; color: #120c08; border: 2px solid transparent; border-radius: 12px`

**Text style:** `small` — dmSans 400 · 15px/20px · tracking 0.005em

**Observed:** The opaque button is nested into Email glass; it remains visually distinct from the translucent input.

### Email capsule

**Use:** Single-field low-friction action in the opening and botanical band.

**CSS:** `display: flex; align-items: center; justify-content: space-between; width: 275px; height: 50px; padding: 3px; background: rgba(227,221,207,0.2); border: 1px solid rgba(255,255,255,0.1); border-radius: 16px; backdrop-filter: blur(8px)`

**Text style:** `small` — dmSans 400 · 15px/20px · tracking 0.005em

**Observed:** An unboxed input takes the left space; Photo button occupies the right. In the opening the whole capsule sits at bottom center.

### Question row

**Use:** Objection handling in a narrow centered stack.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 32px; padding: 24px; background: #ffffff; border: 2px solid transparent; border-radius: 16px`

**Text style:** `body` — dmSans 400 · 17px/24px

**Observed:** Closed rows are 84px tall and 540px wide at desktop, touching in one stack. A small downward chevron is aligned right; the answer uses small gray type with 8px top space.

**Transfer:** Use accessible disclosure buttons and let open rows grow naturally.

### Customer story card

**Use:** Personal proof layered over a broad dot-map stage.

**CSS:** `display: flex; gap: 24px; padding: 24px; max-width: 766px; background: #ffffff; border-radius: 16px`

**Text style:** `quote` — abcMarist 350 · 24.9px/1.1 · tracking -0.008em

**Observed:** A tall candid portrait takes about half the card. Quote sits at top right with the name and small monospaced organization tag at the bottom. One card is foregrounded at a time, not three miniature quote tiles.

**Transfer:** Use one substantive outcome quote and a genuine person rather than a decorative avatar.

### Attribution tag

**Use:** Organization annotation paired with a customer name.

**CSS:** `padding: 4px 6px; background: #f9f8f5; color: #666666; border-radius: 4px; white-space: nowrap`

**Text style:** `attribution` — dmMono 400 · 10px/1.54 · tracking -0.01em

**Observed:** A tiny cream rectangle anchors the lower edge of the customer story card.

### Footer text link

**Use:** Compact grouped secondary destinations.

**CSS:** `color: #120c08; text-decoration-line: underline; text-decoration-color: transparent; text-underline-offset: 2px`

**Text style:** `small` — dmSans 400 · 15px/20px · tracking 0.005em

**Observed:** Links sit below gray group labels, in sparse columns, with 7px between row boxes.

**States:** Declared: hover reveals inherited underline color.

### Recruiting row

**Only for:** recruiting lists

**Use:** Full-row job destination over a landscape photograph.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 32px; height: 66px; padding: 24px; background: #ffffff; border: 2px solid transparent; border-radius: 12px`

**Text style:** `body` — dmSans 400 · 17px/24px

**Observed:** A 538px-wide centered stack carries role names left and an ivory 18px-radius mono action inset right. Rows touch, making a scalloped white column against the flowers.

**States:** Declared: hover background #f9f8f5; focus-visible border 2px solid #42b5dc; active background #120c08 and text #ffffff.

**Transfer:** Use for actual vacancies or an equivalent scoped opportunity list, not as the default feature-card style.

## Imagery and graphics

### Human close-up film

**Use:** Full-viewport opening background.

**Observed:** A person's face fills the right side and extends beyond the frame; the left is softly defocused teal and warm gray. Natural skin detail and subdued exposure make centered white text readable. The photograph occupies the entire first screen behind small navigation and actions.

**Transfer:** Film or photograph a real user concentrating in their own environment. Minimum version: one high-resolution candid still, cover-fitted with soft negative space and gentle darkening rather than an illustrated substitute.

### Sunlit botanical band

**Use:** Emotional release and conversion near the close; landscape variation for recruiting.

**Observed:** Yellow and orange poppies, green stems and pale-blue sky are viewed through blurred foreground flowers. Color is rich but filtered by soft daylight and fine grain. The conversion band is 1376px wide within 32px gutters, with 64px corners; white serif copy and a small form float centrally. Recruiting uses a wider field and more open sky.

**Transfer:** Use a real sunlit landscape or macro plant photograph that evokes breathing room, with shallow focus and space for white copy. Keep this natural photographic counterpoint on a new page even when the product has no visual interface.

### Painterly product stage

**Use:** Focused demonstration beside a small explanatory text block.

**Observed:** A large rounded panel contains vertical and slightly slanted streaks of muted yellow, pale blue, violet and green with grain. A small cream work-status panel sits centrally; thin offset layers peek below the main panel. Text stays outside, small and left aligned.

**Transfer:** Show a single understandable task on this atmospheric backing instead of a whole dashboard. Minimum version: one static task card over a streaked texture.

**Build:** In an SVG roughly 800px by 500px, layer broad irregular vertical paths in muted botanical yellow, blue-violet and sage using low-opacity fills; blur the color bands by 20px, overlay fine feTurbulence grain at low opacity, and clip the result to a 64px rounded rectangle. Add two narrower rounded backing shapes offset downward by about 8px each. Keep the work card sharp above the texture; exact color stops are not essential.

### Floating outcome collage

**Use:** Central outcome claim surrounded by fragments of real life and product work.

**Observed:** Small rounded photos of flowers, a person walking and hands at a keyboard occupy the edges; cream task cards overlap some images. A large serif percentage sits above a two-line outcome in the clear center. Elements vary in scale rather than following a tile grid.

**Transfer:** Combine three real-world details with two or three simplified task fragments related to the new product. Preserve the open central reading area; use a verified outcome or a qualitative statement.

**Build:** Position image rectangles in an asymmetric perimeter around a centered heading block. Use 16px photo corners, cream task fragments layered partially across photos, no connector lines and no shadows. Keep peripheral groups separated by broad ivory gaps; the central numeral can use the display recipe.

### Dot-field proof map

**Use:** Broad social-proof stage behind customer stories.

**Observed:** A pale dotted geographic silhouette about 1008px wide is punctuated by irregular clusters of dark circular marks of varied sizes. No geographic labels or legend compete with the centered headline or foreground portrait card.

**Transfer:** Use a relevant geographic silhouette only when there is genuine geographic proof; otherwise use a domain-relevant dotted silhouette with truthful cluster annotations. Keep the dots restrained and the human story in front.

**Build:** Clip an SVG hexagonal or staggered circle grid to a silhouette. Render background circles in brown-black at about 5% opacity on ivory, then place selected opaque brown-black circles at grid points with varied radii. Match the airy point field; do not turn it into a glowing network.

### Feature task illustrations

**Use:** Three-column explanation of the product workflow.

**Observed:** Square warm-cream backings hold small crisp white interface fragments with ample empty space. Modest green status accents belong to the depicted product, not the marketing canvas. Captions and gray explanations sit beneath, outside the square.

**Transfer:** Create simplified, readable task artifacts rather than exhaustive app screens. Keep all three panels consistent in backing, scale and whitespace.

### Monumental closing identity

**Use:** Final visual signature beneath the footer.

**Observed:** A white serif identity fills 96% of the viewport width over Closing sky gradient. The visible lettering box is about 1382px by 382px at desktop; the foreground footer overlaps the upper part of this separate backdrop.

**Transfer:** Fit the new product's own name or a short identity word to the same near-full-width stage. Live serif lettering is an acceptable alternative to custom vector artwork.

**Build:** Create an SVG with white serif text fitted to its viewBox width, or use live text sized to fill a 96%-wide wrapper. Anchor it 10px above the bottom of a 900px pale gradient stage behind Closing white shell. Reveal approximately 418px of the stage after the foreground footer.

### Orbiting workplace gallery

**Only for:** company and mission pages

**Use:** Trust statement surrounded by documentary details.

**Observed:** Small rounded candid photos of people, objects, notes and workplace interiors gather around a central serif statement and small identity symbol. Photographs overlap in loose pairs and leave the central words unobstructed.

**Transfer:** Use actual people and meaningful workspace details in a loose perimeter, not a symmetrical employee headshot grid.

### Icons

**Observed:** Small functional marks are restrained: a 20px white outline status symbol uses 1.3px strokes; action arrows are 20px, while the question control appears as a tiny dark chevron inside a larger hit area. Identity marks are solid organic silhouettes, not line icons.

**Transfer:** Choose simple monochrome utility marks and keep them subordinate to labels; use the new identity's own symbol for repeated brand punctuation.

## Section recipes

How recurring sections are built.

### First screen: Human film opening

**Observed:** A 900px-tall full-bleed image or video is the back layer, gently subdued for white type. Floating navigation sits at the top, with the conversion utility cluster separated to the right. The centered headline occupies about 528px of width and two tightly led lines; the first line is roman, the second italic. A 40px gap leads to a 17px support line and a small live-work status beneath it. Email capsule is bottom-centered 16px above the screen edge. The first 900px shows the full human image, complete headline, support, status and email action; the ivory product introduction begins below this screen.

**Transfer:** Use a close-up of a person benefiting from the new product, or a high-quality candid still if film is unavailable. Write a short human identity statement followed by a contrasting italic release from drudgery. Company and mission pages instead open with editorial-display in black on ivory, centered in the full-height screen with a short editorial-body afterthought.

**Avoid:** Do not replace the image with a split-column SaaS hero, a large app window, a colored badge stack or a huge central button.

**Text style:** `display` — abcMarist 350 · 86.5px/0.95 · tracking -0.02em

### Editorial proposition and demonstration

**Observed:** A centered heading on ivory introduces the product; below it, a broad Painterly product stage holds a focused work fragment, with small quote-sized headline and small gray support positioned beside the stage.

**Transfer:** Explain one task at a time. Keep the visual larger than its caption and allow substantial space around it.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Outcome in an orbit

**Observed:** Floating outcome collage surrounds a centered serif statement; a prominent numeral can sit above the outcome sentence. The center remains free of photographic overlaps.

**Transfer:** Use one consequential result or behavioral change, supported by peripheral real-world details rather than a row of numbered cards.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Geographic and personal proof

**Observed:** Centered serif trust statement above Dot-field proof map. A Customer story card overlays the map with portrait left and quote right; a compact dark story action with thumbnail sits below.

**Transfer:** Join broad proof with one identifiable human story. Adapt the silhouette to the audience rather than assuming a particular country.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Workflow triptych

**Observed:** A centered heading precedes a feature-grid of three square Feature task illustrations with 24px gaps and 32px side gutters. Each has a feature-title and a gray body explanation beneath. The section uses 200px top and 96px bottom padding.

**Transfer:** Use three comparable stages or capabilities, giving each a concrete verb and one explanatory sentence.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Narrow questions

**Observed:** A standalone faq-heading sits over a 540px centered column of Question rows. The overall band has 160px top and bottom padding and no ornamental frame.

**Transfer:** Address adoption, compatibility, effort, cost and trust in direct reader language.

**Text style:** `faq-heading` — abcMarist 350 · 58.3px/1 · tracking -0.01em

### Botanical invitation

**Observed:** Sunlit botanical band fills the wide-stage with white centered heading, identity symbol above and Email capsule below. The surrounding canvas fades from ivory toward white.

**Transfer:** Close the emotional argument with a short metaphor of relief and one compact action rather than repeating a feature list.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Layered closing identity

**Observed:** Closing white shell is about 517px tall, with 80px top padding, 32px side padding and 24px bottom padding. At left is a two-line heading with italic second line and Primary button; right holds three Footer text link groups and small identity/copyright details lower down. Beneath its 64px lower corners the Monumental closing identity is revealed.

**Transfer:** Preserve both the useful compact footer and the overscale identity artwork; fit a new proposition and name to the same hierarchy.

**Text style:** `heading` — abcMarist 350 · 58.3px/1.05 · tracking -0.01em

### Mission and opportunities

**Only for:** company and recruiting pages

**Observed:** Centered serif editorial passages lead into an Orbiting workplace gallery. Later, a field photograph inside a 64px rounded wide panel backs a white heading and narrow stack of Recruiting rows. Institutional proof follows as names and simple monochrome marks on ivory fading to white.

**Transfer:** Use for an organization's beliefs and real opportunities, then substantiate with relevant institutional support; retain the shared layered closing identity.

**Text style:** `editorial-body` — abcMarist 350 · 33.3px/1.1

## Page flow

**Storyline:** Human promise → focused work demonstration → outcome proof → human trust → practical explanation → reassurance → emotional invitation → useful footer and monumental identity.

### Marketing landing page that humanizes a complex automated service

1. **Promise** — Full-screen human film, paired roman/italic headline and low-friction email action.
2. **Product demonstration** — Short editorial proposition followed by atmospheric task stages.
3. **Quantified proof** — Centered outcome surrounded by workplace photos and work fragments.
4. **Social proof** — Dotted reach visualization and foregrounded customer stories.
5. **Capability explanation** — Three square task illustrations with verb-led captions.
6. **Objection handling** — Narrow question stack.
7. **Closing call** — Warm botanical image with compact email form.
8. **Identity and navigation** — White rounded footer followed by enormous white lettering over pale sky.

**Transfer:** Use the human-to-practical-to-human arc flexibly; the signature devices can move to fit the product's story without preserving this section count.

### Company narrative and recruiting page

1. **Mission** — Full-height ivory opening with centered black serif statement and short afterthought.
2. **Belief** — Centered serif prose in a narrow column.
3. **Social proof** — Documentary workplace details orbit a central trust statement.
4. **Invitation** — Mission language transitions to a landscape-backed opportunity list.
5. **Institutional proof** — Simple supporter names and monochrome marks in a broad row.
6. **Identity and navigation** — Shared white footer and pale-gradient monumental wordmark.

**Transfer:** Use the text-led opening and documentary details for an organization story; reserve the landscape list for genuine opportunities.

## Writing

Warm, direct and grounded in real work. The confidence comes from naming what gets handled and how life improves, not from sounding futuristic.

**Do not copy:** Do not reuse Lassie's name, flower mark, proprietary artwork, customer identities, testimonials, investor associations, performance figures or industry-specific claims. All new claims and quotes must belong to the new product and be supportable. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you; describe the product by name as the actor that handles work. Use we for organizational beliefs.
- **Rhythm:** Short complete headlines, often paired across two lines; one-sentence support copy and concrete verb-led captions. Longer mission copy remains conversational, with occasional underlined emphasis rather than hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the human role, then contrast it with the burden it should not become. | Two short sentences, about 7 words total. | “You’re a doctor. Not a machine.” |
| Support | A direct invitation to delegate a specific category of work. | About 6 words. | “Let [Brand] do your admin” |
| Feature caption | Active verb plus concrete work object. | 2–4 words. | “Enrolls electronic payments”<br>“Posts payments” |
| Feature explanation | Explain the operation, then connect it to relief for the reader. | One sentence, about 15–23 words. | “Sets up and manages enrollments automatically, so you never have to deal with physical paper again.” |
| Closing invitation | Everyday sensory metaphor for a better working life. | About 10 words. | “A breath of fresh air for your office” |
| Primary action | Plain verb phrase with little commitment anxiety. | 1–2 words. | “Get started”<br>“Demo” |
| Question | Ask the practical objection exactly as a prospective user would. | 5–9 words. | “Do I need to change my existing systems?” |

**Words and phrasing to use:** handles; automatically; your team; busywork; more time; works; helps; get started

**Avoid:** revolutionary platform; supercharge; 10x everything; agentic paradigm; unprecedented; disrupt

**Rules:**

- Pair emotional relief with an explicit task; neither metaphor nor automation jargon should carry the whole argument.
- Prefer everyday verbs over feature-category nouns.
- Keep claims in large serif type short enough to understand without a paragraph.
- Answer objections directly, including what the reader still needs to do.

## Do's and Don'ts

### Do

- Use the 86.5px roman/italic headline pair for the photographic opening.
- Keep the page reading ground ivory and content cards white with no shadows.
- Use 32px desktop gutters around broad media and 24px feature-grid gaps.
- Keep navigation compact at 40px tall and conversion buttons at 42px.
- Maintain 24px inner padding on quote and question cards.
- Make the 540px question column visibly narrower than the surrounding stages.
- Carry a real-life photographic detail into proof sections, not just the opening.
- Finish with the 64px lower-corner white shell and near-full-width white identity artwork.

### Don't

- Do not replace the literary serif with a bold geometric headline font.
- Do not turn the orange navigation accent into a full-page orange brand field.
- Do not apply pill radii to the 12px rounded-rectangle action buttons.
- Do not add default drop shadows to white cards; their separation is tonal.
- Do not expand the floating navigation into an opaque full-width toolbar.
- Do not color large claims with green status accents borrowed from interface illustrations.
- Do not make customer stories into a dense grid of tiny avatars and centered sans-serif quotes.
- Do not put the footer links directly over the cyan wordmark stage; keep them in the white foreground shell.

## Motion and responsive

### Motion

**Observed:**

- Navigation background transitions are declared at 0.3s cubic-bezier(0, 0, .2, 1).
- Conversion button color transitions are declared at .15s cubic-bezier(.4, 0, .2, 1); footer underline color uses the same duration and curve.
- Email capsule min-width transitions are declared at 0.3s cubic-bezier(0, 0, .2, 1).
- The visual sequence includes fixed navigation, scroll-staged proof scenes, changing work-status text and an identity backdrop revealed below the foreground footer.

**Transfer:**

- Preserve the distinction between a stable reading center and changing peripheral proof imagery.
- For a static implementation, retain the complete composed proof scenes and layered footer reveal rather than inserting empty scroll distance.

**Unknown:**

- Exact scroll choreography, video playback timing and interpolation of canvas artwork are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 394px, 640px, 768px, 1024px, 1280px, 1440px and 1536px.
- The serif scale uses viewport-relative clamp formulas.
- Story-card classes switch from stacked content to side-by-side portrait and text; page gutters and large media corner sizes vary across breakpoints.

**Transfer:**

- On narrow screens, preserve the human full-height opening and compact form, but reframe the subject so both text lines remain readable.
- Stack story portrait above quote, keep the tiny attribution subordinate, and move orbiting peripheral images away from text.
- Reduce wide media gutters and allow workflow panels to stack or scroll horizontally instead of shrinking their task fragments to illegibility.

**Unknown:**

- Actual mobile compositions, navigation collapse behavior and exact small-screen sizes were not visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
