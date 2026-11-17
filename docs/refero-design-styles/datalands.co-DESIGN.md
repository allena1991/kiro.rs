# Datalands — information as graphic spectacle

## Overview

A black gallery of oversized graphic work, understated grotesk sentences and technical monospace markings. White typography and fine rules give vivid data art room to feel loud without making the page busy. Monumental word shapes and a powder-blue closing panel add a playful, almost poster-like confidence suited to creative tools, information products and design-led services.

### Essentials

- Identity becomes the opening artwork: a white, chunky geometric word sculpture spans 1380px inside 30px gutters, in a 286px-high SVG stage with 180px of space above. Include an equally monumental custom product-name treatment, even without product media.
- Headlines sound conversational rather than typographically loud: regular grotesk at 38px/1.1 for the introductory promise, 42px/1.1 with -0.04em tracking for chapter headings, and 35px/1 for project descriptions.
- Controls are outlined punctuation: the main contact action combines a 148×40px capsule with a separate 40px circular arrow, using 12.5px uppercase mono with 0.05em tracking rather than a solid rectangular button.
- Color lives in the exhibits and the ending: black surrounds white text throughout the main narrative; saturated imagery sits in isolated frames, pink is concentrated in the newsletter controls, and the final 995px panel flips to powder blue with black text.
- Proof is a staggered gallery, not a uniform card wall: rounded media at 30px radius varies from roughly 578px to 911px wide, with black capsule labels and 35px descriptions 18px below. Use original geometric benefit or metric art when no comparable media exists.
- Information is indexed like an exhibition: white dot-plus-mono section labels, 60px numbered capability rows split at the page midpoint, and thin horizontal rules. Preserve the numbering and the large left/right division.
- The ending is a second poster: repeat the giant word sculpture in black, then three 444px outlined social shapes with 24px gaps, followed by an 80px contact line and small uppercase mono utilities.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Powder blue | `#94bcee` | `--color-closing` | background | Default full-width closing panel. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Candy pink | `#fc74dd` | `--color-newsletter-action` | action, surface | Compact submit capsules among the long newsletter fields. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery black | `#000000` | `--color-canvas` | background, text, surface | Default page canvas, floating project tags and all text on the light closing panel. |
| Soft gray | `#d9d9d9` | `--color-muted` | text | Newsletter invitation and secondary text on black. |
| Chalk | `#f3f3ef` | `--color-input` | surface | Oversized newsletter input capsules. |
| Gallery white | `#ffffff` | `--color-text` | text, border | Primary text and outlined actions on black. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live green | `#3dcd8b` | `--color-status` | accent | Small live-clock status dot in the navigation; not a general CTA fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| project case studies | Warm paper | `#e7e5dd` | `--color-case-closing` | background | Alternative closing panel with the same black graphics and contact composition. |

## Typography

- **Basis Grotesque Pro** — All prose, chapter titles, capability rows and large contact text. Matter-of-fact grotesk with a warm, unforced regular weight and broad readable shapes. If unavailable, use **DM Sans**. Use regular 400 and preserve role-specific tracking. Font stack: "Basis Grotesque Pro", "DM Sans", Arial, sans-serif.
- **Martian Mono** — Section markings, project tags, navigation, captions and process labels. Technical monospaced forms with semi-wide regular labels, extra-light standard captions and light narrow handles. Font stack: "Martian Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| contact | Basis Grotesque Pro | 400 | 80px | 1 | -0.0025em | Monumental closing contact invitation and email. |
| capability | Basis Grotesque Pro | 400 | 60px | 1 | -0.0033em | Large numbered capability links. |
| social-title | Basis Grotesque Pro | 400 | 60px | 1 | -0.03em | Short platform abbreviations centered in the closing shapes. |
| heading | Basis Grotesque Pro | 400 | 42px | 1.1 | -0.04em | Short chapter headings beside supporting content. |
| intro | Basis Grotesque Pro | 400 | 38px | 1.1 | -0.008em | Introductory product or company statement beneath the opening artwork. |
| project-title | Basis Grotesque Pro | 400 | 35px | 1 | normal | Project descriptions, wider explanatory statements and case-study titles. |
| body | Basis Grotesque Pro | 400 | 22px | 1.25 | -0.01em | Supporting paragraphs and process explanations. |
| process-label | Martian Mono | 400 | 16px | 1.45 | 0.1em, uppercase | Semi-wide mono for process numbers and named phases. |
| caption | Martian Mono | 200 | 16px | 1.45 | -0.05em | Extra-light standard-width mono for artwork captions and newsletter explanation. |
| label | Martian Mono | 400 | 12.5px | 1.25 | 0.05em, uppercase | Semi-wide mono for navigation, dot-led section labels and black project pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| project case studies | case-body | Basis Grotesque Pro | 400 | 26px | 1.25 | normal | Centered narrative interludes between artwork plates. |
| project case studies | metadata | Martian Mono | 200 | 12px | 1.45 | 0.03em | Extra-light standard-width mono for client, year and role details. |

**Notes:**

- Keep prose at weight 400; graphic mass belongs to the custom word sculpture, not bold body headings.
- Use Martian Mono's semi-wide regular cut for labels and its standard extra-light cut for captions; narrow light cuts suit handles. The width distinction is as important as size.
- Tracking varies by role: chapter headings are tightly spaced, project titles remain normal, and uppercase mono labels open up.
- The opening and closing word sculptures are vector artwork, not an 80px text heading. Preserve their unusually broad, dense silhouette separately from the prose scale.

## Layout

**Density:** Airy gallery spacing surrounds large media while labels and information rows remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight flex gaps and top navigation inset. |
| 12px | Newsletter field-to-submit gaps and paired process columns. |
| 18px | Media-to-description separation in project cards. |
| 20px | Paragraph separation and section-label top inset. |
| 24px | Dot-to-label spacing and three-shape closing grid gaps. |
| 30px | Default horizontal page gutters. |
| 40px | Case-study plate top padding and footer bottom padding. |
| 48px | Newsletter vertical input padding and social-shape inner padding. |
| 80px | Major section bottom space and inset case-study galleries. |
| 100px | Separation between staggered gallery projects and narrative top padding. |
| 120px | Case narrative bottom padding and left-column text breathing room. |
| 180px | Opening space above the monumental name graphic. |

### Containers and grids

- **gallery-container**: max width 1440px · side padding 30px. Default full-width desktop composition with a 1380px inner span.
- **split-editorial**: 2 columns · gap 0px. Equal half-width anchors: heading or number on the left, explanation or capability name beginning at the midpoint. Introductory prose uses an 80px separation instead.
- **social-triptych**: 3 columns · gap 24px. Three equal 444px-square social targets across the closing panel.
- **case-pair** (only for project case studies): 2 columns · gap 120px · side padding 80px. Two 580px-wide artwork plates, with the right plate vertically staggered.
- **narrative-column** (only for project case studies): max width 864px · side padding 0px. Centered narrative text between full-width media scenes.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | project-media | 30px |
|  | project-tag | 49px |
|  | contact-capsule | 34px |
|  | newsletter-capsule | 96px |
|  | social-circle | 300px |
|  | social-square | 8px |
| project case studies | case-artwork | 18px |

## Surfaces and depth

### Surfaces

#### Black gallery · level 0

**Use:** Default narrative canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat and untextured; media and rules establish hierarchy without raised cards.

**Transfer:** Let black negative space separate vivid exhibits.

#### Blue closing poster · level 0

**Use:** Default closing conversion area.

**CSS:** `background: #94bcee; color: #000000; padding: 0px 30px 40px`

**Observed:** A complete color inversion rather than a small CTA card.

**Transfer:** Keep all graphics, outlines and contact text black.

#### Chalk capsule · level 1

**Use:** Long newsletter entry fields.

**CSS:** `background: #f3f3ef; border-radius: 96px; box-shadow: none`

**Observed:** Flat, opaque and oversized rather than glassy or elevated.

**Transfer:** Keep the field visually distinct from its small pink submit partner.

#### Paper closing poster · level 0

**Only for:** project case studies

**Use:** Restrained closing variant after colorful project galleries.

**CSS:** `background: #e7e5dd; color: #000000; padding: 0px 30px 40px`

**Observed:** Same construction as Blue closing poster, with a warm neutral backing.

**Transfer:** Use this variant on long visual case studies, not as the default landing-page palette.

## Components

### Navigation strip

**Use:** Persistent utility header.

**CSS:** `display: flex; justify-content: space-between; height: 50px; padding: 10px 30px 0px; color: #ffffff`

**Text style:** `label` — Martian Mono 400 · 12.5px/1.25 · tracking 0.05em · uppercase

**Observed:** A short positioning line sits left; a live clock with a green dot occupies the right-center and the Capsule arrow action finishes the row. Case studies replace the left line with brand/project breadcrumbs.

**Transfer:** Use one short descriptor, status if meaningful, and a single contact action.

### Capsule arrow action

**Use:** Primary contact conversion in the header.

**CSS:** `display: flex; align-items: center; height: 40px; color: #ffffff; background: transparent`

**Text style:** `label` — Martian Mono 400 · 12.5px/1.25 · tracking 0.05em · uppercase

**Observed:** An outlined rounded text capsule touches a separately outlined circular arrow. The text portion is 148px wide with 24px side padding and 34px radius; the arrow occupies a 40px circle. Fine white outlines remain visible against black.

**Transfer:** Retain the paired silhouette for a short contact or trial action.

### Dot section marker

**Use:** Index the gallery's major chapters.

**CSS:** `display: flex; align-items: center; gap: 24px; color: #ffffff`

**Text style:** `label` — Martian Mono 400 · 12.5px/1.25 · tracking 0.05em · uppercase

**Observed:** A filled white dot precedes the uppercase mono label below a thin horizontal divider. Labels align to the 30px gutter.

**Transfer:** Use functional chapter nouns rather than promotional subheadlines.

### Project media card

**Use:** Primary visual proof on marketing pages.

**CSS:** `border-radius: 30px; overflow: hidden; position: relative`

**Observed:** The artwork itself is the linked card; Project pill sits near its upper-left corner and a project-title description sits outside below it. Width and alignment vary across the page, with no surrounding panel or shadow.

**Transfer:** Use product demonstrations, original benefit graphics or editorial compositions as the linked media.

### Project pill

**Use:** Identify the item on top of media.

**CSS:** `background: #000000; color: #ffffff; border-radius: 49px; padding: 10px 22px; height: 36px`

**Text style:** `label` — Martian Mono 400 · 12.5px/1.25 · tracking 0.05em · uppercase

**Observed:** A compact black capsule overlays the colorful artwork; the label is never moved into the description below.

**Transfer:** Keep names short enough that the pill stays a small annotation.

### Capability row

**Use:** Large navigable capability index.

**CSS:** `display: flex; padding: 0px 0px 10px; height: 70px; color: #ffffff; border-bottom: 1px solid #ffffff`

**Text style:** `capability` — Basis Grotesque Pro 400 · 60px/1 · tracking -0.0033em

**Observed:** Number plus slash fills the left half; the capability name starts at the midpoint. Rows have 16px gaps and a fine white underline.

**Transfer:** Apply the same structure to a compact set of major product capabilities.

### Process item

**Use:** Explain a method without boxed cards.

**CSS:** `display: flex; flex-direction: column; color: #ffffff`

**Text style:** `body` — Basis Grotesque Pro 400 · 22px/1.25 · tracking -0.01em

**Observed:** A process-label number and uppercase phase name form a single top row, followed by a body paragraph after 20px. Items pair into two columns within the right half of a split section, with horizontal separators between pairs.

**Transfer:** Use clear phases or product adoption steps with one paragraph per item.

### Newsletter ribbon

**Use:** Playful low-pressure signup.

**CSS:** `display: flex; gap: 12px; overflow: hidden`

**Text style:** `caption` — Martian Mono 200 · 16px/1.45 · tracking -0.05em

**Observed:** Oversized chalk fields alternate with short pink checkmark submit capsules. Fields are 121px high with 48px vertical and 36px horizontal padding; their shared radius is 96px. The ribbon extends beyond both page edges beneath a split invitation/explanation.

**Transfer:** Keep at least one fully usable email form; the repeated ribbon can carry short, playful prompt text.

### Social shape link

**Use:** Large social navigation in the closing poster.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 14px; padding: 48px; width: 444px; height: 444px; border-radius: 300px; border: 1px solid #000000; color: #000000`

**Text style:** `social-title` — Basis Grotesque Pro 400 · 60px/1 · tracking -0.03em

**Observed:** Three equal targets alternate a circle, an 8px-radius square, and a rounded teardrop-like shape. Each contains a platform abbreviation and a much smaller uppercase mono handle.

**Transfer:** Preserve the three-shape rhythm while using the product's real social destinations.

### Contact underline

**Use:** Final direct conversion.

**CSS:** `display: flex; justify-content: space-between; color: #000000; padding: 10px 0px 15px; border-bottom: 5px solid #000000`

**Text style:** `contact` — Basis Grotesque Pro 400 · 80px/1 · tracking -0.0025em

**Observed:** A plain contact invitation aligns left and the email aligns right across equal halves. A heavy horizontal rule joins them into one link-like closing statement; small uppercase utility text follows below.

**Transfer:** Use an equally direct contact or purchase route, not a dense multi-column sitemap.

### Case metadata

**Only for:** project case studies

**Use:** Orient the reader after the project montage.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #ffffff`

**Text style:** `metadata` — Martian Mono 200 · 12px/1.45 · tracking 0.03em

**Observed:** Three rows pair tiny triangular markers, uppercase field labels and values in the left half; a 22px overview paragraph sits on the right beneath a 35px project title.

**Transfer:** Use a minimal set of factual fields relevant to the new project.

## Imagery and graphics

### Monumental name sculpture

**Use:** Opening identity artwork and inverted reprise in the closing panel.

**Observed:** A tightly packed geometric wordmark has blunt heavy stems, circular counters and angular notches. White on black at the opening; black on blue or paper at the close. It spans almost the entire inner width and dwarfs all prose.

**Transfer:** Create a new dense word sculpture from the product name. The minimum equivalent is an original extra-heavy rounded geometric word treatment with custom cuts and counters, rendered as SVG rather than a normal headline.

**Build:** Set the product name as heavy vector paths in a 1380×286 viewBox. Use broad vertical stems and near-circular bowls, reduce inter-letter space until shapes nearly touch, and subtract small circles or diagonal wedges as counters and notches. Fit the whole silhouette to the inner container; use white fill on black and invert to black in the closing panel.

### Staggered graphic exhibits

**Use:** Main marketing proof gallery.

**Observed:** Vivid abstract charts, colorful identity motion, report pages and fitness footage appear in alternating large and small rounded frames. Some scenes fill their frames edge-to-edge while isolated gradient forms float on black. Black label pills contrast with the imagery.

**Transfer:** Use the product's own visual output. Without finished media, make original circles, bars, wedges and typographic benefit diagrams with clear informational meaning; alternate a large central exhibit with offset paired work.

**Build:** Create SVG plates using a few oversized circles, diagonally clipped rectangles and narrow mono annotations. Use the product's accent palette inside each plate, sharply bounded by a 30px rounded clip. Keep black outside the plates and leave large asymmetric gaps.

### Campaign editorial plates

**Only for:** report and campaign case studies

**Use:** Show a graphic language across multiple formats.

**Observed:** Warm white editorial pages carry translucent cyan, mint, yellow, coral and pink charts; cover art mixes soft overlapping colored fields. Plates alternate full-bleed montages, staggered inset spreads and square social graphics. Captions are light mono below, often aligned right with tiny triangle pointers.

**Transfer:** Use a coherent original palette and repeat one chart grammar across reports and small-format cards; do not turn the marketing canvas into the campaign artwork.

**Build:** On a warm off-white artboard, layer two or three large overlapping circular color fields; blur the cover fields softly but keep the interior charts crisp. Build rounded bars and intersecting circles with translucent fills, placing concise labels nearby. Mount the finished plate against the black gallery.

### Geometric metric art

**Only for:** data-system case studies

**Use:** Demonstrate information design at poster scale.

**Observed:** Acid yellow-green, hot magenta, orange, blue, gray and white form circles, wedges, tapering cones and diagonal hatching. Sparse mono annotations surround enormous geometric quantities. Art alternates inset rounded plates, edge-to-edge scenes and tall paired posters.

**Transfer:** Replace the metrics with truthful product data; make the geometry express scale or change rather than serve as decorative dashboard filler.

**Build:** Build SVG circles sized by relative area, triangles connecting before/after values, fine axis lines and clipped diagonal hatch patterns. Limit each plate to a few dominant shapes, keep labels small and airy, and deliberately let a single circle exceed the plate bounds.

### Physical product stage

**Only for:** digital-product case studies

**Use:** One immersive context scene amid flat artwork.

**Observed:** A dark laptop sits at a slight angle on a rough white stone plinth against a flat gray studio background. Bright graphic UI on its screen supplies almost all the color; soft directional light reveals the stone and dark metal.

**Transfer:** Use a product device or physical package on a sculptural neutral prop, with restrained studio lighting. A carefully composited device on a textured pedestal is the minimum equivalent.

### Capsule portraits

**Only for:** team or founder sections

**Use:** Human proof beside a short editorial statement.

**Observed:** Two natural-color bust portraits sit in tall oval frames on near-black backgrounds; small names and role captions sit below. The pair occupies the right half while concise text occupies the left.

**Transfer:** Keep real people, restrained lighting and a paired oval silhouette rather than a wall of avatar circles.

### Icons

**Observed:** Icons act as punctuation: a small right-arrow glyph in a separate circular contact target, filled dots for section labels and live status, tiny triangular pointers near case metadata and captions, and checkmarks in pink signup capsules.

**Transfer:** Use simple glyphs or filled SVG shapes, not a general line-icon library. Keep arrows inside their own circular target and status color limited to the small dot.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture opening

**Observed:** Black is the back layer; the 50px Navigation strip sits at the top with its left descriptor and right Capsule arrow action. The white Monumental name sculpture stretches across the 30px-gutter inner width in a 286px-high SVG box after 180px of top breathing room; the whole opening identity band is 506px high. The first 900px shows the utility row, enormous word shape and the start of the media stage below. The 38px introductory promise, 22px supporting paragraph and gallery remain below the first screen. The graphic, not a prose H1, supplies the visual headline.

**Transfer:** Create an equally dense original product-name silhouette, with the intro recipe reserved for the human-readable promise beneath it. If no media exists, use an original geometric product-benefit film or plate in the following stage. Case-study openings instead use a full-width montage immediately under breadcrumb navigation, with title and facts following.

**Avoid:** Do not replace the word sculpture with a centered two-line SaaS headline, a gradient slogan or an above-fold cluster of CTA buttons.

**Text style:** `intro` — Basis Grotesque Pro 400 · 38px/1.1 · tracking -0.008em

### Split introduction

**Observed:** The intro statement and body support sit side by side inside 30px padding with an 80px gap. The left statement occupies roughly half the width; the right paragraph remains smaller. Dot section marker introduces the proof gallery below.

**Transfer:** State what the product is on the left and the effect it creates on the right.

**Text style:** `intro` — Basis Grotesque Pro 400 · 38px/1.1 · tracking -0.008em

### Asymmetric proof gallery

**Observed:** Project media card exhibits vary in size and align center, left and right across the full container. Some pair a 722px image with a 578px one; larger solo media is roughly 858–911px wide. Project pills sit inside; descriptions follow 18px below. Black negative space separates projects by about 100px.

**Transfer:** Use an uneven editorial cadence for demonstrations and outcomes rather than giving every feature equal visual weight.

**Text style:** `project-title` — Basis Grotesque Pro 400 · 35px/1

### Ruled capability index

**Observed:** Dot section marker precedes a vertical group of Capability rows. Their split at the midpoint is echoed by a 35px explanatory statement in the right half after a broad gap.

**Transfer:** Use a short index to name major ways the product helps, then explain the unifying value beside it.

**Text style:** `capability` — Basis Grotesque Pro 400 · 60px/1 · tracking -0.0033em

### Editorial people and method

**Observed:** A short 42px heading occupies the left half. On the right, either paired Capsule portraits with small captions or paired Process items create a denser counterweight. Method pairs are separated by fine rules.

**Transfer:** Use people where human trust matters, or use steps to explain how adoption works, while maintaining the left-heading/right-detail relationship.

**Text style:** `heading` — Basis Grotesque Pro 400 · 42px/1.1 · tracking -0.04em

### Newsletter interlude

**Observed:** A Dot section marker and thin divider introduce a split 22px invitation and 16px mono explanation. Newsletter ribbon fills the lower portion with cream and pink capsules running beyond the page edges.

**Transfer:** Make signup feel low-pressure and playful; keep the explanatory promise specific about what the reader receives.

**Text style:** `body` — Basis Grotesque Pro 400 · 22px/1.25 · tracking -0.01em

### Closing graphic poster

**Observed:** Blue closing poster carries a black reprise of the name sculpture in a 297px-high graphic area. Social shape links form three equal columns beneath it with 24px gaps. Contact underline spans the lower width in 80px text; small mono utility links and legal text close the page with 40px bottom padding. Case studies use Paper closing poster with the same construction.

**Transfer:** Always end with a bold identity reprise and a direct contact route. Use the product's own destinations and name while retaining the large shape rhythm and palette inversion.

**Text style:** `contact` — Basis Grotesque Pro 400 · 80px/1 · tracking -0.0025em

### Case study montage and facts

**Only for:** project case studies

**Observed:** Breadcrumb Navigation strip precedes a full-width collage of artwork, beginning 20px below the header. A 35px title and split factual overview follow: Case metadata left, 22px summary right.

**Transfer:** Open a detailed product story with a composed overview of outputs before explaining the brief.

**Text style:** `project-title` — Basis Grotesque Pro 400 · 35px/1

### Case study visual essay

**Only for:** project case studies

**Observed:** Centered 864px narrative interludes at 26px or 35px alternate with full-bleed plates and two 580px-wide inset images in 80px side padding. Right-hand plates are vertically offset; small mono captions punctuate the larger scenes. A sparse next-project row precedes the closing poster.

**Transfer:** Alternate proof scale and reading density, ending the story with a meaningful next destination rather than another explanatory paragraph.

**Text style:** `case-body` — Basis Grotesque Pro 400 · 26px/1.25

## Page flow

**Storyline:** Graphic identity or visual hook → brief promise and context → expansive visual proof → explanation of capabilities or method → direct contact and identity reprise.

### Default marketing landing page: establish visual authority and turn interest into a conversation

1. **Identity hook** — Monumental white word sculpture beneath a sparse utility header.
2. **Promise** — Split statement and support beneath the opening media stage.
3. **Visual proof** — Staggered rounded project gallery with short outcome descriptions.
4. **Capability explanation** — Large numbered index and an offset unifying statement.
5. **Trust and method** — Client marks, paired portraits and a numbered process grid.
6. **Light engagement** — Oversized playful newsletter ribbon.
7. **Closing call** — Powder-blue graphic poster with social shapes and a large direct-contact underline.

**Transfer:** Lead with original graphic identity and output rather than generic claims; adapt the proof and method chapters to the new product.

### Campaign case study: show how one visual language extends across editorial and social formats

1. **Visual hook** — Full-width multi-page montage beneath breadcrumbs.
2. **Context** — Project title, minimal facts and a split overview.
3. **Design rationale** — Centered narrative followed by staggered cover and chart plates.
4. **System proof** — Full-width chart spreads and overlapping editorial page compositions.
5. **Extension** — Square social artwork and a concluding narrative statement.
6. **Continuation and closing call** — Sparse next-project link, then warm-paper graphic footer.

**Transfer:** Present a product launch or campaign as one coherent visual system expressed at different sizes.

### Data-system case study: show coherence across abstract metrics, editorial compositions and product context

1. **Visual hook** — Bright geometric montage beneath breadcrumbs.
2. **Context** — Project title, factual metadata and concise overview.
3. **System explanation** — Short centered narrative followed by paired metric plates.
4. **Immersive proof** — Studio device scene and large graphic compositions.
5. **Range and outcome** — Tall paired posters, a concluding statement, then full-width metric art.
6. **Continuation and closing call** — Next-project row followed by warm-paper graphic footer.

**Transfer:** Use truthful metrics and a small consistent graphic vocabulary to demonstrate a product system's range.

## Writing

Confident, design-literate and conversational, with occasional playful phrasing. Claims focus on the work and the change it creates rather than a grand manifesto.

**Do not copy:** Do not reuse the studio name, its wordmark artwork, client identities, project titles, contact details, proprietary claims, years of experience, metric values or case-study facts. Source examples illustrate tone only.

- **Addressing the reader:** Use we for the maker and you sparingly for invitations or expectations; describe project outcomes in direct, active language.
- **Rhythm:** Short sentence-like chapter headings contrast with medium-length outcome descriptions and compact explanatory paragraphs. Uppercase belongs to mono labels, not all prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning statement | Say what the organization is in one unembellished sentence. | About 10–15 words | “[Brand] is a data visualization and information design studio.” |
| Chapter heading | A compact human phrase with an unexpected pairing. | 3–5 words | “Design obsessed duo.”<br>“Big vibes, small core.” |
| Proof description | Begin with an active gerund and explain the transformation. | About 10–18 words | “Overhauling how a beloved sportswear company visualizes data.” |
| Supporting line | Describe a concrete working advantage in plain first-person language. | One or two sentences | “We know brands, we know design. Our experience spans a combined 30 years.” |
| Primary action | A short conversational invitation rather than a sales command. | 2 words | “Let’s talk” |
| Secondary signup | Disarm with an honest promise about frequency. | One short sentence | “Sign up for our extremely infrequent newsletter!” |

**Words and phrasing to use:** visual language; systems; shaping; reimagining; extending; together; we help; in action

**Avoid:** revolutionary AI-powered platform; unlock limitless potential; synergy; best-in-class; transform your business forever

**Rules:**

- Name the object of the work and its practical effect, not just an adjective.
- Let concise project descriptions carry proof; use longer paragraphs only when explaining a method or brief.
- Use a little warmth in chapter headings and signup copy, while factual labels remain terse.
- Make expectations concrete when asking for an email or conversation.

## Do's and Don'ts

### Do

- Keep the primary canvas black and prose white; reserve the powder-blue inversion for the closing poster.
- Use 30px desktop side gutters and align chapter labels to them.
- Make the word sculpture almost container-wide, separate from the 38px prose introduction.
- Set regular grotesk headings at 42px/1.1 and project descriptions at 35px/1.
- Use 12.5px uppercase semi-wide mono for navigation and small project tags.
- Stage project media in mixed widths with 30px rounded corners and 18px caption separation.
- Preserve the capsule-plus-circle silhouette of the 40px-high primary action.
- Give the closing contact line 80px regular type and a visibly heavier underline than the section rules.

### Don't

- Do not apply candy pink to large page backgrounds; it belongs to the signup controls.
- Do not turn the 10px green status dot into the main button color.
- Do not use shadows or glass panels to separate content; the gallery is flat.
- Do not put 60px capability titles inside raised feature cards; they belong to full-width ruled rows.
- Do not use the warm-paper case-study footer as the default landing-page closing color.
- Do not make every artwork thumbnail the same width or center every description.
- Do not uppercase the 22px supporting prose; reserve that treatment for technical markings.
- Do not add a conventional dense sitemap in place of the large social shapes and direct contact line.

## Motion and responsive

### Motion

**Observed:**

- Nine short footer links declare color transitions of 0.3s cubic-bezier(0.44, 0, 0.56, 1).
- Media includes video; the newsletter ribbon is horizontally translated and extends beyond the viewport.

**Transfer:**

- Keep the newsletter's overflow-ribbon character while preserving a stable usable form.
- Use motion to animate original graphic exhibits rather than adding unrelated UI ornament.

**Unknown:**

- Video playback details, scroll reveal timing, ribbon speed and easing, and focus-visible treatments are not established.

### Responsive

**Observed:**

- Declared width boundaries cluster around 810px, 1200px, 1440px and 1920px.

**Transfer:**

- On narrow widths, keep the word sculpture fitted to the available width rather than substituting a standard heading.
- Stack editorial halves and staggered media while preserving the distinction between oversized artwork and small mono markings.
- Allow the large contact invitation and address to stack; preserve the palette inversion and graphic closing shapes.

**Unknown:**

- Mobile type sizes, gutters, navigation behavior and exact stacking rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
