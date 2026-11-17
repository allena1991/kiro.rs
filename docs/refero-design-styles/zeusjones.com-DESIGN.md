# Zeus Jones — meaning in motion

## Overview

An editorial, art-led style that pairs a delicate literary serif with an unforced contemporary sans. Warm cream and deep midnight provide a restrained frame for richly colored photography, abstract light and expressive graphic work. It suits ambitious products and services that need a human point of view as much as a functional explanation, with low text density and expansive visual pauses.

### Essentials

- Headlines change voice within one sentence: mix FeatureDeckLight and ZJSansDisplay at 90px/100px with -0.02em tracking; underline selected sans words and finish an occasional phrase in true serif italic.
- The opening is a statement suspended in atmosphere: a 900px-high neutral, softly clouded field, a left-aligned two-line headline across most of the width, and a small corner identity opposite a 24px menu control. Keep the first screen free of supporting-copy clutter.
- Cream is the default stage, not white: #fcfaf3 carries most of an ordinary landing page with #1a1c2c text. Concentrated color lives inside rounded media and very fine iridescent link accents; full midnight and lavender bands belong to deeper service or product narratives.
- Images behave like an editorial exhibition rather than uniform cards: 20px corners, mixed landscape and portrait ratios, offset neighboring frames and visible cream between them. Include a media-led proof gallery; when no photography exists, commission original typographic or diagrammatic product studies.
- Controls are small punctuation beside oversized ideas: 54px primary pills, 2px borders, 16px 32px padding and regular 18px text; secondary links remain plain underlined text.
- Give proof a literary scale: use a 60px/64px light-serif text roll for a list of supporters or outcomes, alongside a numbered capability selector with a large serif title. These expressive text devices must survive adaptation, without turning into a logo wall or a dense feature dashboard.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Iridescent gold | `#b2993f` | `--color-gold` | link, accent | Beginning and end of a multicolor underline, not a solid marketing background. |
| Iridescent blue | `#6592f7` | `--color-blue` | link, accent | Middle of the gold-blue-pink underline and abstract spectrum graphics. |
| Iridescent pink | `#f8a7ff` | `--color-pink` | accent, surface, link | Underline stop; also a process-card color cap in extended product narratives. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#fcfaf3` | `--color-canvas` | background, text, surface, action | Default page canvas and inverse foreground; pale action fill on midnight. |
| Warm stone | `#ebe9e4` | `--color-stone` | surface, background | Editorial invitation panel; comparison and question bands in the product narrative. |
| Midnight ink | `#1a1c2c` | `--color-ink` | text, background, action, border | Primary foreground and pill fill on cream; inverse page canvas for deeper capability narratives. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| extended product narratives | Blue charcoal | `#25283c` | `--color-panel` | surface, background | Dark cards and the base of atmospheric system sections. |
| extended product narratives | Light steel | `#a6b5bc` | `--color-steel` | background | Cool light source at the upper center of the radial system backdrop. |
| extended product narratives | Cream card edge | `#e1dfdb` | `--color-soft-edge` | border | Visible ink at 12% over cream, used for question-card outlines. |
| extended product narratives | Dark panel edge | `#4e4e5d` | `--color-dark-edge` | border | Visible cream at 18% over blue charcoal for dark process cards. |
| extended product narratives | Lavender | `#bab2ff` | `--color-lavender` | background, text, accent | Capability-carousel band and small labels on midnight. |
| extended product narratives | Process coral | `#f97f5f` | `--color-coral` | surface | One process-card color cap. |
| extended product narratives | Process yellow | `#fac541` | `--color-yellow` | surface | One process-card color cap. |
| extended product narratives | Process lime | `#ddf946` | `--color-lime` | surface | One process-card color cap. |
| extended product narratives | Pale lime label | `#eefaa4` | `--color-lime-label` | text | Small closing-call label over dark animated color. |

## Typography

- **ZJSansDisplay** — Sans headline fragments, body copy, captions, labels and controls. An open, rounded contemporary grotesk with conversational proportions; mostly regular weight. If unavailable, use **DM Sans**. Use 400 for most copy, 500 for labels; tune line breaks to preserve the broad editorial measure. Font stack: "ZJSansDisplay", "DM Sans", Arial, sans-serif.
- **FeatureDeckLight** — Literary headline fragments, capability titles and large text-only proof. Fine high-contrast strokes, narrow proportions and graceful true italic, kept visibly light even when declared at 400. If unavailable, use **Instrument Serif**. Use regular and italic; preserve fine strokes rather than synthesizing bold. Font stack: "FeatureDeckLight", "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-serif | FeatureDeckLight | 100 | 90px | 100px | -0.02em | Default opening sentence's serif fragments. |
| display-sans | ZJSansDisplay | 400 | 90px | 100px | -0.02em | Sans fragments in the opening; selected meaning-bearing words are underlined. |
| display-italic | FeatureDeckLight | 100 italic | 90px | 100px | -0.02em | True italic closing phrase in the opening statement. |
| heading-serif | FeatureDeckLight | 100 | 60px | 64px | normal | Large section-heading fragments, capability selector titles and text-only supporter roll. |
| heading-sans | ZJSansDisplay | 400 | 60px | 64px | normal | Sans section-heading fragments and major project promise. |
| statement | ZJSansDisplay | 400 | 40px | 1.2 | normal | Editorial invitation headline, large project descriptions and testimonial text. |
| body-large | ZJSansDisplay | 400 | 24px | 1.6 | normal | Announcement strip, introductory paragraphs and footer column titles. |
| capability-support | ZJSansDisplay | 400 | 24px | 1.5 | normal | Capability-selector support sentence with an opening medium-weight proposition. |
| gallery-caption | ZJSansDisplay | 400 | 24px | 1.25 | normal | Compact outcome statements below media in the horizontal gallery. |
| body | ZJSansDisplay | 400 | 18px | 1.6 | normal | Paragraphs, attribution and ordinary text links. |
| button | ZJSansDisplay | 400 | 18px | 1 | normal | Primary 54px pill. |
| button-small | ZJSansDisplay | 400 | 16px | 1 | normal | Compact newsletter signup pill. |
| tag | ZJSansDisplay | 500 | 12px | 1 | 0.05em, uppercase | Outlined identity labels below proof media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| extended product narratives | product-display | FeatureDeckLight | 400 | 90px | 100px | -0.02em | Centered manifesto opening and large left-aligned editorial calls. |
| system architecture presentations | system-heading | FeatureDeckLight | 400 | 70px | 0.8 | normal | Large sparse panel headings, with enough surrounding space to prevent collisions. |
| extended product narratives | product-heading | FeatureDeckLight | 400 | 52px | 56px | normal | Comparison, capability, process and questions section headings. |
| extended product narratives | closing-serif | FeatureDeckLight | 400 | 52px | 58px | normal | Long closing invitation over dark moving color. |
| capability and case-study chapters | chapter-heading | ZJSansDisplay | 400 | 48px | 56px | normal | Narrative chapter titles and centered project closing question. |
| capability and case-study chapters | chapter-serif | FeatureDeckLight | 100 | 48px | 56px | normal | A single serif word or phrase woven into the chapter headline. |
| extended product narratives | capability-card-title | FeatureDeckLight | 400 | 45px | 51px | normal | Feature carousel titles. |
| system architecture presentations | system-support | ZJSansDisplay | 400 | 27px | 31px | normal | Centered overview and large explanatory text within system panels. |
| extended product narratives | process-title | FeatureDeckLight | 400 | 27px | 32px | normal | Color-cap process-card title. |
| extended product narratives | question | FeatureDeckLight | 400 | 22px | 27px | normal | Question-row text. |
| extended product narratives | card-body | ZJSansDisplay | 400 | 16px | 25px | normal | Process and capability-card explanations. |
| capability and case-study chapters | chapter-label | ZJSansDisplay | 500 | 14px | 1.6 | 0.12em, uppercase | Short chapter label above headline. |
| extended product narratives | product-label | ZJSansDisplay | 500 | 12px | 1.6 | 0.12em, uppercase | Small labels above serif headings. |

**Notes:**

- The serif and sans are equal partners within a line, not separate tiers. Align their baselines and keep their nominal sizes equal.
- Only the 90px display uses -0.02em tracking. Most smaller text remains normally spaced; uppercase labels gain 0.05em or 0.12em according to role.
- The default serif headings are declared at weight 100; the extended product narrative uses the same fine-stroked family at 400. Preserve optical delicacy rather than adding heavy emphasis.
- Large supporter names run as continuous comma-separated prose rather than discrete logos. Use the heading-serif recipe over several lines.

## Layout

**Density:** Airy: short islands of text are separated by generous cream or midnight fields and large media.

### Spacing

| Value | Use |
| --- | --- |
| 16px | Compact heading-to-copy and label-to-title gaps; question-row separation. |
| 20px | Grid gutters and column padding in the main editorial framework. |
| 24px | Gallery captions, chapter-label gaps and product-card gutters. |
| 32px | Header vertical padding, CTA spacing and editorial-panel text inset. |
| 40px | Main wrapper side padding and column gutter. |
| 48px | Heading-to-gallery distance and product section grid separation. |
| 64px | Footer vertical padding and large nested system-panel inset. |
| 120px | Default gallery and capability-selector section breathing room. |
| 128px | Extended narrative band padding above and below. |
| 160px | Spacing between major case-study modules and portfolio items. |
| 240px | Large vertical pause around the centered case-study closing call. |

### Containers and grids

- **Editorial wrapper**: max width 1424px · side padding 40px. Centered wrapper; at 1440px the outer 8px plus internal padding place visible content 48px from each side.
- **Capability split** (only for capability narratives): 2 columns · gap 40px. Two equal text/art columns, about 652px each at desktop, vertically centered; alternate art and text sides.
- **Reading column** (only for case studies): max width 883px. Narrower case-study prose and chapter headings within the wider wrapper.
- **Gallery pair** (only for portfolio indexes): 2 columns · gap 192px. Two 576px-wide columns at desktop, with the second offset vertically; captions occupy less than the full image width.
- **Question column** (only for extended product narratives): max width 1100px. Centered question stack below a left-aligned section heading.
- **Process grid** (only for extended product narratives): max width 1248px · 4 columns · gap 20px. Four cream cards with saturated color caps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Media and editorial panels | 20px |
|  | Action and identity pills | 9999px (pill) |
| extended product narratives | Product cards and question rows | 15px |
| system architecture presentations | System shell | 16px |
| extended product narratives | Carousel arrow controls | 50% |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default marketing page.

**CSS:** `background: #fcfaf3; color: #1a1c2c`

**Observed:** Broad unboxed areas carry text and media without elevation.

**Transfer:** Let whitespace, typography and media define sections rather than wrapping everything in cards.

#### Stone editorial panel · level 1

**Use:** Contained editorial invitation.

**CSS:** `background: #ebe9e4; border-radius: 20px`

**Observed:** A single wide horizontal panel with an image flush to its left edge.

**Transfer:** Use for a useful secondary destination, not every CTA.

#### Midnight canvas · level 0

**Only for:** capability and extended product narratives

**Use:** Inverse long-form storytelling.

**CSS:** `background: #1a1c2c; color: #fcfaf3`

**Observed:** Entire capability narratives and selected product chapters use the inverse palette, including the footer.

**Transfer:** Treat it as a coherent theme, not alternating dark boxes for every feature.

#### Stone band · level 0

**Only for:** extended product narratives

**Use:** Comparison and question sections.

**CSS:** `background: #ebe9e4; color: #1a1c2c; padding: 128px 0px`

**Observed:** Full-width neutral band containing open comparison columns or cream question rows.

**Transfer:** Use to slow the story for evaluation and practical questions.

#### Lavender band · level 0

**Only for:** extended product narratives

**Use:** Interactive capability display.

**CSS:** `background: #bab2ff; color: #1a1c2c; padding: 128px 0px`

**Observed:** A broad colored field frames the cream carousel cards.

**Transfer:** Reserve a full accent field for a clear change in mode.

#### Steel atmosphere · level 0

**Only for:** system architecture presentations

**Use:** Backlight behind nested system panels.

**CSS:** `background: radial-gradient(93.48% 93.48% at 57.53% 10.83%, #a6b5bc 0px, #25283c 82.99%); padding: 128px 0px`

**Observed:** Cool pale light spills from the upper center into charcoal edges.

**Transfer:** Keep contrast strongest at the top and use dark inner shells to recover readability.

#### Translucent system shell · level 1

**Only for:** system architecture presentations

**Use:** Large inset overview and paired architecture panels.

**CSS:** `background: rgba(26, 28, 44, 0.7); border-radius: 16px; padding: 64px; color: #fcfaf3`

**Observed:** A wide shell contains a centered introduction and two darker panels with 15px corners and 24px gap; no drop shadow or frosted-glass blur.

**Transfer:** Explain two complementary parts of a product with substantial space for an original simple diagram.

#### Dark process card · level 1

**Only for:** extended product narratives

**Use:** Small numbered method cards over colored atmospheric media.

**CSS:** `background: #25283c; border: 1px solid rgba(252, 250, 243, 0.18); border-radius: 15px; overflow: hidden`

**Observed:** Text sits above a dark gradient veil over purple-blue moving media.

**Transfer:** Preserve the text-first clarity and subtle edge, using original colored light.

## Components

### Corner navigation

**Use:** Persistent identity and compact menu access.

**CSS:** `display: flex; justify-content: space-between; padding: 32px 40px; max-width: 1424px`

**Observed:** A small two-line identity at left balances a three-line 24px menu control at right. Header wrapper is fixed and 135px high; its foreground follows the theme. It retreats during reading.

**Transfer:** Use the new identity with comparable visual scale rather than a full desktop link bar.

### Primary pill

**Use:** Main conversational conversion action.

**CSS:** `background: #1a1c2c; color: #fcfaf3; border: 2px solid #1a1c2c; border-radius: 9999px; padding: 16px 32px; height: 54px`

**Text style:** `button` — ZJSansDisplay 400 · 18px/1

**Observed:** An isolated short action, left aligned under a capability statement. Inverse theme uses cream fill and border with ink text.

**States:** Declared: hover background-color transparent, color var(--theme-foreground), outline 0px; focus-visible unknown; active matches hover. Transition 0.25s.

### Signup pill

**Use:** Compact action next to a newsletter field.

**CSS:** `background: #1a1c2c; color: #fcfaf3; border: 2px solid #1a1c2c; border-radius: 9999px; padding: 12px 20px; height: 44px`

**Text style:** `button-small` — ZJSansDisplay 400 · 16px/1

**Observed:** Sits on the same baseline as the field, separated by 16px. Reverses to cream in the dark footer.

**States:** Declared: hover background-color transparent, color var(--theme-foreground), outline 0px; focus-visible unknown; active matches hover.

### Identity tag

**Use:** Name the project or proof source below media.

**CSS:** `border: 1px solid #1a1c2c; border-radius: 9999px; padding: 7px 16px; margin-bottom: 16px`

**Text style:** `tag` — ZJSansDisplay 500 · 12px/1 · tracking 0.05em · uppercase

**Observed:** A small outlined capsule above the descriptive outcome sentence, not a filled badge.

### Media tile

**Use:** Proof-gallery and project imagery.

**CSS:** `border-radius: 20px; overflow: hidden; max-width: 100%; transition: transform 0.35s`

**Text style:** `gallery-caption` — ZJSansDisplay 400 · 24px/1.25

**Observed:** Media stands above Identity tag and an outcome caption without a card background. Landscape and portrait formats coexist in a horizontal track. Portfolio indexes enlarge captions to the statement recipe.

**Transfer:** Show tangible outcomes, use context-rich original photography or designed product studies instead of generic thumbnails.

### Capability selector

**Use:** Explain a range of offerings without a dense grid.

**CSS:** `padding: 120px 64px`

**Text style:** `heading-serif` — FeatureDeckLight 100 · 60px/64px

**Observed:** A small current/total number precedes a large serif title, a compact 24px support sentence with an emphasized lead, a Primary pill below, and a right-aligned Next control with a long arrow.

**Transfer:** Use one focused promise per selected item and retain an explicit next control.

### Editorial invitation

**Use:** Promote a publication or deeper perspective.

**CSS:** `background: #ebe9e4; border-radius: 20px; display: flex; align-items: center; max-width: 1093px`

**Text style:** `statement` — ZJSansDisplay 400 · 40px/1.2

**Observed:** A 290px square artwork is flush left; the text side has 32px inset, a short statement and an underlined text action 24px below.

**Transfer:** Pair an original editorial cover or abstract product study with a genuinely useful reading destination.

### Newsletter field

**Use:** Lightweight signup within the footer.

**CSS:** `border-bottom: 2px solid #1a1c2c; opacity: 0.4; padding-bottom: 8px`

**Text style:** `body` — ZJSansDisplay 400 · 18px/1.6

**Observed:** An unboxed single-line email field about 422px wide at desktop, with a floating label and adjacent Signup pill. Inverse theme changes the rule to cream.

### Footer

**Use:** A useful editorial ending, not a giant navigation sitemap.

**CSS:** `padding: 64px 0px`

**Text style:** `body` — ZJSansDisplay 400 · 18px/1.6

**Observed:** A 532px desktop footer repeats in light or dark theme. Social glyphs and two-line address occupy the left, a direct email link the middle, and newsletter signup the right. Below are a small identity mark and a responsibility statement with a certification mark. Tiny legal links and copyright finish at lower right.

**Transfer:** Preserve the asymmetric contact-and-subscription composition; use a truthful responsibility statement appropriate to the product.

### Question row

**Only for:** extended product narratives

**Use:** Practical objections and implementation questions.

**CSS:** `background: #fcfaf3; border: 1px solid rgba(26, 28, 44, 0.12); border-radius: 15px; margin-bottom: 16px; overflow: hidden`

**Text style:** `question` — FeatureDeckLight 400 · 22px/27px

**Observed:** Full-row button with 24px 32px inset, question left and plus/minus right. Closed rows are 82px tall; the first expanded row includes a smaller sans answer and reaches 156px.

**Transfer:** Use real buyer questions; expand in place while preserving the single-column rhythm.

### Color cap process card

**Only for:** extended product narratives

**Use:** Explain stages of an engagement or onboarding.

**CSS:** `background: #fcfaf3; border-radius: 15px; overflow: hidden`

**Text style:** `process-title` — FeatureDeckLight 400 · 27px/32px

**Observed:** An 88px-high saturated color block sits above the cream body with 24px inset. Four cards use coral, yellow, pink and lime caps, serif titles and card-body text.

**Transfer:** Use concise stage names with one practical paragraph, not an illustrated icon in every cap.

### Capability carousel card

**Only for:** extended product narratives

**Use:** Present practical use cases in an editorial carousel.

**CSS:** `background: #fcfaf3; border-radius: 15px; padding: 36px 32px; outline: 1px solid rgba(255, 255, 255, 0.9); outline-offset: -1px`

**Text style:** `capability-card-title` — FeatureDeckLight 400 · 45px/51px

**Observed:** Center card is enlarged to scale 1.18 and fully opaque, about 402px by 409px; neighboring 341px by 347px cards fade to 0.65 and 0.38 opacity. Text uses a serif title and small sans body. Circular 44px previous/next buttons sit underneath.

**States:** Declared: hover on arrow controls background-color rgba(252, 250, 243, 0.5); focus-visible unknown. Card transform 0.45s cubic-bezier(0.22, 1, 0.36, 1), opacity 0.45s.

## Imagery and graphics

### Soft neutral atmosphere

**Use:** Default first-screen background behind the typographic promise.

**Observed:** A nearly monochrome, warm gray cloud field with fine grain fills the viewport. Broad out-of-focus light and shadow add material without a recognizable object or bright glow; dark lettering remains dominant.

**Transfer:** Create the same sense of tactile, softly moving air behind the new promise. This is the minimum opening artwork even when the product has no visual assets.

**Build:** On a cream base, layer two or three oversized radial gradients in rgba(26,28,44,0.06) to rgba(26,28,44,0.14), with transparent edges. Offset the soft shapes across the upper left and lower right, blur the atmosphere layer by 80px, and add an SVG feTurbulence monochrome grain layer at low opacity. Keep contrast low and text on a separate sharp foreground layer; match the soft clouding rather than hard gradient stops.

### Exhibited proof media

**Use:** Horizontal gallery, offset portfolio and case-study storytelling.

**Observed:** Saturated packaging, campaign collages, portrait photography, objects held in hands and real environments are framed with 20px corners. Portrait and landscape media alternate; cream gutters are broad and captions sit outside the image. Long case studies switch between full-width 1440px by 810px views, inset 1113px by 626px views and mismatched square/portrait pairs.

**Transfer:** Photograph the product in human use and show designed outcomes at several scales. For software, combine photographed devices with restrained interface boards; do not reproduce the interface's typography as marketing typography.

### Iridescent editorial cover

**Use:** Square cover within the Editorial invitation and related reading media.

**Observed:** Fine serif cover lettering sits over midnight with translucent flowing ribbons of violet, pink, electric blue and yellow-green. The cover is visually intense but contained inside a single small square beside the much larger neutral text panel.

**Transfer:** Produce an original title treatment with an abstract colored material. Minimum version: fine serif type over two flowing multicolor ribbons, not a generic stock gradient rectangle.

**Build:** Use an SVG path forming two broad S-curves across opposite corners of a square midnight field. Stroke with a blue-to-pink-to-gold gradient, duplicate at lower opacity with 12px blur, then overlay a fine turbulence displacement and subtle grain. Keep the center clear for cream editorial lettering.

### Orbit and system diagrams

**Only for:** capability narratives

**Use:** Large abstract illustrations paired with short capability statements.

**Observed:** Cream hairline circles, dots, brackets, spirals, paths and square grids surround a small softly iridescent sphere on midnight. The art occupies roughly half the section but has ample internal negative space; no rectangular art backing is visible.

**Transfer:** Use a simple diagram for the relationship the product enables. Preserve thin linework and a single spectral focal point rather than adding detailed pictograms.

**Build:** Use a 652px by 560px SVG stage. Draw two concentric cream circles with 2px strokes and small filled nodes, or a sparse 3-by-3 outline grid. Place a roughly 160px circular clipping mask at the center containing blurred blue, pink and gold radial color layers with subtle noise. Other variants can use two overlapping circles, bracket corners or a winding path; keep color localized to the central sphere.

### System and closing light

**Only for:** extended product narratives

**Use:** Atmospheric backdrops for the system reveal, small method cards and final invitation.

**Observed:** The architecture scene has cool steel light above charcoal nested panels and tiny point-and-orbit diagrams. Method cards carry muted purple-blue light through a dark veil. The final invitation uses very dark indigo and violet moving color under cream serif copy, not a photographic scene.

**Transfer:** Create original slow color fields and legible simple diagrams. A static layered gradient is an acceptable minimum when moving media is unavailable.

**Build:** For the system use Steel atmosphere plus Translucent system shell; add a small cream dot and a faint circular stroke as a diagram. For method and closing scenes put oversized blurred blue and pink radial shapes behind a midnight layer, then apply a linear-gradient(rgba(37,40,60,0.75), rgba(37,40,60,0.55)) veil to keep text clear. Use subtle light rather than luminous neon edges.

### Icons

**Observed:** Very few icons: small solid social glyphs at 16px or 18px, a compact 24px three-line menu, and a 45px by 32px right arrow drawn with 2px butt-ended strokes. Plus/minus and chevrons identify question and carousel controls.

**Transfer:** Keep icons monochrome and subordinate. Use a long simple arrow for forward movement; do not introduce a colored feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric sentence opening

**Observed:** A 900px-high Soft neutral atmosphere fills the first screen. Corner navigation overlays the top, with a small two-line identity at left and menu at right. A left-aligned two-line sentence sits around the vertical center, spanning about 85% of the width with an open right margin on its second line. Its sharp 90px display-serif, display-sans and display-italic fragments share 100px line height and -0.02em tracking; selected sans verbs are heavily underlined. Back to front: cream base, grainy cloud field, statement, navigation. There is no separate object, support paragraph or CTA in this screen. The announcement strip starts immediately below the first 900px.

**Transfer:** Write one strong product belief and alternate type by meaning, not mechanically by word. Recreate the subtle atmosphere with CSS/SVG if there is no artwork. For a project story, open with edge-to-edge human-use media before the promise; for a capability page, use a centered 60px sans introduction and a cropped giant serif ticker; for a product manifesto use a centered 90px serif sentence on midnight.

**Avoid:** Do not turn this into a conventional centered headline/subtitle/two-button hero with a dashboard mockup; do not replace the cloudy neutral field with a saturated mesh gradient.

**Text style:** `display-serif` — FeatureDeckLight 100 · 90px/100px · tracking -0.02em

### Announcement rule

**Observed:** A 103px cream strip has 32px vertical padding, a 1px ink bottom rule and an inline 24px title, one-sentence description and underlined reading link.

**Transfer:** Use for one timely product idea or release, keeping the message short enough to read as one horizontal editorial line.

**Text style:** `body-large` — ZJSansDisplay 400 · 24px/1.6

### Mixed heading and proof track

**Observed:** An equal-size serif/sans heading pair sits 48px above a horizontally clipped row of Media tiles. The track mixes 549px by 309px landscapes and 354px by 473px portraits, with Identity tags and 24px outcome captions outside the pictures. Section padding is 152px above and 120px below.

**Transfer:** Show varied but related examples of the product's value; let neighboring items peek past the viewport and retain differing media ratios.

**Text style:** `heading-serif` — FeatureDeckLight 100 · 60px/64px

### Numbered capability focus

**Observed:** Capability selector presents a current/total marker, 60px serif title, 24px support sentence, Primary pill and separate Next arrow. The content has a broad right-side empty field rather than a boxed feature illustration.

**Transfer:** Adapt it to a set of product capabilities, stages or benefits while showing only one fully developed item at a time.

**Text style:** `heading-serif` — FeatureDeckLight 100 · 60px/64px

### Editorial invitation and supporter roll

**Observed:** Editorial invitation is a centered, wide Stone editorial panel. A separate proof block pairs a modest 24px lead with a continuous 60px serif roll of names, flowing across several lines before the footer.

**Transfer:** Include both a deeper point-of-view destination and large textual proof. Replace names with verified supporters, integrations or compact outcome phrases as appropriate.

**Text style:** `heading-serif` — FeatureDeckLight 100 · 60px/64px

### Asymmetric contact ending

**Observed:** Footer uses the page's theme and 64px vertical padding. Contact/social information anchors the left, email sits between columns and newsletter form occupies the right. A responsibility message and mark form a second right-hand block, while a small identity emblem anchors the lower left. Legal material is quiet at lower right.

**Transfer:** Keep the ending useful and personal, preserving the email field, contact route and understated values proof rather than adding a dense sitemap.

**Text style:** `body` — ZJSansDisplay 400 · 18px/1.6

### Alternating diagram chapter

**Only for:** capability narratives

**Observed:** On Midnight canvas, equal 652px columns pair Orbit and system diagrams with a 14px uppercase label, a 48px mixed serif/sans title and 18px explanatory copy. Rows are about 560px high with 160px between them; art switches sides. The opening's oversized cream serif ticker is clipped at both viewport edges, with lettering around 200px high.

**Transfer:** Use each chapter to connect a product capability to a human outcome; retain the diagram's spare geometry and alternating cadence.

**Text style:** `chapter-heading` — ZJSansDisplay 400 · 48px/56px

### Case-study essay and exhibition

**Only for:** case studies

**Observed:** A full-width 16:9 human-use film opens the story, followed by a 24px project name, 60px sans promise and two columns for context and roles. Centered 40px testimonial text provides proof. Later chapters use uppercase 14px labels, 48px sans titles and an 883px reading measure. Full-width media alternates with inset media and offset square/portrait pairs with 20px corners. Outcome prose carries quantified proof in sentences rather than isolated stat tiles.

**Transfer:** Build a paced argument using the problem, approach, outcome and real applications; derive photo pairings from the new product rather than forcing identical content counts.

**Text style:** `chapter-heading` — ZJSansDisplay 400 · 48px/56px

### System explanation and practical adoption

**Only for:** extended product narratives

**Observed:** A serif manifesto opens on midnight, then a cream promise chapter. Stone band supports a two-column old/new comparison. Dark process cards lead to Steel atmosphere and Translucent system shell: centered intro above paired architecture panels. Lavender band holds Capability carousel cards; a later midnight chapter holds four Color cap process cards.

**Transfer:** Separate philosophy, system and practical use. Use scoped themes as chapters, not a requirement to repeat a fixed sequence.

**Text style:** `product-heading` — FeatureDeckLight 400 · 52px/56px

### Questions and closing invitations

**Only for:** extended product narratives

**Observed:** Stone band contains a 52px serif heading and centered 1100px Question row stack, spaced 16px apart with one answer open. A cream reading invitation uses a 90px serif title and small pill. The closing call is a 588px dark moving-color field with 128px vertical padding, pale lime label, 52px/58px serif proposition and cream pill, followed by the dark Footer.

**Transfer:** Answer concrete implementation concerns, offer a deeper resource and close with a human invitation in a distinct atmospheric field.

**Text style:** `closing-serif` — FeatureDeckLight 400 · 52px/58px

### Project closing and continuation

**Only for:** case studies

**Observed:** Credits precede a centered mixed-type 48px question in a roughly 600px section with 240px vertical padding. A plain underlined action sits 29px below. Previous/next project labels and two large 652px by 367px rounded images lead into the cream Footer.

**Transfer:** End the detailed project story with a short invitation, then provide adjacent relevant work without a sales-card grid.

**Text style:** `chapter-heading` — ZJSansDisplay 400 · 48px/56px

## Page flow

**Storyline:** point of view → visible outcomes → capabilities or explanatory chapters → deeper perspective and trust → conversational action and useful contact ending

### Broad marketing landing page

1. **Promise** — Full-screen mixed-type sentence over neutral atmosphere.
2. **Timely context** — Thin announcement strip linking to a deeper idea.
3. **Visible proof** — Mixed-ratio horizontal gallery with outcome captions.
4. **Capabilities** — Numbered serif-title selector with short support and contact pill.
5. **Perspective and trust** — Square-cover editorial panel followed by a large comma-separated supporter roll.
6. **Contact ending** — Light asymmetric footer with direct email and newsletter signup.

**Transfer:** Use a compact narrative with a strong belief, selected proof and one focused way into the offering.

### Evidence-rich project story

1. **Demonstration** — Full-width film of the work in human use.
2. **Framing** — Project promise, context and role list.
3. **Social proof** — Centered testimonial with small attribution.
4. **Narrative chapters** — Opportunity, approach and outcome prose separated by full-width, inset and offset application media.
5. **Outcome proof** — Specific numerical results woven into prose and an underlined source link.
6. **Closing call** — Credits, centered mixed-type question, adjacent-project pair and light footer.

**Transfer:** Alternate explanation and tangible evidence to make a complex product story enjoyable to read.

### Capability overview

1. **Promise** — Centered sans introduction and cream contact pill on midnight.
2. **Expressive orientation** — Oversized cropped serif ticker.
3. **Capability chapters** — Alternating line-art diagrams and mixed-type headlines.
4. **Proof** — Four portrait project cards.
5. **Perspective** — Two reading cards with underlined titles.
6. **Contact ending** — Dark asymmetric footer.

**Transfer:** Use a coherent inverse theme and a family of related diagrams to make abstract capabilities concrete.

### Browsable portfolio index

1. **Visible proof** — Begin directly with staggered two-column media, without a separate manifesto.
2. **Breadth** — Continue mixed portrait and landscape frames, small identity capsules and large outcome statements.
3. **Contact ending** — Last outcome caption gives way to the shared light footer.

**Transfer:** Use offset editorial columns when the work itself is the best introduction; do not add filters or uniform boxed tiles by default.

### Extended product narrative

1. **Point of view** — Centered cream serif manifesto on midnight, then large left-aligned promise on cream.
2. **Differentiation** — Two-column comparison on stone and an atmospheric proposition band.
3. **Method** — Text-first dark chapter with three numbered cards.
4. **System explanation** — Nested architecture panels over steel light.
5. **Practical value** — Lavender capability carousel and four color-cap process cards.
6. **Objection handling** — Long cream question-row stack on stone.
7. **Closing call** — Deeper-reading invitation, dark atmospheric conversion chapter and dark footer.

**Transfer:** Use chapter-level theme changes to move from an idea to a usable system, then remove adoption uncertainty before asking for contact.

## Writing

Confident, thoughtful and culturally alert, with human warmth rather than hard-selling urgency. Abstract ideas are balanced by concrete verbs, practical explanations and specific outcomes.

**Do not copy:** Do not reuse the brand name, identity artwork, client list, proprietary product names, certification claims, project metrics, testimonials or distinctive campaign artwork. Source examples illustrate sentence structure only; write substantiated claims for the new product.

- **Addressing the reader:** Use we for the maker and you/your for the reader when explaining partnership or practical value. Let headlines state beliefs directly rather than repeatedly naming the product.
- **Rhythm:** Short declarative headlines and conversational fragments lead into one-sentence descriptions or a compact paragraph. Contrast paired phrases, use purposeful em dashes, and let occasional longer manifesto sentences carry the large serif treatment.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A belief about growth or change expressed as a human consequence, not a list of features. | 8–14 words | “Brands grow when they mean more to the world.”<br>“A new brand philosophy, made for an age of change.” |
| Capability headline | A compact conceptual pairing or unexpected noun/verb relationship. | 3–7 words | “Meaning, made visible.”<br>“Insights with depth.” |
| Proof caption | An active participle introduces the change created for people or a market. | 9–20 words | “Building a future of sport where every kid feels—and knows—that they belong.”<br>“Restoring the joy of sweetness thanks to breakthrough tech.” |
| Support copy | Explain what the team does, then why that matters; connect systems to people. | One compact paragraph | “We work with brands to find their center, and build systems that carry it through to everything they do.” |
| Primary action | Invite a conversation in plain language. | 2–5 words | “Interested? let’s talk”<br>“Let’s do it” |
| Question | Direct buyer question about implementation, ownership or fit. | 5–14 words | “How does it integrate with our current systems?” |

**Words and phrasing to use:** meaning; people; culture; connection; build; evolve; judgment; possibility; work; systems

**Avoid:** revolutionary all-in-one solution; supercharge; 10x everything; limited-time offer; seamless synergy; disrupt or die

**Rules:**

- Tie every abstract proposition to something the product enables people to do.
- Use paired contrasts to clarify a change: not just launch, but evolve; not merely store, but learn.
- Use precise outcome claims in case studies and restrained invitations in conversion copy.
- Let labels name the chapter; let the headline make its argument.

## Do's and Don'ts

### Do

- Keep the default canvas warm cream with midnight ink, reserving saturated color for exhibited media.
- Set the opening's serif and sans fragments at the same 90px size and 100px line height.
- Use 20px corners consistently on proof imagery and editorial panels.
- Give the primary action a 54px pill with a 2px border and 16px 32px padding.
- Keep gallery identity tags at 12px with 0.05em tracking, distinct from 14px chapter labels.
- Use 120px–160px breathing room between major visual arguments.
- Preserve the 60px serif supporter roll as text, and pair it with a numbered capability focus.
- End with an asymmetric contact and newsletter footer using 64px vertical padding.

### Don't

- Do not replace the fine serif with a bold slab or use 700-weight sans headlines.
- Do not make all media the same landscape ratio or give every image a filled card shell.
- Do not use bright lavender as the default canvas; it is a scoped capability-interaction field.
- Do not add drop shadows to raise cards; this system uses flat fill, edges and contrast.
- Do not inflate small identity capsules into prominent colored category badges.
- Do not apply -0.02em tracking indiscriminately to body copy or the normally spaced 60px headings.
- Do not replace the underlined email field with a rounded filled input box.
- Do not substitute a dense logo grid for the large serif prose treatment of trust.

## Motion and responsive

### Motion

**Observed:**

- Primary and signup pills declare 0.25s transitions; hover removes the fill while preserving the border.
- Media declares transform 0.35s; project-title underlines declare background-size 0.3s using the gold-blue-pink gradient.
- The fixed header declares transform 0.3s ease-in-out and has a hidden position above the viewport.
- Capability carousel cards declare transform 0.45s cubic-bezier(0.22, 1, 0.36, 1) and opacity 0.45s; active and neighboring cards use scale and opacity hierarchy.
- Atmospheric media and oversized text tickers provide ambient movement rather than dense microinteraction.

**Transfer:**

- Keep the selected carousel card fully legible while neighboring cards recede; preserve explicit previous/next controls.
- Use restrained image transforms and fine underline reveals, not bouncing CTAs.
- Keep atmospheric motion behind text; a static cloud field must retain the same material character.

**Unknown:**

- Exact ambient-media timing, ticker speed, autoplay behavior and scroll-trigger sequencing are unspecified.
- Focus-visible styling and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop composition uses a 1424px maximum wrapper with 40px side padding.
- Styles include width breakpoints at 767px/768px and 1023px/1024px among many others; specific narrow-layout rules are not established.

**Transfer:**

- On narrow screens, retain the mixed-type sentence and natural line breaks, reducing display size before sacrificing type contrast.
- Stack capability art and text, preserving one complete diagram per chapter and its single spectral focal point.
- Convert multi-column proof to a readable vertical exhibition while retaining varied ratios; keep the horizontal gallery's intentional peeking only where captions remain readable.
- Stack footer contact and newsletter regions without losing the underlined field and compact pill pairing.

**Unknown:**

- Exact mobile sizes, gutters, navigation overlay contents and carousel breakpoints are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
