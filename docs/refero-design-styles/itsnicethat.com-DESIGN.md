# It's Nice That — curiosity in full colour

## Overview

A bright editorial style that pairs a restrained magazine framework with exuberant creative work. White space, charcoal grotesk headings and literary serif paragraphs give photography, print, illustration and moving images room to speak. Cream utility strips, violet actions and occasional pastel chapters keep the experience sociable rather than corporate. It suits products with a strong creative output, a community or a substantial library of stories.

### Essentials

- The opening sells through an object, not a slogan: a centred 168×55px masthead, compact 161px news strip and a 1059×690px editorial image establish the first impression; the 40px headline follows the image.
- Headlines have the relaxed spread of magazine furniture: regular-weight sans at 40px/48px with 1px tracking, paired with Bradford serif at 17px/25px rather than matching sans body copy.
- Navigation is a floating instrument over the imagery: a 57px-high frosted capsule with 75px corners, 32px backdrop blur and a violet 118×49px Search pill; include an original circular brand badge beside it.
- Colour belongs to editorial framing, not every card: white dominates the reading canvas, cream fills the 64px utility ribbon, violet is concentrated in actions, and selected full-width chapters use pastel washes behind white cards.
- Images are the headline's equal or superior: square-edged, unshadowed editorial media spans 1059px for a lead story and about 339px in three-column collections. With no commissioned photography, stage a real product artefact or a crisp typographic specimen, never an empty decorative panel.
- The ending becomes a dark magazine back cover: a charcoal 560px subscription panel with serif invitation and four compact options leads into a spacious charcoal footer with 15px/26px link columns; use a relevant ongoing relationship instead of a generic sales banner.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#8147ff` | `--color-violet` | action, accent | Search action and text-selection background, not the ordinary page canvas. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link purple | `#6219ff` | `--color-link` | link, text | Tiny category links. |
| Utility cream | `#ffedd1` | `--color-cream` | surface | Four-part utility ribbon across the top. |
| Lilac chapter wash | `#decafb` | `--color-lilac-wash` | background | Chapter backing made with violet-lilac #bc94fb at 0.5 opacity over white; keep the effect softly tinted. |
| Lemon chapter wash | `#faf6b2` | `--color-lemon-wash` | background | Chapter backing made with #f4ec64 at 0.5 opacity over white. |
| Rose chapter wash | `#fad1e1` | `--color-rose-wash` | background | Chapter backing made with #f4a3c3 at 0.5 opacity over white. |
| Apricot chapter wash | `#f9daa2` | `--color-apricot-wash` | background | Chapter backing made with #f3b444 at 0.5 opacity over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Dominant reading canvas, borderless editorial cards and reversed text on dark sections. |
| Frosted white | `#f8f8f8` | `--color-glass` | surface | Visible neutral of rgba(244,244,244,0.64) over white; over media it takes on the image underneath. |
| Feed grey | `#f4f4f4` | `--color-feed` | surface, border | News-strip furniture and directory filter buttons. |
| Metadata grey | `#676767` | `--color-muted` | text | Timestamps, secondary captions and subdued footer credit. |
| Charcoal | `#2b2b2b` | `--color-ink` | text, background, border | Primary reading ink and dark closing surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| curated directory pages | Directory card grey | `#f5f5f5` | `--color-directory-card` | surface | Inset media cards on curated directories. |
| curated directory pages | Directory rule | `#e1e1e1` | `--color-directory-rule` | border | Visible 20% metadata-grey rule over white; use rgba(103,103,103,0.2) over card backgrounds. |
| curated directory pages | Active mint | `#deffd9` | `--color-active-filter` | action, surface | Selected directory filter. |
| searchable archives | Search edge | `#d5d5d5` | `--color-search-edge` | border | Thin archive search outline and selected pagination underline. |

## Typography

- **Labil** — Editorial headings, labels and navigation; use the LabilVariable face for larger editorial text. Friendly open grotesk with rounded counters and loose, regular-weight setting. If unavailable, use **DM Sans**. Use 400 for editorial text and 500 for navigation; preserve the positive tracking. Font stack: "Labil", "DM Sans", Arial, sans-serif.
- **Bradford** — Support paragraphs and editorial standfirsts. Bookish, warm serif contrasting with the matter-of-fact sans headings. If unavailable, use **Libre Caslon Text**. Use regular weight; allow natural paragraph wrapping. Font stack: "Bradford", "Libre Caslon Text", Georgia, serif.
- **GT-Planar** (only for curated directory pages) — Uppercase names and filter controls. Compact geometric sans with a more systematic, exhibition-label character. If unavailable, use **Space Grotesk**. Font stack: "GT-Planar", "Space Grotesk", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Labil | 400 | 40px | 1.2 | 0.025em | fixed | Lead editorial headline and large story panels. |
| heading | Labil | 400 | 25px | 32px | 0.032em | fixed | Section headings, compact landing-page titles and closing invitation. |
| card-title | Labil | 400 | 18px | 23px | 0.0556em | fixed | Multi-line editorial card headlines. |
| body | Bradford | 400 | 17px | 25px | 0.005em | fixed | Lead story support and closing invitation copy. |
| compact-body | Bradford | 400 | 15px | 23px | 0.027em | fixed | Compact introductions and inset story panels. |
| footer-link | Labil | 400 | 15px | 26px | 0.067em | fixed | Footer link columns and contact details. |
| navigation | Labil | 500 | 13px | 1.4 | normal | fixed | Floating navigation and feed header. |
| action | Labil | 400 | 13px | 1.4 | normal | fixed | Search action and small functional controls. |
| caption | Labil | 400 | 13px | 19px | 0.077em | fixed | Secondary labels, subscribe action and cross-links. |
| metadata | Labil | 400 | 11px | 16px | 0.091em | fixed | Category links and timestamps. |
| utility | Labil | 500 | 11px | 1.4 | normal | fixed | Labels beneath utility marks. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| curated directory pages | directory-intro | Bradford | 400 | 35px | 1.4 | 0.0026em | fixed | Centred editorial standfirst. |
| curated directory pages | directory-name | GT-Planar | 400 | 22px | 1.25 | 0.0173em, uppercase | size clamp(20px, 2vw, 22px) | Names in directory cards. |
| curated directory pages | directory-body | Bradford | 400 | 17px | 1.5 | 0.005em | fixed | Short profiles beneath names. |
| curated directory pages | directory-filter | GT-Planar | 400 | 17px | 1.4 | normal, uppercase | size clamp(13px, 1.4vw, 17px) | Centred discipline or category filter. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Positive tracking is a defining feature: do not tighten the larger headlines into a conventional startup display style.
- Keep the sans/serif division intact: sans names the story, serif explains why it matters.
- Use LabilVariable, Labil, sans-serif for display, heading, card-title, caption and footer-link; use Labil, sans-serif for small functional text.

## Layout

**Density:** Airy between editorial chapters, compact inside utility furniture and metadata.

### Spacing

| Value | Use |
| --- | --- |
| 1px | Seams between adjacent utility and editorial cells. |
| 5px | Tight heading-to-label spacing and metadata padding. |
| 10px | Half gutters and compact search padding. |
| 16px | Navigation gaps, news header padding and directory insets. |
| 20px | Image-to-title separation and card text padding. |
| 24px | Directory grid gap. |
| 30px | Closing heading-to-copy separation. |
| 40px | Inset feature panel padding and card bottom breathing room. |
| 60px | Container side padding, chapter starts and inter-chapter separation. |
| 80px | Directory standfirst separation and deep footer rhythm. |

### Containers and grids

- **editorial-container**: max width 1200px · side padding 60px. Centred desktop shell; the 1080px inner area gives roughly 1060px visible media after half gutters.
- **story-collection**: 3 columns · gap 0px. Three 360px editorial cells inside the inner shell, with 10px side insets giving about 339px media widths and 1px cell seams.
- **archive-grid** (only for searchable archives): 5 columns · gap 20px. Dense image-first catalogue with narrower headlines, visible as five columns at desktop.
- **directory-grid** (only for curated directory pages): max width 1200px · 3 columns · gap 24px · side padding 32px. Three approximately 363px cards with square image windows.
- **standfirst** (only for curated directory pages): max width 700px. Centred directory introduction with natural two-line serif wrapping.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | floating-navigation | 75px |
|  | editorial-media | 0px |
| curated directory pages | selected-filter | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-navigation | `0px -11px 15px 0px rgba(0,0,0,0.08), 0px 24px 38px 0px rgba(0,0,0,0.08), 0px 9px 46px 0px rgba(0,0,0,0.08), 0px 11px 15px 0px rgba(0,0,0,0.08)` | Only the floating frosted navigation; editorial cards remain flat. |

### Surfaces

#### Paper canvas · level 0

**Use:** Reading field and editorial cards.

**CSS:** `background: #ffffff`

**Observed:** No decorative card outlines or raised framing.

**Transfer:** Let content and image edges define the layout.

#### Pastel chapter · level 0

**Use:** Full-width backing for a selected collection.

**CSS:** `background: rgba(188,148,251,0.5)`

**Observed:** Soft lilac, lemon, rose and apricot backings sit beneath white editorial cells.

**Transfer:** Choose a single chapter tint rather than applying a rainbow to each card.

#### Dark closing field · level 0

**Use:** Subscription module and footer.

**CSS:** `background: #2b2b2b; color: #ffffff`

**Observed:** The subscription is contained within the editorial width; the footer stretches edge to edge.

**Transfer:** Use a substantial dark ending that carries useful navigation, not a small legal strip.

#### Frosted navigation · level 2

**Use:** Fixed navigation above the media.

**CSS:** `background: rgba(244,244,244,0.64); backdrop-filter: blur(32px); border-radius: 75px; box-shadow: 0px -11px 15px 0px rgba(0,0,0,0.08), 0px 24px 38px 0px rgba(0,0,0,0.08), 0px 9px 46px 0px rgba(0,0,0,0.08), 0px 11px 15px 0px rgba(0,0,0,0.08)`

**Observed:** Underlying imagery visibly colours the frosted capsule.

**Transfer:** Reserve this material for navigation rather than turning all cards into glass.

## Components

### Utility ribbon

**Use:** Related destinations above the main identity.

**CSS:** `background: #ffedd1; height: 64px; padding: 12.5px; display: flex; flex-direction: column; align-items: center; justify-content: space-between`

**Text style:** `utility` — Labil 500 · 11px/1.4

**Observed:** Four equal square-edged cells separated by 1px white seams. Each contains a small destination mark above its descriptive label.

**Transfer:** Use original wordmarks or compact text identities for genuinely related destinations.

### Floating navigation

**Use:** Persistent category access without a bulky fixed header.

**CSS:** `height: 57px; padding: 4px; border-radius: 75px; background: rgba(244,244,244,0.64); backdrop-filter: blur(32px); display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Labil 500 · 13px/1.4

**Observed:** A separate circular identity badge sits at the left. Category links precede the Search pill; on focused archive pages, a short context label replaces the full category list. Desktop wrapper sits 32px above the viewport bottom.

**States:** Declared: hover background-color rgba(0,0,0,0.08) on category links; focus-visible unknown. Category background transition duration is 0.2s.

**Transfer:** Keep one original round badge and a short category vocabulary rather than a full sitemap.

### Search pill

**Use:** Primary functional action within floating navigation.

**CSS:** `background: #8147ff; color: #ffffff; border-radius: 75px; height: 49px; width: 118px; padding: 0px 20px; display: flex; align-items: center; justify-content: center; gap: 12px`

**Text style:** `action` — Labil 400 · 13px/1.4

**Observed:** White outline magnifying glass precedes the label.

**States:** Declared: hover text-decoration none; focus-visible unknown.

### News strip

**Use:** Compact topical proof near the opening.

**CSS:** `background: #f4f4f4; padding: 16px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Labil 500 · 13px/1.4

**Observed:** Header pairs a small title and refresh status with an Explore All link and boxed arrow. Below, three horizontal items pair small square thumbnails with short headlines and source/date furniture.

**Transfer:** Use recent releases, field notes or tangible proof updates; keep this much smaller than the lead image.

### Editorial card

**Use:** Image-led story, use-case or project collection.

**CSS:** `background: #ffffff; padding-bottom: 40px; margin-right: 1px; margin-bottom: 1px; border-radius: 0px`

**Text style:** `card-title` — Labil 400 · 18px/23px · tracking 0.0556em

**Observed:** Image first, then a multi-line title with 20px top separation, timestamp and category links. Images keep varied editorial aspect ratios; cells in a row share their overall backing height.

**Transfer:** Use substantive projects rather than interchangeable feature icons.

### Category link

**Use:** Small taxonomy below editorial text.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 5px 10px; color: #6219ff`

**Text style:** `metadata` — Labil 400 · 11px/16px · tracking 0.091em

**Observed:** Compact rectangular text labels in close rows with 1px spacing; colour carries the navigational emphasis, not a large solid button.

### Subscribe action

**Use:** Conversion within the dark relationship-building panel.

**CSS:** `width: 240px; height: 50px; padding: 15px 20px 16px 20px; color: #2b2b2b; margin-top: 20px; border-radius: 0px`

**Text style:** `caption` — Labil 400 · 13px/19px · tracking 0.077em

**Observed:** A solid backing is painted by a pseudo-element behind the dark label; it is not styled like the violet navigation pill.

**States:** Declared: hover text-decoration none; focus-visible unknown.

### Footer link column

**Use:** Useful browsing and company destinations in the dark ending.

**CSS:** `color: #ffffff; padding: 0px 20px`

**Text style:** `footer-link` — Labil 400 · 15px/26px · tracking 0.067em

**Observed:** Links sit in narrow 176px text columns, with separate columns for primary destinations, social links and company information.

**States:** Declared: hover color #fff and text-decoration-color rgba(160,116,255,0.3); focus-visible unknown. Transition is 0.05s ease-in-out.

### Directory filter

**Only for:** curated directory pages

**Use:** Category selection above a large curated grid.

**CSS:** `background: #f4f4f4; color: #2b2b2b; border: 1px solid #f4f4f4; padding: 16px 32px; height: 58px`

**Text style:** `directory-filter` — GT-Planar 400 · 17px/1.4 · uppercase

**Observed:** Centred wrapping row separated by 1px seams. Active filter has a mint fill and 40px corners; the inactive controls are square.

**States:** Declared: hover border-radius 40px; focus-visible unknown. Transition is border-radius 0.3s cubic-bezier(0.19, 1, 0.22, 1), background 0.3s.

### Directory card

**Only for:** curated directory pages

**Use:** Image-rich profile or curated item.

**CSS:** `background: #f5f5f5; display: flex; flex-direction: column; padding: 16px 16px 8px 16px`

**Text style:** `directory-name` — GT-Planar 400 · 22px/1.25 · tracking 0.0173em · uppercase

**Observed:** Square 331px media window, uppercase name, serif profile, then two ruled information rows. Content is inset another 16px beneath the image with 16px gaps. Information rows use 13px sans and 12px vertical padding.

**Transfer:** Apply to people, collections or carefully selected products with meaningful metadata.

### Archive search

**Only for:** searchable archives

**Use:** Search within a category beside the result count.

**CSS:** `border: 1px solid #d5d5d5; padding: 10px; width: 245px; height: 48px`

**Text style:** `metadata` — Labil 400 · 11px/16px · tracking 0.091em

**Observed:** Small outline magnifier, plain label and a compact category token. The control aligns right while the count aligns left.

## Imagery and graphics

### Editorial artefact stage

**Use:** The lead image and major story media.

**Observed:** An open physical book fills a wide rectangular image, with visible paper, binding and high-contrast printed artwork against a black backing. The image dominates the first screen while the page around it remains white; no rounded frame or artificial UI shell is added.

**Transfer:** Photograph an actual product, publication, tool or output at generous scale. A minimum equivalent is a carefully typeset original specimen presented on a photographed sheet or a sharp flat background, with real content and a deliberate edge.

### Eclectic collection imagery

**Use:** Repeated editorial cards.

**Observed:** Print design, saturated typographic covers, portraits, illustration and documentary photography coexist. The grid is consistent but image ratios and palettes vary; the surrounding typography supplies continuity.

**Transfer:** Select distinct but related outputs, retaining their native colour and material rather than imposing one colour filter on all images.

### Illustrated category banner

**Only for:** culture-led category pages

**Use:** Compact immersive category opening.

**Observed:** A dense mural-like image of figures, architectural details and decorative motifs spans the full page behind white text. A 40% black overlay creates a subdued, cinematic banner rather than a bright wallpaper.

**Transfer:** Use a detailed contextual photograph or commissioned illustration relevant to the new category, with the same darkened framing.

### Curated square art windows

**Only for:** curated directory pages

**Use:** Directory media above profiles.

**Observed:** Square windows show grainy multicolour print, a pale fashion illustration with dark glasses, and a formally staged portrait against dark green. Soft-grey card matting separates these very different image worlds.

**Transfer:** Keep heterogeneous work credible by standardising its square window, inset and caption hierarchy, not by homogenising the work.

### Icons

**Observed:** Sparse functional outline icons: Search is white with 2px strokes, small directional arrows are about 10px with square ends, and the header menu is three simple horizontal lines. The circular identity badge is a separate graphic, not a generic app icon.

**Transfer:** Use simple square-ended arrows and outline search glyphs; make a new circular emblem with comparable black-and-white weight.

## Section recipes

How recurring sections are built.

### First screen: Editorial object opening

**Observed:** White paper is the base. A 64px cream Utility ribbon spans the width, then a centred compact masthead and right-aligned menu complete a 160px header. The News strip fills about 1060px across beneath it, with its 50px header and compact image/text rail. After a substantial white interval, a 1059×690px lead image begins around the middle of the first 900px viewport and continues below it. The display headline follows the image, set in the left three-fifths of the content row, with serif support and category links on the right; neither headline nor support is visible before the first fold. Floating navigation overlaps the image near the bottom of the viewport. Actions above the fold are Menu, Explore All and Search, not an oversized sales CTA.

**Transfer:** Make an original identity masthead, concise topical rail and one strong artefact image the first impression. The first screen can introduce a product through its output before explaining it below. Focused archives instead open with a small outlined heading and serif introduction; immersive categories use a short image banner. Curated directories may lead with a wide campaign film before a centred standfirst.

**Avoid:** Do not substitute a centred giant slogan and two conversion pills above a small mockup, or stretch the masthead into a full-screen logo.

**Text style:** `display` — Labil 400 · 40px/1.2 · tracking 0.025em

### Pastel collection chapter

**Observed:** Pastel chapter backs a centred editorial shell. A heading and tiny category link sit at the top with 60px opening space; Editorial cards form a three-column row with 40px collection padding and 60px separation from adjacent chapters.

**Transfer:** Use colour to identify a content family such as use cases, field stories or advice; keep each card white and typographically consistent.

**Text style:** `heading` — Labil 400 · 25px/32px · tracking 0.032em

### Immersive story panel

**Observed:** A 900px-tall image-led stage carries a left-aligned white panel roughly 648px wide with 40px padding. Display headline sits above compact serif copy and small category links; some promotional panels use a 25px heading and a rectangular Explore action.

**Transfer:** Use a large real scene with a readable inset editorial card for a particularly rich case study. Keep the panel's reading hierarchy even when the artwork is simpler.

**Text style:** `display` — Labil 400 · 40px/1.2 · tracking 0.025em

### Subscription back cover

**Observed:** A contained 1060×560px Dark closing field pairs a roughly 408px copy/form area on the left with 530×560px moving media on the right. Heading, serif invitation, four compact subscription rows and Subscribe action are stacked with 30px and 40px separations.

**Transfer:** Offer a continuing editorial relationship, updates or useful membership. Use an original moving artwork or product-output film as the other half, with a considered still when motion is unavailable.

**Text style:** `heading` — Labil 400 · 25px/32px · tracking 0.032em

### Deep closing navigation

**Observed:** The full-width Dark closing field continues into a 790px footer, separated from the prior module by 60px. Contact and three link groups sit within the shared shell; 176px text columns and 15px/26px type make the footer readable. A lower statement row and muted small credit finish the page with substantial bottom space.

**Transfer:** End with contact, a compact sitemap, social destinations and necessary organisational information. Directory pages go straight from their grid to this footer without the subscription panel.

**Text style:** `footer-link` — Labil 400 · 15px/26px · tracking 0.067em

### Archive introduction and catalogue

**Only for:** searchable archives

**Observed:** Outlined 40px-high heading tag uses heading type, 1px charcoal border and asymmetric 15px/16px side padding with 6px bottom padding. Serif introduction follows after 40px. A count/search row precedes a five-column image-first archive. Centred 15px pagination has 20px padding per number, 60px above and below, and a subtle active underline.

**Transfer:** Use when a new product has a substantial searchable library, not as the default promotional hero.

**Text style:** `heading` — Labil 400 · 25px/32px · tracking 0.032em

### Curated directory chapter

**Only for:** curated directory pages

**Observed:** A 700px-wide centred serif standfirst is separated by 80px from adjacent blocks. Directory filter sits above Directory cards with 72px space before the grid. Three columns and 24px gaps give a measured exhibition-catalogue rhythm.

**Transfer:** Use a short curation promise, meaningful filters and substantive profile information. The campaign media can be a custom film or a still sequence; keep it specific to the collection.

**Text style:** `directory-intro` — Bradford 400 · 35px/1.4 · tracking 0.0026em

## Page flow

**Storyline:** identity and timely context → tangible output → curated stories and deeper immersion → ongoing relationship → useful closing navigation

### Broad editorial landing page

1. **Orientation** — Utility ribbon, masthead and compact topical strip.
2. **Tangible proof** — Large artefact image before the lead headline and supporting explanation.
3. **Capability chapters** — Repeated editorial groups, pastel-backed collections and immersive feature panels.
4. **Continued discovery** — A further reading collection before the conversion module.
5. **Closing invitation** — Dark subscription back cover followed by deep footer columns.

**Transfer:** Lead with real output, organise the middle by reader interests and close with a useful ongoing connection.

### Immersive category destination

1. **Context** — Short darkened illustrated banner with outlined title and serif description.
2. **Curated proof** — Three-column editorial series alternate with full-height feature panels.
3. **Special feature** — A distinct dark video-series area with wide graphic title and centred introduction.
4. **Closing invitation** — Subscription back cover and shared footer.

**Transfer:** Use richer atmosphere for a category with a coherent visual world, while preserving the editorial card grammar.

### Searchable content archive

1. **Orientation** — Compact outlined heading and serif introduction.
2. **Discovery control** — Result count and category search.
3. **Breadth of proof** — Five-column story catalogue followed by centred pagination.
4. **Closing invitation** — Subscription back cover then deep footer.

**Transfer:** Make browsing efficient; let the catalogue replace long marketing exposition.

### Curated campaign directory

1. **Campaign identity** — Wide film stage.
2. **Curation promise** — Centred large serif standfirst.
3. **Discovery control** — Uppercase filter row with rounded mint active selection.
4. **Detailed proof** — Extensive three-column profile grid with square art and ruled metadata.
5. **Closing navigation** — Shared dark footer without a subscription block.

**Transfer:** Use a distinct catalogue look for a curated launch or collection rather than imposing campaign fonts on normal landing pages.

## Writing

Curious, informed and warmly conversational. It celebrates the specifics of how something was made, with editorial confidence rather than superlative sales claims.

**Do not copy:** Do not reuse the brand name, logos, face emblem, destination identities, artist names, article titles, quotations, proprietary imagery or claims such as audience totals, archive counts and years. Source examples illustrate voice only.

- **Addressing the reader:** Headlines usually describe a subject in the third person; invitations turn directly to you. First-person plural is used for the editorial team's curation and invitation.
- **Rhythm:** Long, descriptive headlines can carry a colon, quote or concrete mechanism; compact labels use plus signs. Support is usually one substantial sentence or a short paragraph. Actions are exceptionally short.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Lead headline | Name the subject and the intriguing process or tension; explain rather than announce. | About 12–20 words | “Source Type’s Dictionary of the Illegible explores what happens when typography stops making sense” |
| Section heading | Plain paired nouns linked with a plus sign. | 2–4 words | “Projects + Creatives”<br>“Resources + Advice” |
| Invitation | Friendly question followed by a concrete reason to stay in touch. | Two conversational sentences | “Fancy a bit of [Brand] in your inbox? Sign up to our newsletters and we'll keep you in the loop with everything good going on in the creative world.” |
| Action | Direct functional verb, no inflated promise. | 1–2 words | “Explore All”<br>“Subscribe” |
| Profile | Location-based subject plus an active verb describing a distinctive practice. | One sentence | “Moscow-based graphic designer combining analogue printing techniques with subversive editorial systems.” |

**Words and phrasing to use:** explore; meet; inside; made by hand; process; world; in the loop

**Avoid:** revolutionary platform; unlock limitless potential; industry-leading solution; 10x your workflow; disrupt everything

**Rules:**

- Describe tangible work, people and mechanisms before abstract benefits.
- Use an editorial question or a concrete contrast to earn interest.
- Keep controls literal even when story titles are playful.
- Use numbers only when they support a verifiable editorial detail.

## Do's and Don'ts

### Do

- Keep large editorial type at weight 400 and 40px/48px with positive 1px tracking.
- Pair the sans headline with 17px/25px serif explanatory copy.
- Give the lead artefact about 1060px of width inside the shared desktop shell.
- Use 1px seams and square edges for editorial collections.
- Keep the floating control 57px high with a 49px violet action inside.
- Use 60px and 80px spacing for chapter-level breathing room.
- Preserve the charcoal closing field and narrow readable footer columns.
- Reserve 24px grid gaps and uppercase geometric names for curated directories.

### Don't

- Do not make the main typography bold, condensed and tightly tracked; the regular open setting is essential.
- Do not round every card to match the navigation's 75px capsule.
- Do not apply navigation shadows to the editorial media.
- Do not fill the ordinary reading canvas with violet; concentrate it in actions and selection.
- Do not replace varied editorial aspect ratios with identical software-thumbnail mockups.
- Do not use sans paragraphs throughout; the serif voice is part of the design.
- Do not turn category labels into oversized conversion buttons.
- Do not reduce the dark ending to a thin legal bar.

## Motion and responsive

### Motion

**Observed:**

- Floating navigation has a declared 0.3s transition; category backgrounds have a 0.2s transition.
- Directory filter corners transition for 0.3s with cubic-bezier(0.19, 1, 0.22, 1); background transitions for 0.3s.
- Footer links declare 0.05s ease-in-out; the Explore promotional action declares filter 0.2s ease-in-out and hover saturate(80%) brightness(120%).

**Transfer:**

- Keep movement local to utility surfaces and image-led media. Preserve the corner-morphing filter interaction on directory variants.

**Unknown:**

- Playback timing, media choreography, scroll-linked effects and focus-visible treatment are not specified.

### Responsive

**Observed:**

- Shared declared width breakpoints include 660px, 767px, 768px, 900px, 1080px, 1400px and 1480px.
- Directory names use clamp(20px, 2vw, 22px); filters use clamp(13px, 1.4vw, 17px).
- Desktop navigation category links are hidden by a small-screen utility class; directory controls use flex-wrap.

**Transfer:**

- On narrow layouts retain the circular identity and Search capsule while reducing contextual category furniture.
- Recommended adaptation: stack image before text, move three-column collections to fewer columns and let filter labels wrap without shrinking their hit areas.

**Unknown:**

- Exact mobile layouts, side gutters, breakpoints for individual grid changes and media crops are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
