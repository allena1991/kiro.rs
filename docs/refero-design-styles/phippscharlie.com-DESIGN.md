# Charlie Phipps — oversized type, exposed work

## Overview

An editorial portfolio language that pairs enormous, regular-weight grotesk lettering with small, matter-of-fact annotations. A dark photographic opening gives way to a predominantly white, exceptionally spacious gallery, with color carried by the work rather than the interface. It suits design-led products and services whose visual proof can carry a substantial part of the story; a dark text-led variant feels more personal and reflective.

### Essentials

- Identity behaves like a moving strip rather than a centered slogan: a single-line 162px regular grotesk headline, 0.9 line height and -2px tracking extends beyond both edges over a full-screen image.
- The opening is a photographic editorial cover: a 900px-tall dark image stage, a 30% charcoal overlay, a small left annotation, an offset 19.4px supporting paragraph and plain links along the bottom.
- Actions remain typography, not filled buttons: 19.4px or 20.7px text links with directional arrows, no enclosing shape, and active opacity 0.7.
- Color belongs to the exhibited work: the interface is white, charcoal and gray throughout, with vivid photographs and campaign artwork occupying entire image chapters rather than coloring navigation or labels.
- Proof alternates between postage-stamp previews and room-filling imagery: 578×363px previews sit in broad white fields before 1440px-wide, roughly 900px-high demonstrations; use a real product artifact or an original typographic specimen if photography is unavailable.
- The grid has a deliberate left-hand annotation lane: 25.9px outer insets, roughly one quarter of the width for labels, and 63.5px/1 descriptive headings beginning in the remaining three quarters.
- The close becomes a second typographic event: a 154.8px/1 uppercase action strip clipped at the edges, bracketed by 1px gray rules and followed by a small operational footer. Carry this monumental action device into every landing page, even when the available action is simply a conversation.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#101011` | `--color-dark` | background, surface | Opening fallback and dark editorial canvas; also the source hue of the 30% image veil. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial ink | `#191919` | `--color-ink` | text, action | Visible result of 90% black over white for the large descriptive headings and closing action strip. |
| Annotation black | `#000000` | `--color-black` | text | Small labels and closing support copy on white. |
| Index ink | `#131313` | `--color-index-ink` | text, action | Large terminal navigation and direction arrows on white. |
| Muted white | `#888888` | `--color-muted-light` | text, link | Visible result of 50% white over charcoal for secondary links; over photography it remains translucent. |
| Navigation gray | `#8e8e8e` | `--color-nav` | text, link | Persistent navigation links across the gallery and opening. |
| White-canvas rule | `#e5e5e5` | `--color-rule-light` | border | Visible 20% mid-gray separator over white. |
| Soft white | `#e7e7e7` | `--color-display-light` | text | Visible result of 90% white over charcoal for the opening strip and dark-page records; over photography the tone follows the image beneath. |
| Device-stage gray | `#ededed` | `--color-stage` | surface, background | Full-width neutral backing for a device demonstration. |
| Gallery white | `#ffffff` | `--color-canvas` | background, text, border | Main gallery canvas, bright text over imagery, and underlines on dark pages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark editorial sections | Charcoal-canvas rule | `#262627` | `--color-rule-dark` | border | Visible 20% mid-gray separator over charcoal. |
| dark profile or company-story pages | Warm editorial white | `#ede9e3` | `--color-cream` | text | Large personal statements and chapter headings. |
| case-study covers | Photographic title white | `#f3f2f1` | `--color-case-light` | text | Project title and parenthesized date over the case-study cover. |

## Typography

- **Helvetica Neue** — All marketing text, labels, navigation and display lettering. Neutral neo-grotesk with regular strokes and compact spacing; the hierarchy comes from scale rather than weight. If unavailable, use **Arial**. Use regular and italic; preserve tight display tracking. Font stack: "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Helvetica Neue | 400 | 162px | 0.9 | -2px | Single-line opening identity marquee. |
| closing-strip | Helvetica Neue | 400 | 154.8px | 1 | -0.0097em | Uppercase monumental closing links. |
| heading | Helvetica Neue | 400 | 63.5px | 1 | -0.0236em | Gallery introduction and large descriptive project paragraphs. |
| navigation | Helvetica Neue | 400 | 20.7px | 1.2 | normal | Header links and small operational footer. |
| body | Helvetica Neue | 400 | 19.4px | 1.2 | -0.01em | Opening support paragraph and image-stage links. |
| support | Helvetica Neue | 400 | 18.1px | 1.2 | normal | Closing invitation and navigation-support sentences. |
| metadata | Helvetica Neue | 400 | 16.8px | 1.2 | -0.012em | Project labels, role lists, counts and gallery eyebrows. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study covers | case-title | Helvetica Neue | 400 | 162px | 0.9 | -0.0185em | Case title and separately anchored parenthesized year. |
| case-study endings | index-display | Helvetica Neue | 400 | 162px | 1 | -0.0185em | Two opposing destination links at the end of a visual case study. |
| dark profile or company-story pages | profile-heading | Helvetica Neue | 400 | 86.8px | 1 | -0.023em | Chapter names above structured records and contact details. |
| dark profile or company-story pages | profile-statement | Helvetica Neue | 400 | 68.7px | 1 | -0.0218em | Expansive personal or company statement. |
| dark profile or company-story pages | profile-italic | Helvetica Neue | 400 italic | 68.7px | 1 | -0.0218em | Parenthesized name and concluding discipline phrase within the statement. |
| dark profile or company-story pages | profile-prose | Helvetica Neue | 400 | 45.4px | 1.05 | -0.0044em | Long editorial paragraphs with offset first lines. |
| dark profile or company-story pages | record | Helvetica Neue | 400 | 20.7px | 1.3 | normal | Experience, recognition and contact rows. |
| dark profile or company-story pages | profile-label | Helvetica Neue | 400 | 15.6px | 1.1 | normal | Compact uppercase marginal labels and contact-channel names. |

**Notes:**

- Use weight 400 throughout; do not simulate hierarchy by introducing semibold or bold headings.
- Large descriptive paragraphs use display typography rather than conventional body sizing. Small metadata remains close to default grotesk spacing while display lettering tightens.
- Italic emphasis belongs to the dark editorial variant, not the default photographic cover. Uppercase is concentrated in metadata and the closing action strip.

## Layout

**Density:** Airy overall, with compact annotations inside exceptionally open image and text chapters. Spacing follows the composition rather than a universal modular grid.

### Spacing

| Value | Use |
| --- | --- |
| 6.5px | Inner padding of small grid cells and record rows. |
| 13px | Nested gallery cell padding. |
| 25.9px | Main horizontal page inset and recurring content padding. |
| 51.8px | Extra lower padding around closing content. |
| 187px | Breathing room above and below the gallery introduction. |
| 210px | Separation between a small project preview and its large descriptive text. |
| 249px | Broad top field before a small project preview. |

### Containers and grids

- **edge-to-edge canvas**: side padding 25.9px. No fixed maximum content width; content spans the viewport minus equal small side insets. Media chapters can escape those insets entirely.
- **annotation and statement**: 4 columns · gap 0px. One quarter-width lane for labels beside a three-quarter-width statement. At desktop the inner field is 1388px wide; the statement lane is 1041px.
- **paired gallery** (only for visual case studies): 2 columns · gap 25.9px. Half-width image compositions can occupy only one side of a spread, alternating sides between chapters. Preserve the empty side as intentional breathing room rather than filling it with cards.
- **record columns** (only for dark profile or company-story pages): 4 columns · gap 0px. Empty first quarter, followed by role or institution, detail, and a narrow right-aligned date field.

## Corner radius

| Element | Radius |
| --- | --- |
| Gallery media and page surfaces | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Flat page surfaces | `none` | No site-level elevation; physical object shadows remain part of the imagery. |

### Surfaces

#### Gallery canvas · level 0

**Use:** Default surface after the opening.

**CSS:** `background: #ffffff; color: #191919`

**Observed:** An uninterrupted white page, not a stack of raised cards.

**Transfer:** Separate chapters with space, media and fine rules rather than card containers.

#### Image veil · level 1

**Use:** Readable opening photograph.

**CSS:** `background: rgba(16, 16, 17, 0.3); position: absolute; inset: 0px`

**Observed:** A dark translucent layer sits between the full-bleed architectural image and the type.

**Transfer:** Keep the image legible as material and structure; do not reduce it to an indistinct black field.

#### Device demonstration stage · level 0

**Use:** A full-width product demonstration chapter.

**CSS:** `background: #ededed`

**Observed:** A black landscape tablet is centered with generous space around it. Its rounded hardware and soft physical shadow belong to the pictured object, not to a site card.

**Transfer:** Place a single accurate device or product artifact on an even neutral field; keep the website surface itself flat.

#### Hairline divider · level 0

**Use:** Quiet boundaries across both light and dark compositions.

**CSS:** `height: 1px; background: rgba(127, 127, 127, 0.2); border: 0px`

**Observed:** Runs nearly the full inset content width, including around the closing strip and between editorial records.

**Transfer:** Reuse the same translucent gray so it naturally adapts to both canvases.

#### Dark editorial canvas · level 0

**Only for:** dark profile or company-story pages

**Use:** Opening fallback and extended text-led variant.

**CSS:** `background: #101011; color: #ede9e3`

**Observed:** Flat charcoal without gradients, glow or ornamental texture.

**Transfer:** Use warm light text for major prose and translucent white for supporting records.

## Components

### Fixed navigation

**Use:** Persistent orientation without a heavy navigation bar.

**CSS:** `position: fixed; z-index: 4; color: #8e8e8e; padding: 19.4px 25.9px 6.5px; background: transparent`

**Text style:** `navigation` — Helvetica Neue 400 · 20.7px/1.2

**Observed:** Identity is left aligned, the index starts at the second grid lane, and the profile link sits at the far right. The header is about 51px high in the default treatment. A small filled dot marks the active destination in editorial and case-study variants.

**States:** Declared: hover color #c1c1c1 on default navigation links; focus-visible unknown; active opacity 0.7.

**Transfer:** Use a short identity, an overview destination and a company-story destination; preserve the dispersed alignment.

### Image stage link

**Use:** Opening actions and external destinations.

**CSS:** `color: rgba(255, 255, 255, 0.5); padding-bottom: 1.9px; background: transparent`

**Text style:** `body` — Helvetica Neue 400 · 19.4px/1.2 · tracking -0.01em

**Observed:** Plain inline text with a small northeast arrow for external links. Social destinations cluster in the second lane while direct contact is right aligned.

**States:** Declared: hover color #ffffff; focus-visible unknown; active opacity 0.7.

**Transfer:** Choose meaningful destinations rather than introducing a filled primary button.

### Marginal metadata

**Use:** Numbering, discipline and context beside large content.

**CSS:** `color: #000000`

**Text style:** `metadata` — Helvetica Neue 400 · 16.8px/1.2 · tracking -0.012em

**Observed:** Compact stacked labels pair an uppercase category with a count, year or short role list. They occupy the narrow left lane, not a badge.

**Transfer:** Annotate an evidence chapter with its category, sequence or scope.

### Project statement

**Use:** Explain the value and intent of a visual proof chapter.

**CSS:** `color: rgba(0, 0, 0, 0.9); margin: 0px`

**Text style:** `heading` — Helvetica Neue 400 · 63.5px/1 · tracking -0.0236em

**Observed:** A substantial paragraph occupies the right three quarters beside the role list. A large right-pointing arrow ends the paragraph on its own line and provides the destination.

**Transfer:** Write one clear outcome followed by a short explanation; treat the whole block as editorial content, not a small card blurb.

### Preview image

**Use:** A restrained first glimpse before a large demonstration.

**CSS:** `width: 578px; height: 363px; margin-bottom: 8.4px; object-fit: fill`

**Observed:** A rectangular image sits alone within a much larger white field. Other previews are as small as 233×187px or combine two differently sized images; there is no shared card shell.

**Transfer:** Retain each asset's intended aspect ratio rather than stretching arbitrary replacement artwork; the stated dimensions describe the default preview.

### Closing action strip

**Use:** Make the main contact or conversion destinations monumental.

**CSS:** `color: rgba(0, 0, 0, 0.9); padding-bottom: 15.5px; white-space: nowrap`

**Text style:** `closing-strip` — Helvetica Neue 400 · 154.8px/1 · tracking -0.0097em

**Observed:** Several uppercase destinations repeat along a horizontally clipped strip, with substantial air above and below and fine rules bounding the larger zone.

**States:** Declared: hover color rgba(0, 0, 0, 0.3); focus-visible unknown; active opacity 0.7.

**Transfer:** Use short conversion verbs or channel names and repeat the track seamlessly. Preserve a readable complete destination within the sequence.

### Editorial record row

**Only for:** dark profile or company-story pages

**Use:** Structured experience, credentials or chronological proof.

**CSS:** `display: flex; flex-wrap: wrap; align-items: flex-start; padding: 6.5px`

**Text style:** `record` — Helvetica Neue 400 · 20.7px/1.3

**Observed:** Aligned text columns begin after an empty first quarter. Hairline dividers span the whole field, and dates share a right-side column; rows have much more separation than their compact text requires.

**Transfer:** Use for certifications, milestones or service history instead of a boxed logo grid.

### Underlined editorial link

**Only for:** dark profile or company-story pages

**Use:** Credential references and personal contact links.

**CSS:** `color: rgba(255, 255, 255, 0.9); border-bottom: 1px solid #ffffff`

**Text style:** `record` — Helvetica Neue 400 · 20.7px/1.3

**Observed:** A thin text-length underline distinguishes links from adjacent record text. Contact rows place a bent directional arrow immediately before the link and a small channel label above.

**States:** Declared: hover color rgba(255, 255, 255, 0.5) and border-bottom 0px solid #ffffff; focus-visible unknown; active opacity 0.7.

### Terminal index links

**Only for:** case-study endings

**Use:** Close a visual case study with two clear routes onward.

**CSS:** `color: #131313`

**Text style:** `index-display` — Helvetica Neue 400 · 162px/1 · tracking -0.0185em

**Observed:** An information destination sits at the left, with a parenthesized index destination anchored right. Both are oversized and sit above the last divider and small footer.

**States:** Declared: hover color #a5a5a5 and border-bottom 0px solid #ffffff; focus-visible unknown; active opacity 0.7.

**Transfer:** Pair a detail or contact route with the route back to the collection.

## Imagery and graphics

### Dark architectural cover

**Use:** The default landing-page opening image.

**Observed:** A close, high-contrast view of angular folded metal and brick architecture, nearly monochrome and darkened. Diagonals and broad charcoal planes fill the entire first screen beneath the typography; there is no separate product card.

**Transfer:** Use tightly framed product material, industrial detail, workspace architecture or an original physical object with strong diagonals. If photography is unavailable, create a credible angular material study rather than a generic gradient.

**Build:** Minimum version: layer several large irregular SVG polygons in charcoal tones over a brick or fine-grain photographic texture. Let diagonal folds cross the center and lower edge, add subtle light-to-dark shading within each plane, desaturate the composition, and place the 30% charcoal Image veil over it. Keep light text above all image layers.

### Artifact demonstrations

**Use:** Large proof chapters and small previews throughout the gallery.

**Observed:** Realistic tablets, phones, laptops, printed campaigns and outdoor installations show design in use. Treatments range from a frontal black tablet on a pale gray field to a laptop photographed obliquely in textured daylight. Full-width photographs are allowed to bleed past the viewport edges; smaller previews retain rectangular edges.

**Transfer:** Show actual work at convincing scale and in plausible use. When there is no physical product, use a well-composed interface demonstration or original typographic artifact, with neutral backing and natural light rather than decorative floating cards.

### Campaign gallery spreads

**Only for:** visual campaign case studies

**Use:** Detailed documentation of one visual system across formats.

**Observed:** Full-width environmental advertising alternates with half-width poster layouts and deliberately empty opposing columns. The artwork contains saturated navy, coral, pink, mint and purple fields, solid and outlined condensed lettering, and inset photographs of people outdoors. Pale lavender or cream presentation boards are inside the artwork, while the surrounding site remains white.

**Transfer:** Document a new product's own visual language across multiple real formats. Carry color inside the artwork instead of importing these campaign hues into the site's controls. A minimum gallery can pair an original poster specimen with a believable in-context photograph.

### Small monochrome portrait

**Only for:** dark profile or company-story pages

**Use:** A human annotation beneath the opening statement.

**Observed:** A small black-and-white head-and-shoulders portrait, about 139×192px, sits in the second grid lane beside a compact biographical list. It is subordinate to the oversized prose and has no decorative frame.

**Transfer:** Use an authentic founder, maker or team-detail portrait; retain the small scale and tonal relationship to the charcoal page.

### Icons

**Observed:** Sparse typographic direction marks: large simple right arrows at the ends of project paragraphs, small northeast arrows on external links, a down arrow at the opening's lower left, bent arrows in dark contact rows, and a filled dot for the active navigation item. Icons inherit the nearby text color rather than using accent fills.

**Transfer:** Use plain SVG or text arrows with a single consistent stroke; keep their size tied to the text role. Do not substitute illustrated icon tiles or a broad feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Photographic marquee cover

**Observed:** A full-viewport photograph forms the back layer, the Image veil darkens it, and type and fine rules sit above. Fixed navigation occupies the top edge. Directly below it, the 162px display line spans far more than the viewport and is clipped on both sides. Around the vertical middle, a hairline aligns a small left-hand annotation with a compact 19.4px support paragraph beginning at the second quarter of the grid; its first line is indented within the text block. The paragraph takes roughly one third of the page width. At the bottom, a down arrow sits left, Image stage links occupy the second lane, and contact aligns right. All of these are visible within the first 900px; the white gallery introduction starts below the cover.

**Transfer:** Use a concise identity-and-purpose line long enough to form a continuous typographic strip, one short supporting paragraph and a convincing dark material image. Without a photograph, use the Dark architectural cover build. A case study instead uses a static 162px title at upper left and a parenthesized year at lower right over a full-bleed project image. A company-story page opens directly with large warm-white prose, italic inserts and a small portrait on charcoal.

**Avoid:** Do not turn this into a centered SaaS hero with a boxed screenshot, stacked filled buttons or a short title floating in unused space.

**Text style:** `display` — Helvetica Neue 400 · 162px/0.9 · tracking -2px

### Offset gallery introduction

**Observed:** Gallery canvas with 187px of air above and below the text group. Marginal metadata occupies the left quarter beside an initial heading in the right three quarters. A continuing 63.5px descriptive line then spans the full field, producing an editorial hanging start rather than a rigid card grid.

**Transfer:** Introduce the collection, capabilities or product evidence with a short category line and one large explanatory sentence.

**Text style:** `heading` — Helvetica Neue 400 · 63.5px/1 · tracking -0.0236em

### Preview and editorial explanation

**Observed:** A Preview image sits within a broad open field, often preceded by about 249px of white space. Metadata identifies the proof below it. After roughly 210px, the Project statement occupies the right three quarters, balanced by a role list on the left. A large inline arrow leads to the full story.

**Transfer:** Make a small artifact tease and a large outcome-led explanation work together; vary the preview's alignment while preserving the annotation lane.

**Text style:** `heading` — Helvetica Neue 400 · 63.5px/1 · tracking -0.0236em

### Immersive demonstration chapter

**Observed:** A roughly 900px-high media stage follows the editorial explanation. Media may fill the viewport with environmental photography or use the Device demonstration stage for a centered artifact. No caption card or tinted UI wrapper interrupts the composition.

**Transfer:** Give one visual proof enough screen area to be inspected. For a service, use a concrete deliverable or documented result instead of stock illustration.

### Monumental closing invitation

**Observed:** A small 18.1px contact invitation and two secondary routes sit in adjacent middle columns above a Hairline divider. The Closing action strip occupies a spacious band below, with partially visible repeated destinations at the edges. Another divider separates it from a small footer with ownership on the left, professional context in the second lane, and a live date and clock aligned right.

**Transfer:** End with a direct, low-pressure invitation, then enlarge the actual conversion destinations into the main visual object. Keep operational information small and aligned rather than adding a multi-column sitemap.

**Text style:** `closing-strip` — Helvetica Neue 400 · 154.8px/1 · tracking -0.0097em

### Dark editorial chapters

**Only for:** dark profile or company-story pages

**Observed:** Warm prose sits on the Dark editorial canvas. The 68.7px opening statement mixes regular and italic phrases; later 45.4px prose begins after an inset marginal label and continues across the page. Chapter names use 86.8px type in the second lane. Editorial record rows and Underlined editorial links supply detailed proof without changing the flat surface.

**Transfer:** Use this variant for a human, company or craft narrative, allowing the writing itself to become the visual centerpiece.

**Text style:** `profile-heading` — Helvetica Neue 400 · 86.8px/1 · tracking -0.023em

### Editorial contact ending

**Only for:** dark profile or company-story pages

**Observed:** A left annotation accompanies the 86.8px contact heading in the second lane. A ruled contact area below places small uppercase channel labels above bent-arrow Underlined editorial links. The remaining space stays charcoal, with ownership and context at bottom left and a date and clock at bottom right.

**Transfer:** Use a compact human contact directory for the dark editorial variant rather than the landing-page action marquee.

**Text style:** `profile-heading` — Helvetica Neue 400 · 86.8px/1 · tracking -0.023em

### Case study terminal navigation

**Only for:** case-study endings

**Observed:** After the image sequence, a small project name and year are followed by a broad white interval, a rule and a compact category summary. Terminal index links then span the final content row. A final hairline introduces the small footer, whose right side contains external contact links rather than a clock.

**Transfer:** Return readers from immersive evidence to clear context and two next destinations.

**Text style:** `index-display` — Helvetica Neue 400 · 162px/1 · tracking -0.0185em

## Page flow

**Storyline:** identity and promise → curated visual proof → editorial explanation → immersive demonstration → direct contact or onward navigation

### Introduce a visual practice or design-led product and make its proof easy to explore

1. **Identity and promise** — Dark photographic cover, oversized marquee identity, compact offset support and discreet external links.
2. **Collection framing** — White editorial introduction with small counted label and large hanging text.
3. **Capability proof** — Repeated small previews, annotated outcome paragraphs and full-screen demonstrations.
4. **Closing call** — Small conversational invitation, monumental action strip and operational footer.

**Transfer:** Replace the projects with product outcomes, applications or capabilities; keep the contrast between tiny context and enormous proof without requiring a fixed number of chapters.

### Give a practice, founder or company a more personal and credentialed narrative

1. **Point of view** — Warm-white statement with italic identity and discipline phrases on charcoal, followed by a small portrait and metadata.
2. **Context and approach** — Large prose with inset opening lines and tiny parenthetical marginal labels.
3. **Credential proof** — Oversized chapter names over ruled experience and recognition rows.
4. **Contact** — Large contact heading, underlined channel links and a sparse dark footer.

**Transfer:** Use the text-led dark variant when people, methods and track record are the primary evidence.

### Let one body of work unfold through its applications rather than through dense explanation

1. **Project identity** — Full-screen environmental image with a static large title, categories, sequence number and separately anchored year.
2. **System demonstration** — A long white gallery alternates large contextual photographs with half-width campaign boards and digital examples.
3. **Context recap** — Small project name and category metadata reappear after the visual sequence.
4. **Onward navigation** — Opposing monumental information and index destinations above the footer.

**Transfer:** Use this for an in-depth product launch or case study, adapting the gallery's format changes to real evidence rather than filling every slot with a mockup.

## Writing

Confident and design-literate but conversational. The tone explains intent and craft through concrete descriptions, with a personal invitation rather than a hard sell.

**Do not copy:** Do not reuse Charlie Phipps's name, portfolio years, employers, client names, campaign slogans, social handles, project claims, experience totals, awards or artwork. Replace them with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular for a personal practice; a company can use first-person plural with the same directness. Address the reader sparingly and naturally in the closing invitation.
- **Rhythm:** Short functional labels frame long, flowing editorial sentences. Large descriptive paragraphs can run several lines; actions remain one to three words or a channel name. Parentheses, date ranges, colons and copyright marks contribute an archival tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | Name or product, location or context, discipline and edition expressed as a continuous identity line. | 8–12 words plus context markers | “[Brand] (LDN) Graphic Designer: Portfolio ©2022.” |
| Supporting paragraph | State what is made, for whom and with what emphasis; use concrete craft language rather than a string of superlatives. | 25–40 words | “Graphic Designer based in London, crafting details to create impact and better connect brands to their audiences. With a focus on digital experiences, identities and design direction.” |
| Section label | A terse category, count or chronological marker. | 1–5 words plus markers | “EXPLORE (04) Case Studies”<br>“PROFILE 2016–2022” |
| Project explanation | Lead with the opportunity or outcome, then describe how the experience embodies it. | 30–55 words | “A new home for a first-of-its-kind in the art world. Creating a digital experience that felt like an extension of the physical space, as well as the brand ethos. Modern, sophisticated and forward thinking.” |
| Primary action | Use the destination itself, or a brief directional word with an arrow. | 1–3 words | “EMAIL”<br>“Info” |
| Closing invitation | A calm, human offer to continue the conversation. | 10–16 words | “Feel free to drop me a message if you have any questions.” |

**Words and phrasing to use:** crafting details; experience; identity; direction; connect; curiosity; impact; selected; explore

**Avoid:** revolutionary; game-changing; 10x; unlock your potential; hurry; limited-time offer

**Rules:**

- Let the visual evidence substantiate the claims; describe the work's purpose instead of adding unsupported performance language.
- Use labels as editorial annotations rather than promotional badges.
- Keep the final invitation personal and low pressure.
- Use parenthetical dates and counts only when they add genuine context.

## Do's and Don'ts

### Do

- Keep all marketing typography at weight 400, including the 162px opening line.
- Preserve the 25.9px outer inset and the one-quarter annotation lane on wide layouts.
- Pair the 63.5px descriptive text with 16.8px metadata rather than adding intermediate bold headings.
- Let a single visual proof occupy roughly 900px of vertical stage space.
- Use 1px translucent gray rules to organize large open fields.
- Make the closing conversion visible at 154.8px rather than burying it in a conventional footer.
- Keep colorful work rectangular and unframed; retain the white interface around it.
- Use warm #ede9e3 text only for the dark editorial narrative variant.

### Don't

- Do not introduce pill buttons or rounded marketing cards; the action language is unboxed text.
- Do not add interface accent colors to the monochrome navigation simply because the artwork is colorful.
- Do not convert the left annotation lane into a permanent sidebar panel with its own fill.
- Do not put drop shadows on website sections; shadows belong only to pictured physical artifacts.
- Do not shrink every large descriptive paragraph into ordinary 18px body copy.
- Do not fill every empty half-spread with explanatory text; asymmetry is part of the gallery rhythm.
- Do not use condensed campaign lettering as the main site font; the surrounding typography remains Helvetica Neue.
- Do not give every image identical framing or scale; the contrast between small previews and immersive demonstrations matters.

## Motion and responsive

### Motion

**Observed:**

- The opening identity and closing action destinations occupy repeated, translated marquee tracks clipped at the horizontal edges.
- Links declare active opacity 0.7; default navigation lightens on hover, while light text links over the opening brighten to white.
- No component-specific transition duration is established.

**Transfer:**

- Keep marquee tracks continuous with duplicated text and preserve readable, actionable destinations within the closing track.
- Retain the photographic stage as a stable backing while typography provides the horizontal movement.

**Unknown:**

- Marquee speed, direction over time, timing curves and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The wide layout uses viewport-spanning content rather than a fixed maximum-width container.

**Transfer:**

- On narrow screens, preserve the cover's image, huge typographic strip and bottom text-link character; allow support copy to use more width.
- Stack annotations above their descriptive paragraphs when the quarter-width lane becomes too narrow.
- Retain alternating media scale and intentional pauses, but let half-width case-study artwork expand to the available width.

**Unknown:**

- Mobile type sizes, breakpoint thresholds, navigation changes and exact narrow-screen section heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
