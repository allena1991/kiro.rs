# Caldera — halftone industrial optimism

## Overview

A light, emphatic technology style with warm gray space, heavy compact grotesk headlines and flashes of hot orange and electric violet. Rounded modular panels and dotted printing textures make complex infrastructure feel tangible and approachable. Black-and-cream isometric machinery supplies the visual storytelling, with sparse text and oversized proof points suited to ambitious platform and product launches.

### Essentials

- Headlines have the weight of stamped signage: compact ultrabold display lettering, normal tracking, 80px/1.1 section titles and 189px/0.94 manifesto statements, paired with DM Sans at weight 500.
- The opening is a shaped poster rather than a centered text stack: a 1328×765px graphic stage inside 56px desktop gutters, with headline space cut out at upper left and a 539×187px support-and-action pocket at lower right.
- Controls are capsule-like and tactile without shadows: orange actions use 800px radii, 48px height and 12px 24px padding; larger opening actions are 56px high with a dotted-outline companion.
- Color arrives in concentrated blocks, not a page-wide wash: warm gray #e2e2df remains the default canvas, cream panels carry most copy, and #fc5000 and #524ae9 fill selected proof, illustration and conversion panels.
- Printed dots tie the page together: include a high-contrast orange/violet halftone opening and a low-contrast gray dot field behind a later chapter and the ending. Generate variable-radius SVG dots when bespoke media is unavailable.
- Modules almost touch: 40px rounded cards with 16px gaps form linked rows, using small same-color bridges across the middle of selected seams. Proof uses 64px numerals near the bottom of orange panels; the closing uses a black statement card beside orange social discs and a cream utility card.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fc5000` | `--color-orange` | action, surface, accent | Primary capsules, proof panels, social circles and illustration backdrops. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#524ae9` | `--color-violet` | surface, accent | Large supporting story and conversion panels; second color in opening halftone. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#070607` | `--color-ink` | text, surface, border | Headlines, paragraph text, dotted rules and closing statement panel. |
| Warm gray canvas | `#e2e2df` | `--color-canvas` | background, text | Default page ground; reversed campaign lettering. |
| Pale navigation wash | `#e7e6e3` | `--color-nav-wash` | surface | Visible result of rgba(247,246,243,0.224) over the gray canvas; navigation grows visually cream as it condenses. |
| Warm white | `#f7f6f2` | `--color-paper` | text, surface | Reverse text, proof logos and secondary tiles. |
| Cream panel | `#f7f6f3` | `--color-panel` | surface | Large editorial panels and utility cards. |
| White dotted rule | `#ffffff` | `--color-white-rule` | border | Dotted input outline on violet. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product detail openings | Lemon marker | `#f2ef89` | `--color-label-lemon` | surface | Small product identification chip. |
| launch campaigns | Soft lemon | `#f5f28e` | `--color-lemon` | surface | Middle panel in a campaign utility trio. |
| product detail and technical reference sections | Technical charcoal | `#151317` | `--color-charcoal` | surface, text | Dark product action and technical reference panels. |

## Typography

- **PP Neue Corp Compact** — Headlines, card titles and large numbers. Dense compact grotesk with blunt, ultrabold forms and tightly fitted counters. OpenType features: "ss06", "ss10". If unavailable, use **Barlow Condensed**. Use 800–900; tune width to retain the dense block silhouette. Font stack: "PP Neue Corp Compact", "Barlow Condensed", sans-serif.
- **DM Sans** — Body, navigation, labels and actions. Rounded geometric sans, medium weight and open line spacing. Font stack: "DM Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| manifesto | PP Neue Corp Compact | 800 | 189px | 0.94 | normal, features "ss06", "ss10" | Rare, full-width two-line declaration between modular chapters. |
| section-heading | PP Neue Corp Compact | 800 | 80px | 1.1 | normal, features "ss06", "ss10" | Centered one- or two-line section introductions. |
| proof-number | PP Neue Corp Compact | 800 | 64px | 1 | normal | Orange proof cards. |
| community-number | PP Neue Corp Compact | 800 | 56px | 1 | normal, features "ss06" | Cream audience proof cards. |
| card-heading | PP Neue Corp Compact | 800 | 48px | 1 | normal, features "ss06", "ss10" | Feature and conversion panel titles. |
| compact-heading | PP Neue Corp Compact | 800 | 40px | 1 | normal, features "ss06", "ss10" | Compact feature panels and closing statement. |
| tab-heading | PP Neue Corp Compact | 800 | 32px | 1 | 0.02em, features "ss06", "ss10" | Collapsed category rows and short outcome labels. |
| story-copy | DM Sans | 500 | 30px | 1.5 | normal | Extended narrative within a violet panel. |
| body-lead | DM Sans | 500 | 18px | 1.5 | normal | Opening support line, proof labels and explanatory feature copy. |
| body | DM Sans | 500 | 16px | 1.55 | normal | Default support text and navigation. |
| button | DM Sans | 500 | 16px | 1.25 | normal | Standard action labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| launch campaigns | campaign-symbol | PP Neue Corp Compact | 800 | 300px | 0.94 | normal, features "ss06", "ss10" | Single monumental identifier between announcement lines. |
| launch campaigns | campaign-heading | PP Neue Corp Compact | 800 | 120px | 0.94 | normal, features "ss06", "ss10" | Flanking announcement lines and launch manifesto. |
| product detail openings | product-title | PP Neue Corp Compact | 800 | 70px | 0.94 | normal, features "ss06", "ss10" | Headline inside a split product opening. |
| product detail benefit grids | feature-label | PP Neue Corp Compact | 800 | 27px | 1 | 0.02em | Three-column compact benefit cards. |
| product detail benefit grids | small-body | DM Sans | 500 | 14px | 1.5 | normal | Supporting descriptions in compact benefit cards. |

**Notes:**

- Ultrabold is the visual cut of the display family, not a regular-weight sans. Keep body text at 500 so it remains composed beside the heavy headings.
- Most display tracking stays normal; the short 32px and 27px labels alone add 0.02em. Display leading is 0.94 for very large declarations, 1 for panel titles and 1.1 for centered section headings.
- Opening poster lettering uses the same compact ultrabold silhouette at about 96px on desktop; use 6.67vw as a reconstruction guide and fit the line breaks to the shaped opening. This is artwork-scale lettering rather than a new default section size.

## Layout

**Density:** Airy between chapters, tightly joined inside modular groups; long gray breathing spaces separate dense bursts of cards.

### Spacing

**Spacing system:**

- **horizontal grid** 8px, horizontal — Explains most desktop insets and card gaps; preserve special 10px and 15.4px joins rather than rounding them.

| Value | Use |
| --- | --- |
| 8px | Small icon and text relationships. |
| 16px | Default panel-to-panel gap. |
| 20px | Compact panel title-to-copy separation. |
| 24px | Closing title-to-action separation. |
| 32px | Heading-to-secondary-action gap; compact card padding. |
| 40px | Default card padding. |
| 48px | Large story and product opening panel padding. |
| 56px | Desktop side gutters and footer perimeter. |
| 64px | Inner conversion panel insets and grouped content spacing. |
| 80px | Section title to modular content. |
| 160px | Late chapter top padding and feature chapter bottom padding. |
| 168px | Proof chapter top padding. |
| 200px | Major capability chapter top padding and proof chapter bottom padding. |

### Containers and grids

- **main container**: max width 1900px · side padding 56px. Centered page content; 1328px usable width at a 1440px viewport.
- **proof strip**: max width 1166px · 4 columns · gap 15.4px. Four equal orange proof panels with a cream logo strip beneath.
- **conversion column**: max width 938px · gap 16px. Narrower centered audience, outcome and signup group within the wide page.
- **feature pair**: 2 columns · gap 16px. Asymmetric text and illustration panels; reverse the wider side on the next row.
- **benefit grid** (only for product detail benefit grids): 3 columns · gap 16px. Three equal compact cards for product benefits.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | major panels | 40px |
|  | compact benefit cards | 32px |
|  | icon badges | 16px |
|  | actions | 800px |
|  | signup input | 100px |
| launch campaigns | launch utility cards | 24px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #e2e2df; color: #070607`

**Observed:** Flat matte gray, with no elevated shadow hierarchy.

**Transfer:** Separate chapters with space rather than bands of unrelated neutrals.

#### Cream panel · level 1

**Use:** Text, benefit and utility groups.

**CSS:** `background: #f7f6f3; border-radius: 40px; box-shadow: none`

**Observed:** Large soft corners carry the hierarchy; outlines are generally absent.

**Transfer:** Keep text panels cream when the adjacent illustration is saturated.

#### Orange proof · level 1

**Use:** Quantified proof and graphic stages.

**CSS:** `background: #fc5000; color: #f7f6f2; border-radius: 40px`

**Observed:** Solid fill with reversed type, visually joined into rows.

**Transfer:** Put a short label above a large bottom-weighted value.

#### Violet story · level 1

**Use:** Explanatory story and conversion emphasis.

**CSS:** `background: #524ae9; color: #f7f6f2; border-radius: 40px`

**Observed:** An uninterrupted color plane, not a glowing or glossy material.

**Transfer:** Use one large colored story panel instead of tinting every feature.

#### Black closing panel · level 1

**Use:** Final brand promise and conversion.

**CSS:** `background: #070607; color: #f7f6f2; border-radius: 40px; padding: 40px`

**Observed:** Anchors the left half of the closing assembly.

**Transfer:** Keep its statement brief enough for two or three compact lines.

#### Technical dark panel · level 1

**Only for:** technical reference sections

**Use:** Reference identifiers and verification actions.

**CSS:** `background: #151317; color: #e2e2df; border-radius: 32px`

**Observed:** One large 1328×900px rounded field contains an illustration on one side and two reference groups on the other.

**Transfer:** Use for specifications or verifiable technical identifiers, not as the default page theme.

## Components

### Floating navigation

**Use:** Persistent global navigation.

**CSS:** `display: flex; align-items: center; gap: 10px; padding: 8px 8px 8px 24px; background: rgba(247, 246, 243, 0.224); border-radius: 800px; height: 64px`

**Text style:** `body` — DM Sans 500 · 16px/1.55

**Observed:** At the top it spans most of the width with full wordmark, text links, social glyphs and a primary action. On scroll it contracts into a centered cream capsule with a small brand symbol. Dotted vertical dividers separate groups.

**Transfer:** Keep the compact capsule legible above both plain and dotted chapters.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #fc5000; color: #f7f6f2; border-radius: 800px; padding: 12px 24px; height: 48px`

**Text style:** `button` — DM Sans 500 · 16px/1.25

**Observed:** Short centered label without an arrow. The opening version grows to 56px high and sits beside a dotted-outline secondary action.

**Transfer:** Use a brief verb phrase; leave arrows for explicit navigation controls.

### Plain navigation link

**Use:** Header and footer destinations.

**CSS:** `color: #070607; text-decoration: none`

**Text style:** `body` — DM Sans 500 · 16px/1.55

**Observed:** Unboxed medium sans text. Active product navigation uses a short orange underline.

**States:** Declared: hover color #000; background-color initial; text-decoration-line none.

**Transfer:** Keep this visually quieter than filled actions.

### Proof card

**Use:** Four-part quantitative proof row.

**CSS:** `background: #fc5000; color: #f7f6f2; border-radius: 40px; padding: 40px; display: flex; flex-direction: column; gap: 80px`

**Text style:** `proof-number` — PP Neue Corp Compact 800 · 64px/1

**Observed:** An 18px label sits above a large number. Each desktop card is 280×251px. Same-color narrow necks connect the row through the middle while gray slots remain above and below.

**Transfer:** Use only substantiated metrics; pair the row with a monochrome logo strip.

### Feature text card

**Use:** Text half of an alternating illustration pair.

**CSS:** `background: #f7f6f3; border-radius: 40px; padding: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `compact-heading` — PP Neue Corp Compact 800 · 40px/1

**Observed:** Small black icon badge at the top; title, body and a text action form a lower cluster. A 544×589px text panel faces a wider illustration panel. Product detail variants use 48px titles.

**Transfer:** Keep the empty middle as deliberate separation between symbol and explanation.

### Category selector

**Use:** A selectable use-case narrative.

**CSS:** `border-radius: 40px; padding: 40px; display: flex; flex-direction: column; justify-content: center`

**Text style:** `tab-heading` — PP Neue Corp Compact 800 · 32px/1 · tracking 0.02em

**Observed:** Collapsed options are shallow dotted-outline capsules. The active option opens into a cream card with a black icon badge, 48px title and short support text. A larger Violet story panel sits alongside.

**Transfer:** Use categories to reveal substantial narrative, not a row of small pills with no content.

### Newsletter panel

**Use:** Audience conversion within the dotted chapter.

**CSS:** `background: #524ae9; color: #f7f6f2; border-radius: 40px; padding: 88px 64px 64px; display: flex; flex-direction: column; align-items: center; gap: 80px; max-width: 938px`

**Text style:** `card-heading` — PP Neue Corp Compact 800 · 48px/1

**Observed:** Centered title constrained to 584px, then a single long capsule input.

**Transfer:** Place beneath a joined proof row or another compact credibility group.

### Dotted signup input

**Use:** Single email entry in the Newsletter panel.

**CSS:** `border: 1.5px dotted #ffffff; border-radius: 100px; padding: 24px 64px 24px 32px; height: 80px; background: transparent`

**Observed:** One uninterrupted 810px-wide field at desktop, with space reserved at the right for submission.

**Transfer:** Retain the dotted outline rather than adding a filled white field.

### Carousel control

**Use:** Paired previous and next controls for editorial content.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 16px; border: 1.5px dotted #070607; border-radius: 800px; padding: 0px 4px; width: 107px; height: 56px`

**Observed:** Two 40px arrow buttons share one capsule, divided by a dotted vertical seam. The control aligns with the right edge opposite the section title.

**Transfer:** Use for a horizontally clipped card rail; provide accessible button labels.

### Closing statement card

**Use:** Last conversion prompt.

**CSS:** `background: #070607; color: #f7f6f2; border-radius: 40px; padding: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `compact-heading` — PP Neue Corp Compact 800 · 40px/1

**Observed:** Orange wordmark at top, compact reversed promise below it, then an orange Primary button. Beside it sits a row of seven orange social circles above a cream utility card with dotted divider.

**Transfer:** Preserve the two-part closing assembly even when there are fewer social destinations.

### Product marker

**Only for:** product detail openings

**Use:** Identify the product before the promise.

**CSS:** `background: #f2ef89; color: #070607; padding: 7px 14px; border-radius: 24px`

**Text style:** `button` — DM Sans 500 · 16px/1.25

**Observed:** A small lemon chip sits above the headline in the cream opening panel.

**Transfer:** Use a short category or product descriptor.

## Imagery and graphics

### Chromatic halftone poster

**Use:** Signature opening stage.

**Observed:** Orange and violet circles form billowing, variable-density waves across nearly the entire hero. The image has no perspective frame or photographic subject; its outline makes room for the upper-left headline and lower-right supporting copy.

**Transfer:** Create an abstract field expressing the new product's energy; the minimum version is a carefully masked two-color SVG halftone, not a generic gradient.

**Build:** Use a 1328×765 SVG viewBox with a violet ground and a regular grid of orange circles about 12px apart. Vary radii from nearly zero to 6px using broad overlapping sine-wave fields. Clip to a 40px-rounded outline; subtract a headline pocket at upper left and a 539×187 support pocket at lower right, rounding both inner turns. Put real accessible headline text above the graphic.

### Gray halftone atmosphere

**Use:** Signature background behind a later capability or audience chapter and the closing assembly.

**Observed:** Large, soft gray dots vary in diameter like a printed wave. The pattern spans beyond the viewport and remains visible between cream cards and behind the footer without competing with black type.

**Transfer:** Repeat the opening's print vocabulary in a low-contrast neutral register.

**Build:** Generate an SVG grid at roughly 24px intervals with circles varying from 3px to 11px radius. Use rgba(7,6,7,0.06) on the gray canvas, modulating radius with a broad radial or wave envelope. Oversize the field to about twice the viewport width and fade its edges. These are reconstruction settings; match the soft printed appearance rather than exact dot positions.

### Isometric black machinery

**Use:** Capability illustrations and split product openings.

**Observed:** Black modular towers, switches and rails are drawn in three-quarter isometric view with thin cream edge lines and small dotted glyphs. Forms extend beyond the rounded panel edges; orange and violet backdrops alternate. The artwork occupies roughly half or more of a feature pair.

**Transfer:** Translate the product's mechanisms into connected physical objects: relays, workstations, blocks or conduits. A minimum version uses clean vector extruded boxes with cream outlines, strong black fill and one saturated backdrop.

**Build:** Draw SVG cuboids on 30-degree isometric axes; use black faces, 1px cream edge strokes and sparse cream circles for controls. Join objects with parallel rails and clip oversized forms inside 40px-rounded orange or violet rectangles. Avoid realistic metallic reflections.

### Monochrome proof marks

**Use:** Partner strips and endorsement grids.

**Observed:** Black logos centered on cream plates; strip cells have dotted vertical dividers, while later endorsement plates form a roomy four-column grid.

**Transfer:** Normalize new marks optically rather than making every logo the same width.

### Device preview collage

**Only for:** product preview conversion sections

**Use:** Large violet preview panel near the ending.

**Observed:** A phone and tablet are angled and overlap, framed with hand-drawn black-and-cream device edges. Their light interface screens contrast against the violet ground and extend toward the card edges.

**Transfer:** Show one authentic product screen in a flat device silhouette if a sophisticated collage is unavailable; preserve the black outline and saturated backing.

### Outlined coin stacks

**Only for:** launch campaigns

**Use:** Flanking a centered long-form explanation.

**Observed:** Cream discs with thick black outlines and black banded edges enter from both page sides. The central copy remains unobstructed.

**Transfer:** Use a simple repeated physical metaphor related to the new launch, keeping it monochrome and pushed to the edges.

### Icons

**Observed:** Functional and social symbols are solid monochrome glyphs, generally 24px in navigation and 36–42px in cards. Feature symbols use a dot-matrix construction within black 72–83px rounded-square badges; social symbols reverse out of orange circles.

**Transfer:** Choose filled glyphs for navigation and build simple dotted pictograms for major features. Do not mix a thin multicolor line-icon library into these badges.

## Section recipes

How recurring sections are built.

### First screen: Shaped poster opening

**Observed:** A fixed navigation zone occupies the first 112px. Beneath it a 1328×765px Chromatic halftone poster fills the desktop width between 56px gutters. Back to front: gray Canvas, rounded two-color dot field, gray cutout pockets, heavy two-line lettering at upper left, then lower-right support copy and paired actions. The headline occupies a little under half the width and uses artwork-scale lettering about 96px high. The main graphic bridges the remaining upper-right and lower-left areas. The lower-right 539×187px pocket has a 40px rounded inner corner and contains an 18px/1.5 support sentence and two 56px capsules, orange primary and dotted secondary. The full headline, main graphic, support and both actions are visible by 900px; proof begins below the first screen.

**Transfer:** For a new landing page, fit a two-line promise into the upper-left pocket and generate the signature halftone field without needing a literal product object. Use section-heading as the baseline display recipe and enlarge it to fit the poster silhouette. Product detail openings instead pair a 582×544px illustrated panel with a 730×544px cream panel, lemon marker, 70px/0.94 product title and dark action. Launch campaigns can open with a full orange rounded poster and centered monumental typography.

**Avoid:** Do not replace the shaped composition with a centered heading floating over an unbroken gradient; do not let the support pocket obscure the main color field or push actions below the first screen.

**Text style:** `section-heading` — PP Neue Corp Compact 800 · 80px/1.1

### Centered heading and proof strip

**Observed:** An 80px/1.1 centered heading sits above a small outline action, with 32px separation within the heading group and 80px to content. Four Proof cards occupy a 1166px strip; the cream monochrome logo strip sits 16px below.

**Transfer:** Use for quantified credibility, adoption or results. Shorten claims so the title remains a compact two-line block.

**Text style:** `section-heading` — PP Neue Corp Compact 800 · 80px/1.1

### Manifesto and alternating mechanisms

**Observed:** A 189px/0.94 declaration spans the wide container before two Feature text card and illustration rows. The rows alternate narrow cream text and wider art, with 16px joins and a Gray halftone atmosphere behind the chapter. Major section padding is 200px above and 160px below.

**Transfer:** Turn one core strategic advantage into a short declarative headline, then explain it through two concrete mechanisms rather than more abstract slogans.

**Text style:** `manifesto` — PP Neue Corp Compact 800 · 189px/0.94

### Category narrative pair

**Observed:** A centered section title leads to a 420px category column beside a 730px Violet story panel. One expanded cream category exposes an icon, title and short description; inactive categories remain dotted capsule rows. The story uses 30px/1.5 sans text and proof marks near its bottom.

**Transfer:** Organize several audiences or jobs-to-be-done around one substantial explanation per selection.

### Editorial rail

**Observed:** A left-aligned 80px title faces the Carousel control. Cream rounded cards form a horizontally clipped rail with orange-led thumbnail art, a small lemon category marker, compact bold title and date.

**Transfer:** Use for fresh evidence, releases or stories; keep thumbnail art visually related to the poster and mechanism palette.

### Audience conversion and endorsement

**Observed:** Gray halftone atmosphere backs a centered 80px title, a joined row of three cream audience cards with orange social badges and 56px values, then the Newsletter panel. A separate endorsement grid continues the dotted ground.

**Transfer:** Combine human or organizational proof with one clear continuing relationship action; replace audience totals with another verified proof format when necessary.

### Shared modular ending

**Observed:** All page types finish with 56px perimeter padding around a two-column assembly: a 664×285px Closing statement card on the left and a 648px right stack. Seven 79px orange social circles sit above a cream navigation-and-copyright panel, separated by a dotted horizontal rule. The gray printed atmosphere continues behind the entire assembly.

**Transfer:** Keep the black promise panel and the social-over-utility stack as the signature closing device. Adapt destination count and text to the new organization.

**Text style:** `compact-heading` — PP Neue Corp Compact 800 · 40px/1

### Launch announcement and utility trio

**Only for:** launch campaigns

**Observed:** An orange poster with 32px corners sits within a narrow gray perimeter. Three centered announcement lines use 120px/0.94 black flanking text and a 300px/0.94 gray identifier. The next chapter opens with a 120px manifesto and three vertically staggered 395×520px utility cards, orange, lemon and violet, with 24px corners and 40px padding.

**Transfer:** Reserve this louder treatment for a specific launch or announcement; let the identifier be short enough to carry the poster.

**Text style:** `campaign-symbol` — PP Neue Corp Compact 800 · 300px/0.94

### Launch explanation and reference

**Only for:** launch campaigns

**Observed:** Centered 80px explanation title and an 18px paragraph are flanked by outlined physical tokens, followed by a small black action. A Technical dark panel holds a large symbol illustration and two labeled identifier groups. The final acquisition group returns to the dotted gray ground with six monochrome destination marks arranged in paired cream plates.

**Transfer:** Move from purpose to verification to availability. Use the dark reference panel for durable identifiers or specifications, then present trusted access destinations.

### Product outcomes and preview

**Only for:** product detail conversion sections

**Observed:** A centered 80px title introduces a 938px column. A cream title bar connects to a four-outcome matrix with dotted internal rules; below it a large violet preview card holds a 48px title, a pale filled action, a secondary text action and the Device preview collage.

**Transfer:** Summarize outcomes before offering a tangible preview; keep the interface subordinate to the bold outer composition.

## Page flow

**Storyline:** bold promise → credibility → mechanism chapters → practical outcomes → ongoing relationship or access → modular closing call

### Broad platform marketing

1. **Promise** — Shaped halftone opening with upper-left headline and lower-right actions.
2. **Quantified proof** — Centered heading, orange metric row and monochrome marks.
3. **Capability chapters** — Monumental declaration and alternating cream text with illustrated mechanisms.
4. **Practical relevance** — Category selector paired with a violet narrative.
5. **Fresh proof** — Editorial card rail.
6. **Relationship and endorsement** — Dotted audience chapter, signup panel and endorsement plates.
7. **Closing call** — Black statement card beside social discs and cream utility panel.

**Transfer:** Use the broad-to-concrete progression while selecting proof appropriate to the new product.

### Focused launch announcement

1. **Announcement** — Orange typographic poster with an oversized central identifier.
2. **Purpose** — Oversized statement and staggered colored utility cards.
3. **Explanation** — Centered paragraph flanked by monochrome physical metaphors.
4. **Verification** — Dark technical reference panel.
5. **Access** — Paired cream destination plates on the dotted ground.
6. **Closing call** — Shared modular ending.

**Transfer:** Keep campaign saturation concentrated around the announcement and utility trio; use the same neutral closing grammar.

### Single product explanation and preview

1. **Promise** — Illustration and cream headline panel in a split opening.
2. **Ecosystem proof** — Centered heading and a network of monochrome circular partner marks.
3. **Mechanisms** — Large declaration and alternating illustrated feature pairs.
4. **Practical benefits** — Three joined compact benefit cards.
5. **Outcome and conversion** — Connected outcome matrix over a violet device preview card.
6. **Closing call** — Shared modular ending.

**Transfer:** Use the split opening when one tangible mechanism deserves immediate explanation; preserve the halftone vocabulary in later chapters.

## Writing

Confident, expansive and practical. Ambition is expressed in short declarative promises, then grounded in plain explanations of what the product enables.

**Do not copy:** Do not reuse Caldera or product names, token identifiers, logos, proprietary artwork, partner affiliations, performance claims, source metrics or quotations as claims for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly product-led and declarative in headlines; supporting copy addresses developers or users as you and your. Imperative verbs drive actions and capability descriptions.
- **Rhythm:** Headlines commonly use three to nine words with title-style capitalization. Large declarations can split into two terse sentences; support typically uses one to three sentences with concrete verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name a new category or arrival, not an abstract mission. | 5–8 words | “The Internet Of Chains Is Here” |
| Manifesto | Two short statements with repetition or contrast. | 4–8 words | “More Is More. Go Horizontal.”<br>“Fuel everything. Built for purpose.” |
| Feature headline | Benefit first, then a concrete contrast or objection removed. | 5–12 words | “Settlement In Seconds, Not Minutes. No Matter The Route.”<br>“No Integration Headaches. No Walled Gardens.” |
| Supporting line | Specific action and result, with technical terms only where useful. | 12–35 words | “Enable zero fee gameplay & instant cross-chain asset transfers.” |
| Primary action | Plain imperative plus destination or next step. | 2–5 words | “Explore Chains”<br>“Book A Call”<br>“Join The Waitlist” |

**Words and phrasing to use:** built for; connect; enable; scale; power; everywhere; no headaches; next wave

**Avoid:** synergy; revolutionary solution; unparalleled excellence; whimsical jokes; excessive exclamation marks

**Rules:**

- Let the largest statement describe a transformation; let the adjacent paragraph explain the mechanism.
- Use contrast and parallel structure in feature titles without making every headline a slogan.
- Attach each quantitative claim to a clear noun label.
- Keep action labels literal and short.

## Do's and Don'ts

### Do

- Use 80px/1.1 compact ultrabold for main section headings.
- Keep the default canvas warm gray and large text panels cream.
- Use 40px corners and 16px seams to make modular groups read as one assembly.
- Preserve the chromatic-to-neutral halftone relationship across the opening and ending.
- Place proof labels above 64px values, leaving a substantial vertical interval.
- Keep feature art black and cream against flat orange or violet.
- Retain dotted rules in controls and utility separations.
- Finish with the black statement and social-over-utility closing assembly.

### Don't

- Do not use regular-weight display lettering just because the display cut is declared with a regular CSS weight.
- Do not turn the whole ordinary landing page orange; reserve that all-over poster treatment for launch campaigns.
- Do not apply shadows to every cream module; separation comes from fill and 16px seams.
- Do not substitute glossy gradient spheres for the printed dots and outlined mechanisms.
- Do not make buttons mildly rounded rectangles; use the full 800px capsule construction.
- Do not put violet body text on orange panels; reverse core panel copy in warm white.
- Do not apply letter spacing to every heading; normal tracking is the main display rule.
- Do not turn the footer into a generic dark full-width link band.

## Motion and responsive

### Motion

**Observed:**

- Navigation visibly changes from a broad wordmark-led header to a centered compact capsule on scroll.
- Declared link color transitions use 0.1s cubic-bezier(0.44,0,0.56,1). The signup field declares a 0.2s transition.
- The opening contains video media; exact playback choreography is not defined here.

**Transfer:**

- Carry the wide-to-capsule navigation transformation into long pages.
- Keep link color changes short and restrained so the print-like modules remain visually stable.

**Unknown:**

- Exact scroll thresholds, video timing and entry animation choreography.
- Focus-visible and active treatments for primary actions.

### Responsive

**Observed:**

- Declared width breakpoints cluster around 768px, 1000px, 1300px and 1600px.

**Transfer:**

- On narrow screens, preserve the shaped-poster idea with smaller stacked text pockets rather than squeezing the desktop line breaks.
- Stack illustration/text pairs while keeping their saturated-versus-cream pairing; wrap proof rows and the closing assembly without losing their group identity.

**Unknown:**

- Exact mobile type sizes, gutters, navigation replacement and card ordering are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
