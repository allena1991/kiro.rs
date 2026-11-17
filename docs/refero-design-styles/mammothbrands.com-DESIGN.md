# Mammoth Brands — monumental humanism

## Overview

A monumentally scaled identity sits beside a warm editorial voice. White transitional serif headlines and close-set grotesk paragraphs float on a medium-gray canvas, punctuated by saturated rectangular showcases. Natural portraits and workplace photography make the spare, unusually text-forward composition feel human rather than technical. It suits ambitious consumer products, portfolios and mission-led organizations, with a charcoal variant for people-focused storytelling.

### Essentials

- Identity becomes architecture: a two-line white word sculpture spans nearly the entire 1440px viewport with 10px side clearance, followed by an oversized abstract initial that continues below the first screen. Recreate this device with the new identity, even without product photography.
- Editorial grandeur meets conversational density: main serif headings use 115.2px/1.05, weight 600 and -0.02em tracking; substantive centered sans paragraphs use 36px/1, weight 400 and -0.02em tracking.
- Gray is the field, not a disabled state: #818181 carries most of the default page with white text; saturated blue, purple and orange stay concentrated in a showcase occupying roughly one eighth of the long page rather than washing every section.
- Controls resemble small tabs, not oversized conversion pills: white navigation has 6px corners, 3px inset padding and 32px-high links; the active inset has 4px corners. The scoped recruitment action is a 38px-high rust rectangle.
- Images are direct and undramatized: white-backed portraits nearly fill compact 337px-wide cards, while flat-color showcase panels are 686px by 432px with centered marks and 8px corners. Use a typographic product emblem when no suitable media exists.
- Proof and closure retain the editorial scale: unboxed 100.8px serif numbers have smaller 72px suffixes, and the final inset 8px-corner panel pairs a substantial white line-art emblem with 30px serif navigation. Preserve both devices with relevant proof and a new emblem.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5100` | `--color-orange` | surface | Bright isolated showcase panel, not the main page field. |
| Electric blue | `#0000c0` | `--color-electric-blue` | surface | Distinct concluding showcase tile. |
| Royal blue | `#1f35a9` | `--color-blue` | surface, accent, border | Showcase panels, selected text background and dashed keyboard focus. |
| Deep purple | `#280d66` | `--color-purple` | surface | Companion flat showcase panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mammoth gray | `#818181` | `--color-canvas` | background, text, surface | Default full-page field, navigation inactive text and selected tab inset. |
| Showcase black | `#000000` | `--color-black` | surface | One of the flat showcase panel colors, kept distinct from charcoal. |
| Charcoal | `#151517` | `--color-charcoal` | background, surface | Default closing panel; full-page field only for people-focused storytelling. |
| Portrait gray | `#949494` | `--color-card-gray` | surface, text | Portrait card frames and small portrait controls; inverse footer panel on people-focused pages. |
| Soft white | `#f7f7f7` | `--color-soft-white` | text | Card captions and footer links. |
| White | `#ffffff` | `--color-white` | text, surface, accent | Primary editorial text, oversized identity artwork and navigation backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| benefits pages | Violet | `#7d00ff` | `--color-violet` | surface | Additional benefit category panel. |
| recruitment and benefits pages | Rust | `#c84d25` | `--color-rust` | surface, action | Recruitment action and benefits tile. |
| benefits pages | Forest | `#1a4120` | `--color-forest` | surface | Additional benefit category panel. |

## Typography

- **fontSanomat** — Editorial headings, large proof numbers and footer navigation. Sturdy transitional serif with pronounced bracketed serifs, broad capitals and an approachable editorial presence. If unavailable, use **Libre Caslon Text**. Use 600 for major headings and 500 for smaller titles; preserve the broad setting and close display tracking. Font stack: "fontSanomat", "Libre Caslon Text", Georgia, serif.
- **fontNeueMontreal** — Narrative paragraphs, navigation, captions and controls. Matter-of-fact neo-grotesk with compact spacing and a high, open lowercase. If unavailable, use **Inter**. Use 400 for oversized prose and 500 for small information; retain tight prose tracking. Font stack: "fontNeueMontreal", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | fontSanomat | 600 | 115.2px | 1.05 | -0.02em | size clamp(70px, 8vw, 150px) | Main promise, major chapter titles and people-page opening. |
| stat-number | fontSanomat | 600 | 100.8px | 1.05 | -0.02em | size clamp(80px, 7vw, 140px) | Unboxed numerical proof. |
| heading-medium | fontSanomat | 600 | 72px | 1.05 | -0.02em | size clamp(60px, 5vw, 140px) | Suffixes next to proof numbers; section headings in the people-focused variant. |
| statement | fontSanomat | 500 | 50px | 1 | 0.01em | size clamp(30px, 8vw, 50px) | Multi-line editorial standfirst and large tile headings. |
| narrative | fontNeueMontreal | 400 | 36px | 1 | -0.02em | fixed | Main prose, support paragraphs and narrative lists. |
| small-title | fontSanomat | 500 | 30px | 1.05 | 0.01em | fixed | Footer destination links and compact editorial row titles. |
| caption | fontNeueMontreal | 500 | 18px | 1.15 | 0.01em | fixed | Stat explanations, person names and contact links; underline actual contact links only. |
| utility | fontNeueMontreal | 500 | 15.8px | 1.4 | 0.02em | fixed | Navigation, role captions, compact explanatory text and footer group labels. |
| micro-action | fontNeueMontreal | 500 | 12px | 1.2 | 0.02em | fixed | Portrait reveal controls and small footer utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| benefits pages | narrative-aside | fontNeueMontreal | 400 italic | 36px | 1 | -0.02em | fixed | Inline explanatory qualification within a benefits introduction. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- White serif titles are title case rather than all-capital labels. The opening identity is custom block lettering, not the serif display face.
- Large headings and oversized sans prose share -0.02em tracking; small titles loosen to 0.01em and small utility text to 0.02em.
- The main reading experience is 36px prose at a tight 1 line height, not conventional 16px body copy. Keep smaller utility text subordinate.
- The 72px serif recipe is a proof suffix by default; on people-focused pages it becomes the chapter heading while the opening remains 115.2px.

## Layout

**Density:** Airy between chapters but dense within prose: 200px major separations contrast with 36px tightly stacked narrative lines.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Small caption stacks and vertical section-navigation gaps. |
| 10px | Showcase and benefits grid gutters; compact control padding. |
| 16px | Fixed header inset and closing panel outer margin. |
| 20px | Benefits tile padding and footer label-to-link spacing. |
| 24px | Heading/support pairing, proof column gutters and footer link stacks. |
| 40px | Closing panel padding and editorial row separation. |
| 50px | Declared block spacing token and separation between narrative paragraphs. |
| 100px | Main title-to-content spacing and spacing between large chapter elements. |
| 200px | Top and bottom margins of major editorial chapters. |

### Containers and grids

- **Showcase container**: max width 1400px · side padding 29px. Nearly full-width content at desktop; the visible span is 1382px within the 1440px window.
- **Narrative column**: max width 940px. Centered prose column, rendered about 922px wide at desktop.
- **Editorial title container**: max width 1400px. Centered major titles occupy about four fifths of the main container, approximately 1106px.
- **Portfolio grid**: 2 columns · gap 10px. Two equal wide panels; an odd last panel is centered at roughly half row width.
- **Proof row**: 4 columns · gap 24px. Four centered unboxed metrics with narrow explanatory captions.
- **Portrait grid** (only for team and leadership sections): 4 columns · gap 12px. 337px-wide portrait cards, with 8px row gaps.
- **Benefits grid** (only for benefits pages): 3 columns · gap 10px. 454px by 318px category cards, two rows in the full version.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary panels and media | 8px |
|  | Navigation shell and recruitment button | 6px |
|  | Active tab and micro-control | 4px |
| team and leadership sections | Portrait frame | 12px |

## Surfaces and depth

### Surfaces

#### Gray canvas · level 0

**Use:** Default marketing page field.

**CSS:** `background: #818181; color: #ffffff`

**Observed:** Continuous flat neutral field across long editorial passages; no texture or tonal gradient.

**Transfer:** Let typography and isolated showcase colors carry hierarchy.

#### Flat showcase · level 1

**Use:** Product or brand identity panels.

**CSS:** `background: #1f35a9; border-radius: 8px; box-shadow: none`

**Observed:** Deep purple, signal orange, black and electric blue are sibling fills; there are no decorative edge lines.

**Transfer:** Use one flat color per distinct identity or capability, with centered white marks.

#### Inset closing panel · level 1

**Use:** Final navigation and contact destination.

**CSS:** `background: #151517; color: #f7f7f7; border-radius: 8px; padding: 40px; margin: 16px`

**Observed:** The people-focused variant swaps the fill to portrait gray against its charcoal canvas.

**Transfer:** End with a contrasting panel rather than another display-sized sales pitch.

#### Charcoal canvas · level 0

**Only for:** people-focused pages

**Use:** Dark editorial variant.

**CSS:** `background: #151517; color: #ffffff`

**Observed:** The whole story uses charcoal, with a contrasting gray closing panel.

**Transfer:** Keep the same typography and spacing rather than redesigning the page as a different brand.

#### Portrait frame · level 1

**Only for:** team and leadership sections

**Use:** White-backed photography with caption backing.

**CSS:** `background: #949494; border-radius: 12px; padding: 5px; box-shadow: none`

**Observed:** The inset photograph has 8px corners; the gray caption area is an integrated part of the frame.

**Transfer:** Keep portrait lighting consistent and let the backing separate images from the page.

## Components

### Segmented navigation

**Use:** Compact global page selection at the upper right.

**CSS:** `background: #ffffff; border-radius: 6px; padding: 3px; display: flex; gap: 4px`

**Text style:** `utility` — fontNeueMontreal 500 · 15.8px/1.4 · tracking 0.02em

**Observed:** Fixed header places a small white wordmark at the opposite corner. Three text tabs sit over a moving gray inset with 4px corners; each tab has 5px by 16px padding and is 32px high.

**Transfer:** Use a few short destination names, with page-level selection distinct from chapter navigation.

### Chapter link

**Use:** Right-aligned in-page navigation below the segmented navigation.

**CSS:** `display: flex; align-items: center; justify-content: flex-end; gap: 5px; color: #ffffff`

**Text style:** `utility` — fontNeueMontreal 500 · 15.8px/1.4 · tracking 0.02em

**Observed:** Links form a vertical list with 5px gaps and a small white dot marking the current section. The header remains unobtrusive and does not occupy a solid full-width bar.

**States:** Declared: hover unspecified; focus-visible 2px dashed #1f35a9 outline with 3px offset.

### Portfolio panel

**Use:** Large interactive identity showcase.

**CSS:** `background: #1f35a9; border-radius: 8px; height: 432px; display: flex; align-items: center; justify-content: center`

**Observed:** A centered white identity sits inside a generous central zone about three fifths of panel width and one half its height. A full-panel button overlays the presentation; desktop panels are 686px wide, with a centered narrower odd final panel.

**Transfer:** Replace the mark with a product name or concise typographic emblem, not a paragraph of features.

### Metric

**Use:** Quantified proof without enclosing cards.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 24px; max-width: 400px; color: #ffffff; text-align: center`

**Text style:** `stat-number` — fontSanomat 600 · 100.8px/1.05 · tracking -0.02em

**Observed:** The numeric value and smaller serif unit share one line; an 18px explanatory caption follows. Four metrics share one row, with no rules or colored statistic badges.

**Transfer:** Use meaningful verified quantities and retain the deliberately unequal number/suffix sizes.

### Footer destination

**Use:** High-importance links within the closing panel.

**CSS:** `color: #f7f7f7; display: flex; align-items: center; justify-content: space-between`

**Text style:** `small-title` — fontSanomat 500 · 30px/1.05 · tracking 0.01em

**Observed:** Small sans group labels precede serif destination links by 20px. Links in a column are separated by 24px; contact information uses smaller underlined sans text.

**States:** Declared: hover unspecified; focus-visible 2px dashed #1f35a9 outline with 3px offset.

### Portrait reveal card

**Only for:** team and leadership sections

**Use:** A person introduction with a compact biography reveal.

**CSS:** `background: #949494; border-radius: 12px; padding: 5px; display: flex; flex-direction: column; text-align: center`

**Text style:** `utility` — fontNeueMontreal 500 · 15.8px/1.4 · tracking 0.02em

**Observed:** A 327px by 408px portrait nearly fills the front. Role appears above name underneath; View Bio sits over the top-right image corner in 12px text beside the tiny loop-arrow. A reverse face holds the biography and Close control.

**Transfer:** Use only when people are relevant proof, keeping the caption order and minimal image overlay.

### Recruitment action

**Only for:** recruitment pages

**Use:** Compact fixed-header conversion action.

**CSS:** `background: #c84d25; color: #ffffff; border-radius: 6px; padding: 8px 12px; display: flex; align-items: center`

**Text style:** `utility` — fontNeueMontreal 500 · 15.8px/1.4 · tracking 0.02em

**Observed:** The 38px-high action sits to the left of the global navigation and ends in a fine up-right arrow; it is not a hero-sized button.

**States:** Declared: hover unspecified; focus-visible 2px dashed #1f35a9 outline with 3px offset.

### Benefit flip tile

**Only for:** benefits pages

**Use:** An explorable category with detail on a reverse face.

**CSS:** `background: #1f35a9; border-radius: 8px; padding: 20px; height: 318px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `statement` — fontSanomat 500 · 50px/1 · tracking 0.01em

**Observed:** Large white serif title anchors the upper left; a small Learn more label and loop-arrow anchor the lower left. The reverse uses a white backing. Companion fronts use deep purple, rust, gray, violet and forest.

**Transfer:** Use for a small set of categories requiring explanation, keeping the front face mostly empty.

## Imagery and graphics

### Monumental identity sculpture

**Use:** Signature opening and identity punctuation.

**Observed:** Heavy white block lettering is stacked in two tightly fitted rows, almost edge to edge on gray. The lettering occupies about the upper 390px of the first screen; an enormous angular initial begins around the lower third and extends beyond the viewport.

**Transfer:** Every new marketing page needs a word sculpture and enlarged emblem treatment. If no custom mark exists, tightly fit a new name in an extra-bold grotesk and use its initial as the abstract lower form.

**Build:** Create an SVG with two centered rows of outlined extra-bold lettering, white fill, compressed interline space and a 1420px-wide desktop viewBox. Under it, create an independent oversized white initial using a polygon or outlined glyph; clip its lower portion at the viewport and scale it across a two-screen scene. Use sharp triangular notches and broad solid masses only when appropriate to the new initial; no shadows or gradients.

### Centered identity on color

**Use:** Saturated showcase panels.

**Observed:** White marks are modest in size relative to the field; panels carry blue, purple, orange or black with no photographic collage or texture. Color appears in large discrete blocks surrounded by gray.

**Transfer:** Use a new typographic mark, concise product label or simple white symbol centered in the same generous field.

**Build:** Place a white SVG or text emblem in a flex-centered 8px-corner rectangle. Give the emblem a maximum zone of 60% panel width and 50% panel height; retain substantial clear space.

### Closing line-art emblem

**Use:** Signature closing-panel anchor.

**Observed:** A white engraved-style animal illustration occupies roughly 266px by 204px on the left, balancing three text groups across the remaining panel. Fine dark incisions articulate the solid silhouette.

**Transfer:** Include an original illustrated emblem appropriate to the new identity. The minimum version is a substantial white silhouette with several dark contour incisions, not a tiny stock icon.

**Build:** Draw a white SVG silhouette within a roughly 4:3 viewBox. Add a restrained set of curved strokes in the panel's background color to describe internal texture and anatomy or construction. Size near 266px by 204px on desktop and align its top with the footer labels.

### Natural portrait wall

**Only for:** team and leadership sections

**Use:** Human credibility near the end of an organization story.

**Observed:** Friendly waist-up and chest-up portraits on white to pale-gray backgrounds. Subjects face the lens in normal clothing; color stays natural, with soft even studio lighting. Images dominate the card, with a narrow gray caption strip below.

**Transfer:** Use consistently lit new portraits with similar head scale and lightly varied poses rather than dramatic monochrome executive headshots.

### Workplace documentary

**Only for:** people-focused pages

**Use:** Large opening photograph and smaller interlude.

**Observed:** Warm wood, polished concrete, glass walls and people in everyday office conversation. The opening photograph is broad, 1244px by 939px, with 8px corners; a later 691px by 461px photograph is centered with generous charcoal around it.

**Transfer:** Photograph real use or collaboration in a warm, credible environment. Preserve natural light and contextual room detail rather than isolating people as cutouts.

### Community identity rail

**Only for:** culture and community pages

**Use:** A horizontal strip of community marks.

**Observed:** Five landscape 432px by 243px graphics sit in a single rail with 10px gaps and 6px corners; cards extend off both viewport edges. Color belongs to the marks on pale backing; a compact caption appears beneath the featured item.

**Transfer:** Use actual community or program identities, maintaining the cropped-at-edges rail rather than turning the artwork into decorative stickers.

### Icons

**Observed:** Tiny horizontal loop-arrows are 20px by 9px, drawn with 1px strokes and butt caps in white, soft white or gray. The recruitment action uses a 13px up-right corner arrow with 1.5px lines; the active chapter indicator is a 6px circle.

**Transfer:** Keep interaction icons fine and secondary to words. Use loop-arrows for reveals and the up-right arrow only for outbound conversion actions.

## Section recipes

How recurring sections are built.

### First screen: Identity sculpture opening

**Observed:** The gray canvas supports a huge two-row white block wordmark, spanning virtually the whole width with 10px side clearance and filling about 390px of height. A wide interval of gray separates it from an enlarged white angular initial entering around 640px down the first 900px screen. The initial continues below the fold through an 1800px opening scene. Layers are flat gray, white word sculpture, then the independently enlarged initial; there is no photograph, supporting paragraph or central conversion button in this first screen. Compact global navigation becomes visible as the editorial chapters begin. The first prose headline that follows is the centered serif display recipe, not a continuation of the block logo.

**Transfer:** Use the new name as a similarly weighty outlined word sculpture and enlarge one of its distinctive letters below it; product imagery is not needed. People-focused pages instead open on charcoal with a centered two-line serif display heading starting after 200px of top space, then a broad photograph after a 100px gap; only the upper portion of that photograph is visible within the first 900px.

**Avoid:** Do not replace the identity scene with a conventional left-copy/right-product hero, or crowd it with eyebrow text, badges and paired sales buttons.

**Text style:** `display` — fontSanomat 600 · 115.2px/1.05 · tracking -0.02em

### Centered editorial promise

**Observed:** A display headline spans a broad centered title container. After 100px, 36px narrative text sits in the Narrative column, with 50px between substantive paragraphs. The promise can break into three emphatic lines.

**Transfer:** Write one plain-language promise, then explain the operating principle behind it; keep the prose visually as important as a normal section heading.

**Text style:** `display` — fontSanomat 600 · 115.2px/1.05 · tracking -0.02em

### Heading and colorful showcase

**Observed:** A centered display title and 36px support line are separated by 24px. After 100px comes the Portfolio grid of Flat showcase surfaces, with a centered odd final panel.

**Transfer:** Use the panel system to make the product range or principal offerings tangible; adapt the number of panels to the actual content.

### Editorial history

**Observed:** A major display title leads to a 50px serif standfirst after 100px; the long explanation switches to the Narrative column and 36px sans. Paragraphs are spaced by 50px, with 200px around the whole chapter.

**Transfer:** Use this for a founding problem, technical breakthrough or product philosophy, separating the big framing assertion from its more conversational explanation.

### Unboxed impact proof

**Observed:** A wide typographic program mark introduces centered narrative text, followed after 100px by the Proof row of Metric components. Values use the stat-number recipe with heading-medium suffixes, then caption text. A further narrative line follows after about 100px.

**Transfer:** Make the proof chapter a measured pause in the story; preserve the unboxed oversized serif data treatment even if there are fewer relevant metrics.

### Illustrated closing directory

**Observed:** Inset closing panel pairs Closing line-art emblem on the left with three destination groups: two serif links, one social destination and an underlined contact address. Utility labels sit above links; tiny legal links align at the bottom right. Default panel height is 339px with 40px padding and 16px outer margin. People-focused pages use gray instead of charcoal.

**Transfer:** Close with useful next destinations and a confident emblem. Preserve the illustrated ending rather than adding a generic newsletter block or a second oversized hero.

### Portrait credibility wall

**Only for:** team and leadership sections

**Observed:** Centered display chapter title, 100px gap, then the Portrait grid of Portrait reveal cards. The final row leads into a 200px chapter separation before the closing panel.

**Transfer:** Use people only where they establish expertise or trust; do not substitute a generic testimonial grid for this portrait treatment.

### Compact principle rows

**Only for:** people-focused pages

**Observed:** A 72px centered serif heading and centered narrative introduction lead into a 940px-wide list. Each row has a 30px serif title occupying roughly one third of the width, with utility-sized explanatory copy beside it and a 24px gap. Rows have 40px separation; a smaller workplace photograph closes the chapter.

**Transfer:** Use for working principles or editorial distinctions that deserve reading rather than icon cards.

**Text style:** `heading-medium` — fontSanomat 600 · 72px/1.05 · tracking -0.02em

### Benefit exploration

**Only for:** benefits pages

**Observed:** A 72px title precedes centered narrative prose with an italic continuation after 100px. Another 100px gap leads to the Benefits grid of Benefit flip tiles. Compact eligibility information follows below, before a gray closing panel.

**Transfer:** Keep category titles short enough for two or three serif lines and put detailed qualifications on the reverse or beneath the grid.

## Page flow

**Storyline:** identity → promise → tangible range → explanatory story → proof → human credibility → illustrated directory; people-focused stories adapt this into invitation → lived context → principles → practical detail → directory.

### A broad marketing introduction that turns a distinctive identity into a credible operating story

1. **Identity** — A two-screen white word sculpture and enlarged initial on gray.
2. **Promise** — Oversized serif statement with centered sans explanation.
3. **Offering demonstration** — Color-block panels with centered identity marks.
4. **Origin and differentiation** — Serif chapter and standfirst followed by long, closely set sans paragraphs.
5. **Quantified proof** — A program wordmark, contextual prose and four unboxed serif metrics.
6. **Human credibility** — Large portrait wall with biography reveals.
7. **Next destinations** — Contrasting illustrated footer with editorial navigation and contact details.

**Transfer:** Use the visual devices as a narrative vocabulary, not a prescribed count or order; keep only content that proves the new product's promise.

### A people-focused editorial page that explains an environment and gives practical reasons to participate

1. **Invitation** — Two-line serif display on charcoal above a large workplace photograph.
2. **Context** — Centered oversized sans introduction.
3. **Principles** — Compact title-and-description rows ending in documentary photography.
4. **Community proof** — Large prose and a horizontal rail of community identities.
5. **Practical detail** — Colored category flip tiles, qualifications and supporting information.
6. **Next destinations** — Gray illustrated footer inverting the darker page.

**Transfer:** Adapt this variant to recruiting, community or organizational stories; use authentic context imagery and practical detail rather than importing the default identity scene unchanged.

## Writing

Warm, ambitious and plainspoken. The voice explains how people do things differently, balancing big organizational intent with concrete human motivations.

**Do not copy:** Do not reuse the Mammoth Brands name, wordmarks, mammoth artwork, portfolio identities, people, proprietary mission quotation, market-leadership claims, dates, impact figures or benefit promises. Create truthful equivalents for the new organization. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly first-person plural: we and our describe shared work. People and customers are named directly; second-person address is sparse and practical.
- **Rhythm:** Very short title-case chapter headings alternate with substantial conversational paragraphs. Sentences can accumulate examples, then resolve with a short plain assertion; occasional contractions and dashes keep the tone human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | A compact, active, everyday-language ideal rather than a technical feature list. | 4–7 words | “Create Things People Like More” |
| Chapter title | Simple possessive or descriptive noun phrase in title case. | 1–4 words | “Our Brands”<br>“Our Story”<br>“Our Values” |
| Supporting line | State the proposition plainly with we/our, leaving the explanation for the paragraph. | One sentence | “We are a growing portfolio of category leading brands.”<br>“We believe that diverse teams build the best businesses.” |
| Action | Plain destination or invitation, with no inflated urgency. | 2–3 words | “Join Our Team”<br>“Open Roles”<br>“Learn more” |
| Principle | Short imperative, sometimes gently playful, followed by a concrete behavioral explanation. | 2–7 words | “Grow Forth”<br>“Own It”<br>“See the Person. Serve the People” |

**Words and phrasing to use:** people; better; building; community; serve; learning; we believe; simply put

**Avoid:** revolutionary ecosystem; unlock synergies; frictionless disruption; act now; 10x everything

**Rules:**

- Tie an ambitious claim to an actual method or lived example.
- Prefer familiar verbs to technical or corporate abstractions.
- Use contractions in explanatory prose, while keeping navigation succinct.
- Let a short title introduce a longer explanation rather than forcing every passage into a slogan.

## Do's and Don'ts

### Do

- Pair 115.2px serif chapter titles with 36px sans narrative, preserving their shared -0.02em tracking.
- Keep showcase gutters at 10px so the saturated panels read as a deliberate block.
- Leave 200px between major narrative chapters and 100px between their large elements.
- Use the gray field continuously through prose rather than separating every topic into a card.
- Keep footer links editorial at 30px, clearly larger than their 15.8px group labels.
- Render proof as 100.8px values with 72px suffixes and concise 18px captions.
- Give the ending a substantial white illustrated emblem and a contrasting 8px-corner inset panel.
- Keep portraits naturally lit, tightly framed and consistently scaled within their 5px backing.

### Don't

- Do not turn all paragraphs into 16px utility text; the 36px narrative setting is central to the character.
- Do not apply 9999px pill corners to navigation or actions; the control language is 4px to 6px rectangles.
- Do not add glows, gradient fills or drop shadows to flat showcase panels.
- Do not use the full benefits rainbow throughout an ordinary marketing page; violet, forest and rust belong to scoped practical-information sections.
- Do not use uppercase mono eyebrows above every serif heading; the hierarchy is direct title and prose.
- Do not make metric units the same size as the values; the 72px suffix is deliberately subordinate.
- Do not give every navigation item a separate colored button; one compact white segmented shell carries global destinations.
- Do not turn portrait captions into large quote blocks; role then name is the compact front-face hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Declared transforms transition over 0.6s with cubic-bezier(.4,0,.2,1); card structures include two faces with rotate3d about the vertical axis.
- Declared chapter-link color transitions use .3s cubic-bezier(.4,0,.2,1).
- Declared active navigation inset width and left transitions use 0.3s cubic-bezier(.4,0,.2,1) with 0.2s delay.
- Declared root background transition is 0.6s cubic-bezier(.4,0,.2,1); footer background transition is .3s with the same curve.
- The opening has a two-screen scene with fixed-position artwork, and a marquee keyframe is declared.

**Transfer:**

- Keep the word sculpture and enlarged initial as independently layered artwork across the opening scroll.
- Keep reveals tied to the two-face card construction, and retain a clear Close control on detail faces.

**Unknown:**

- Exact scroll interpolation, reveal triggers and marquee speed are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 1080px, 1280px, 1536px, 1600px, 1601px, 1800px and 2400px.
- Display sizes use the clamp formulas listed in typography.
- Benefit grid declarations support one, two and three columns; portrait declarations support two, three, four and five columns.
- Footer declarations support centered stacked groups before changing to left-aligned horizontal groups.

**Transfer:**

- Preserve the dominance of the word sculpture on narrow screens by refitting its two rows rather than shrinking it into a normal logo.
- Allow narrative text and principle rows to stack within the reading column; retain the hierarchy between serif title and sans explanation.
- Reflow category cards and portraits instead of scaling desktop text to illegibility; keep the footer emblem visibly substantial.

**Unknown:**

- Exact rendered narrow-screen font sizes, header arrangement and opening scroll behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
