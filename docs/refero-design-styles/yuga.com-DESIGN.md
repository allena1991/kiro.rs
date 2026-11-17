# Yuga — pixel-field bravado

## Overview

A bold, exhibition-like identity for products that want to feel like cultural worlds rather than utilities. Black and white dominate, with a sharp yellow-green interruption, heavy grotesk typography, pixel-field graphics and oversized emblem cards. The density alternates between almost empty theatrical stages and tightly packed statements, with cinematic media carrying personality.

### Essentials

- The opening is an emblem event rather than a sales stack: a black 900px stage, white undulating square field and centered symbol around 355px wide, with a 50px navigation rail pinned to the bottom.
- Headlines land like compressed manifestos: 102px grotesk, weight 800, 0.82 line height and -0.03em tracking in capitals; the moving banner grows to 160px with the same proportions.
- The interface has two scales at once: 14px bottom navigation and directory links sit beside monumental lettering, while conversion buttons remain compact at 51px high with 90px radii and 2px black borders.
- Color arrives as a single exhibit, not a theme wash: black and white occupy nearly the entire page; #131313 backs emblem cards and #d3de5d is isolated to one square in the horizontal showcase.
- Images behave like artifacts in an exhibition: 665px square showcase tiles, 30px gutters, rounded clipping and centered white emblems or near-black dimensional objects; use a custom geometric product symbol when no rich media exists.
- A giant repeated text ribbon and a recurring corner emblem hold the page together: the ribbon uses 160px uppercase lettering and the small solid emblem sits above the bottom rail; both remain part of the identity even with entirely different content.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid exhibit | `#d3de5d` | `--color-accent` | surface, accent | One emphatic showcase tile amid otherwise monochrome content; not a general action color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text, border, action | Default opening and showcase canvas; text, rules and buttons on white. |
| Charcoal tile | `#131313` | `--color-tile` | surface | Low-contrast backing for white showcase emblems. |
| Exhibition white | `#ffffff` | `--color-white` | background, text, border | Support and conversion bands; type and rules on black. Company storytelling uses white as its dominant canvas. |

## Typography

- **AK Monument Grotesk** — All text, from giant statements to tiny navigation. Dense neo-grotesk with forceful heavy capitals, compact lowercase and blunt, unornamented forms. If unavailable, use **Inter**. Use 800 for display and keep the tightly compressed line height and negative tracking. Font stack: "AK Monument Grotesk", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| ribbon | AK Monument Grotesk | 800 | 160px | 0.82 | -0.03em, uppercase, features "calt" 0, "liga" 0, "ordn", "salt", "ss01", "ss02", "ss03" | Repeated oversized showcase title extending beyond the viewport. |
| statement | AK Monument Grotesk | 800 | 102px | 0.82 | -0.03em, uppercase, features "calt" 0, "liga" 0, "ordn", "salt", "ss01", "ss02", "ss03" | Primary verbal statement after the emblem opening, section titles and centered conversion invitation. |
| manifesto-copy | AK Monument Grotesk | 800 | 52px | 0.9 | -0.02em | Large sentence-case explanatory statements; these are substantial visual blocks rather than ordinary body copy. |
| directory-title | AK Monument Grotesk | 700 | 32px | 30px | normal | Heading above the ruled directory. |
| footer-link | AK Monument Grotesk | 700 | 32px | 0.9 | normal | Bold internal, policy and social navigation at the ending. |
| directory-category | AK Monument Grotesk | 700 | 24px | 20px | normal | Small bold category names in the directory. |
| button | AK Monument Grotesk | 400 | 16px | 1 | normal | Compact pill action labels. |
| navigation | AK Monument Grotesk | 400 | 14px | 1 | normal | Bottom navigation rail. |
| directory-link | AK Monument Grotesk | 200 | 14px | 1.1 | normal | Lightweight compact directory lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling pages | editorial-display | AK Monument Grotesk | 800 | 152px | 0.82 | -0.03em, uppercase, features "calt" 0, "liga" 0, "ordn", "salt", "ss01", "ss02", "ss03" | Separated opening title words and monumental closing statement. |
| company storytelling pages | editorial-body | AK Monument Grotesk | 500 | 24px | 1 | -0.02em, features "kern" 0 | Dense narrative paragraphs in the narrower right column. |

**Notes:**

- Display capitals are compressed vertically at 0.82 line height; the 52px sentence-case statements relax to 0.9, not to conventional paragraph leading.
- The design has no recurring eyebrow tier. Hierarchy comes from scale, alignment and long pauses, not a small label above every heading.
- Use normal tracking for navigation and footer lists. Do not spread the monumental capitals out.
- The first screen contains graphic identity rather than a typographic headline; the statement recipe governs the verbal reveal that follows.

## Layout

**Density:** Theatrically airy at the section scale, deliberately tight within text blocks and footer lists.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Directory category inner padding. |
| 20px | Stage top/bottom inset and narrative paragraph separation. |
| 25px | Space after horizontal rules and before the giant ribbon. |
| 30px | Desktop side insets, showcase gutters and gap from conversion headline to action. |
| 40px | Gap from large supporting statement to its action. |
| 100px | Bottom padding of editorial narrative block. |
| 200px | Top and bottom breathing room around centered editorial mission. |
| 245px | Deep footer space beneath link groups. |
| 290px | Long pause between a support-band heading and its large explanatory sentence. |

### Containers and grids

- **page-stage**: max width 1440px · side padding 30px. Desktop page stage; content spans 1380px between narrow side insets, while major backgrounds and opening graphics bleed edge to edge.
- **showcase-track**: 3 columns · gap 30px. Horizontal track of 665px square tiles, showing two tiles and a clipped continuation rather than shrinking all items to fit.
- **statement-measure**: max width 1035px. Large sentence-case statements occupy about three quarters of the inner stage, aligned left.
- **directory**: 4 columns. Four compact categories around 160px wide cluster at the left of a full-width ruled container; unused space remains on the right.
- **footer-grid**: 12 columns. Internal links at the far left, policy links beside them and right-aligned social links at the opposite edge.
- **editorial-grid** (only for company storytelling pages): 20 columns. Broad left headline balanced against a 483px narrative column beginning beyond the midpoint; full-width cinematic video precedes it.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-pill | 90px |
|  | showcase-shell | 40px |
|  | showcase-asset | 30px |
| company storytelling pages | editorial-video | 10px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Opening and showcase default.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black with no shadow or decorative border. The opening field sits directly on this canvas.

**Transfer:** Use full-bleed monochrome stage changes to create drama.

#### White band · level 0

**Use:** Large support statement, conversion invitation and default footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** An abrupt inversion of the dark stage, not a gradient or softly tinted panel.

**Transfer:** Let the whole section change polarity instead of putting white cards on black.

#### Exhibit backing · level 1

**Use:** Showcase emblems.

**CSS:** `background: #131313; border-radius: 30px; overflow: hidden; box-shadow: none`

**Observed:** White art floats in the middle with substantial breathing room. One variant uses acid yellow-green; dimensional artifacts can use pure black.

**Transfer:** Treat backing as part of the graphic, without textual card chrome.

#### Acid exhibit · level 1

**Use:** A single high-energy interruption within the showcase.

**CSS:** `background: #d3de5d; border-radius: 30px`

**Observed:** The saturated fill occupies one square rather than spreading into the page.

**Transfer:** Reserve this surface for the strongest exhibit.

#### Ruled region

**Use:** Directory, footer and conversion boundaries.

**CSS:** `border-top: 1px solid #000000; padding-top: 25px`

**Observed:** Rules span the full inner width. Company-story endings reverse to white rules on black.

**Transfer:** Use simple hairlines to divide functional regions rather than boxes or elevated panels.

## Components

### Bottom navigation rail

**Use:** Persistent minimal global navigation.

**CSS:** `position: fixed; bottom: 0px; height: 50px; padding: 0px 30px; background: #000000; color: #ffffff; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — AK Monument Grotesk 400 · 14px/1

**Observed:** Text identity sits left and two small page links sit right; a thin horizontal rule runs above. The rail switches to black-on-white for light sections.

**Transfer:** Keep the global link set extremely short; retain the unusual bottom placement.

### Primary button

**Use:** Low-noise action underneath a major statement.

**CSS:** `background: #000000; color: #ffffff; border: 2px solid #000000; border-radius: 90px; padding: 0px 20px; height: 51px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — AK Monument Grotesk 400 · 16px/1

**Observed:** Text-only pill with width determined by the label; examples are 126px and 170px wide. It is much smaller than adjacent display text.

**States:** Declared: hover background-color #ffffff and color #000000; focus-visible and active are unspecified.

**Transfer:** Use one concise action, not a paired row of oversized sales buttons.

### Showcase tile

**Use:** A linked visual exhibit in the horizontal product track.

**CSS:** `width: 665px; height: 665px; border-radius: 40px; overflow: hidden; margin-right: 30px; position: relative`

**Observed:** Rounded outer link contains an independently rounded 30px asset layer. A centered mark is around 345px wide; no caption or description competes with the art.

**Transfer:** Show a custom product symbol, identity lockup or dimensional artifact, one per tile.

### Giant text ribbon

**Use:** Typographic anchor for the showcase.

**CSS:** `display: flex; white-space: nowrap; margin-top: 25px; color: #ffffff`

**Text style:** `ribbon` — AK Monument Grotesk 800 · 160px/0.82 · tracking -0.03em · uppercase

**Observed:** A single repeated phrase runs well outside the stage and is clipped at the edges; the right edge fades toward the recurring corner emblem.

**Transfer:** Choose a short category phrase that reads both as title and pattern.

### Directory heading

**Use:** Introduce the compact navigational catalogue at the end.

**CSS:** `color: #000000; margin: 0px`

**Text style:** `directory-title` — AK Monument Grotesk 700 · 32px/30px

**Observed:** Placed immediately above a full-width rule, larger than category labels but much smaller than the preceding conversion headline. Reverses to white on the company-story ending.

### Directory link

**Use:** Short links under catalogue categories.

**CSS:** `color: #000000; transition: opacity 0.4s cubic-bezier(0.19, 1, 0.22, 1)`

**Text style:** `directory-link` — AK Monument Grotesk 200 · 14px/1.1

**Observed:** Small lightweight text forms tight vertical lists beneath bold category names. Company-story variant uses white text.

**States:** Declared: hover opacity 0.5; focus-visible and active are unspecified.

### Footer link

**Use:** Internal, policy and social links in the final navigation region.

**CSS:** `color: #000000; transition: opacity 0.4s cubic-bezier(0.19, 1, 0.22, 1)`

**Text style:** `footer-link` — AK Monument Grotesk 700 · 32px/0.9

**Observed:** Heavy stacked links; social labels are right aligned while internal and policy groups are left aligned. Company-story variant reverses to white.

**States:** Declared: hover opacity 0.5; focus-visible and active are unspecified.

### Directory row

**Use:** Compact categorized navigation beneath the closing section.

**CSS:** `display: flex; flex-wrap: wrap; border-top: 1px solid #000000; padding-top: 25px`

**Text style:** `directory-category` — AK Monument Grotesk 700 · 24px/20px

**Observed:** Four small groups cluster at the left; each has 12px padding, a bold category name and a list of Directory links. The region sits inside 30px page padding.

**Transfer:** Group real destinations without stretching short lists across the entire width.

### Footer grid

**Use:** Final link region with a deliberately deep empty lower area.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); border-top: 1px solid #000000; padding-top: 25px; padding-bottom: 245px`

**Observed:** Footer link groups stay at the top of the region while the recurring corner emblem occupies the lower right above the Bottom navigation rail. The default ending is white; the company-story ending is black.

**Transfer:** Preserve the strong horizontal separation and disproportionate breathing room below the links.

## Imagery and graphics

### Undulating pixel field

**Use:** Signature identity stage in the opening.

**Observed:** White tiny rounded squares swell into broad diagonal waves over pure black. The largest squares are toward opposing corners, while the center stays relatively open for a solid white, soft-cornered emblem. No photography or colored lighting appears here.

**Transfer:** Create an original product emblem and use the same black-and-white field. A static SVG is the minimum acceptable version when interactive rendering is unavailable.

**Build:** Use a 1440px by 850px SVG field above the rail. Place white rounded rects on a roughly 25px lattice, subtly displacing rows into diagonal waves. Vary square widths from 1px to 24px using two broad sine-shaped envelopes running upper-left to lower-right; leave a dark central basin. Give rects about 2px corner radii. Layer an original white emblem around 355px wide and 390px high at center. Keep edges sharp and use no blur.

### Recurring corner emblem

**Use:** Identity punctuation across the scroll and beside the giant ribbon.

**Observed:** A solid rounded modular symbol occupies about 104px by 110px near the lower-right content edge, above the fixed rail. It flips black or white with the background.

**Transfer:** Reduce the opening emblem to a bold silhouette that remains recognizable at this smaller size.

**Build:** Construct an original SVG from connected rounded rectangular modules on a small orthogonal grid. Use a single black or white fill, no outline, and a compact near-square silhouette. Anchor it to the lower-right stage inset above the rail, allowing it to punctuate rather than obscure text.

### Artifact and emblem exhibits

**Use:** Main horizontal showcase.

**Observed:** A near-black rotating coin-like object has subtle metallic edge highlights and embossed details against black. Adjacent tiles hold crisp monochrome illustrated identity lockups, one on charcoal and one on acid yellow-green. Art occupies the center while tile backgrounds occupy most of the area.

**Transfer:** Combine a restrained dark material rendering of the product with flat original emblems. If 3D is unavailable, use a carefully lit silhouette or a simple embossed SVG symbol rather than stock photography.

### Cinematic story video

**Only for:** company storytelling pages

**Use:** Wide visual interlude between mission and narrative.

**Observed:** A 1380px by 776px video with 10px clipped corners. Visible material is a warm, cinematic animated character close-up with amber lighting, dark brown shadows and soft green and violet background lights.

**Transfer:** Use a tightly framed scene of the product's world or people, with warm directional lighting and shallow focus. Let media carry color while the surrounding editorial page stays monochrome.

### Icons

**Observed:** The editorial opening includes a very thin black downward arrow with a long shaft and open diagonal wings at the lower left. Actions and footer links otherwise rely on text rather than icon decoration.

**Transfer:** Use a simple open arrow for scroll direction, not a circular icon-button system. Keep the graphic emblem distinct from interface icons.

## Section recipes

How recurring sections are built.

### First screen: Emblem field opening

**Observed:** The first 900px is a full-bleed Black stage with the Undulating pixel field behind a large centered white emblem, around one quarter of the viewport width and nearly half its height. The field reaches all edges except the 50px Bottom navigation rail, which sits in front at the bottom. There is no headline, support copy or conversion button in this first screen; the only text is the tiny brand label and two navigation links. The verbal statement falls below the fold and reveals in three tightly stacked left-aligned lines using statement typography.

**Transfer:** For a different product, create a strong original geometric emblem and the prescribed SVG field; identity leads before explanation. Company storytelling instead opens on white with two separated 152px uppercase title words at top and bottom center, a thin downward arrow at lower left and the corner emblem at lower right.

**Avoid:** Do not turn this into a conventional top-navbar, headline-and-button split hero or overlay a sales paragraph across the central symbol.

**Text style:** `statement` — AK Monument Grotesk 800 · 102px/0.82 · tracking -0.03em · uppercase

### Manifesto reveal

**Observed:** The 102px uppercase statement begins at the 30px left inset and resolves into three compact lines. A later 52px sentence-case statement uses about 75% of the content width. The corner emblem and bottom rail remain the visual anchors as the palette inverts to white.

**Transfer:** Use a short positioning phrase followed elsewhere by a single substantial sentence explaining what the product enables.

**Text style:** `manifesto-copy` — AK Monument Grotesk 800 · 52px/0.9 · tracking -0.02em

### Horizontal exhibition

**Observed:** Showcase tiles occupy most of a sticky 900px stage. Two 665px squares and a clipped continuation move horizontally with 30px gutters. The Giant text ribbon sits 25px beneath the tiles, oversized and clipped; the corner emblem punctuates its right end.

**Transfer:** Use this for product worlds, capabilities or flagship examples without adding ordinary card descriptions.

**Text style:** `ribbon` — AK Monument Grotesk 800 · 160px/0.82 · tracking -0.03em · uppercase

### Support band

**Observed:** A White band places a 102px uppercase title at the upper left, with an important inline name underlined. After a 290px pause comes a 52px sentence-case supporting block and a Primary button 40px below.

**Transfer:** Use for an enabling technology, ecosystem partner or foundational product capability. The long gap separates declaration from explanation.

**Text style:** `statement` — AK Monument Grotesk 800 · 102px/0.82 · tracking -0.03em · uppercase

### Centered invitation

**Observed:** A 900px White band bounded by a thin top rule centers a two-word 102px invitation. A Primary button follows 30px below, leaving large, balanced areas of white above and below.

**Transfer:** Use a short invitation and a single next step, retaining the extreme scale contrast between heading and button.

**Text style:** `statement` — AK Monument Grotesk 800 · 102px/0.82 · tracking -0.03em · uppercase

### Ruled functional ending

**Observed:** The default white ending uses Directory heading above Directory row, then Footer grid with grouped bold links and a deep 245px lower pause. Social links sit at the far right. The corner emblem remains above the bottom rail. The company-story variant reverses directory, rules and footer to white-on-black while the bottom rail stays white.

**Transfer:** End with a compact real-destination catalogue and strong navigation structure, not a dense utility sitemap or another marketing card.

### Editorial story

**Only for:** company storytelling pages

**Observed:** A centered uppercase mission uses statement typography with 200px breathing room above and below. Cinematic story video spans the inner stage. Below it, a 52px left headline and a 483px right narrative column sit on a 20-column grid, with 24px body text and 20px paragraph gaps.

**Transfer:** Tell an origin or perspective through one strong premise and a focused narrative rather than a series of small feature cards.

**Text style:** `editorial-body` — AK Monument Grotesk 500 · 24px/1 · tracking -0.02em

### Monumental continuation

**Only for:** company storytelling pages

**Observed:** A full black 900px stage centers a white 152px uppercase continuation statement across two tightly packed lines. It leads directly into a black directory and footer, rather than returning to a light action panel.

**Transfer:** End a narrative with a short forward-looking declaration, keeping the dark polarity through the functional ending.

**Text style:** `editorial-display` — AK Monument Grotesk 800 · 152px/0.82 · tracking -0.03em · uppercase

## Page flow

**Storyline:** identity spectacle → concise positioning → world or product proof → explanation → invitation or forward-looking declaration → ruled navigation ending

### Flagship marketing landing page

1. **Identity hook** — Full-screen emblem in a monochrome pixel field with bottom navigation.
2. **Promise** — Three-line uppercase verbal reveal followed by large sentence-case explanation.
3. **Product proof** — Horizontal artifact and emblem exhibition over a giant repeated text ribbon.
4. **Capability explanation** — White support band with oversized title, large explanatory sentence and compact action.
5. **Closing call** — Centered short invitation and one pill action.
6. **Navigation ending** — White ruled catalogue followed by grouped bold links and corner identity mark.

**Transfer:** Keep the identity-led drama and scale contrasts; adapt the number and placement of proof and explanation blocks to the product.

### Company or origin storytelling

1. **Identity hook** — Separated oversized title words on white with a downward scroll arrow.
2. **Purpose** — Centered compressed uppercase mission.
3. **World demonstration** — Wide cinematic video.
4. **Narrative proof** — Left premise and narrow right narrative column.
5. **Continuation** — Monumental white-on-black forward-looking line.
6. **Navigation ending** — Black ruled catalogue and bold footer links.

**Transfer:** Use the light editorial variant for longer stories, retaining the black closing declaration and reversed ending rather than averaging it with the landing-page conversion section.

## Writing

Confident, culture-facing and declarative. It mixes institutional ambition with conversational origin details, speaking in concrete actions rather than technical specifications.

**Do not copy:** Do not reuse the brand names, logos, collection identities, artwork, proprietary claims, launch dates, membership counts or quoted origin story. Source examples illustrate rhythm only; write new claims grounded in the new product.

- **Addressing the reader:** Uses we and us for the organization, with little direct you-address. Product descriptions are often third person; invitations shift to inclusive language.
- **Rhythm:** Short two- or three-word declarations contrast with one long, forceful explanatory sentence. Editorial paragraphs are tightly packed but separated by clear pauses; contractions keep the tone human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning | An active participle plus the thing being shaped and its context. | 3–6 words | “Building culture onchain.” |
| Supporting statement | Move from tangible examples to a broad user benefit using parallel verbs. | 20–35 words | “From Bored Ape Yacht Club to Otherside, we turn imagination into products that millions can build on, play in, and own.” |
| Section declaration | Short collective claim with a named foundation. | 3–5 words | “WE RUN ON ApeCoin.” |
| Primary action | Plain verb phrase with no hype or elaborate promise. | 2–4 words | “Learn more”<br>“Partner with [Brand]” |
| Closing declaration | Brief inclusive invitation or unfinished forward momentum. | 2–5 words | “Join us”<br>“And we’re still building” |

**Words and phrasing to use:** build; imagination; play; own; community; storytelling; experiences; next chapter

**Avoid:** best-in-class; seamless solution; unlock your potential; revolutionary platform; feature-packed; limited-time offer

**Rules:**

- Lead with a cultural or experiential promise, then explain what people can actually do.
- Use parallel active verbs for benefit statements.
- Keep button labels understated even when adjacent typography is enormous.
- Use concrete origin details in narrative sections rather than generic mission filler.

## Do's and Don'ts

### Do

- Keep main uppercase statements at weight 800, 0.82 line height and -0.03em tracking.
- Use 30px desktop stage insets and 30px showcase gutters.
- Keep pill actions at 51px high with 16px labels.
- Maintain the contrast between 665px exhibits and 14px utility text.
- Separate functional ending regions with 1px rules.
- Retain the pixel field, giant ribbon and recurring emblem as identity devices.
- Use flat white bands for explanation and conversion after the dark spectacle.
- Keep narrative paragraphs at 24px with 20px separation in the editorial variant.

### Don't

- Do not replace the monochrome canvas with charcoal everywhere; #131313 belongs to exhibit backing.
- Do not make acid yellow-green the button color or a repeated background for every section.
- Do not add drop shadows or glass effects to the flat exhibition surfaces.
- Do not give the 665px showcase tiles the tiny 10px video radius.
- Do not inflate the 14px bottom navigation to match the 32px footer links.
- Do not loosen the display line height to 1.2; the stacked capitals should read as a compact mass.
- Do not force the four short directory groups to fill four equal quarters of the page.
- Do not shrink the large sentence-case support statement to conventional 16px body text.

## Motion and responsive

### Motion

**Observed:**

- The opening field and emblem change across scroll stages, and the positioning resolves into stacked lines.
- A sticky showcase shifts a horizontal track through oversized tiles; repeated title text travels beneath it.
- Directory and footer links declare opacity 0.4s cubic-bezier(0.19, 1, 0.22, 1) and hover opacity 0.5.
- Pill actions declare white background and black text on hover.
- Marquee and marquee-reverse keyframes are declared.

**Transfer:**

- Preserve the identity-to-language reveal and the horizontal exhibition as the characteristic movement vocabulary.
- When using a static implementation, keep the fully resolved statement, field, emblem and clipped ribbon composition instead of intermediate blank states.

**Unknown:**

- Pixel-field implementation, scroll mapping and animation timing are not fully specified.
- Marquee duration, exact emblem morph timing and focus-visible or active styling are unknown.

### Responsive

**Observed:**

- The desktop composition is a 1440px stage with 30px side padding; no width breakpoint rules are established.

**Transfer:**

- On narrower screens, retain the bottom rail and central emblem; reduce the pixel-field density rather than eliminating it.
- Keep the exhibit track horizontally browsable instead of squeezing its artwork into many columns.
- Stack the editorial premise above its narrative and wrap the compact directory categories as needed. These are adaptation recommendations.

**Unknown:**

- Mobile sizes, breakpoint thresholds, mobile stage heights and touch behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
