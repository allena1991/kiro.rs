# Axel Arigato — contact-sheet luxury

## Overview

A light, image-led retail language with the attitude of an editorial contact sheet. Tiny grotesk labels sit against oversized tactile photography, while white and pale grey keep the interface almost invisible. Butter yellow punctuates the edges of the experience, and a monumental black identity closes it with confidence. It suits design-conscious physical products and culture-led launches with sparse copy but substantial visual storytelling.

### Essentials

- Images do the shouting; headlines behave like captions: the opening uses 13px/1.4, weight 470 grotesk text over two adjoining 720px-wide portrait media panels, each 900px tall.
- Commerce reads like a contact sheet: four adjoining columns, 360×504px media at desktop, no gutters, and 40px white name-and-price strips with 13px/1.5 labels.
- Actions are directional annotations rather than badges: uppercase 13px/1.5, weight 520 text preceded by a small filled triangle; no fill or rounded container. The catalog continuation variant is a square 360×50px outlined rectangle.
- Color belongs to the pictures and the bookends: white and #f3f3f3 dominate the interface; #faedbc is reserved for the 40px announcement band and the full-width closing identity field, not scattered through cards.
- A monumental identity anchors the experience: a black wordmark spans the closing field with 16px side margins, occupying a 1408×194px graphic area at desktop. Recreate this scale using the new identity, even when the product has no campaign artwork.
- Editorial contrast is structural: pair full-bleed portraits with inset portraits on white, and punctuate isolated product views with lived-in images. If campaign photography is unavailable, pair a close material study with a clean product-in-use composition rather than replacing the visual field with copy.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#faedbc` | `--color-butter` | background | Announcement strip and large closing identity field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#090909` | `--color-ink` | text, action, border | Campaign labels, navigation, short headings and outlined actions. |
| Absolute black | `#000000` | `--color-black` | text, link | Catalog labels, editorial links, service copy and the closing identity. |
| Inactive grey | `#aaaaaa` | `--color-inactive` | text | Unselected carousel category labels; distinguish inactivity from the darker primary labels. |
| Hairline grey | `#e9e9e9` | `--color-rule` | border | Service-grid dividers and horizontal rules. |
| Studio grey | `#f3f3f3` | `--color-product-ground` | surface | Product image backing and newsletter entry field. |
| White | `#ffffff` | `--color-canvas` | background, surface | Main canvas, navigation and caption strips. |

## Typography

- **helveticaNow** — All live text, from campaign captions to navigation and editorial prose. Neutral neo-grotesk with compact proportions and modest weight contrast; regular prose and medium labels are close in visual mass. If unavailable, use **Roboto**. Use regular and medium weights; preserve the compact 13px scale and normal tracking. Font stack: "helveticaNow", "Roboto", "HelveticaNow Fallback", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| campaign-caption | helveticaNow | 470 | 13px | 1.4 | normal | Opening headline and short image-led campaign statements. Capital letters are written in the copy; this role is not enlarged into a display headline. |
| label | helveticaNow | 520 | 13px | 1.5 | normal, uppercase | Directional actions, product names, card headings and footer links. |
| utility | helveticaNow | 520 | 13px | 1.5 | normal | Navigation, prices and counters without forced case conversion. |
| body | helveticaNow | 470 | 13px | 1.4 | normal | Newsletter support and compact descriptive paragraphs. |
| announcement | helveticaNow | 520 | 13px | 1.2 | normal, uppercase | Announcement strip text; also compact breadcrumbs on catalog pages. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalog and company-information introductions | heading | helveticaNow | 530 | 16px | 1.15 | normal, uppercase | Restrained page title, only slightly larger than labels. |
| company-information introductions | editorial-body | helveticaNow | 470 | 16px | 1.3 | normal | Multi-paragraph introductory narrative next to a portrait. |
| editorial information cards | editorial-card-copy | helveticaNow | 470 | 13px | 1.5 | normal | One or two lines beneath the card heading. |

**Notes:**

- Keep ordinary marketing typography at 13px; scale and hierarchy come from photography, position and white space rather than large headlines.
- Maintain normal letter spacing even on capitals. Use 470 for descriptive language and 520 for navigational or commercial labels.
- The giant closing identity is artwork, not the heading font. Its condensed heavy capitals should not spill into ordinary text roles.

## Layout

**Density:** Sparse text over expansive media, with tightly packed commercial rows and almost no separation between adjacent panels.

### Spacing

**Spacing system:**

- **step** 8px — Common layout rhythm for 16px panel insets, 24px caption-to-action spacing, 32px footer padding and 40px strips; 12px and 50px remain distinct exceptions.

| Value | Use |
| --- | --- |
| 8px | Service-link stack gaps and compact flex groups. |
| 12px | Editorial-card caption top padding and some input edges. |
| 16px | Standard side inset for labels, caption strips and service cells. |
| 20px | Spacing between carousel category labels. |
| 24px | Space above editorial-card actions and below carousel controls. |
| 32px | Closing identity-field top padding and artwork vertical padding. |
| 40px | Editorial rail top separation; announcement and navigation heights. |
| 50px | Service-band top spacing. |
| 56px | Catalog introduction bottom padding. |

### Containers and grids

- **page-shell**: max width 1920px · side padding 0px. Centered outer shell, otherwise edge-to-edge at desktop. Text takes local 16px insets instead of a narrow global container.
- **campaign-pair**: 2 columns · gap 0px · side padding 0px. Two equal halves; at 1440px each is 720px wide and 900px tall. Each carries its own label and action.
- **commercial-grid**: 4 columns · gap 0px · side padding 0px. 360px columns at desktop, with 5:7 media and a separate 40px caption strip.
- **editorial-rail**: 3 columns · gap 0px · side padding 0px. 480px column allocations; images are visually inset with narrow white borders and text has 16px side padding.
- **service-grid**: 4 columns · gap 0px · side padding 0px. Quarter-width service modules; two contact cells, one subscription cell and breathing room in the remaining quarter.

## Corner radius

| Element | Radius |
| --- | --- |
| panels-and-actions | 0px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Main page, navigation and text strips.

**CSS:** `background: #ffffff; color: #090909`

**Observed:** Flat white space; depth is carried by photography, not raised containers.

**Transfer:** Keep marketing chrome visually continuous.

#### Product stage · level 0

**Use:** Isolated product imagery.

**CSS:** `background-color: #f3f3f3; background-image: linear-gradient(-55.99deg, rgba(217, 217, 217, 0), rgba(217, 217, 217, 0.24)); border-radius: 0px`

**Observed:** A very restrained diagonal grey gradient accompanies the light-grey image backing; product imagery uses multiply blending at rest.

**Transfer:** Use a low-contrast neutral stage with realistic contact shadows. Preserve true product color.

#### Butter field · level 0

**Use:** Small top announcement and monumental closing panel.

**CSS:** `background: #faedbc; color: #000000`

**Observed:** The same pale yellow brackets an otherwise neutral interface; the closing field is much deeper than the top strip.

**Transfer:** Use as a bookend rather than a general card color.

#### Ruled service band · level 0

**Use:** Contact and subscription layer before the identity footer.

**CSS:** `background: #ffffff; border-top: 1px solid #e9e9e9; padding-top: 50px`

**Observed:** A narrow empty breathing band leads into cells divided by fine grey rules.

**Transfer:** Keep it functional and modular; adapt the service categories to the product.

## Components

### Navigation

**Use:** Persistent desktop orientation.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); height: 40px; background: #ffffff; position: sticky; top: 0px`

**Text style:** `utility` — helveticaNow 520 · 13px/1.5

**Observed:** A small condensed identity sits left; category links, search and help are distributed across the width, with tiny favorites and bag controls at the far right. It remains visible while scrolling.

**Transfer:** Retain the horizontal distribution and compact scale rather than turning it into a tall masthead.

### Announcement strip

**Use:** One brief timely message above navigation.

**CSS:** `height: 40px; background: #faedbc; display: flex; align-items: center; padding-left: 16px`

**Text style:** `announcement` — helveticaNow 520 · 13px/1.2 · uppercase

**Observed:** Text is left-aligned and the whole row acts as the link, with no separate button.

**Transfer:** State a release, availability or service message in one short line.

### Directional text action

**Use:** Default marketing conversion link on images or white space.

**CSS:** `display: flex; align-items: center; color: #090909; background: transparent; border-radius: 0px`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** A tiny filled right-pointing triangle precedes the label in a 15px icon box. Actions sit near lower edges of campaign panels and are independently associated with each image.

**States:** Declared: hover is not specified; focus-visible uses a 2px solid black outline, 2px outline offset and a white 4px spread ring.

**Transfer:** Use one direct verb plus the destination or product family.

### Product tile

**Use:** Commercial selections in carousels and catalog grids.

**CSS:** `width: 360px; border-radius: 0px; background: #ffffff`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** A 360×504px Product stage sits above a 40px white strip with 8px vertical and 16px horizontal insets. Name sits left and price right in utility type. Tiles adjoin without gutters; occasional full-height lifestyle media interrupts the row.

**Transfer:** Make the object dominant but leave neutral space around it; keep title and price out of the image.

### Carousel category control

**Use:** Switch between commercial selections.

**CSS:** `color: #aaaaaa; background: transparent; text-transform: uppercase`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** Unselected category is grey; selected category is black. Controls sit in a 60px header row with 16px top and side insets, a fraction counter and previous/next labels.

**States:** Declared: hover is not specified; focus-visible uses a 2px solid black outline, 2px outline offset and a white 4px spread ring.

### Editorial card action

**Use:** Destination link beneath a tall editorial image.

**CSS:** `display: flex; align-items: center; padding-top: 24px; color: #000000`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** Triangle-led link follows a small heading and optional compact description. The action aligns near the bottom of its card, so varied copy lengths do not disrupt the row.

**States:** Declared: hover is not specified; focus-visible uses a 2px solid black outline, 2px outline offset and a white 4px spread ring.

### Service cell

**Use:** Practical routes to help or offline discovery.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; min-height: 210px; padding: 16px; border-right: 1px solid #e9e9e9`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** Heading at the top, short stack of triangle-led links at the bottom. It is a ruled grid cell, not a freestanding card.

### Newsletter entry

**Use:** Subscription invitation in the service grid.

**CSS:** `height: 50px; width: 360px; padding: 8px 12px 8px 16px; background: #f3f3f3; border: 0px; border-radius: 0px`

**Observed:** Uppercase invitation appears inside a flat grey entry field; a sentence-case supporting paragraph in body type sits beneath it with 16px insets.

**Transfer:** Use a meaningful invitation with a short account of what subscribers receive, not an oversized conversion panel.

### Identity footer

**Use:** Shared closing identity and utility navigation.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); padding-top: 32px; background: #faedbc; color: #000000`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** Four compact utility columns precede a lower row for copyright, location and language. A full-width heavy condensed wordmark follows, with 16px side and 32px vertical padding. The footer is sticky behind the main content, producing a reveal at the end.

**Transfer:** Use the new brand identity as a near-edge-to-edge black graphic; preserve the contrast between small utilities and monumental lettering.

### Outlined continuation

**Only for:** catalog endings

**Use:** Move from an exhausted selection to the next category.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; width: 360px; height: 50px; padding: 16px 90px; border: 1px solid #090909; border-radius: 0px; color: #090909; background: transparent`

**Text style:** `label` — helveticaNow 520 · 13px/1.5 · uppercase

**Observed:** Centered alone in a spacious white band after the final product row. A triangle separates the action phrase from the next destination.

**States:** Declared: hover is not specified; focus-visible uses a 2px solid black outline, 2px outline offset and a white 4px spread ring.

## Imagery and graphics

### Tactile campaign pair

**Use:** Dominant opening and major product chapters.

**Observed:** Full-height portraits show close product details on pale rough plaster and concrete, paired with a tightly framed in-use view. Leather, mesh, suede, denim and socks remain tactile. Light is soft and natural; earthy brown, cream and deep green dominate, with occasional vivid garments. Text occupies almost none of the image field.

**Transfer:** Pair a close object or material portrait with a use-context portrait under the same soft light. Without a campaign shoot, use a well-lit material macro and a deliberately framed hand-held or in-use view against neutral physical textures.

### Isolated studio object

**Use:** Repeating commercial tiles.

**Observed:** Side-on objects are centered on very pale grey with ample space above and below, realistic soft contact shadows and consistent scale across variants. Clothing uses similarly isolated front-facing silhouettes. A lifestyle image can replace one complete tile.

**Transfer:** Produce consistent views with matching baseline and optical scale; use the Product stage backing, not decorative pedestals.

### Inset portrait against full bleed

**Use:** Editorial counterpoint within paired campaign chapters.

**Observed:** One white half contains a centered smaller portrait of clustered products and people; the adjoining half is entirely filled by an environmental portrait. Labels stay top-left, actions low-left.

**Transfer:** Keep one side spatially restrained and the other immersive. The inset should be intentional image-within-page framing, not a card.

### Editorial destination photography

**Use:** Three-column discovery rails.

**Observed:** Tall 5:7 images mix a simple product still life, candid flash-lit crowd scene and architectural exterior. Narrow white edges separate images; captions remain outside the image. Company-information variants include pale geometric interiors, a musician at a mixer and product-making material studies.

**Transfer:** Show distinct aspects of a new product's world—object, people, place or process—with consistent portrait framing. Preserve authentic texture instead of using generic polished stock.

### Monumental identity graphic

**Use:** Signature closing field on every page type.

**Observed:** Heavy condensed black capitals fill almost the complete width of a butter-yellow field; the graphic is 1408×194px at 1440px desktop. The effect is an identity stamp rather than a sentence.

**Transfer:** Set the new brand's identity as a bold condensed single-line graphic scaled to the available width. A typeset wordmark is the minimum equivalent when custom lettering is unavailable.

**Build:** Create an SVG with a 1408×194 viewBox and a black text or outlined-letter layer. Use a freely available condensed grotesk such as Roboto Condensed at weight 900, fit the complete new name to the width, and adjust horizontal scale rather than wrapping. Place in a full-width #faedbc wrapper with 16px side and 32px vertical padding; keep the graphic responsive with width:100% and height:auto.

### Icons

**Observed:** Compact filled SVG symbols in 15×15px and 17×17px boxes, principally black or near-black. Triangle pointers lead actions; solid heart, bag and playback controls serve utilities. Icons remain subordinate to the 13px labels.

**Transfer:** Use filled, simple silhouettes with the same compact optical weight, not a large thin-line feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Dual portrait opening

**Observed:** A 40px butter announcement sits above a 40px white Navigation. Beneath, two equal 720px-wide, 900px-tall media panels touch at the center with no outer gutter. The left is a close product pair against textured off-white masonry; the right is a cropped in-use moving image. Image fills the base layer, with a small black two-line campaign-caption inset 16px at the upper left and Directional text actions anchored low in each half. Within the first 900px the announcement, navigation, short headline, enormous object views and lower-edge actions are visible; the final part of the hero and commercial rail continue below the fold.

**Transfer:** Open a marketing landing page with two equally confident visual statements, not a text-led banner. Use a material close-up plus an in-use view if campaign footage is unavailable. Catalog pages instead begin with a compact heading, vertical subcategory list and short description on a four-column framework; company-information pages pair an inset portrait with a heading and narrative on white.

**Avoid:** Do not replace the small corner caption with a centered giant headline or stack pill buttons over a dark gradient scrim.

**Text style:** `campaign-caption` — helveticaNow 470 · 13px/1.4

### Commercial rail

**Observed:** Carousel category control forms a 60px header above four adjoining Product tiles. Fraction counter and previous/next labels share the header. The section is 604px tall at desktop; a lifestyle tile may interrupt otherwise isolated objects.

**Transfer:** Offer a curated selection after an image chapter, keeping the interface terse and the product scale consistent.

### Editorial campaign contrast

**Observed:** A second 900px-tall Campaign pair uses Inset portrait against full bleed. Small statements sit at the top and Directional text actions at the bottom; no heading/body stack competes with the media.

**Transfer:** Use this chapter to reveal a different use, construction or range dimension without adding a conventional feature-card grid.

### Story beside selection

**Observed:** A 720px-wide moving-image panel sits beside a two-column, two-row arrangement of Product tiles. Total section height is 1088px, allowing the image and commercial content to feel like one spread.

**Transfer:** Place a process, material or use film beside directly related objects or options.

### Editorial discovery rail

**Observed:** After 40px top separation, three equal column allocations carry tall imagery, label captions and Editorial card actions. Information-card variants add one or two lines of editorial-card-copy beneath the label.

**Transfer:** Use three visually distinct routes into deeper content, with a common image ratio rather than identical illustrations.

### Shared closing field

**Observed:** Ruled service band leads into the Service cells and Newsletter entry, then Identity footer on Butter field. The functional band is 262px tall and the closing identity field 515px tall at desktop. Tiny utility text gives way to the near-edge-to-edge black identity graphic.

**Transfer:** Keep the practical service layer and monumental identity as the ending device, regardless of how many narrative chapters precede it.

### Catalog introduction and exit

**Only for:** catalog pages

**Observed:** A 217px white introduction uses heading type, a narrow vertical subcategory menu and a short body paragraph. A 40px row carries breadcrumbs, view-density controls and filtering before the four-column commercial grid. After the final row, Outlined continuation sits alone in a 172px white band before the shared ending.

**Transfer:** Use for browsable ranges with many options; do not impose its long grid on a single-product story.

**Text style:** `heading` — helveticaNow 530 · 16px/1.15 · uppercase

### Narrative introduction

**Only for:** company-information pages

**Observed:** A 900px white split composition pairs an inset group portrait on the left with heading and editorial-body paragraphs on the right. The image has substantial white margins; text begins near its upper edge. The following editorial rail has brief supporting copy and Read more actions.

**Transfer:** Use for a substantial origin or approach narrative, pairing a human or process portrait with short separated paragraphs.

**Text style:** `editorial-body` — helveticaNow 470 · 16px/1.3

## Page flow

**Storyline:** Visual proposition → curated objects or deeper context → alternate visual chapters → discovery routes → practical support → monumental identity.

### Image-led marketing and product discovery

1. **Visual proposition** — Dual portrait opening introduces one product family with a caption and two destination actions.
2. **Product demonstration** — Commercial rail translates campaign imagery into browsable objects.
3. **Capability chapters** — Alternating immersive and inset photography reveals variety and use, interspersed with further selections.
4. **Related discovery** — Three portrait destinations broaden the product world.
5. **Closing call** — Support and subscription cells resolve practical needs before the butter identity footer.

**Transfer:** Use visual chapters and commercial selections in a rhythm appropriate to the new offering; keep a strong photographic opening and identity ending without requiring the same chapter count.

### Browsable product-family catalog

1. **Orientation** — Compact heading, subtype links and brief descriptive context.
2. **Selection** — Breadcrumbs and density/filter controls lead into a long, gutterless object grid with occasional lifestyle interruptions.
3. **Continuation** — Single centered outlined next-category action.
4. **Closing call** — Shared service and subscription band followed by identity footer.

**Transfer:** Let the range determine grid length; preserve visual consistency and a clear next destination.

### Company or approach narrative

1. **Introduction** — Inset group portrait beside a compact heading and multi-paragraph narrative.
2. **Supporting context** — Three tall destination images connect the narrative to places, people and process.
3. **Closing call** — Shared service band and monumental identity footer.

**Transfer:** Use factual narrative and authentic world-building images, with the same restrained interface rather than a separate corporate visual language.

## Writing

Fashion-editorial restraint with brief, matter-of-fact commercial language. Product statements sound confident without salesy urgency; longer narrative copy becomes human and culturally engaged.

**Do not copy:** Do not reuse the brand name or wordmark artwork, product names, campaign seasons, founding facts, prices, sustainability claims, slogans or proprietary imagery. Source phrases below illustrate syntax only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Navigation uses direct imperatives. Descriptions usually speak about the object impersonally; company narrative uses the brand name and occasional we or our. Subscription copy uses our without becoming conversational.
- **Rhythm:** Headlines are usually fragments or one short statement; labels and actions are two to five words. Longer narrative uses short paragraphs and occasional paired closing sentences, not a dense wall of text.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign headline | Product designation followed by one concise newness statement, often split into two lines. | 2–9 words per statement | “FLAIR RUNNER. A NEW SILHOUETTE FOR SS27.” |
| Supporting caption | One concrete design characterization or a terse range fact. | 2–10 words | “A RELAXED TAKE ON THE VINTAGE TRACK RUNNER.”<br>“ELEVEN COLORWAYS.” |
| Primary action | Discover or Shop plus a specific destination, in capitals. | 1–4 words | “DISCOVER THE DESIGN”<br>“SHOP MEN” |
| Catalog description | A short origin or positioning sentence followed by material and form information. | Two compact sentences | “Born in 2016, the men’s Clean 90 sneaker is a timeless classic. This best-selling style is handcrafted from certified materials and features a minimal, streamlined design.” |
| Narrative closing | Two compact parallel sentences after factual paragraphs. | Two short clauses | “Built on curiosity. Driven by connection.” |

**Words and phrasing to use:** discover; design; silhouette; crafted; materials; individuality; connection

**Avoid:** game-changing; revolutionary solution; unlock your potential; act now; unbeatable deal

**Rules:**

- Write concrete product differences instead of stacking luxury adjectives.
- Keep uppercase interface labels distinct from sentence-case explanatory prose.
- Use full stops on campaign statements; keep destination labels unpunctuated.
- Use range facts only when they help the visitor understand the offering.

## Do's and Don'ts

### Do

- Keep default campaign text at 13px/1.4 and weight 470.
- Use 13px/1.5, weight 520 capitals for directional actions.
- Preserve equal two-panel campaign compositions with 0px gutters.
- Keep product stages at 5:7 with a separate 40px caption strip.
- Use 16px local text insets even inside edge-to-edge sections.
- Reserve butter yellow for announcement and identity fields.
- Include the full-width black identity stamp in the closing field.
- Keep service cells on a four-column framework with 1px grey dividers.

### Don't

- Do not introduce wide letter spacing on uppercase labels; tracking remains normal.
- Do not make default links filled black or colored buttons; the outlined continuation is a scoped catalog variant.
- Do not round product tiles, inputs or buttons; corners remain 0px.
- Do not add elevated card shadows to the flat commercial grid.
- Do not tint every section yellow or turn it into a saturated gold accent.
- Do not put product titles and prices over isolated product photography; keep them in the white strip.
- Do not use thin outline feature icons where the interface uses tiny solid pointers.
- Do not turn ordinary 16px introduction headings into the visual scale of the closing wordmark.

## Motion and responsive

### Motion

**Observed:**

- Declared action and surface transitions include color 0.2s, opacity 0.15s and opacity 0.3s with cubic-bezier(0.4, 0, 0.2, 1).
- Campaign media includes video with explicit play/pause controls. Navigation remains sticky; the closing footer is sticky behind the content.
- Product-image classes declare a hover swap by reducing the primary image opacity; its resting blend mode is multiply.

**Transfer:**

- Keep video controls compact and near the lower edge of the media panel.
- Retain a restrained image swap and footer reveal rather than adding animated headline choreography.

**Unknown:**

- Playback sequencing, image-swap timing and scroll choreography are not established.

### Responsive

**Observed:**

- Desktop layouts use paired campaigns and four-column product grids; the campaign grid also declares a single-column base layout.
- Declared width breakpoints include 350px, 380px, 480px, 540px, 576px, 769px, 1024px, 1280px, 1370px and 1920px.
- The outer shell has a 1920px maximum width.

**Transfer:**

- For narrow layouts, stack paired campaign panels while keeping each caption and action attached to its own image.
- Scale the closing SVG identity with its available width rather than wrapping its lettering.
- Preserve local label insets and portrait imagery when reducing grid density.

**Unknown:**

- Exact narrow-screen navigation, grid-density defaults and footer reflow are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
