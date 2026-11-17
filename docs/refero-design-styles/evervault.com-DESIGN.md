# Evervault — electric infrastructure theater

## Overview

A near-black technical world lit by pools of electric violet, with restrained grotesk typography and small, matter-of-fact interface text. It suits developer infrastructure and complex products that benefit from visible mechanisms rather than lifestyle imagery. Product interfaces, luminous diagrams and translucent objects give the spacious marketing canvas a working-system feel; dense information stays inside clearly bounded modules.

### Essentials

- Headlines feel like calm statements above live machinery: Roobert at 56px/1.2, weight 500 and -0.02em tracking, with 40px/1.2 section headings rather than oversized bold display type.
- The opening is a centered promise followed by proof and a working interface: a two-line headline, 24px to its support, 36px to paired actions, a monochrome logo strip and a wide two-panel demonstration entering the first 900px.
- Actions are small luminous capsules, not purple rectangles: 40px height, 24px radius, 16px side padding, near-white primary fill and white at 6% secondary fill, with a small right arrow on the primary.
- Violet behaves as light on a mostly dark page: #010314 is the canvas, #6633ee and #8e64ff illuminate selected corners, objects and a substantial closing field; ordinary copy and most section area remain neutral.
- Technical illustrations are staged as physical interface objects: 16px rounded dark panels, fine highlights, floating overlays and purple backlight. Every new landing page includes a legible product mechanism; when no polished media exists, use a simplified HTML interface and SVG connection diagram.
- The page is an instrument panel at architectural scale: 1200px framing, 1px rules with tiny crosshair intersections, occasional vertical edge captions and faded bands of 10px mono characters tracked at 6.1px. Preserve these devices alongside a violet-lit closing call with 50px lower corners.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#6633ee` | `--color-violet` | accent, background, surface | Light fields, graphic cores, active demo controls and small announcement badges. |
| Deep purple atmosphere | `#0a0024` | `--color-top-glow` | background | Subtle top-of-page atmosphere fading into midnight. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet light | `#8e64ff` | `--color-light-violet` | accent, link | Outer light in gradients, text links and selected product controls. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White light core | `#ffffff` | `--color-white` | text, accent | Hot centers of graphic glows, logos and secondary button lettering. |
| Soft white | `#e6e6e8` | `--color-primary-text` | text, action | White at 90% over midnight; primary headings and light action fills. Use the alpha recipe for overlays. |
| Pale gray | `#cccdd0` | `--color-secondary-text` | text | White at 80% over midnight; card subheads, quotes and supporting emphasis. |
| Lavender gray | `#b1b3c3` | `--color-heading-muted` | text | Muted clauses paired with bright clauses in a headline. |
| Smoke | `#999aa1` | `--color-body-text` | text | White at 60% over midnight; explanatory paragraphs. |
| Slate caption | `#8e8fa0` | `--color-caption` | text, link | Compact metadata and understated secondary links. |
| Dim gray | `#80818a` | `--color-muted-text` | text | White at 50% over midnight; footer links and de-emphasized labels. |
| Violet ash | `#6b6580` | `--color-subtle-caption` | text | Announcement explanations and very low-emphasis labels. |
| Architectural rule | `#32354d` | `--color-frame` | border | Section frame lines and technical connectors. |
| Panel edge | `#1d1f2e` | `--color-edge` | border | Hairline panel boundaries and announcement separators. |
| Lavender glass | `#141329` | `--color-form-wash` | surface | Lavender #bea7ff at 10% over midnight in the newsletter form. |
| Faint panel wash | `#101222` | `--color-wash` | surface | White at 6% over midnight; secondary buttons and broad subdued panels. |
| Raised midnight | `#0b0d1c` | `--color-panel` | surface | Dark UI panels and navigation glass, the latter at 80% opacity. |
| Barely raised wash | `#060819` | `--color-faint-wash` | surface | White at 2% over midnight; compact capability tiles. |
| Midnight blue-black | `#010314` | `--color-canvas` | background, text | Default page canvas and text on light buttons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer directories | Directory grid edge | `#2a2b3a` | `--color-grid-edge` | border | One-pixel gutters separating directory cells. |
| pricing pages | Deep plan violet | `#2b078f` | `--color-plan-core` | background | Dark end of the featured plan gradient. |

## Typography

- **Roobert** — Headlines, card titles and uppercase quote attributions. Rounded, open geometric grotesk with a distinctive single-storey feel; medium weight stays approachable despite the technical setting. If unavailable, use **DM Sans**. Use 500 and 600, retaining tight display tracking and open counters. Font stack: "Roobert", "DM Sans", sans-serif.
- **Inter** — Paragraphs, actions, navigation, labels and footer. Compact neutral sans with high legibility at small interface sizes. Font stack: "Inter", sans-serif.
- **IBM Plex Mono** — Decorative character bands between chapters. Widely tracked uppercase monospace creates a faint data texture rather than body copy. Font stack: "IBM Plex Mono", monospace.
- **Geist Mono** (only for product-page testimonials) — Centered customer quotations. Plainspoken technical monospace makes a testimonial feel like an operator's statement. Font stack: "Geist Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Roobert | 500 | 56px | 1.2 | -0.02em | Primary opening and closing promises; two or three controlled lines. |
| stat | Roobert | 500 | 56px | 1.1 | -0.02em | Outcome cards; a short verbal result can occupy the same role as a percentage. |
| heading | Roobert | 500 | 40px | 1.2 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Section leads and the large centered testimonial. |
| subheading | Roobert | 500 | 29.6px | 1.2 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Card benefits, process steps and newsletter heading. |
| lead | Inter | 400 | 19.2px | 28px | -0.02em | Closing support and split product-hero support. |
| body | Inter | 400 | 16px | 1.5 | -0.02em | Marketing explanations and the default opening support. |
| feature-label | Inter | 600 | 16px | 1.45 | -0.02em | Small benefit headings, FAQ questions and commercial values. |
| button | Inter | 500 | 14.4px | 16px | -0.02em | Primary and secondary action capsules. |
| attribution | Roobert | 600 | 14.4px | 1.2 | 0.04em, uppercase | Attribution beneath the large marketing testimonial. |
| footer-heading | Inter | 500 | 14.4px | 1.45 | normal | Footer column names. |
| footer-link | Inter | 400 | 14.4px | 28px | normal | Dense but unhurried footer link lists. |
| form-action | Inter | 500 | 14px | 1 | normal | Newsletter submit action. |
| eyebrow | Inter | 600 | 13px | 14px | 0.05em, uppercase | Compact foundation or category statements; not required above every heading. |
| caption | Inter | 400 | 12.8px | 1.4 | normal | Navigation, short card explanations and metadata. |
| data-band | IBM Plex Mono | 400 | 10px | 1.6 | 0.61em, uppercase | Two-line decorative alphanumeric ribbons, clipped to a center-bright fade. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer directories | story-title | Roobert | 500 | 20px | 1.3 | -0.01em | Multi-line story titles in the proof directory. |
| product-page testimonials | mono-quote | Geist Mono | 400 | 20px | 1.2 | normal | Centered quotation beneath a monochrome customer mark. |

**Notes:**

- Display and headings use medium, not bold. Inter paragraphs and action labels share -0.02em tracking; uppercase metadata reverses this to positive tracking.
- Use soft white as the headline default. A muted lavender-gray clause can precede a bright conclusion without changing size or weight.
- Keep the 56px outcome treatment separate from the ordinary 40px section heading; product-interface text remains subordinate and should not become a second marketing type scale.

## Layout

**Density:** Airy outside, compact inside: chapter spacing is substantial while technical controls and labels remain tightly packed.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact tile padding. |
| 10px | Feature label-to-description spacing and logo-strip gaps. |
| 12px | Action-pair gap and short heading-to-support spacing. |
| 18px | Three-card grid gutters and stacked capability tile gaps. |
| 24px | Main heading-to-body separation and information-card padding. |
| 32px | Outcome card internal padding. |
| 36px | Opening support-to-action separation. |
| 40px | Plan-card padding. |
| 48px | Section side inset, heading-to-grid gap and common feature-column gutter. |
| 64px | Secondary chapter padding and quote section breathing room. |
| 80px | Footer top padding and widely separated process steps. |
| 120px | Major chapter vertical padding and closing-call vertical padding. |

### Containers and grids

- **main-container**: max width 1200px · side padding 48px. Centered architectural frame. At 1440px the outer frame has 120px margins; inset content is commonly 48px inside that frame.
- **reading-container**: max width 800px. Centered opening-copy stack, FAQs and product testimonials; text can be set narrower within it to preserve short lines.
- **outcome-grid**: max width 1104px · 3 columns · gap 18px. Three equal 356px-wide proof or use-case cards within the main frame.
- **feature-grid**: 3 columns · gap 48px. Unboxed benefits beneath a rule or product illustration; icons align with the small heading.
- **plan-grid** (only for pricing pages): max width 1200px · 2 columns · gap 18px. Equal-height featured and custom plan panels, each nested within a fine outer frame.
- **directory-grid** (only for customer directories): max width 1200px · 3 columns · gap 1px. Continuous story and logo matrix, using colored gutters as borders.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-capsules | 24px |
|  | product-panels | 16px |
|  | capability-tiles | 4px |
|  | information-cards | 12px |
|  | chapter-light-field | 50px |
|  | newsletter-form | 500px |
| split product heroes and full-width closing calls | split-hero-and-wide-close | 44px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| panel-highlight | `0px 0px 0px 2px rgba(0,0,0,0.05), 0px 0px 0px 1px rgba(255,255,255,0.1), 0px 0.5px 0px 0px rgba(255,255,255,0.5) inset` | Thin physical edge on dark hero interface panels. |
| floating-navigation | `0px 2px 7.6px 0px rgba(0,0,0,0.3)` | Subtle separation of the navigation capsule from the page. |

### Surfaces

#### Midnight canvas · level 0

**Use:** Default background for marketing pages.

**CSS:** `background: linear-gradient(#0a0024 0%, #010314 7%)`

**Observed:** A purple-black atmosphere at the top quickly resolves to an almost black navy field.

**Transfer:** Keep ordinary information chapters dark; use luminous fields as punctuation.

#### Corner-lit chapter · level 0

**Use:** A major capability overview.

**CSS:** `background: radial-gradient(115.017% 55.492% at 107% -3.2%, #8e64ff 0%, #6633ee 25%, rgba(0,0,0,0) 62.5869%); border-radius: 50px; max-width: 1200px`

**Observed:** The light occupies the upper-right corner, leaving the heading and lists on dark ground.

**Transfer:** Anchor a single violet pool opposite the main text instead of evenly coloring the entire chapter.

#### Machined dark panel · level 1

**Use:** Hero product interfaces and detached technical controls.

**CSS:** `background: #0b0d1c; border: 1px solid #1d1f2e; border-radius: 16px; box-shadow: 0px 0px 0px 2px rgba(0,0,0,0.05), 0px 0px 0px 1px rgba(255,255,255,0.1), 0px 0.5px 0px 0px rgba(255,255,255,0.5) inset`

**Observed:** Fine inset highlights and layered outlines give otherwise flat interface panels a physical rim.

**Transfer:** Use sparingly around the main demonstration, not around every paragraph.

#### Lower-left closing light · level 0

**Use:** Default final conversion section.

**CSS:** `background: radial-gradient(135% 65.7035% at 1.84783% 102.295%, #8e64ff 0%, #6633ee 25%, rgba(0,0,0,0) 62.5869%); border-radius: 0px 0px 50px 50px; padding: 120px 48px; max-width: 1200px`

**Observed:** A dark upper portion gives way to violet light at the lower left, behind centered text and a small light action.

**Transfer:** Make the closing field a substantial destination, not a thin colored banner.

#### Wide basin light · level 0

**Only for:** split product heroes and full-width closing calls

**Use:** Broader violet stage for product-specific promises and final actions.

**CSS:** `background: radial-gradient(176% 113% at 48.1% 6.1%, rgba(1,3,20,0) 39.0608%, #6633ee 73%, #8e64ff 100%); border-radius: 44px; padding: 120px 48px`

**Observed:** Closing fields nearly span the viewport with a narrow outer margin. Split heroes use a related bottom-lit radial treatment and rounded lower corners.

**Transfer:** Reserve the near-full-width wash for a strong conversion moment or a two-column product stage.

#### Featured plan light · level 1

**Only for:** pricing pages

**Use:** Highlight the self-serve plan against a neutral enterprise panel.

**CSS:** `background: radial-gradient(129% 174% at 50% -7.7%, #2b078f 0%, #6633ee 58%, #ffffff 94.8815%); padding: 40px; opacity: 0.9`

**Observed:** The plan is a tall saturated violet block; its sibling uses white at 6%. Both sit within thin squared frames and pin actions near the bottom.

**Transfer:** Use one lit plan rather than competing accents across all plans.

## Components

### Floating navigation

**Use:** Persistent compact site navigation.

**CSS:** `background: rgba(11,13,28,0.8); backdrop-filter: blur(8px); border-radius: 9999px; padding: 8px; gap: 2px; height: 42px; box-shadow: 0px 2px 7.6px 0px rgba(0,0,0,0.3)`

**Text style:** `caption` — Inter 400 · 12.8px/1.4

**Observed:** At the top, the logo sits left, the navigation is centered and login plus a light CTA sit right. After scrolling, the controls consolidate into a floating centered capsule. Individual links have 4px vertical and 12px horizontal padding.

**Transfer:** Keep navigation visually small enough that the product scene remains dominant.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: rgba(255,255,255,0.9); color: #010314; border-radius: 24px; padding: 0px 16px; height: 40px; gap: 4px; backdrop-filter: blur(8px)`

**Text style:** `button` — Inter 500 · 14.4px/16px · tracking -0.02em

**Observed:** Label followed by a small right arrow; width follows content. The text is slightly softened within the light capsule.

**Transfer:** Use one bright action per action group.

### Secondary button

**Use:** Documentation, self-serve entry or secondary sales route.

**CSS:** `background: rgba(255,255,255,0.06); color: #ffffff; border-radius: 24px; padding: 0px 16px; height: 40px; backdrop-filter: blur(8px)`

**Text style:** `button` — Inter 500 · 14.4px/16px · tracking -0.02em

**Observed:** A low-contrast capsule beside the brighter primary, normally without the prominent arrow.

### Capability tile

**Use:** Compact linked building blocks in a capability overview.

**CSS:** `background: rgba(255,255,255,0.02); border-radius: 4px; padding: 8px; min-height: 66px`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.02em

**Observed:** A pale technical icon sits left of a two-line text stack: normal-sized title and 12.8px descriptive caption. Tiles collect in columns under uppercase category names.

**Transfer:** Use concise capability names and descriptions, with one restrained icon family.

### Outcome card

**Use:** Quantified proof or a short verbal outcome.

**CSS:** `background: #010314; padding: 32px; overflow: hidden; position: relative`

**Text style:** `stat` — Roobert 500 · 56px/1.1 · tracking -0.02em

**Observed:** Tall 356px by 565px cards put a customer mark at the top, a large result near the middle, a 29.6px benefit and compact explanation beneath, then a violet story link near the bottom. Each has its own off-center light pool and fine visual boundary.

**Transfer:** Keep the same hierarchy for a verbal result when a credible metric is unavailable; recreate the light using the Soft violet pools imagery recipe.

### Newsletter capsule

**Use:** Footer email acquisition.

**CSS:** `background: rgba(190,167,255,0.1); border: 1px solid rgba(143,143,143,0.1); border-radius: 500px; box-shadow: 0px 0px 0px 1px rgba(190,167,255,0.12) inset; height: 40px; max-width: 400px; padding-left: 6px`

**Text style:** `caption` — Inter 400 · 12.8px/1.4

**Observed:** A single subdued email field shares one rounded outline with the submit action at the right, below a newsletter heading and short support line.

**Transfer:** Keep the input integrated into the footer rather than turning it into a separate bright card.

### Newsletter submit

**Use:** Submit action inside the newsletter capsule.

**CSS:** `background: rgba(190,167,255,0.1); color: #ffffff; border-radius: 100px; height: 38px; padding: 12px 24px`

**Text style:** `form-action` — Inter 500 · 14px/1

**Observed:** The action reads as a slightly denser end cap inside the form.

**States:** Declared: hover background-color rgba(190,167,255,0.25); focus-visible unknown.

### Footer link column

**Use:** Grouped secondary navigation at the page ending.

**CSS:** `color: rgba(255,255,255,0.5); display: flex; flex-direction: column`

**Text style:** `footer-link` — Inter 400 · 14.4px/28px

**Observed:** Small brighter category headings precede unadorned text links. The product list is longest; company and resource lists are shorter, with legal and compliance links stacked under the right side.

### Plan panel

**Only for:** pricing pages

**Use:** Featured commercial offer.

**CSS:** `background: radial-gradient(129% 174% at 50% -7.7%, #2b078f 0%, #6633ee 58%, #ffffff 94.8815%); padding: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `subheading` — Roobert 500 · 29.6px/1.2

**Observed:** Plan name, fit statement and recommended usage come first; icon-led inclusions fill the middle; the price and actions sit low. The neighboring custom offer uses the neutral wash, not a second saturated gradient.

**Transfer:** Keep the commercial hierarchy and equal panel heights while replacing all offer details.

### Story directory cell

**Only for:** customer directories

**Use:** Case-study browsing and proof catalogs.

**CSS:** `background: #010314; padding: 24px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `story-title` — Roobert 500 · 20px/1.3 · tracking -0.01em

**Observed:** A square character-field graphic and centered monochrome mark occupy the top. A small customer label, multi-line title and dim story link follow. Continuous 1px gutters define the matrix; the plain logo matrix below uses shorter cells.

**Transfer:** Keep a consistent graphic treatment across stories rather than mixing unrelated photography.

## Imagery and graphics

### Working product scene

**Use:** Main demonstration beneath the opening and larger capability illustrations.

**Observed:** A small vertical control panel sits alongside a broad transaction-like table on midnight ground, with rounded machined edges, miniature status marks and restrained violet controls. Later scenes use a large violet object with a floating black translucent inspector; grain, faint characters and purple backlight give depth without photography.

**Transfer:** Show the new product's actual workflow with a few legible controls, records and outcomes. Minimum acceptable equivalent: two carefully built HTML panels with truthful example data, one small floating inspector and a violet-lit backing; do not rely on a generic dashboard thumbnail.

**Build:** Use the Machined dark panel surface for a roughly 312px control module beside an approximately 872px-wide record panel. Add hairline row separators, tiny mono identifiers and one selected violet control. For a conceptual scene, center a rounded rectangular product object over a top-bright violet radial field and overlay a dark 318px-wide inspector with a soft black shadow.

### Soft violet pools

**Use:** Outcome cards, use-case art and major chapter corners; a recurring signature light treatment.

**Observed:** Bright violet blooms enter from different card edges, with a small white-hot source that diffuses into purple and then disappears into navy. Some pools sit behind cropped phone or interface fragments rather than becoming standalone decoration.

**Transfer:** Keep light localized and asymmetric; vary its origin across a row while preserving the common palette. A CSS gradient with blur is sufficient.

**Build:** Place an absolute layer behind content. Use radial-gradient(360px 360px at calc(50% - 180px) calc(50% - 270px), #ffffff 0%, #6633ee 38%, #010314 78%), filter blur(40px), and about 0.8 opacity. Use 500px radii and move the source toward the top right or below the card for siblings. Clip within the card; keep text on a dark portion.

### Architectural frame and data ribbons

**Use:** Chapter framing and transitions; both recur as signature devices.

**Observed:** Thin straight rules bound 1200px-wide chapters; small plus-shaped intersections mark corners and narrow vertical category captions sit just outside the content. Between selected chapters, two rows of tiny widely tracked characters fade at both ends.

**Transfer:** Frame substantive product chapters, with meaningful short edge labels. Generate fresh decorative characters for the ribbons; keep them subdued enough to remain texture.

**Build:** Draw 1px #32354d SVG lines with 8px crosshairs at the outer corners and fading short extensions. Keep the content 48px inside the frame. Render two lines with the data-band recipe in a 1200px-wide, 32px-high text region; clip a transparent-to-white-at-60%-to-transparent horizontal gradient to text, with the bright stop near 55%. The containing strip can be 48px tall.

### Mechanism diagrams

**Only for:** technical product explanations

**Use:** Interactive flow comparisons and implementation explanations.

**Observed:** Dotted connectors join dark rounded nodes; violet highlights the product path, green indicates success, red failure and yellow exceptions. Nodes are compact and luminous at the edges. A larger flow board pairs the diagram with 56px outcomes and a slim vertical bar comparison.

**Transfer:** Diagram the new product's real decision paths. Keep semantic hues within the mechanism and make the surrounding marketing explanation neutral.

**Build:** Use SVG dotted elbow connectors beneath HTML nodes about 150px by 76px. Give neutral nodes white-at-2% backgrounds and 10px corners. Use low-opacity colored fills with inset glows on active states; place small dots at connector ports. Pair with a short label and restrained stacked bars, not a decorative full-page network.

### Glass device stage

**Only for:** split product heroes

**Use:** A product-specific opening object.

**Observed:** One scene has a translucent purple phone shell with rounded glass edges and a compact checkout inside. Another uses a wide frosted rim around pale and dark interface panels, extending beyond the right edge of the stage. The object balances the left text and sits over the bottom-lit violet basin.

**Transfer:** Use a single device or framed interface relevant to the new product, not an unrelated phone mockup. Minimum equivalent is a crisp interface panel with a translucent rim and subtle purple inset light.

**Build:** For a phone, make a 320px by 568px rounded shell with 40px corners, 10px inset, a violet-to-transparent top wash and 12px backdrop blur. Add a thin gradient rim and purple inner highlights, then place the interface inside. For a wide stage, use a 16px translucent white rim and about 38px outer corners.

### Character halo proof art

**Only for:** customer directories

**Use:** Uniform story art and the directory's abstract hero.

**Observed:** Story cards center white customer marks within square fields of dark alphanumeric characters. A soft central dark disk clears the mark; faint violet and pale highlights form a peripheral halo. The opening uses a small perspective stack of glossy dark logo tiles edged in violet rather than a photographic montage.

**Transfer:** Use approved partner marks or short typographic identifiers on a consistent data field. If a three-dimensional stack is unavailable, use overlapping dark tiles with a modest perspective transform and purple edge light.

**Build:** Fill a 351px square with 11px mono characters at about 2.6px tracking. Mask a 135deg violet-white-violet gradient into the characters and darken it with a radial overlay. Place a blurred 245px midnight disk at the center, then a clean white mark above it. Keep the field low contrast.

### Icons

**Observed:** Small arrows accompany conversion and story links. Capability art uses pale wireframe geometric objects inside fine square brackets; benefit icons are simpler monochrome line symbols. Utility outline icons are commonly 16px with 1.5px round strokes; larger capability marks are about 36px.

**Transfer:** Choose a coherent fine-line geometric icon set, use 16–24px benefit icons and approximately 36px capability marks, and reserve violet icon backplates for selected actions or product scenes.

## Section recipes

How recurring sections are built.

### First screen: Centered mechanism opening

**Observed:** A 50px announcement strip sits above a 96px header with left logo, centered Floating navigation and right-side login and primary action. The content begins with a centered two-line 56px promise, 24px to a narrow three-line body explanation, then 36px to Primary button and Secondary button separated by 12px. A 1200px-wide muted logo strip sits 48px below the action stack. A broad Working product scene enters below it: controls on the left, records on the right. In the first 900px the entire headline, explanation, actions, logo strip and upper interface rows are visible; the demonstration's lower rows and summary extend below the fold. Layers run from deep purple-black atmosphere, to text and logos, to physically edged dark panels; bright purple is restrained at this opening.

**Transfer:** Use a clear promise and a simplified but credible mechanism for a different product, with real control names and visible results. Match the opening strength with HTML/SVG rather than waiting for custom 3D. Product-specific pages can instead use a left text stack and one large Glass device stage over Wide basin light; a pricing opening centers a short promise directly over plan cards, while a proof directory pairs left text with dark perspective tiles.

**Avoid:** Do not replace the demonstration with a decorative orb, enlarge the headline into a full-width shouting poster, or fill this default first screen with a uniformly saturated purple background.

**Text style:** `display` — Roobert 500 · 56px/1.2 · tracking -0.02em

### Framed chapter heading

**Observed:** Architectural frame and data ribbons establish technical chapter boundaries. A 40px heading sits 48px inside the frame, usually left aligned, with a 12px or 24px support gap. A heading can split into muted setup and bright conclusion; another variant places its explanation to the right.

**Transfer:** Use a short idea per chapter, with a split heading only when the two clauses make a meaningful contrast.

**Text style:** `heading` — Roobert 500 · 40px/1.2 · tracking -0.01em

### Capability inventory

**Observed:** Corner-lit chapter places the section lead at upper left and violet light at upper right. Three columns of uppercase categories, short descriptions and Capability tiles follow, with 48px column spacing and 18px between tiles. A compact foundation statement and small trust marks sit at the bottom.

**Transfer:** Group the new product into a few coherent capability families. Use the luminous corner as the section's visual anchor rather than decorating every tile.

### Mechanism and benefits

**Observed:** A 40px section lead introduces a wide Working product scene. Three unboxed benefits below it use 16px semibold labels, 10px to body descriptions and 48px gutters. A developer-oriented variant removes the large art, pairs title and subhead with two right-aligned actions, and keeps the same benefit row.

**Transfer:** Explain the mechanism first, then its practical consequences. Use the text-only variant when another large diagram would be redundant.

### Outcome proof row

**Observed:** A framed 40px lead sits 48px above three Outcome cards, with 18px gutters. Each card has a distinct Soft violet pools position and an anchored bottom story link.

**Transfer:** Use credible numbers or concise verbal outcomes; maintain the graphic rhythm independently of the exact length of the proof.

### Open testimonial

**Observed:** The default marketing quotation is centered at 40px, with muted context and a bright key phrase; uppercase attribution follows at 24px and a Secondary button at 48px. Product variants use a centered 20px mono quotation in an 800px region, a monochrome mark above it, a light story button and pill-like speaker labels beneath.

**Transfer:** Keep the quotation as a deliberate pause between information-rich chapters. Choose the large sans variant for a broad brand story and the mono variant for a technical operator's account.

### Luminous closing and functional footer

**Observed:** Lower-left closing light centers a 56px promise, 19.2px support line and one small light action, with 120px vertical padding. The broader Wide basin light variant adds a near-viewport-width violet lower edge and 44px corners. A 48px breathing strip separates the close from the footer. Footer content uses a 1200px container with 80px top padding: small mark and newsletter at left, link columns at right. A final 50px utility strip carries copyright left and a small violet-dot system-status link right.

**Transfer:** Close with a direct next step, then return to the plain dark canvas for useful navigation and email signup. Keep the distinctive light field even when the final action is not sales-led.

**Text style:** `display` — Roobert 500 · 56px/1.2 · tracking -0.02em

### Process timeline

**Only for:** onboarding-oriented product pages

**Observed:** A left 40px heading balances a right-hand sequence of 29.6px step headings and body explanations. Small outlined step labels sit beside a thin vertical line with tiny junction marks; steps are separated by 80px.

**Transfer:** Use for a real multi-stage adoption process; keep each step's description concrete rather than promotional.

### Interactive technical chapter

**Only for:** technical product explanations

**Observed:** A 40px heading and body copy introduce Mechanism diagrams or paired before-and-after code panels. Selected tabs are violet capsules while the inactive control track is nearly black. Comparison panels are about 576px wide with 10px corners and captions below. An observability variant uses a tall timeline card beside two stacked information cards with 12px corners and 24px padding.

**Transfer:** Use diagrams for decision logic, paired panels for complexity reduction and the asymmetric card arrangement for visibility or troubleshooting benefits.

### Commercial detail ledger

**Only for:** pricing pages

**Observed:** After the plan pair and customer proof, feature categories run as spacious ledger chapters with 120px vertical padding. A left title and short description occupy roughly one third; the right 800px region holds hairline-separated rows with feature text and links on the left and price plus unit on the right. A neutral support panel, certification row, question list and a smaller complementary offer precede the closing call.

**Transfer:** Preserve the distinction between offer selection and detailed metering. Let genuine pricing complexity determine the ledger length, not a fixed number of categories.

### Proof directory

**Only for:** customer directories

**Observed:** A left-aligned display promise balances abstract perspective tiles. The story matrix uses Story directory cells in three columns, then continues directly into shorter monochrome logo cells with 1px rules and crosshair intersections.

**Transfer:** Create a browsable proof catalog with consistent graphic treatment, then use the compact logo matrix to broaden confidence without adding long copy.

### Questions and resource band

**Only for:** product education and pricing pages

**Observed:** Questions sit in 55px-tall hairline-separated rows within an 800px region, with semibold labels and right chevrons. Product education can follow with a wide framed resource band: compact tag, 40px title, one-line support and light action on the left, violet-backed illustrative art on the right.

**Transfer:** Use questions for practical objections and a resource band for deeper evaluation; avoid treating either as another large feature grid.

## Page flow

**Storyline:** Promise → visible mechanism → modular capabilities → practical benefits → customer proof → evaluation help → luminous final action → functional footer.

### Broad platform introduction

1. **Promise** — Centered headline, paired actions, logo strip and wide interface stage.
2. **Capability overview** — Corner-lit inventory followed by a visual explanation of the underlying model.
3. **Developer confidence** — Compact benefit row and a large open testimonial.
4. **Social proof** — Tall outcome cards, followed by illustrated adjacent use cases.
5. **Closing call** — Centered luminous conversion field and newsletter-plus-link footer.

**Transfer:** Lead with one broad promise and show a working mechanism before listing the full breadth of the product.

### Reduce adoption friction for a specialized product

1. **Promise** — Split hero with left display copy and large translucent interface stage.
2. **Benefits** — Three concise benefits then a vertical adoption timeline.
3. **Product demonstration** — Accordion-like capability list beside a code and interface demonstration.
4. **Proof** — Practical cost and effort benefits followed by a centered mono testimonial.
5. **Closing call** — Wide bottom-lit consultation call, then the shared functional footer.

**Transfer:** Make an intimidating implementation feel finite through steps, a concrete demo and customer validation.

### Explain a technically complex product and its trade-offs

1. **Promise** — Split purple-lit device hero and two-clause outcome headline.
2. **Product demonstration** — Tabbed decision-flow board with diagram, statistics and compact bars.
3. **Differentiation** — Parallel mechanism comparison followed by customer testimony.
4. **Capability chapters** — Implementation and code comparisons, embedded experience demonstration and asymmetric observability cards.
5. **Objection handling** — Centered FAQ list and illustrated evaluation-resource band.
6. **Closing call** — Large luminous final promise and shared newsletter footer.

**Transfer:** Alternate conceptual diagrams, implementation proof and human validation rather than presenting a continuous list of features.

### Help evaluators select an offer and understand usage costs

1. **Offer selection** — Centered pricing promise above two tall plan panels, one violet and one neutral.
2. **Social proof** — Short centered statement and faded logo strip.
3. **Commercial detail** — Category-led metering ledgers with descriptions, docs links and right-aligned unit prices.
4. **Trust and objections** — Support panel, certification marks and question rows.
5. **Expansion** — Small complementary offer inside a precise outer frame.
6. **Closing call** — Sandbox-oriented luminous action followed by the shared footer.

**Transfer:** Separate plan choice from granular pricing and keep long ledgers open on the dark canvas.

### Make customer proof browsable at multiple depths

1. **Promise** — Left-aligned headline and perspective logo-tile sculpture.
2. **Social proof** — Three-column story grid with data-halo art and editorial titles.
3. **Breadth** — Continuous three-column matrix of monochrome logos.
4. **Closing call** — Wide luminous invitation and the shared newsletter footer.

**Transfer:** Offer a few deep stories before a compact breadth-of-adoption layer.

## Writing

Direct, technically literate and calmly confident. Benefits are explained through mechanisms and operational consequences rather than grand claims; warmth comes from reducing the reader's burden.

**Do not copy:** Do not reuse Evervault names, logos, customer marks, quotes, proprietary artwork, customer results, certification claims, speed claims, prices or product-specific promises. Replace all of them with substantiated material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the team or platform doing work on the reader's behalf. Product names appear when specificity helps, not in every heading.
- **Rhythm:** Headlines are short sentence-case statements, commonly 3–8 words. Explanations are one or two compact sentences with concrete verbs; paired clauses often set up a contrast. Actions remain two to four words and punctuation is restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State control, a practical outcome or a sharp reduction in burden. | 3–8 words | “Take control of your payments”<br>“PCI DSS for developers” |
| Section heading | Name a mechanism or show the better alternative in two clauses. | 3–10 words | “A better model for securing card data”<br>“Authenticate once,”<br>“route to any PSP” |
| Supporting line | Explain the division of responsibility or the operational benefit. | One or two concise sentences | “You define the strategy. We provide the infrastructure to power it.”<br>“Detailed logs trace requests end to end, and human-readable errors explain what happened and why.” |
| Feature label | Concrete capability or consequence, not an abstract brand value. | 3–6 words | “No single point of failure”<br>“Debug with full visibility” |
| Primary action | Use a direct verb plus the next step. | 2–4 words | “Book a demo”<br>“Read the guide”<br>“Start for free” |

**Words and phrasing to use:** build; control; integrate; route; collect; full visibility; works with; without; infrastructure; human-readable

**Avoid:** revolutionary; magical; game-changing; unlock limitless potential; next-generation everything; effortless perfection

**Rules:**

- Tie a benefit to a mechanism in the next sentence.
- Use contrast to clarify trade-offs, not to disparage competitors.
- Name the work removed from the reader and the control they retain.
- State units and conditions beside commercial or quantified claims.
- Let documentation links carry implementation depth instead of overloading marketing paragraphs.

## Do's and Don'ts

### Do

- Keep main promises at 56px, weight 500, with -0.02em tracking.
- Pair a 40px chapter heading with 16px/1.5 explanation rather than repeating hero scale everywhere.
- Use 1200px frames and 48px internal insets to align chapters and footer.
- Keep action pairs 12px apart and their capsule heights at 40px.
- Give outcome cards 18px gutters and 32px internal padding.
- Make violet a localized light source; preserve a nearly black area behind important copy.
- Retain 1px architectural rules, crosshair details and at least one faded character ribbon.
- Finish with a substantial violet-lit call and a plain dark newsletter footer.

### Don't

- Do not substitute pure black for the blue-black #010314 canvas.
- Do not turn every body paragraph white; the default explanation is white at 60%.
- Do not make the main CTA a saturated purple block; its default is white at 90%.
- Do not round all cards into the 50px chapter shape; technical panels use 16px and capability tiles 4px.
- Do not give every feature a shadowed card; benefit rows are often unboxed beneath a rule.
- Do not use rainbow marketing gradients; green, red and yellow belong within explanatory product mechanisms.
- Do not make the 10px character ribbons read like important instructions; they are faded decorative texture.
- Do not center the entire site: chapter leads, inventories and ledgers predominantly align left.

## Motion and responsive

### Motion

**Observed:**

- Declared transitions include color, background-color, border-color, border-width, border-radius and box-shadow at 0.15s ease-out on newsletter elements.
- A live-gradient pulse definition scales the light layer through a midpoint and back; hover changes its scale multiplier.
- The navigation consolidates into a floating capsule on scroll.

**Transfer:**

- Keep motion in the illumination layer and navigation transformation rather than animating every heading. Preserve the static glow composition when motion is unavailable.
- Use the declared 0.15s ease-out treatment for the newsletter end-cap's color change.

**Unknown:**

- Pulse duration, scale multipliers and exact scroll-trigger behavior are unspecified.
- Focus-visible and active treatments for the main conversion buttons are unspecified.

### Responsive

**Observed:**

- Styles declare width boundaries around 810px and 1100px, with additional rules around 1440px; additional narrower boundaries exist for the broad landing layout.

**Transfer:**

- On narrow screens, preserve the hierarchy of promise, actions, proof and mechanism: stack the two-panel demonstration rather than shrinking its labels into illegibility.
- Collapse three-column outcome and directory grids into a readable stack; retain the glow origin, fine borders and action hierarchy.
- Replace long horizontal mechanism boards with a vertical path and keep the architectural frame aligned to the content edge.

**Unknown:**

- Exact mobile typography, navigation behavior, gutter sizes and illustration arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
