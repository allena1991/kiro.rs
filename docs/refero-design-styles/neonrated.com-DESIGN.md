# NEON — cinematic billboards and microtype

## Overview

A cinematic, image-led identity pairs towering condensed sans-serif titles with tiny, matter-of-fact grotesk labels. White catalogue space alternates with immersive dark photography, while color comes primarily from the imagery; a hot pink campaign treatment adds a sharper editorial register. It suits visually rich products, cultural launches and curated collections, with dense browsing rows separated by expansive pauses.

### Essentials

- Titles behave like film billboards rather than conventional web headings: Girott bold uppercase at 160px/0.9 with -0.03em tracking, against Focal labels at 12px/14px.
- The opening is an uninterrupted photographic scene: full-width, 900px tall at desktop, with a left-aligned title around its vertical midpoint and a compact 350px-wide navigation/action stack floating above it.
- Actions are miniature utility strips, not rounded promotional pills: the main action is 350×50px, black, with 4px corners, a thumbnail at the left and a small arrow at the right.
- The shell stays black and white; imagery supplies most color. Light grey #f3f3f3 backs media, while pink #ec71da belongs only to the campaign variant, including a half-width editorial panel.
- Collections feel like tightly edited contact sheets: 8px image corners, 16:9 photographs, 10px image-to-caption gaps, and 14px uppercase captions, separated by 140px chapter gaps.
- A monumental closing word sculpture is a signature device: black outlined-channel lettering stretches across a 1380×374px field, with a 296×374px rounded photographic window replacing one letter. Adapt the sculpture to the new identity; when no media exists, photograph a real product or material detail for the window.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Primary type on white; dark media stages and the conversion strip. |
| Reversed rule | `#666666` | `--color-reversed-rule` | border | White at 40% over a black backing, used for the newsletter underline; appearance varies over media. |
| Fine grey edge | `#e6e6e6` | `--color-edge` | border | Visible result of black at 10% over white; footer panel edges and detail separators. |
| Barely grey edge | `#f2f2f2` | `--color-faint-edge` | border | Visible result of black at 5% over white; navigation and carousel-control edges. |
| Media grey | `#f3f3f3` | `--color-media-base` | surface | Backing beneath images and contained product photography, not an empty-content treatment. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default page canvas, navigation and reversed titles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pink campaign detail pages | Campaign pink | `#ec71da` | `--color-campaign` | text, background, border | Campaign title, year, pagination and editorial portrait panel. |

## Typography

- **Girott** — Billboard titles, section headings and newsletter heading. Very condensed, heavy sans-serif with blunt terminals and tall compact capitals. If unavailable, use **Barlow Condensed**. Use 700 for display and 400 for newsletter; preserve narrow proportions and tight spacing. Font stack: "Girott", "Barlow Condensed", sans-serif.
- **Focal** — Utility text, captions, metadata, prices and prose. Compact neutral grotesk, regular for reading and bold for factual uppercase labels. If unavailable, use **Inter**. Use 400 and 700 with the measured negative tracking. Font stack: "Focal", "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Girott | 700 | 160px | 0.9 | -0.03em, uppercase | Hero title and large image-led promotional title. |
| newsletter-heading | Girott | 400 | 42px | 0.8 | -0.03em, uppercase | Newsletter panel heading. |
| section-heading | Girott | 700 | 41px | 0.8 | -0.0307em, uppercase | Short chapter headings above collection rows. |
| caption | Focal | 400 | 14px | 1 | -0.01em, uppercase | Item names directly below media; centered on merchandise. |
| footer-link | Focal | 400 | 14px | 1.5 | -0.0114em | Footer navigation lists. |
| eyebrow | Focal | 700 | 12px | 14px | -0.01em, uppercase | Status, dates, metadata labels and conversion-strip text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalogue pages | catalogue-display | Girott | 700 | 190px | 0.8 | -0.03em, uppercase | Oversized black title on a white index opening. |
| campaign profile sections | portrait-display | Girott | 700 | 147.8px | 0.8 | -0.0325em, uppercase | Two-line name on the editorial portrait panel. |
| product detail review sections | review | Girott | 700 | 42px | 0.85 | -0.03em | Short mixed-case quotation over a full-screen image. |
| product detail pages | body-lead | Focal | 400 | 20px | 1.2 | -0.01em | Main description within a narrow information column. |
| product detail pages | body | Focal | 400 | 16px | 1.2 | -0.01em | Editorial paragraph and factual details. |
| commerce sections | price | Focal | 400 | 14px | 1.2 | -0.0114em | Small centered price beneath a product name. |

**Notes:**

- The jump from 12–14px utility type to 160px display is deliberate; do not fill it with a conventional ladder of medium-sized marketing headings.
- Keep condensed display tightly stacked. Section-heading tracking is -1.3px, not a rounded replacement.
- The profile title fits its container using clamp(1rem,33cqi,16rem); retain container-relative sizing for this variant rather than making it a universal viewport headline.

## Layout

**Density:** Airy between chapters, compact inside collections: small captions and controls sit close to media while white space separates entire stories.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight horizontal media rail gaps. |
| 8px | Commerce tile gaps and compact price groups. |
| 10px | Image-to-caption spacing and icon/text groups. |
| 16px | Footer panel grid gap. |
| 20px | Section heading to media and internal content groups. |
| 30px | Desktop page gutters. |
| 40px | Campaign editorial panel padding. |
| 70px | Declared page section spacing token in the smaller rhythm. |
| 140px | Desktop separation between major chapters and before the footer. |

### Containers and grids

- **page-field**: side padding 30px. Fluid desktop content spans 1380px at 1440px viewport width; no narrow central marketing column.
- **floating-navigation**: max width 350px. Compact centered fixed navigation above the media and content, 35px from the desktop top.
- **commerce-grid**: 4 columns · gap 8px · side padding 30px. Four equal product tiles with centered names and prices.
- **footer-grid**: 4 columns · gap 16px · side padding 30px. Three navigation panels plus one subdivided social tile field.
- **catalogue-grid** (only for catalogue pages): 4 columns · gap 60px · side padding 30px. 300px-wide landscape thumbnails with 64px row gaps.
- **editorial-split** (only for campaign profile sections): 2 columns · gap 0px. Equal 720px portrait and text halves in a 900px-tall story.

## Corner radius

| Element | Radius |
| --- | --- |
| media-and-panels | 8px |
| actions | 4px |
| navigation | 3px |
| closing-image-window | 80px |
| pagination-dots | 10px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default background around collections and footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, untextured space with no decorative shadows.

**Transfer:** Let media and typographic scale provide the contrast.

#### Cinematic stage · level 0

**Use:** Opening and full-width photographic chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Cover media fills the stage, with a black 20% overlay where required for text readability.

**Transfer:** Use a real photographic or filmed scene rather than a floating interface card.

#### Media frame · level 1

**Use:** Landscape cards and product-image fields.

**CSS:** `background: #f3f3f3; border-radius: 8px; overflow: hidden`

**Observed:** Landscape images cover their bounds; isolated products are contained instead. Some landscape cards use a 191-degree black gradient, transparent through 65.48% and 40% black at 86.5%.

**Transfer:** Keep the grey behind actual media and preserve the difference between scenes and objects.

#### Newsletter stage · level 1

**Use:** Large signup block before footer navigation.

**CSS:** `background: #000000; color: #ffffff; border-radius: 8px; overflow: hidden`

**Observed:** 1380×540px desktop media-backed panel; overlay content uses 54px vertical and 45px horizontal padding.

**Transfer:** Use a dark brand-relevant media backing with an uncluttered field for the form.

#### Campaign panel · level 1

**Only for:** pink campaign profile sections

**Use:** Text half of the portrait diptych.

**CSS:** `background: #ec71da; color: #000000; padding: 40px; border-radius: 0px 8px 8px 0px`

**Observed:** A solid pink field beside a monochrome portrait; the text grouping sits low in the visible composition.

**Transfer:** Reserve this much flat color for a specific campaign story, not the general catalogue.

## Components

### Floating navigation

**Use:** Persistent compact site navigation.

**CSS:** `position: fixed; width: 350px; height: 50px; top: 35px; background: #ffffff; color: #000000; border: 1px solid rgba(0, 0, 0, 0.05); border-radius: 3px`

**Observed:** Centered horizontally, with a menu mark and small wordmark on the left, search, wishlist, account and cart on the right. It floats over the page rather than occupying a full-width header bar.

**Transfer:** Keep only relevant utility icons while preserving the small floating footprint.

### Conversion strip

**Use:** Primary action immediately below the floating navigation.

**CSS:** `width: 350px; height: 50px; background: #000000; color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 4px; padding: 0px 20px 0px 7px; display: flex; align-items: center`

**Text style:** `eyebrow` — Focal 700 · 12px/14px · tracking -0.01em · uppercase

**Observed:** Thumbnail precedes the label, while a small right arrow closes the row. The detail variant adds a price and an outlined play triangle.

**States:** Declared: hover unspecified; focus-visible outline transparent solid 2px, outline-offset 2px, zero-size box shadows.

**Transfer:** Use a small product scene and a concrete conversion verb.

### Landscape item

**Use:** Browseable image and name pair.

**CSS:** `background: #f3f3f3; border-radius: 8px; overflow: hidden; position: relative; aspect-ratio: 16 / 9`

**Text style:** `caption` — Focal 400 · 14px/1 · tracking -0.01em · uppercase

**Observed:** Image covers the frame. Caption sits outside the image 10px below it, aligned left; selected cards include a small status label over the image and tiny utility marks.

**Transfer:** Use a scene or demonstration frame rather than turning the entire item into a text card.

### Rail arrow

**Use:** Previous/next controls next to chapter titles.

**CSS:** `width: 28px; height: 28px; border: 1px solid rgba(0, 0, 0, 0.05); border-radius: 4px; display: flex; align-items: center; justify-content: center`

**Observed:** Two small square controls sit side by side with a 2px gap and tiny filled directional arrows.

**States:** Declared: hover border-color rgba(0, 0, 0, 0.5); focus-visible outline transparent solid 2px and outline-offset 2px.

### Status stamp

**Use:** Compact release or availability information.

**CSS:** `border: 1px solid #ffffff; padding: 0px 4px; display: inline-flex; color: #ffffff`

**Text style:** `eyebrow` — Focal 700 · 12px/14px · tracking -0.01em · uppercase

**Observed:** A close-fitting rectangular outline sits above the main hero title. Commerce uses black outlines for availability stamps.

**Transfer:** Use short factual status text, not promotional adjectives.

### Footer navigation panel

**Use:** Grouped footer destinations.

**CSS:** `background: rgba(255, 255, 255, 0.08); border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 8px; padding: 30.5px; display: flex; flex-direction: column; justify-content: space-between; gap: 20px`

**Text style:** `footer-link` — Focal 400 · 14px/1.5 · tracking -0.0114em

**Observed:** Small bold category label at the top; regular links align to the bottom. Desktop panel is 333×322px. The fourth grid column is subdivided into two large and three smaller social tiles.

### Footer text link

**Use:** Simple navigational links within panels.

**CSS:** `display: inline-flex; padding: 2px 10px; margin-left: -10px; border-radius: 4px; color: #000000`

**Text style:** `footer-link` — Focal 400 · 14px/1.5 · tracking -0.0114em

**Observed:** Click padding extends left beyond the text alignment.

**States:** Declared: hover text-decoration-line underline and text-underline-offset 2px; focus-visible outline transparent solid 2px and outline-offset 2px.

### Newsletter input row

**Use:** Email entry and arrow-only subscription action.

**CSS:** `display: flex; align-items: center; border-bottom: 1px solid rgba(255, 255, 255, 0.4); height: 58px`

**Observed:** Long unboxed input spans the media panel near its bottom. A white outlined arrow is the submit action; the newsletter heading occupies the upper area.

**Transfer:** Use a real accessible email input and give the icon-only button a descriptive accessible name.

### Closing word sculpture

**Use:** Memorable final identity statement beneath the footer links.

**CSS:** `position: relative; width: 100%; color: #000000`

**Observed:** A wide outlined-channel black wordmark is 1380×374px at desktop. One central letter becomes a rounded image window with a small white title and a regular one-line credit over it; tiny production and copyright lines finish below.

**Transfer:** Draw a new large SVG word sculpture from the new identity and integrate a photographic window, rather than using an ordinary small footer logo.

### Commerce caption

**Only for:** commerce sections

**Use:** Product-name and price block beneath isolated object imagery.

**CSS:** `display: flex; flex-direction: column; padding-top: 16px; text-align: center; border-radius: 4px`

**Text style:** `caption` — Focal 400 · 14px/1 · tracking -0.01em · uppercase

**Observed:** Uppercase product name is one line with ellipsis where necessary; a regular price follows after a 3px gap. No large purchase button interrupts the grid.

**Transfer:** Keep purchasing detail subordinate to the object photograph.

## Imagery and graphics

### Cinematic scene

**Use:** Opening, large promotional rails and review chapters.

**Observed:** People in real settings fill the screen: cool green mountain-water scenery, warmly lit interiors and saturated violet nightlife. Lighting and grain remain photographic, with darkened midtones supporting white text; the scene dominates the tiny amount of copy.

**Transfer:** Photograph the product in use with people or a believable environment. For a digital product without cinematic footage, stage a physical workspace or real-world consequence of using it, filling the frame with atmosphere rather than a dashboard mockup.

### Channel-letter closing artwork

**Use:** Closing word sculpture.

**Observed:** Heavy rounded black letterforms contain thin white interior channels; an image replaces one full-height glyph. The image has 80px corners, a portrait-like proportion and a white factual caption.

**Transfer:** Preserve the contrast between monumental identity geometry and intimate photographic detail using the new product's own lettering.

**Build:** Create a wide SVG word sculpture in black with rounded outer geometry and narrow white inset strokes following the letter paths. Size the composition to the content width with an approximately 3.7:1 aspect ratio. Reserve a central glyph-sized window about 21% of the width, clip a cover image with an 80px rounded rectangle, and place a small white two-line caption over its middle-left. A minimum version uses a heavy condensed custom word with white inset strokes and one rounded photographic insert.

### Object catalogue

**Only for:** commerce sections

**Use:** Product tiles.

**Observed:** Apparel, books and collectible objects are isolated and centered against pale grey fields, with enough space to reveal silhouette; square or portrait assets retain their shape instead of being forced into landscape.

**Transfer:** Use evenly lit isolated photographs or clean renders on #f3f3f3 and give each object comparable visual scale.

### Portrait diptych

**Only for:** campaign profile sections

**Use:** Editorial authority or maker story.

**Observed:** A full-height monochrome waist-up portrait shows a person against a coarse textured wall. It occupies half the page, beside a flat pink text panel with abundant empty space above the large name.

**Transfer:** Pair a candid monochrome maker or expert portrait with a campaign-colored name panel. Keep the natural wall texture inside the photograph, not across the page.

### Icons

**Observed:** Navigation uses thin black outline icons, commonly 16×16px with 1px round strokes, in 24px action areas. Rail arrows are tiny filled 9–10px shapes; social logos are larger black silhouettes around 35px tall; the subscription arrow is a white 36×28px outline.

**Transfer:** Keep utilities visually light and monochrome; reserve large filled marks for the social tile group.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** The first 900px is a full-bleed, 1440px-wide scene with no surrounding gutter. Layers run from black stage to cover photograph, a 20% black readability overlay, left-aligned status stamp and 160px uppercase title, then floating navigation and Conversion strip. The title sits around mid-height with a 30px left gutter; short names occupy only the left portion and longer names wrap within about 750px. The 350×50px white navigation floats near the top center, directly above its black action strip. A small row of outlined slide dots sits near the bottom, with the active dot stretched to 30×10px. Title, status, action and scene are visible immediately; the collection content begins below the first screen after 140px of breathing room. There is no supporting marketing paragraph in the opening.

**Transfer:** Make the product name or a short named proposition the billboard and let a full-bleed scene do the explaining. Use a real-world product photograph if no film exists. Detail pages keep the same scene composition but may use campaign-colored title and a small year; catalogue pages instead open on white with the catalogue-display title and view controls.

**Avoid:** Do not replace the immersive scene with a centered headline, explanatory paragraph and floating app window.

**Text style:** `display` — Girott 700 · 160px/0.9 · tracking -0.03em · uppercase

### Collection rail

**Observed:** A section-heading sits at the left gutter, sometimes immediately followed by Rail arrows. Media begins 20px below. Landscape item cards use a nearly touching 4px rail gap; standard thumbnails are about 347×195px, while featured pairs are 690×388px. Horizontal overflow reveals the next item.

**Transfer:** Group offerings, use cases or examples by meaningful availability or category, keeping the heading short and factual.

**Text style:** `section-heading` — Girott 700 · 41px/0.8 · tracking -0.0307em · uppercase

### Billboard rail

**Observed:** An oversized cover-image carousel carries the display title directly over imagery. One broad panel fills most of the width and the next panel peeks in at the right. Date labels sit near the upper-left; titles wrap in a large left-aligned block against a darkened photograph.

**Transfer:** Use this for one high-impact announcement or flagship capability, rather than giving every item the same visual weight.

**Text style:** `display` — Girott 700 · 160px/0.9 · tracking -0.03em · uppercase

### Signup and monumental ending

**Observed:** Newsletter stage offers a 42px regular condensed heading above Newsletter input row. A 20px gap leads into the four-column Footer navigation panel field and subdivided social tiles. After a 140px pause, Closing word sculpture spans the content width; a 20px gap separates its tiny credit/legal baseline. This substantial ending recurs across all page types.

**Transfer:** Carry both the useful signup/navigation and the large identity artwork into the new ending; tune the link categories to the new product.

**Text style:** `newsletter-heading` — Girott 400 · 42px/0.8 · tracking -0.03em · uppercase

### Object collection

**Only for:** commerce sections

**Observed:** Four pale media fields across the page show isolated objects. Status stamps sit within the image area, and Commerce caption blocks center the names and prices underneath. The chapter uses section-heading and is separated from neighboring stories by 140px.

**Transfer:** Use a deliberately curated collection of tangible or visual products; keep availability markings small.

### Detail information grid

**Only for:** product detail pages

**Observed:** A small image sits in the left area, a narrow description and proof column occupies the middle, and factual metadata occupies the right. Body-lead is 20px/1.2; detail lines use body at 16px/1.2, with bold 12px uppercase labels and faint horizontal separators.

**Transfer:** Translate the columns into product summary, independent validation and technical facts, not a long sales essay.

### Review stage

**Only for:** product detail pages

**Observed:** A 900px-tall cover photograph carries a short 42px review quotation at left and an attribution mark toward the opposite edge. Small campaign-colored slide indicators sit toward the bottom.

**Transfer:** Use an actual short testimonial over an image that demonstrates the experience, with clear attribution.

**Text style:** `review` — Girott 700 · 42px/0.85 · tracking -0.03em

### Maker diptych

**Only for:** campaign profile sections

**Observed:** Portrait diptych and Campaign panel form equal halves across a 900px-tall stage. The right text group has a small eyebrow, two-line portrait-display name and a short 16px paragraph; the composition leaves a large clear field above it.

**Transfer:** Give the person or expert behind the product an editorial moment without converting it into a generic team-card grid.

**Text style:** `portrait-display` — Girott 700 · 147.8px/0.8 · tracking -0.0325em · uppercase

### Catalogue opening and grid

**Only for:** catalogue pages

**Observed:** White space above the 190px black uppercase heading gives the floating navigation room. Four 60×60px outlined squares and a line-based view toggle sit opposite the title. Below a 140px pause, four columns of landscape media use 60px column and 64px row gaps.

**Transfer:** Use this quieter browsing mode for a substantial library, maintaining the billboard title even without a hero photograph.

**Text style:** `catalogue-display` — Girott 700 · 190px/0.8 · tracking -0.03em · uppercase

## Page flow

**Storyline:** Immersive identity → curated discovery → deeper context or proof → further exploration → signup, navigation and monumental identity close.

### Image-led marketing and discovery landing

1. **Promise** — Cinematic opening with one named subject and a direct conversion strip.
2. **Product discovery** — Large featured pair and an oversized announcement billboard.
3. **Breadth and proof** — Compact landscape rails alternate with object collections and a curated recognition grouping.
4. **Closing call** — Media-backed signup, modular footer navigation and an identity sculpture.

**Transfer:** Alternate flagship moments with compact evidence collections; the number and order of collections can follow the new product's story.

### Browse a complete collection

1. **Orientation** — Oversized title, floating filter strip and view controls on white.
2. **Exploration** — Long four-column landscape grid with small uppercase names.
3. **Closing call** — Shared signup and monumental footer.

**Transfer:** Keep the catalogue utilitarian and media-first while retaining the small floating tools and huge typography.

### Explain and convert a single flagship offering

1. **Promise** — Full-screen campaign scene with title, year and watch action.
2. **Context and proof** — Description, awards and factual details in narrow columns.
3. **Related offer** — Curated object collection.
4. **Social proof** — Full-image quotation stage.
5. **Authority** — Monochrome portrait and pink editorial panel.
6. **Product demonstration** — Large photographic gallery rail.
7. **Further exploration** — Related-item thumbnails.
8. **Closing call** — Shared newsletter, navigation tiles and huge closing artwork.

**Transfer:** Use the detail variant to balance emotional visual proof with compact factual information and a human authority story.

## Writing

Curatorial, blunt and confident. The interface behaves like a programme or catalogue: names and facts carry the weight, while expressive language is concentrated in attributed editorial quotations.

**Do not copy:** Do not reuse NEON's name, logo paths, film titles, artwork, merchandise names, award claims, release dates, prices or review quotations as claims for another product. Use the examples only to understand the form. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal labels and named subjects; actions address the reader through direct verbs rather than conversational second-person prose.
- **Rhythm:** One- to five-word labels and headings dominate. Description is reserved for detail pages, where a compact paragraph can tell a story; quotations supply the occasional emotional burst.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero title | Name the subject, without a supporting slogan. | 1–7 words | “Fjord”<br>“Once Upon A Time In Harlem” |
| Section heading | Factual grouping or availability category. | 2–4 words | “Coming Soon”<br>“New Merch Arrivals”<br>“You May Also Like” |
| Primary action | Direct verb and destination or immediacy. | 1–2 words | “Get Tickets”<br>“Watch Now”<br>“Subscribe” |
| Detail label | Short classification preceding factual content. | 1–3 words | “Synopsis”<br>“Additional Details” |
| Editorial proof | Brief attributed reaction, not a house-authored superlative. | 4–8 words | “A wild, profane blast” |

**Words and phrasing to use:** All; Now; Coming Soon; Limited Edition; See More; Gallery; Best Sellers

**Avoid:** revolutionary platform; unlock your potential; seamless solution; game-changing ecosystem

**Rules:**

- Let a name be the headline when imagery already communicates the experience.
- Use uppercase through typography, not by inflating the language.
- Keep status labels factual and date-specific where useful.
- Separate descriptive prose, factual metadata and attributed opinion into distinct roles.

## Do's and Don'ts

### Do

- Keep the hero title at 160px/0.9 on desktop and left-aligned to the 30px gutter.
- Preserve the 350×50px floating navigation and matching action-strip footprint.
- Use 140px between major chapters but only 20px from section title to media.
- Keep image corners at 8px and control corners at 4px.
- Put item names below images in 14px uppercase Focal rather than covering every image with copy.
- Use the 16px footer grid gap and its 30.5px panel padding.
- Give the ending a full-width word sculpture and an integrated rounded media window.
- Use factual 12px bold labels to organize detail-page information.

### Don't

- Do not turn the white shell into an all-black technology theme; dark areas belong to immersive media and actions.
- Do not distribute campaign pink across ordinary navigation, every card and every button.
- Do not add soft drop shadows to the flat media frames or footer panels.
- Do not replace condensed headlines with a wide geometric sans at the same size.
- Do not turn the 350px conversion strip into a rounded capsule or an oversized centered button.
- Do not enlarge every caption into a medium-weight 24px card heading.
- Do not force isolated products into the cover behavior of landscape scene thumbnails.
- Do not reduce the closing artwork to a small logo beside conventional footer columns.

## Motion and responsive

### Motion

**Observed:**

- Navigation and action color properties declare 0.5s cubic-bezier(0.4, 0, 0.2, 1) transitions.
- Large title underlines declare background-size .7s cubic-bezier(0.19,1,0.22,1), beginning at zero width with an 8px underline treatment.
- Closing-image hover declares scale-105 with a 1s transform transition; the page also declares opacity .4s and transform .75s entrances with cubic-bezier(0.19,1,0.22,1).

**Transfer:**

- Keep interaction concentrated on media, title underlines and small utility edges instead of animating every information label.
- Provide user-operable controls for image rails and pagination; preserve an intelligible still-image composition.

**Unknown:**

- Autoplay timing, precise scroll choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px, among smaller intermediate widths.
- Footer grid classes specify one column before the four-column desktop layout; the closing image window is desktop-only.
- Hero title grouping is centered in smaller-layout declarations and left-aligned at the large breakpoint.

**Transfer:**

- On narrow screens, retain the compact floating utility identity while fitting it within the available width.
- Stack the editorial portrait/text halves and footer panels; keep horizontal media rails rather than shrinking all their items into tiny columns.
- Scale and wrap the condensed display to preserve its billboard character; keep the identity sculpture readable as a width-fitting SVG.

**Unknown:**

- Exact mobile typography sizes, gutters and rendered breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
