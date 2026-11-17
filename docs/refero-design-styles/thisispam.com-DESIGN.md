# Pam — condensed type, expansive images

## Overview

An image-led editorial style with the confidence of a design studio and the intimacy of a printed catalogue. Condensed, emphatic grotesk headlines sit against tiny literary serif text, white space, butter yellow and near-black brown. Natural-light photography, tactile objects and interfaces shown in real settings carry most of the expression; the surrounding layout remains sparse and sharply rectangular.

### Essentials

- Headlines behave like compact poster blocks rather than giant billboards: condensed bold capitals at 48px/0.9 with -0.02em tracking, paired with 14px/1.5 serif prose.
- The default opening is a three-image contact sheet before the promise: three 448px-wide media panels with 24px gutters, a two-line left-aligned headline underneath and an almost empty right half.
- Navigation and conversion controls are deliberately small and unboxed: a fixed 288×44px logo/menu strip, a 21×10px two-bar menu icon, and 11px condensed uppercase contact actions without pill backgrounds.
- Color belongs to editorial punctuation, not every module: the majority of the canvas is white, a full-width butter-yellow proof field provides one strong interruption, and the closing field is brown-black with butter-yellow type.
- Images read as physical pages: square corners, edge-to-edge portrait pairs at 720×900px, white serif caption strips, and screens embedded in hands, furniture or printed objects. Use tactile product-in-context still lifes when lifestyle photography is unavailable.
- A dotted rule and an enlarged closing emblem are recurring signatures: dots repeat every 9px across a 2px band; the final dark field ends with a centered flat yellow graphic about 400px wide. Create an original simple emblem for the new product, even when no supplied brand illustration exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#fff3b8` | `--color-butter` | surface, text, accent | Proof band and floating navigation backing; inverse text and emblem in the dark closing field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link, action, accent | Text and small graphic marks on light backgrounds. |
| Brown black | `#1b1512` | `--color-dark` | background, border | Closing field, contact-panel backing and FAQ rules. |
| White paper | `#ffffff` | `--color-canvas` | background, text | Default page canvas and project-title text over photographs. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| service-page contact panels | Warm stone text | `#eae5e3` | `--color-stone-text` | text, action | Softer inverse text in the dark half of the contact-and-questions composition. |

## Typography

- **TeX Gyre Heros Cn** — Headlines, project names and compact uppercase labels. Narrow neo-grotesk, heavy and workmanlike; closed-up lines form sturdy rectangular blocks. If unavailable, use **Roboto Condensed**. Use 700 and preserve the narrow measure and -0.02em tracking. Font stack: "TeX Gyre Heros Cn", "Roboto Condensed", "Arial Narrow", sans-serif.
- **TeX Gyre Termes** — Body prose, captions, numbers, directories and footer links. Times-like editorial serif with a relatively delicate texture; italic provides the secondary caption voice. Font stack: "TeX Gyre Termes", Times, "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | TeX Gyre Heros Cn | 700 | 48px | 0.9 | -0.02em, uppercase | Default opening promise, proof heading, geographic statement and closing manifesto. |
| project-title | TeX Gyre Heros Cn | 700 | 32px | 0.9 | -0.02em, uppercase | Centered project names over large photographs; also numbered proof statements. |
| body | TeX Gyre Termes | 400 | 14px | 1.5 | normal | General explanatory paragraphs and normal caption text. |
| directory | TeX Gyre Termes | 500 | 14px | 1.5 | normal | Small lead-ins, evidence labels, statistics and names in directories. |
| caption-italic | TeX Gyre Termes | 400 italic | 14px | 1.5 | normal | Category and platform suffixes in project captions. |
| footer-link | TeX Gyre Termes | 400 | 14px | 2 | normal | Footer navigation, language choices and social links. |
| micro-label | TeX Gyre Heros Cn | 700 | 11px | 0.9 | -0.02em, uppercase | Footer contact labels, text-only calls to action and collection filters. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| service landing pages | service-display | TeX Gyre Heros Cn | 700 | 60px | 0.88 | -0.02em, uppercase | Service promise, chapter heading and contact-panel headline. |
| service-page question panels | question | TeX Gyre Heros Cn | 700 | 24px | 0.9 | -0.02em, uppercase | Full-width accordion question controls. |
| service landing pages | service-body | TeX Gyre Termes | 400 | 14px | 1.3 | normal | Compact service explanations, usually limited to a 440px measure. |

**Notes:**

- Keep the contrast between very small serif text and dense condensed capitals. Do not unify both into one sans-serif system.
- The headline family retains -0.02em tracking from 11px labels through 60px headings; body text uses normal tracking.
- The default headline is 48px. The larger 60px treatment belongs to service-specific promises and explanatory chapters, not every ordinary section.
- Line breaks make compact left-aligned blocks. Italic is reserved for small metadata rather than display emphasis.

## Layout

**Density:** Airy at section scale and compact at text scale: long pauses surround small prose, while photographs often meet with no gutter.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight directory row gaps and adjacent caption fragments. |
| 12px | Caption vertical padding and filter spacing. |
| 24px | Page inset, principal grid gutter, panel padding and image-to-headline gap. |
| 28px | Service heading-to-copy gap. |
| 32px | Directory heading-to-list separation. |
| 48px | Number-to-proof-statement separation. |
| 80px | Separation between top content and bottom-aligned content in service contact panels. |
| 96px | Default opening top inset and pauses before footer navigation and closing artwork. |
| 160px | Wide pause before the mixed-width capability media row. |

### Containers and grids

- **page-inset**: side padding 24px. Fluid, almost full-window composition. At 1440px the inset content spans 1392px; avoid a narrow centered master container.
- **opening-triptych**: 3 columns · gap 24px. Three equal media columns, each 448px wide at the desktop reference width.
- **editorial-halves**: 2 columns · gap 24px. 684px-wide inset halves, one carrying text and the other a tall photograph.
- **portrait-pair**: 2 columns · gap 0px · side padding 0px. Full-bleed paired projects with 720px-wide portrait media.
- **proof-quarters**: 4 columns · gap 24px. Four 330px-wide numbered proof statements.
- **footer-grid**: 12 columns · gap 24px · side padding 24px. Closing manifesto spans six columns; three contact blocks occupy two columns each.
- **reading-measure** (only for service landing pages): max width 440px. Short service explanations within a much wider half-page column.

## Corner radius

| Element | Radius |
| --- | --- |
| editorial-panels | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default continuous page field.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Images and text sit directly on the page rather than inside raised cards.

**Transfer:** Use whitespace and alignment to group information.

#### Butter proof field · level 0

**Use:** Large proof directories and compact floating navigation backing.

**CSS:** `background: #fff3b8; color: #000000; border-radius: 0px`

**Observed:** A flat uninterrupted color field, without texture, gradients or shadows.

**Transfer:** Reserve this color event for a concentrated proof or reassurance moment.

#### Dark closing field · level 0

**Use:** Closing manifesto, contacts, navigation and graphic sign-off.

**CSS:** `background: #1b1512; color: #fff3b8; padding: 24px`

**Observed:** A full-width editorial ending rather than a short utility footer.

**Transfer:** Keep the sign-off spacious enough to host a substantial promise and a final emblem.

#### Service contact field · level 0

**Only for:** service landing pages

**Use:** Dark half of the paired contact-and-questions section.

**CSS:** `background: #1b1512; color: #eae5e3; padding: 24px`

**Observed:** Warm stone text distinguishes this invitation from the butter-colored global ending.

**Transfer:** Pair with the Butter proof field rather than adding a third background color.

## Components

### Floating navigation

**Use:** Persistent compact brand and menu access.

**CSS:** `position: fixed; top: 24px; left: 24px; width: 288px; height: 44px; display: flex; align-items: center; justify-content: space-between; z-index: 50`

**Observed:** A small logo sits at the left and a two-bar menu control at the right. The opening rests visually on white; scrolling introduces a rectangular butter backing.

**Transfer:** Use a compact original wordmark rather than a conventional full-width navigation bar.

### Menu control

**Use:** Open the site navigation.

**CSS:** `padding: 14px; background: transparent; color: #000000; border-radius: 0px`

**Observed:** The icon is two solid horizontal bars occupying 21×10px; the control occupies 49×38px.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

### Project portrait

**Use:** Large linked visual proof.

**CSS:** `position: relative; display: grid; aspect-ratio: 4 / 5; border-radius: 0px`

**Text style:** `project-title` — TeX Gyre Heros Cn 700 · 32px/0.9 · tracking -0.02em · uppercase

**Observed:** The photograph fills the whole rectangle; a white name is centered across it in a sticky lower-edge label with 24px padding. Portraits meet edge to edge in pairs.

**Transfer:** Use one tightly framed image per outcome, with the name readable against the image itself.

### Project caption strip

**Use:** Quietly name the work performed and its category.

**CSS:** `display: flex; justify-content: space-between; padding: 12px 24px; height: 112px; color: #000000; background: #ffffff`

**Text style:** `body` — TeX Gyre Termes 400 · 14px/1.5

**Observed:** Normal serif scope text flows into an italic category/platform phrase; the short line sits at the top of a deliberately tall white strip.

**Transfer:** Use factual metadata rather than a description paragraph.

### Proof directory item

**Use:** Names in the yellow proof band.

**CSS:** `font-size: 14px; line-height: 21px; color: #000000`

**Text style:** `directory` — TeX Gyre Termes 500 · 14px/1.5

**Observed:** Plain names form two tight columns in the right half of a large field, with 4px row gaps and 24px between columns. Some names link to a discovery action.

**Transfer:** Use real customers, integrations, publications or other verifiable names.

### Footer link

**Use:** Service, location, language and social navigation within the closing field.

**CSS:** `color: #fff3b8; background: transparent; line-height: 28px`

**Text style:** `footer-link` — TeX Gyre Termes 400 · 14px/2

**Observed:** An unboxed serif text link. Service links wrap with 24px horizontal and 4px vertical gaps; the utility row groups smaller clusters.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

### Contact text action

**Only for:** service landing pages

**Use:** Direct conversion beneath a service invitation.

**CSS:** `background: transparent; color: #eae5e3; border-radius: 0px`

**Text style:** `micro-label` — TeX Gyre Heros Cn 700 · 11px/0.9 · tracking -0.02em · uppercase

**Observed:** A tiny condensed uppercase button follows the paragraph. It has no filled silhouette or enclosing outline.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

### Question row

**Only for:** service-page question panels

**Use:** Compact objection handling at the bottom of a butter panel.

**CSS:** `padding: 20px 0px; text-align: left; border-top: 1px solid #1b1512; background: transparent; color: #000000; width: 100%`

**Text style:** `question` — TeX Gyre Heros Cn 700 · 24px/0.9 · tracking -0.02em · uppercase

**Observed:** A stack of full-width text controls, approximately 63px per row including the top rule. The group anchors to the panel bottom.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

### Archive row

**Only for:** portfolio and collection pages

**Use:** Dense textual index after the visual gallery.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); padding: 6px 0px; color: #000000`

**Text style:** `directory` — TeX Gyre Termes 500 · 14px/1.5

**Observed:** A 33px-high link row aligns a name, year and category across a broad white field. The last grid track preserves empty breathing room.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

### Collection filter

**Only for:** portfolio and collection pages

**Use:** Small category switches above the gallery.

**CSS:** `background: transparent; color: #000000`

**Text style:** `micro-label` — TeX Gyre Heros Cn 700 · 11px/0.9 · tracking -0.02em · uppercase

**Observed:** Three inline text controls sit inside a white strip at the upper right, separated by 12px gaps. The selected label is dark; inactive labels are visually muted.

**States:** Declared: hover unknown; focus-visible outline solid 2px.

## Imagery and graphics

### Tactile interface triptych

**Use:** Signature opening media and capability proof.

**Observed:** A hand-held phone against quilted fabric, a laptop on a lap and an isolated interface on black establish three different distances from the product. Equal 448×349px opening frames have hard edges and 24px white gaps. The later proof row changes proportion to one 684px landscape and two 330px portraits, all about 428px high.

**Transfer:** Show the new product being used, displayed in a real material setting and viewed directly. If photography is unavailable, combine a close-up of an object or hand with a clean interface composition on a dark backing; do not replace all three panels with generic stock scenes.

### Full-bleed editorial portraits

**Use:** Large project gallery and compact reference strips.

**Observed:** Fashion, furniture, cycling details, food and artwork are tightly framed with natural light and tactile surfaces. Muted stone, olive and brown coexist with vivid color inside the photographs. Large images use a 4:5 ratio; the six-image reference strip uses contiguous 232×290px portraits.

**Transfer:** Choose subject-specific editorial photography or convincing product still lifes. Keep natural lighting and deliberate cropping rather than applying a universal tint.

### Dotted editorial rule

**Use:** Signature section and footer separators.

**Observed:** A fine dotted horizontal band, 2px high with a 9px repeat, spans the inset content width. Black on white becomes butter on brown-black.

**Transfer:** Use the same dotted cadence to separate chapters without introducing card borders.

**Build:** Use an SVG pattern tile 9×2px containing one centered 2px circle in currentColor. Repeat it across a 2px-high rule; set currentColor to black or butter according to the field.

### Enlarged closing emblem

**Use:** Required graphic sign-off near the bottom of the dark closing field.

**Observed:** A flat butter-yellow fan or rising-sun silhouette is centered below the utility navigation, roughly 400px wide and 207px tall, with a broad horizontal base. Its scale is much larger than the small logo above.

**Transfer:** Create an original one-color geometric sign for the new product and enlarge it as the final visual punctuation. A simple custom monogram or radial emblem is the minimum acceptable replacement.

**Build:** Draw a single-color SVG in an approximately 400×210 viewBox. Unite a low horizontal base with a central mass and several radiating rectangular or tapered rays; leave brown-black negative-space wedges between rays. Fill with butter, center it, and leave a 96px pause above. Keep edges crisp with no glow, texture or shadow.

### Atmospheric service photography

**Only for:** service landing pages

**Use:** Wide scene after the opening and tall media beside explanatory copy.

**Observed:** A dark interior facing misty mountains and a sunlit horse-and-rider scene fill 1440×749px bands. Later photographs show a phone on a rounded table, a laptop on a wooden stool, a framed poster in a room and a garden swimming pool, typically in 684×786px or 684×800px frames.

**Transfer:** Use a real environment that embodies the product's pace and audience; follow wide scene-setting images with tangible close-ups.

### Icons

**Observed:** Interface iconography is sparse: a small solid wordmark/emblem and a 21×10px two-bar menu icon in black. Decorative service icon grids are absent.

**Transfer:** Use solid simple navigation marks; let photography and typography carry meaning instead of adding feature icons.

## Section recipes

How recurring sections are built.

### First screen: Contact-sheet opening

**Observed:** White canvas sits behind a compact Floating navigation at the upper left. At a 96px top inset, three equal media rectangles occupy almost the full width with 24px outer insets and gutters; each is about 448×349px. The media leads, not the headline. A 48px condensed uppercase promise follows after 24px, left aligned and broken into two compact lines occupying roughly the left third. A deep white pause leads to a thin row of small serif descriptors distributed across the width and a Dotted editorial rule. Within the first 900px, the complete triptych, headline, descriptor row, divider and beginning of the two-column introductory prose are visible; the next media row falls below. The opening has no large conversion button; navigation and contextual text links supply the actions.

**Transfer:** For a new product use three complementary views: use in context, a tactile detail and a clean direct demonstration. Keep the headline shorter than the image row is wide. Service-specific pages instead place a 60px promise low on the left two thirds, a 448×345px image at upper right and its small support paragraph underneath; a rule and descriptor row precede a wide atmospheric scene. Collection pages begin directly with four adjacent portraits and upper-right filters.

**Avoid:** Do not replace the triptych with a centered headline above one floating dashboard, or place a giant pill CTA in the empty right half.

**Text style:** `display` — TeX Gyre Heros Cn 700 · 48px/0.9 · tracking -0.02em · uppercase

### Split introduction and capability still lifes

**Observed:** A small serif lead-in occupies the left half while a 684px-wide text block sits at right. After a 160px pause, a mixed-width media row uses a wide interface scene plus two narrow tactile photographs. Short captions align labels to the left and modest proof counts to the right. A 48px uppercase statement closes the chapter above a dotted rule.

**Transfer:** Explain the product in plain prose, then show distinct uses or outputs. Keep metrics as small caption facts, not giant numerical billboards.

### Paired image proof

**Observed:** Two Project portrait components meet without a gutter, each at 720×900px. Their white sticky names sit over the media; Project caption strips provide the serif metadata below.

**Transfer:** Use this for outcomes, applications or customer stories. Alternate subject scale and photographic palette while preserving equal panel geometry.

### Butter directory

**Observed:** Butter proof field spans the full width with 24px padding. A 48px heading occupies the left half while Proof directory items run in two 330px columns at right. The field is about 709px tall, leaving substantial empty space beneath the names.

**Transfer:** Collect one persuasive set of real proof into a single color event instead of scattering logo cards throughout the page.

### Manifesto closing field

**Observed:** Dark closing field is approximately 827px tall. Its upper half uses Footer grid: a five-line 48px manifesto at left and three tiny-labeled contact groups at right. A 96px pause precedes the Footer links, then a dotted rule and a utility row with small identity, copyright, languages, social links and privacy. The Enlarged closing emblem is centered near the bottom with another generous pause.

**Transfer:** Write a substantial closing belief or promise in the new product's voice, give direct contact routes, and conclude with an original enlarged emblem instead of ending at the legal links.

**Text style:** `display` — TeX Gyre Heros Cn 700 · 48px/0.9 · tracking -0.02em · uppercase

### Alternating editorial chapter

**Only for:** service landing pages

**Observed:** Editorial halves use a 24px gutter and insets. One half carries a 60px headline and a 440px-wide paragraph, separated by 28px; the other contains a tall contextual image. Later chapters swap the image side. Dotted rules punctuate the transitions.

**Transfer:** Give each chapter one reason, process or benefit rather than a generic feature inventory.

**Text style:** `service-display` — TeX Gyre Heros Cn 700 · 60px/0.88 · tracking -0.02em · uppercase

### Numbered reasons

**Only for:** service landing pages

**Observed:** Four 330px-wide columns separated by 24px show small serif numbers from 01 onward and, 48px below, 32px uppercase proof statements. Each column is about 184px tall.

**Transfer:** Use concise, concrete differentiators with comparable line counts, not icon-led cards.

### Contact and questions diptych

**Only for:** service landing pages

**Observed:** Two flush 720px-wide panels form a 749px-tall composition. Service contact field holds a 60px invitation, short prose and Contact text action at top, with three compact contact blocks near the bottom. Butter proof field holds a tiny label above a bottom-anchored stack of Question rows.

**Transfer:** Pair a direct invitation with the most practical purchase questions. Preserve the sharp two-color division and useful content at both top and bottom.

### Six-frame reference strip

**Only for:** service landing pages

**Observed:** A 60px heading sits at top left; a long white pause of about 230px separates it from six contiguous 232×290px portraits. The strip remains inside the 24px page inset.

**Transfer:** Present related outcomes in one compact filmstrip rather than six raised testimonial cards.

### Visual archive and human coda

**Only for:** portfolio and collection pages

**Observed:** Four-column portrait groups alternate with double-width paired projects. A white archive follows with a 48px heading and 33px Archive rows. Before the dark ending, a 696×900px fashion portrait sits beside a 48px heading, a small lower-right paragraph, discovery link and a 228×304px environmental image.

**Transfer:** Move from selective visual impact to exhaustive factual coverage, then add a human or cultural note before conversion.

## Page flow

**Storyline:** Visual promise → plain-language explanation → tangible proof → concentrated reassurance → direct invitation → graphic sign-off.

### Broad brand or product landing page

1. **Visual promise** — Three complementary media views precede a compact uppercase promise.
2. **Explanation** — Small split-column prose introduces the offer, followed by mixed-width capability imagery and caption-sized proof counts.
3. **Outcome proof** — Full-bleed paired portraits turn the offer into concrete examples.
4. **Social proof** — A butter-yellow name directory creates a concentrated reassurance field.
5. **Closing call** — Dark manifesto, direct contacts, utility navigation and enlarged emblem.

**Transfer:** Default for a new marketing page: let media carry the first impression and keep prose small and specific.

### Detailed service or product-capability landing page

1. **Promise** — A low-left 60px headline balances an upper-right image and concise support.
2. **Scene setting** — A full-width atmospheric photograph follows a descriptor row.
3. **Capability chapters** — Alternating tall-image and text halves explain approach, context and technical delivery.
4. **Differentiation** — Four numbered reasons condense the argument.
5. **Objection handling** — A dark contact invitation pairs with butter-yellow questions.
6. **Outcome proof** — A six-frame reference strip precedes the shared dark ending.

**Transfer:** Use the service variant when detailed explanation matters more than a broad editorial introduction.

### Platform or specialized solution landing page

1. **Promise** — Asymmetric service opening with product-in-hand media.
2. **Scene setting** — Wide lifestyle imagery and a compact partner endorsement.
3. **Use cases** — Three equal text columns distinguish creation, improvement and transition needs.
4. **Capability chapters** — Alternating contextual media and compact prose explain process and ongoing support.
5. **Reassurance** — Numbered reasons, contact/questions diptych and six-image proof strip.
6. **Closing call** — Shared manifesto, contacts and graphic sign-off.

**Transfer:** Translate the three service tracks into the new product's genuine adoption paths, without forcing the same topics.

### Portfolio or visual collection with an exhaustive index

1. **Product demonstration** — Immediate four-column gallery with small category filters; paired full-size images interrupt the smaller rhythm.
2. **Comprehensive proof** — A dense serif archive lists name, year and category.
3. **Human context** — An asymmetric portrait-and-copy coda adds a personal register.
4. **Closing call** — The same dark manifesto and enlarged emblem close the page.

**Transfer:** Use the gallery variant for collections; no separate hero slogan is necessary when the content itself supplies the opening impact.

## Writing

Assured, pragmatic and design-literate. The voice values useful work, long-term involvement and clarity over hype, with occasional short English studio phrases inside predominantly French copy.

**Do not copy:** Do not reuse Pam's identity, emblem, customer names, partner badges, address, contact details, project images, counts, dates, geographic claims or promises as claims for another product. Source phrases are voice examples, not supplied product copy. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** French nous and votre create a direct professional relationship; the brand sometimes refers to itself in the third person. English appears in concise labels and editorial statements.
- **Rhythm:** Compact headlines contrast with measured explanatory paragraphs. Parallel phrases, short negations and concrete lists build assurance; actions are usually one to three words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the discipline or outcome directly, using a compact noun phrase. | 4–10 words | “Branding & E-commerce Studio”<br>“Des boutiques Shopify sur mesure.” |
| Section lead | A short declaration ties two complementary disciplines together. | 3–7 words | “Design et technologie, alignés.”<br>“Une stack moderne et maîtrisée” |
| Supporting explanation | Explain the operational value, then reject an unhelpful shortcut. | Several short sentences | “Le webdesign n’est jamais décoratif. Il sert le propos, guide la lecture et installe une atmosphère juste.” |
| Differentiator | Make one concrete commitment; use contrast rather than superlatives. | 7–12 words | “Des sites pensés pour durer, pas pour faire de l’effet” |
| Action | Use a plain verb or direct invitation, without benefit-stuffed button copy. | 1–3 words | “Nous contacter”<br>“Découvrir” |

**Words and phrasing to use:** sur mesure; utile; clair; aligné; durable; besoins réels; accompagner; conception; aujourd’hui et demain

**Avoid:** révolutionnaire; incroyable; magique; solution ultime; disruption; exclamation-led urgency

**Rules:**

- Ground statements in what the product does and how it supports real usage.
- Keep metadata factual and category-like; it should read as a caption, not an advertisement.
- Let one strong closing sentence express the working philosophy without repeating every feature.
- Use short English phrases only when they serve the editorial voice; do not make the whole page a collage of slogans.

## Do's and Don'ts

### Do

- Use condensed 700-weight capitals with -0.02em tracking for the full heading hierarchy.
- Keep the default display at 48px/0.9 and supporting serif prose at 14px/1.5.
- Align media, rules and text to the 24px inset and 24px principal gutter.
- Let selected portrait images meet with a 0px gutter at full page width.
- Preserve the small 11px uppercase contact controls rather than increasing their visual weight.
- Use modest 14px proof numbers in captions and 48px number-to-statement spacing in numbered reasons.
- Give the butter proof field and dark closing field enough height to feel like chapters.
- Finish with a crisp one-color emblem about 400px wide, beneath the utility links.

### Don't

- Do not replace the serif body with the condensed headline family; the two textures are essential.
- Do not introduce rounded image cards, pill buttons or soft drop shadows into the flat editorial system.
- Do not spread butter-yellow backgrounds over every section; white remains the dominant reading field.
- Do not turn the caption-sized proof counts into oversized dashboard statistics.
- Do not put a dark gradient or universal color wash over every photograph; preserve natural material color.
- Do not increase body text to 20px and collapse the long white pauses into ordinary card-grid spacing.
- Do not fill empty halves with decorative feature icons; the asymmetry is intentional.
- Do not reduce the closing field to a short legal strip; the manifesto and graphic sign-off carry the final impression.

## Motion and responsive

### Motion

**Observed:**

- Declared action and surface transitions include all 0.2s ease and top 0.2s.
- The new-project contact label declares pulse 2s cubic-bezier(.4, 0, .6, 1) infinite.
- Project-name overlays use sticky positioning near the image bottom; the navigation remains fixed.
- Opening media includes video as well as still images.

**Transfer:**

- Keep motion concentrated in media, compact navigation backing and the small contact label; the surrounding editorial grid stays stable.
- Preserve the image-title relationship while scrolling long portraits.

**Unknown:**

- Menu opening choreography, filter transitions and accordion expansion animation are not established.
- Exact media-fade timing and the closing emblem's full scroll transform are not established.

### Responsive

**Observed:**

- Desktop composition uses three-column opening media, two-column editorial sections, four-column reasons and a twelve-column footer.
- Class declarations indicate a two-column gallery below the large layout, reduced caption heights and hidden secondary archive metadata on smaller screens; no numerical breakpoint widths are established.

**Transfer:**

- On narrow screens, keep media before the default promise and preserve the three complementary views in a stacked composition.
- Stack editorial text and tall imagery while retaining a clear hierarchy; let the contact/questions diptych become two full-width fields.
- Keep captions small and make the closing emblem scale to the available width rather than clipping it.

**Unknown:**

- Exact mobile font sizes, breakpoint values, navigation-panel layout and final stacking order are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
