# Instagram — everyday expression amplified

## Overview

An open, people-first marketing style that pairs enormous regular-weight humanist sans typography with candid social photography and informal video. White dominates, black creates an occasional dramatic pause, and orange-to-pink-to-purple accents give small actions a vivid spark. The feeling is conversational and expressive rather than luxurious or technical, with sparse opening compositions and more informational editorial endings.

### Essentials

- A sentence is the opening object: a left-aligned 100px/1.05 regular headline with -0.035em tracking occupies roughly two thirds of the content width, with a hand-drawn underline beneath its emotional payoff.
- Navigation stays out of the story: a 156px white header puts a 54px menu at the left and a small login action plus a 72px identity mark at the far right; no desktop link rail competes with the headline.
- Conversion is outlined, not filled: the primary action is a 52px-high pill with a 2px yellow–orange–pink gradient rim, white interior and 16px uppercase label.
- Color behaves like expression on a monochrome page: the default canvas and type are white and black, with gradients limited to short inline heading links, button rims and small graphic punctuation; photography carries most of the color.
- Media feels like a friend's post, not a polished billboard: candid portraits and videos sit beside 48px/1.05 headings, using 10px media corners and a mixture of portrait and landscape frames. Include a small expressive annotation near a frame; when no equivalent media exists, show a real person using the new product in an ordinary setting.
- A contrasting typographic pause and a human closing line balance the story: use a full-width black statement band with 100px white type, and a centered two-line 48px closing invitation above the footer. Adapt their placement to the narrative rather than imposing a fixed sequence.
- Editorial labels have a compressed voice: 16px uppercase condensed eyebrows and 20px bold condensed hashtag labels in 8px-radius outlined tags contrast with regular-weight 24px article titles.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Rim yellow | `#ffd500` | `--color-button-yellow` | accent, action | First stop of the primary button rim. |
| Link orange | `#ff7a00` | `--color-orange` | accent, link | First gradient-text stop; also solid picture underbars on resource pages. |
| Rim orange | `#ff7b00` | `--color-button-orange` | accent, action | Middle stop of the primary button rim. |
| Rim pink | `#ff006a` | `--color-button-pink` | accent, action | Final stop of the primary button rim. |
| Link pink | `#ff0169` | `--color-pink` | accent, link | Middle stop of the short inline-link gradient. |
| Link purple | `#d300c5` | `--color-purple` | accent, link | Final stop of the short inline-link gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-black` | text, background, action | Default headline ink, icons and statement bands. |
| Editorial ink | `#1c1e21` | `--color-ink` | text, border | Fine outlines and editorial text; informational-page default text. |
| Muted gray | `#6a717a` | `--color-muted` | text | Default footer secondary links and utility text. |
| White | `#ffffff` | `--color-white` | background, text, surface | Dominant canvas, button interiors and inverse lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| resource directories | Resource magenta | `#ff0069` | `--color-resource-pink` | border | Solid underbar below resource photography. |
| resource directories | Resource yellow | `#ffd600` | `--color-resource-yellow` | border | Alternate resource-picture underbar. |
| resource directories | Resource blush | `#ffabe1` | `--color-resource-blush` | border | Alternate guideline-picture underbar. |
| informational and company article lists | Metadata gray | `#999999` | `--color-metadata` | text | Unboxed article categories. |
| informational and company pages | Light secondary gray | `#a6a6a6` | `--color-secondary-muted` | text | Secondary footer and utility links. |

## Typography

- **Instagram Sans** — Display, headings, paragraphs, links and navigation. Friendly humanist sans with rounded contours, distinctive terminals and a generous x-height; regular weight remains expressive at monumental sizes. If unavailable, use **DM Sans**. Use 400 and 500; preserve the tight display tracking and match line breaks. Font stack: "Instagram Sans", "DM Sans", -apple-system, system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif.
- **Instagram Sans Condensed** — Compressed editorial eyebrows and hashtag categories. Tall, narrow sans; medium eyebrows and punchier bold tag lettering. If unavailable, use **Barlow Condensed**. Use 400, 500 and 700 without widening the letters. Font stack: "Instagram Sans Condensed", "Barlow Condensed", Arial Narrow, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Instagram Sans | 400 | 100px | 1.05 | -0.035em | fixed | Default opening sentence. |
| statement | Instagram Sans | 400 | 100px | 1.2 | normal | fixed | White display copy within the black statement band. |
| heading | Instagram Sans | 400 | 48px | 1.05 | -0.03em | fixed | Feature statements, news heading and centered closing invitation. |
| body | Instagram Sans | 400 | 24px | 1.2 | normal | fixed | Article titles, footer primary links and substantial support paragraphs. |
| tag | Instagram Sans Condensed | 700 | 20px | 1.2 | normal, uppercase | fixed | Outlined hashtag categories below square thumbnails. |
| secondary-link | Instagram Sans | 400 | 18px | 1.4 | normal | fixed | Footer secondary links and language control. |
| eyebrow | Instagram Sans Condensed | 500 | 16px | 1.2 | normal, uppercase | fixed | Compact editorial section labels. |
| button-label | Instagram Sans | 500 | 16px | 1.2 | normal, uppercase | fixed | Primary gradient-rim actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| informational and company page openings | split-display | Instagram Sans | 400 | 104px | 1.05 | -0.035em | size calc(49.9px + 3.7551vw) | Large sentence split between light and photographic halves. |
| informational pages | editorial-display | Instagram Sans | 400 | 61.9px | 1 | -0.03em | size calc(43.1px + 1.30612vw) | Prominent information-band heading and large related-reading introduction. |
| informational and company pages | editorial-heading | Instagram Sans | 400 | 45.9px | 1 | -0.03em | size calc(27.1px + 1.30612vw) | Directory leads, company feature headings and article-list introduction. |
| informational and company pages | list-title | Instagram Sans | 400 | 32px | 1.2 | normal | fixed | Ruled article-row title and resource-panel heading. |
| informational and company pages | editorial-label | Instagram Sans Condensed | 400 | 24px | 1 | normal | fixed | Uppercase section labels and gray hashtag metadata. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large type gains character through scale and tight tracking, not bold weight. Display tracking is -0.035em; section-heading tracking is -0.03em; body and metadata return to normal.
- Keep a feature's final linked noun and arrow at the same size and weight as its heading. A color change, not a separate button, completes the sentence.
- The default opening has no separate explanatory paragraph; the headline carries the promise. Informational layouts use larger support text rather than shrinking paragraphs into UI-sized copy.

## Layout

**Density:** Airy: broad white intervals isolate sentence-and-media chapters, while editorial cards and footer links become deliberately denser.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Base rhythm for heading offsets, section padding and linked lists; not a rule for fluid horizontal geometry.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Eyebrow-to-heading and stacked-link spacing. | fixed |
| 16px | Heading padding and social-icon gaps. | fixed |
| 24px | Image-to-tag-group margin and utility-block separation. | fixed |
| 32px | Default editorial grid gutters and row text insets. | fixed |
| 48px | Button horizontal inset and editorial-list top spacing. | fixed |
| 56px | Default chapter bottom padding and article-row vertical insets. | fixed |
| 72px | Information-panel heading-to-columns gap. | fixed |
| 80px | Directory heading padding and information-chapter breathing room. | fixed |
| 96px | Closing invitation top offset and informational footer separation. | fixed |
| 160px | Company-gallery chapter separation. | fixed |
| 102.8px | Informational outer side inset. | 7.142vw |
| 205.7px | Informational reading-section side inset. | 14.285vw |

### Containers and grids

- **marketing container**: max width 1920px · 12 columns · gap 32px · side padding 92px. Desktop default: 1256px of content at 1440px, with headline spanning about nine grid columns. Side margins expand with the viewport.
- **news grid**: 4 columns · gap 32px. Four 290px square thumbnails above tags, titles and dates.
- **footer grid**: 6 columns · gap 32px. Six evenly sized columns followed by centered utility controls.
- **editorial reading container** (only for informational and company pages): max width 1600px · side padding 205.7px. 1029px desktop reading width for resource panels and ruled article lists.
- **resource grid** (only for resource directories): 3 columns · gap 51.4px. Three 309px-wide picture-led resource columns.
- **split canvas** (only for informational and company openings): max width 1440px · 2 columns · gap 0px. Equal 720px-wide halves, each 900px tall at desktop; one white, one full-bleed photograph.

## Corner radius

| Element | Radius |
| --- | --- |
| action pills | 90px |
| feature media | 10px |
| news thumbnails | 16px |
| hashtag tags | 8px |
| video control | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Dominant page field and unboxed content.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Sections share the page field rather than alternating a succession of tinted cards.

**Transfer:** Use whitespace and image placement to distinguish chapters.

#### Black statement band · level 0

**Use:** Strong tonal interruption behind oversized white copy.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full bleed, 639px tall in the main marketing treatment; informational variant is 475px tall with smaller editorial-display lettering.

**Transfer:** Give a short human outcome its own typographic stage, with complete visible copy rather than decorative empty space.

#### Photo legibility veil · level 1

**Only for:** split photographic openings

**Use:** White headline legibility over the image half.

**CSS:** `background: linear-gradient(0deg, rgba(0, 0, 0, 0.5) 25%, rgba(0, 0, 0, 0) 75%)`

**Observed:** A bottom-weighted dark veil preserves the photograph while supporting lower-right white lettering.

**Transfer:** Keep the upper image recognizable and place the sentence ending over its darker lower area.

#### Ruled editorial field · level 0

**Only for:** informational and company article lists

**Use:** Separation without boxed cards.

**CSS:** `border-top: 1px solid #1c1e21; border-bottom: 1px solid #1c1e21`

**Observed:** First row introduces the top rule; subsequent rows share boundaries. The field stays white.

**Transfer:** Use a continuous reading list rather than a card stack.

## Components

### Minimal navigation

**Use:** Default marketing masthead.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 40px 0; background-color: #ffffff; position: sticky`

**Observed:** Menu sits alone at left; login and identity mark align right. Header occupies 156px. The menu target is 54px and the identity image is 72px. Informational variants use a 130px fixed header, a 32px menu target and inverse identity treatment over photography.

**Transfer:** Use the new product's compact identity, not a wordy horizontal menu.

### Gradient rim button

**Use:** Primary conversion and editorial index action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 52px; padding: 0px 48px; border: 2px solid transparent; border-radius: 90px; background-image: linear-gradient(90deg, #ffd500, #ff7b00, #ff006a); background-origin: border-box; box-shadow: #ffffff 0px 1440px 0px 0px inset; color: #000000`

**Text style:** `button-label` — Instagram Sans 500 · 16px/1.2 · uppercase

**Observed:** The label is centered in a white pill with a fine multicolor perimeter; width is content-driven, about 190px for the primary label.

### Inline gradient action

**Use:** Completes a feature heading with a linked noun and arrow.

**CSS:** `background-image: linear-gradient(90deg, #ff7a00 0%, #ff0169 50%, #d300c5 100%); background-clip: text; color: rgba(0, 0, 0, 0)`

**Text style:** `heading` — Instagram Sans 400 · 48px/1.05 · tracking -0.03em

**Observed:** The link is grammatically part of the black heading. A right arrow means continuation; a diagonal arrow marks an outward destination.

**States:** Declared: hover text-decoration underline; focus-visible unspecified.

**Transfer:** Link the meaningful final noun, not a detached 'learn more' label.

### Hashtag tag

**Use:** Article categories under square thumbnails.

**CSS:** `display: flex; align-items: center; padding: 2px 8px; margin-right: 6px; border: 1px solid #1c1e21; border-radius: 8px; color: #000000`

**Text style:** `tag` — Instagram Sans Condensed 700 · 20px/1.2 · uppercase

**Observed:** Two short labels often share a line; groups wrap with an 8px row gap and sit 24px below the thumbnail.

**States:** Declared: hover text-decoration underline; focus-visible unspecified.

### News card

**Use:** Image-led editorial recommendations.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start`

**Text style:** `body` — Instagram Sans 400 · 24px/1.2

**Observed:** Unboxed 290px-wide columns pair a 290px square, 16px-radius image with Hashtag tags, a regular title and a small clock/date line. Cards align across a 474px-tall row.

**Transfer:** Mix people-led editorial images with isolated product demonstrations rather than repeating the same mockup.

### Footer link

**Use:** Primary sitemap navigation.

**CSS:** `color: #000000`

**Text style:** `body` — Instagram Sans 400 · 24px/1.2

**Observed:** Primary links lead six columns; subordinate links use secondary-link in muted gray with 8px bottom rhythm. External destinations add a small diagonal arrow.

**States:** Declared: hover text-decoration underline; focus-visible unspecified.

### Language pill

**Use:** Centered locale selection in the marketing footer.

**CSS:** `padding: 12px 32px 12px 12px; border: 2px solid #1c1e21; border-radius: 90px; color: #000000`

**Text style:** `secondary-link` — Instagram Sans 400 · 18px/1.4

**Observed:** Globe precedes the label; the control is about 193px wide and 53px high. A centered row of six black social circles follows.

### Ruled article row

**Only for:** informational and company pages

**Use:** Text-led related or featured reading.

**CSS:** `border-bottom: 1px solid #1c1e21; padding: 56px 32px; position: relative`

**Text style:** `list-title` — Instagram Sans 400 · 32px/1.2

**Observed:** Gray condensed categories sit above the title with an 8px gap. Text takes about three quarters of the width; a large right arrow occupies the far edge. Rows are about 183px tall and the first adds a top rule.

**States:** Declared: hover text-decoration underline on title links; focus-visible unspecified.

**Transfer:** Use editorial titles, not product-feature bullet lists.

### Color bar resource tile

**Only for:** resource directories

**Use:** Visual entry to a family of tools or reference material.

**CSS:** `border-bottom: 23px solid #ff0069; position: relative`

**Text style:** `body` — Instagram Sans 400 · 24px/1.2

**Observed:** A square 309px photograph sits immediately over a flat colored underbar. Below are a condensed uppercase category, a 24px description and compact arrow links. Alternate bars are orange, yellow and blush; there is no rounded card enclosure.

**Transfer:** Use color to distinguish resource families, leaving the text field white.

### Resource panel

**Only for:** informational pages

**Use:** Paired explanatory resource blocks.

**CSS:** `border-left: 2px solid #1c1e21; padding-left: 16px`

**Text style:** `list-title` — Instagram Sans 400 · 32px/1.2

**Observed:** A title precedes 24px explanatory text with inline gradient links. Two panels share a row with a broad 205.7px gap; the narrow vertical edge can take the link-gradient treatment.

**Transfer:** Give each panel one resource and one paragraph rather than a miniature feature grid.

## Imagery and graphics

### Everyday social scenes

**Use:** Primary feature media and personal product stories.

**Observed:** People are photographed close, often by themselves or friends: a casual errand, an umbrella selfie, a getting-ready video. Natural light, ordinary interiors, imperfect camera angles and saturated real-world clothing supply warmth. Portrait video can be 505px by 687px; broader media reaches 719px wide. Images sit directly on white beside much smaller blocks of text.

**Transfer:** Photograph people genuinely using the new product, at their own scale and in familiar environments. A credible still in the same framing is the minimum substitute for video.

### Expressive annotations

**Use:** Small human punctuation around feature media and the opening payoff word.

**Observed:** A curved black underline emphasizes the last hero word; a heart-notification bubble and oversized social-action outlines sit near picture edges. They are isolated accents, not a wallpaper of stickers.

**Transfer:** Use one curved underline and a compact annotation tied to the new product's human outcome. Retain the informal line quality even without social-product symbols.

**Build:** Draw an SVG path beneath the payoff word, spanning its width with a slightly arched, uneven black stroke about 6px thick and rounded caps. Place one compact, saturated notification-like bubble across a media edge with a white outcome glyph; keep it far smaller than the photo. Use existing accent pink rather than adding broad chromatic backgrounds.

### Editorial thumbnails

**Use:** News-card squares.

**Observed:** Some thumbnails are full-frame people photography; others place one or two dark phone interfaces on a solid black backing. All share a square silhouette and 16px corners. Interface interiors stay subordinate to the overall photographic or black-backed composition.

**Transfer:** Use authentic product imagery inside a black square, or a people-led editorial image. Keep the device view legible as a single object rather than reproducing tiny UI details.

### Workplace documentary

**Only for:** company and recruiting pages

**Use:** Split feature and offset image gallery.

**Observed:** Bright real workplaces with people moving through them, exposed building services, furniture and colored architectural installations. A later gallery offsets a wide 823px by 464px image against a narrower 411px by 547px portrait image, with broad white space between their starting edges. Pastel light appears within photographed architecture, not as a page-wide gradient wash.

**Transfer:** Show lived-in workspace and a distinctive physical detail of the new organization. Pair wide and tall documentary images at different vertical positions; use real material and light rather than generic team headshots.

### Icons

**Observed:** Black outline menu and informal directional arrows contrast with solid black social circles containing white symbols. Feature controls include a 32px translucent black circular play/pause control. Social icons are 40px in the default footer; informational-page navigation symbols are larger.

**Transfer:** Choose a small coherent icon set with clear rounded outlines for actions and simple filled circles for social destinations. Give arrows enough visual personality to sit alongside the humanist type.

## Section recipes

How recurring sections are built.

### First screen: Sentence first opening

**Observed:** A White canvas supports Minimal navigation above a left-aligned display sentence. The headline occupies roughly two thirds of the content width, wraps across three lines at 100px/1.05, and ends in a curved underline. The right third is intentionally open. A Gradient rim button follows about 59px below the lettering. Within the first 900px the complete headline, one action and the top edge of the next chapter's right-hand portrait video are visible; the feature explanation and most media remain below the fold. Layers are simply canvas, headline/underline and action, with no hero photograph behind the text and no support paragraph.

**Transfer:** Make the new product's human benefit the main object, ending on a short memorable word that can carry the underline. Keep one outlined action. Informational or company pages instead open with the Split sentence scene, not a compressed version of this composition.

**Avoid:** Do not center the headline, fill the empty right side with a dashboard, or introduce a subtitle and a row of competing actions.

**Text style:** `display` — Instagram Sans 400 · 100px/1.05 · tracking -0.035em

### Alternating human feature

**Observed:** Everyday social scenes pair with heading text and an Inline gradient action on White canvas. One treatment puts a 397px text column beside 505px-wide portrait video on the right, with unused space at left; other chapters use 719px-wide media and a shorter opposite-side text column. Text is vertically centered against the media. Expressive annotations attach to the scene rather than forming a second content block.

**Transfer:** Alternate the dominant media side to create an unhurried rhythm. Let each sentence resolve into one linked capability.

**Text style:** `heading` — Instagram Sans 400 · 48px/1.05 · tracking -0.03em

### Typographic contrast pause

**Observed:** Black statement band interrupts the light chapters with oversized white statement type. The main marketing treatment is 639px tall and keeps the copy left-aligned to the content edge; the informational treatment has an editorial-display headline and one 24px supporting line.

**Transfer:** Use a compact emotional outcome as the visual event. Keep the band purposeful and text-led rather than treating black as a default page theme.

**Text style:** `statement` — Instagram Sans 400 · 100px/1.2

### Editorial grid lead

**Observed:** An eyebrow sits 8px above a heading. A Gradient rim button aligns to the far right of the heading row. After 56px bottom padding, a four-column News card grid presents square imagery, Hashtag tags, titles and dates.

**Transfer:** Use this for fresh stories or concrete examples that reward exploration.

**Text style:** `heading` — Instagram Sans 400 · 48px/1.05 · tracking -0.03em

### Centered conversion ending

**Observed:** The closing invitation is centered on White canvas, beginning 96px below the preceding section. Two adjacent 48px heading lines lead into paired download badges. Six footer columns follow, then the Language pill, a centered social-icon row and quiet legal links. The whole closing field is 795px tall.

**Transfer:** Close with two short lines that connect the product outcome to an immediate action. Replace store badges with the new product's actual conversion mechanism, keeping the compact centered action cluster.

**Text style:** `heading` — Instagram Sans 400 · 48px/1.05 · tracking -0.03em

### Split sentence scene

**Only for:** informational and company page openings

**Observed:** Two 720px by 900px halves fill the screen: white at left, edge-to-edge photograph at right. Split-display black text begins the sentence in the upper-middle left; white text completes it near the lower-right of the photo over Photo legibility veil. A bold downward arrow anchors the lower left, and the fixed header overlays both halves.

**Transfer:** Split one coherent promise across the two fields. Use a candid human or workplace photograph relevant to the page purpose.

**Text style:** `split-display` — Instagram Sans 400 · 104px/1.05 · tracking -0.035em

### Resource directory chapter

**Only for:** informational resource pages

**Observed:** A centered editorial-heading lead receives 80px top and bottom padding. A Resource grid follows with three Color bar resource tiles. Compact links form a denser tail below each description. A guidelines variant uses a short caption and circular previous/next arrows outside the three-image row.

**Transfer:** Organize tools, learning paths or policies into visual families without turning the page into an application menu.

**Text style:** `editorial-heading` — Instagram Sans 400 · 45.9px/1 · tracking -0.03em

### Editorial reading ending

**Only for:** informational and company pages

**Observed:** A condensed editorial-label precedes a 45.9px heading, or a 61.9px heading for the more prominent related-reading variant. Ruled article rows follow, then a centered 'View More' text action with right arrow. A 572px white footer begins with 78px breathing room and six columns, followed by black social circles and a low-contrast utility line; there is no large conversion invitation or outlined locale pill in this variant.

**Transfer:** Finish an informational journey by handing the reader onward to useful content and a navigable sitemap.

**Text style:** `editorial-heading` — Instagram Sans 400 · 45.9px/1 · tracking -0.03em

### Workplace feature and gallery

**Only for:** company and recruiting pages

**Observed:** A 720px by 900px documentary photo fills the left half; an editorial-heading, one 24px paragraph and a 32px arrow link sit centered vertically in the opposite half. Later, Workplace documentary imagery is presented as a wide-low image and a tall-high image across a 900px chapter, separated from neighboring chapters by 160px white intervals.

**Transfer:** Let physical details and a short invitation communicate culture without converting the layout into a staff-card grid.

**Text style:** `editorial-heading` — Instagram Sans 400 · 45.9px/1 · tracking -0.03em

## Page flow

**Storyline:** Human promise → lived experience → useful capabilities or resources → emotional or institutional reassurance → further reading → contextual closing and navigation.

### Broad product marketing and discovery

1. **promise** — A monumental benefit sentence, underlined payoff and one outlined action.
2. **capability chapters** — Alternating candid media with sentence-completing gradient links.
3. **emotional reinforcement** — A black typographic statement band.
4. **further reading** — Condensed editorial lead and four square-image stories.
5. **closing call** — Centered two-line invitation, compact acquisition actions and six-column footer.

**Transfer:** Translate the product into everyday human outcomes before adding editorial depth.

### Information-rich trust and resource directory

1. **promise** — Split sentence opening across white and candid portrait photography.
2. **resource navigation** — Three picture-led categories with colored underbars and compact tool links.
3. **reassurance** — Broad collaboration statement followed by two left-ruled explanatory panels.
4. **focused initiative** — Black information band with headline and supporting link.
5. **reference material** — Guidelines carousel with candid pictures and colored bars.
6. **further reading** — Three large ruled article rows and a centered continuation action.
7. **navigation ending** — Six-column footer, social circles and understated utility links.

**Transfer:** Keep functional detail readable while using people photography to make trust feel personal.

### Company story and recruiting

1. **promise** — A sentence spans a white half and a workplace photograph.
2. **invitation** — A large documentary image pairs with a short people-first paragraph and an arrow link.
3. **cultural proof** — Two differently sized architectural photographs form an offset gallery.
4. **further reading** — Condensed lead, ruled stories and continuation action.
5. **navigation ending** — The informational footer without the large conversion invitation.

**Transfer:** Use the organization's real environments and one concrete invitation rather than an abstract values manifesto.

## Writing

Warm, plainspoken and socially fluent. Benefits are framed as ordinary human experiences, with reassuring directness when the subject becomes informational.

**Do not copy:** Do not reuse Instagram or Meta names, identity assets, social-product symbols as brand marks, article titles, dates, audience numbers, named programs, institutional claims or recruitment claims. Source examples illustrate syntax and tone only.

- **Addressing the reader:** Speak to 'you' and 'your' in marketing; use 'we' and 'our' for responsibility and collaboration. Refer to the product by name only where it anchors a promise or clarifies a resource.
- **Rhythm:** Long conversational hero sentences can span several lines. Feature copy is usually a single sentence ending in a linked noun; closing copy becomes short parallel clauses. Informational paragraphs are fuller but stay direct.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Product plus a relational benefit, ending on an emotionally meaningful word. | About 12–18 words | “[Brand] brings you closer to the people and things you love” |
| Feature heading | An active verb and a personal outcome resolve into the linked capability. | About 10–18 words | “Protect your account and peace-of-mind with our”<br>“Entertain, inspire and reach new audiences as a” |
| Primary action | Short direct verb phrase, rendered uppercase only by styling. | 2–3 words | “Try it now”<br>“View more” |
| Closing invitation | A compact three-verb benefit line followed by a direct action line. | Two short sentences | “Create, share and connect.”<br>“Download now.” |
| Company heading | Friendly invitation rather than institutional jargon. | 3–5 words | “Work with us” |

**Words and phrasing to use:** closer; people; everyday; share; connect; your; help; learn more; explore

**Avoid:** revolutionary ecosystem; unparalleled; synergy; dominate; enterprise-grade excellence; unlock limitless potential

**Rules:**

- Lead with what someone can do or feel, not a list of technical specifications.
- Let a feature link complete the sentence grammatically.
- Use a right arrow for onward movement and a diagonal arrow for outward destinations.
- Make trust copy concrete about actions and assistance; avoid absolute guarantees.
- Keep headlines sentence case while condensed editorial labels and button labels supply uppercase contrast.

## Do's and Don'ts

### Do

- Set the opening at 100px, weight 400, line-height 1.05 and -0.035em tracking.
- Keep feature statements at 48px and attach the gradient link directly to the sentence.
- Make the primary pill 52px high with a 2px multicolor rim and white interior.
- Preserve 32px gutters in four-column news grids.
- Use 16px corners on square news thumbnails and 10px corners on feature media.
- Give the closing invitation 96px of top breathing room before the six-column navigation ending.
- Use the black statement band as a distinct interruption, not an all-page theme.
- Keep resource underbars 23px tall and square-edged within their scoped directory layout.

### Don't

- Do not make the display typography bold; the core headings are weight 400.
- Do not flood marketing sections with pink or rainbow gradient fills; gradient use belongs to small actions and annotations.
- Do not use the 90px button radius for every content container; news media uses 16px and feature media 10px.
- Do not put a bordered card shell around every article; the default card is unboxed.
- Do not turn uppercase condensed labels into tracked-out monospace captions.
- Do not use the 24px informational eyebrow as the default marketing eyebrow; the default is 16px.
- Do not substitute polished studio stock portraits for ordinary self-shot scenes.
- Do not carry the gray unboxed article-list metadata into the bold outlined hashtag treatment; these are separate page-type variants.

## Motion and responsive

### Motion

**Observed:**

- The marketing header declares transform 0.5s ease-in-out.
- Gradient-rim buttons declare height 0.3s ease-in-out.
- Split-opening arrows declare a 2.5s infinite animation with cubic-bezier(0, 0, 0.1, 1).
- Media and text elements declare transform transitions of 1s cubic-bezier(0, 0, 0.1, 1), with some opacity transitions of 666ms cubic-bezier(0.33, 0, 0.67, 1).

**Transfer:**

- Keep movement attached to the header, scene entrances and downward invitation rather than adding animated decorative backgrounds.
- Retain a complete, readable statement when motion or media is unavailable.

**Unknown:**

- Exact scroll triggers, video playback policy, arrow displacement and the full black-band animation are not established.

### Responsive

**Observed:**

- Split-display and editorial headings use the viewport formulas given in their type recipes.
- Informational side insets use 7.142vw and 14.285vw. Desktop split panels are equal halves.

**Transfer:**

- On narrow screens, preserve the sentence's reading order before stacking media; keep its linked final noun visually attached.
- Reduce grid column counts rather than squeezing the square imagery into tiny thumbnails.
- For split openings, keep the first sentence portion readable on white and the completion legible over its photograph even when the panels stack.

**Unknown:**

- Mobile layout, exact component breakpoints and small-screen type bounds are not established. Narrow-screen stacking is design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
