# The Resonance — blue-lit instruments

## Overview

A dark, software-native style with an almost physical sense of glass, illuminated edges and blue light. Tightly fitted contemporary sans headings sit above calm system-sans explanations and large, carefully staged interface demonstrations. It suits focused creative tools and single-product launches: sparse at the page level, richly detailed inside the product scenes.

### Essentials

- Headlines behave like a single fitted phrase: Ritual at 70px/1 for the opening and 64px/1 for section leads, weight 500 with -0.03em tracking; a short concluding word turns blue in section headings.
- The opening is a centered promise suspended above an instrument: an 800px floating navigation bar, headline beginning after 285px of top space, an 860px support line, one 54px action, then a 1130px-wide application window entering the first fold.
- Actions feel like softly molded controls rather than pills: 16px corners, blue fill, dark lettering and a 1px inset pale-blue edge; primary controls are 54px high with 24px horizontal padding.
- Blue is light, not the whole canvas: near-black dominates the middle of the page, while broad black-to-electric-blue gradients illuminate the opening demonstration and closing area. Body copy remains neutral; only brief headline endings and actions carry blue.
- Interface scenes supply the spectacle: a large translucent 16px-radius desktop shell and smaller blue-backed capability vignettes. Use a coherent constructed interface scene when finished product media is unavailable, not stock photography.
- One offer or proof panel receives a luminous machined rim: 18px corners, a 4px blue perimeter and pale inner bevel surrounding a slate-blue fill. Retain this distinctive edge treatment even when the panel presents evidence rather than a price.
- The ending is a black plate floating in blue light: a centered 64px closing question and repeated primary action precede a broad 16px-radius footer panel with a left signup and two narrow link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#509dfc` | `--color-primary` | action, accent | Main action fill and small offer labels. |
| Electric blue | `#0068f0` | `--color-electric` | background | Bright portion of the opening and closing light fields. |
| Sky light | `#4ca3ff` | `--color-sky` | background | Brightest gradient endpoint beneath the closing footer. |
| Deep text blue | `#417bdc` | `--color-deep-blue` | text | Darker blue variant on the capability heading's final verb. |
| Headline blue | `#6da7ff` | `--color-light-blue` | text, action | Highlighted heading endings and compact navigation action. |
| Cobalt light | `#00358a` | `--color-cobalt` | background | Broad blue gradient field. |
| Night blue | `#030a1c` | `--color-night-blue` | background | Dark atmospheric transition between black and blue. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Rim blue | `#2888ff` | `--color-rim` | border | Bright external perimeter of the highlighted panel. |
| Pale bevel | `#a7caff` | `--color-bevel` | border | Inset action edge and illuminated panel bevel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised slate blue | `#202f45` | `--color-raised` | surface | Highlighted offer panel and action hover backing. |
| Navigation edge | `#1d2738` | `--color-nav-edge` | border | Cool outlined navigation perimeter. |
| Plate black | `#000000` | `--color-black` | background, surface | Footer plate and dark gradient endpoints. |
| Navigation black | `#090b0e` | `--color-sunken` | surface | Opaque floating navigation backing. |
| Blue black | `#0a0c11` | `--color-canvas` | background, text | Default canvas and dark lettering on blue actions. |
| Lifted charcoal | `#15171c` | `--color-card` | surface | Visible card fill from soft chalk at 5% over blue black. |
| Quiet edge | `#212328` | `--color-rule` | border | Visible 10% chalk hairline over the canvas; 5% is used for accordion dividers. |
| Footer gray | `#898989` | `--color-subtle` | text | Secondary footer links; white at approximately 53.8% over black. |
| Body silver | `#c7c7c8` | `--color-muted` | text | Visible body text from white at 77% over the dark canvas; use the alpha recipe over changing backgrounds. |
| Soft chalk | `#eef1ea` | `--color-foreground` | text | Headlines and high-emphasis text. |

## Typography

- **ritual** — Display headings, card titles and accordion questions. Contemporary sans with rounded bowls, open counters and close-fitting letterforms; medium rather than heavy. If unavailable, use **Inter**. Use weight 500 and preserve the tight tracking. Font stack: "ritual", "Inter", Arial, sans-serif.
- **-apple-system** — Support copy, navigation, actions and supporting lists. Familiar neutral system sans with a practical software tone. Font stack: "-apple-system", system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | ritual | 500 | 70px | 1 | -0.03em | size clamp(40px, 4.861vw, 70px) | Centered opening promise and major price numerals. |
| section-heading | ritual | 500 | 64px | 1 | -0.03em | size clamp(32px, 4.444vw, 64px) | Centered section leads and the closing question. |
| card-heading | ritual | 500 | 32px | 1.15 | -0.03em | fixed | Capability titles and the offer explanation. |
| footer-brand | ritual | 500 | 28px | 1.333 | -0.03em | fixed | Footer product identity beside its symbol. |
| lede | -apple-system | 400 | 20px | 1.6 | normal | fixed | Opening support and the highlighted offer's main explanation. |
| body | -apple-system | 400 | 18px | 1.6 | normal | fixed | Capability paragraphs and section support. |
| button | -apple-system | 500 | 18px | 1.556 | normal | fixed | Primary actions. |
| offer-label | -apple-system | 500 | 18px | 1.6 | normal | fixed | Short blue label over the price or proof figure. |
| small-body | -apple-system | 400 | 16px | 1.6 | normal | fixed | Included-feature lists, footer links and signup label. |
| question | ritual | 500 | 16px | 1.5 | -0.03em | fixed | Accordion question labels. |
| caption | -apple-system | 400 | 14px | 1.43 | normal | fixed | Trial reassurance, requirements and signup privacy line. |
| compact-button | -apple-system | 500 | 14px | 1.43 | normal | fixed | Compact navigation action. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use the same -0.03em fit across display, section, card and question text; hierarchy comes from scale, not a jump to bold.
- Keep paragraph and action tracking normal. Section headings can color only their concluding word or clause without changing its font metrics.
- Prices reuse the opening display size, with a superscript currency symbol around 31.5px and a muted struck-through comparison around 32.2px.

## Layout

**Density:** Airy between chapters, compact within the interface and list controls.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Icon-to-label spacing in actions. | fixed |
| 16px | Card-title to paragraph gap and action-to-reassurance gap. | fixed |
| 24px | Opening headline-to-lede gap, card horizontal padding and feature-grid column gap. | fixed |
| 32px | Main container side padding and card vertical padding. | fixed |
| 45px | Opening lede-to-action gap. | clamp(28px, 3.125vw, 45px) |
| 64px | Heading-to-feature-grid gap and demonstration top spacing. | fixed |
| 96px | Social proof vertical padding and bottom clearance under the footer. | fixed |
| 128px | Section-heading to accordion gap. | fixed |
| 144px | Desktop chapter top and bottom padding. | fixed |
| 285px | Opening content top offset. | fixed |

### Containers and grids

- **Main container**: max width 1194px · side padding 32px. Centered content frame yielding 1130px of usable desktop width.
- **Navigation**: max width 800px. Compact centered floating bar, considerably narrower than the content.
- **Opening lede**: max width 860px. Centered paragraph, two lines at desktop.
- **Feature grid**: 2 columns · gap 24px. Two equal feature cards followed by a full-width horizontal card; vertical row gap 20px.
- **Offer split**: 2 columns · gap 48px. Explanation and inclusions at left; luminous highlighted panel at right inside one broad card.
- **Questions container**: max width 1024px · side padding 32px. Narrower 960px usable accordion column.
- **Footer frame**: max width 1368px · side padding 32px. Broader than the main content; contains a 1304px black plate.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions and shell | 16px |
| Content cards | 18px |
| Input and vignette | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Application glass | `inset 0px 0px 0px 1px rgba(255,255,255,0.11), inset 0px 1px 0px rgba(255,255,255,0.08), inset 0px -1px 0px rgba(114,132,168,0.08), 0px 18px 52px rgba(0,0,0,0.3)` | Large demonstration window; combines fine reflective edges with depth. |
| Action bevel | `inset 0px 0px 0px 1px #a7caff` | Primary and compact blue controls. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page base.

**CSS:** `background: #0a0c11; color: #eef1ea`

**Observed:** The middle chapters are almost uninterrupted dark ground.

**Transfer:** Let the product scenes, rather than alternating light bands, create contrast.

#### Content card · level 1

**Use:** Capability and offer grouping.

**CSS:** `background: rgba(238,241,234,0.05); border: 1px solid rgba(238,241,234,0.1); border-radius: 18px`

**Observed:** A faint raised layer, not an opaque light tile.

**Transfer:** Reuse for explanatory content with generous media below.

#### Application glass · level 2

**Use:** Opening product demonstration shell.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.13) 0%, rgba(255,255,255,0.08) 42%, rgba(255,255,255,0.035) 100%); border-radius: 16px; padding: 10px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.11), inset 0px 1px 0px rgba(255,255,255,0.08), inset 0px -1px 0px rgba(114,132,168,0.08), 0px 18px 52px rgba(0,0,0,0.3)`

**Observed:** The blue scene behind it remains visible through the dark translucent framing.

**Transfer:** Keep the shell visually lighter than its internal panels.

#### Blue light field · level 0

**Use:** Atmosphere behind the demonstration and final conversion area.

**CSS:** `background: linear-gradient(#0a0c11 0%, #030a1c 21%, #00358a 57%, #0068f0 80%, #4ca3ff 100%)`

**Observed:** Opening light rises and returns to dark; closing light grows steadily brighter toward the bottom.

**Transfer:** Keep the opening text area dark and put maximum light behind or below the media; use the rising variant behind the final plate.

#### Black plate · level 1

**Use:** Footer within the blue closing field.

**CSS:** `background: #000000; border-radius: 16px; padding: 40px 32px`

**Observed:** A large opaque black island with a clear blue margin around it.

**Transfer:** Retain the contrast between luminous exterior and completely black footer.

## Components

### Floating navigation

**Use:** Persistent compact site navigation.

**CSS:** `max-width: 800px; height: 62px; display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 12px 28px; background: #090b0e; border: 1px solid #1d2738; border-radius: 16px`

**Observed:** Fixed centrally near the top with product symbol and name at left, four understated section links in the middle and a compact blue action at right. Header top spacing is 50.4px on desktop.

**Transfer:** Use a small recognizable product symbol; keep the bar narrower than the main content.

### Primary button

**Use:** Single dominant conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 54px; padding: 0px 24px; background: #509dfc; color: #0a0c11; border-radius: 16px; box-shadow: inset 0px 0px 0px 1px #a7caff`

**Text style:** `button` — -apple-system 500 · 18px/1.556

**Observed:** A dark platform symbol precedes the label; width follows content. Repeated in the opening, highlighted offer and closing call.

**States:** Declared: hover changes to raised slate-blue backing and soft-chalk text; focus-visible uses an action-blue border and 1px pale-blue inset edge.

### Compact action

**Use:** Navigation conversion control.

**CSS:** `height: 36px; padding: 8px 28px; background: #6da7ff; color: #0a0c11; border-radius: 16px; box-shadow: inset 0px 0px 0px 1px #a7caff`

**Text style:** `compact-button` — -apple-system 500 · 14px/1.43

**Observed:** Text only, shorter and paler than the primary control.

**States:** Declared: hover changes to raised slate-blue backing and soft-chalk text; focus-visible retains the pale-blue inset edge.

### Capability card

**Use:** Explain one capability alongside a focused interface vignette.

**CSS:** `display: flex; flex-direction: column; padding: 32px 24px; background: rgba(238,241,234,0.05); border: 1px solid rgba(238,241,234,0.1); border-radius: 18px`

**Text style:** `card-heading` — ritual 500 · 32px/1.15 · tracking -0.03em

**Observed:** Title and paragraph are inset farther than the media. Paired cards place media below text; the wide variant puts explanation at left and an interface scene at right.

**Transfer:** Give each card one concrete operation and its visible result.

### Luminous offer panel

**Use:** Emphasized price or decisive proof.

**CSS:** `position: relative; padding: 32px; background: #202f45; border: 4px solid transparent; border-radius: 18px`

**Text style:** `display` — ritual 500 · 70px/1 · tracking -0.03em

**Observed:** Blue label, oversized figure with smaller superscript currency and struck-through comparison, separator, promise and low-positioned action. The edge has a bright blue outer band, a pale inner bevel and top-light/bottom-shadow treatment.

**Transfer:** Carry the rim to a quantified proof panel when there is no purchase offer; keep the figure prominent and supporting terms subdued.

### Question row

**Use:** Compact objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 0px; min-height: 56px; border-bottom: 1px solid rgba(238,241,234,0.05); color: rgba(238,241,234,0.9)`

**Text style:** `question` — ritual 500 · 16px/1.5 · tracking -0.03em

**Observed:** Plain full-width question and small right-aligned downward chevron; no filled tile behind each row.

**States:** Declared: hover brightens text to soft chalk; focus-visible changes border to action blue.

### Email signup

**Use:** Low-key updates subscription in the footer.

**CSS:** `height: 56px; max-width: 420px; padding: 0px 56px 0px 20px; background: rgba(238,241,234,0.03); border: 1px solid rgba(238,241,234,0.1); border-radius: 8px`

**Text style:** `small-body` — -apple-system 400 · 16px/1.6

**Observed:** Label above, email field below, a 40px square outlined arrow control embedded at the right, then a short privacy reassurance.

**Transfer:** Keep this subordinate to the main conversion; use a simple updates invitation.

### Footer plate

**Use:** Site ending with signup, resource links and credits.

**CSS:** `background: #000000; border-radius: 16px; padding: 40px 32px`

**Text style:** `small-body` — -apple-system 400 · 16px/1.6

**Observed:** Product identity on top; signup at left and two link columns at right, separated by ample black space. A faint top rule introduces a bottom row of copyright, credit and two small circular social marks. Links use subdued gray and brighten on hover.

**Transfer:** Preserve the left-heavy identity and signup versus narrow resource columns, with a distinct ruled bottom row.

## Imagery and graphics

### Working application stage

**Use:** Large opening proof and smaller capability demonstrations.

**Observed:** A dark desktop application with tiny chrome controls surrounds a large colorful website preview, a side control area and a timeline. Violet-blue reflective abstract shapes and experimental editorial artwork appear inside the preview, not as page-wide decoration. The main shell spans 1130px and dominates the view after the opening text.

**Transfer:** Show a plausible working state for the new product, not an empty dashboard. If finished media is unavailable, construct one coherent dark interface with a vivid output preview and several believable operation controls; reuse its details in the smaller scenes.

### Blue-backed capability vignettes

**Use:** Media inside explanatory cards.

**Observed:** Small interface windows, a phone-sized preview, timeline tracks and export controls float against deep blue-to-black grounds. Some windows are deliberately cut by the media boundary; pale edges and restrained shadows give them a physical software-panel feel.

**Transfer:** Isolate the single operation each paragraph describes. Keep blue backing, dark chrome and concentrated color within the output preview.

**Build:** Use an 8px-radius clipped media well with a vertical gradient between black, night blue and cobalt. Place one dark interface panel above it, add 1px white-at-8% edges and a soft black shadow, then overlap a smaller control strip or narrow output preview. Use a bright blue 1px selection outline sparingly.

### Continuous blue illumination

**Use:** Opening and ending atmosphere.

**Observed:** Broad smooth vertical color fields progress through black, midnight blue, cobalt and luminous sky blue without visible grain or discrete decorative blobs.

**Transfer:** Retain a continuous light field behind the major product scene and a rising light field beneath the footer.

**Build:** Layer a full-width vertical gradient behind the content. For the opening, keep the first fifth nearly black, reach sky blue around three fifths and fade back to the canvas at the bottom; overlay black fading to transparent from the top. For the closing, start at the canvas and increase through night blue, cobalt and electric blue to sky blue at the bottom. Match the soft light; exact intermediate stops are not essential.

### Beveled luminous perimeter

**Use:** Signature edge on the highlighted offer or proof panel.

**Observed:** An electric-blue external rim encloses a pale reflective inner band, with a brighter upper edge and darker lower edge; it reads as a machined glowing frame rather than a blurred neon halo.

**Transfer:** Use once on a high-value panel, keeping ordinary cards much quieter.

**Build:** On an 18px-radius panel, reserve a 4px perimeter. Use a masked pseudo-element with rim blue beneath a white-at-20% to black-at-20% vertical overlay. Add an inner pale-blue band and inset white-at-25% top and black-at-25% bottom highlights. Keep the center slate blue and free of glow.

### Icons

**Observed:** Marketing chevrons are 20px outline SVGs with 2px round strokes in muted white; platform symbols in actions are solid dark silhouettes around 25px. Social marks are small light circles with dark glyphs.

**Transfer:** Use restrained round-stroke utility icons for disclosure and arrows; reserve filled symbols for platform identity and social destinations.

## Section recipes

How recurring sections are built.

### First screen: Instrument opening

**Observed:** A dark atmospheric ground sits behind a centered floating navigation bar. A broad centered headline begins after 285px of top space and fits on one line across most of the 1130px content width at 70px/1. Below it, an 860px paragraph uses two lines at 20px/32px, followed by 45px of space to Primary button and a 14px reassurance line 16px lower. The 1130px Application glass shell starts 64px below the text block. Within the first 900px, the navigation, full headline, support, action, reassurance and upper portion of the application are visible; the timeline and full shell continue below the fold. Back-to-front layers are blue light field, translucent application shell, dark internal panels and colorful output preview.

**Transfer:** Give a different product an equally direct category-and-audience promise and one dominant action. Build a convincing application scene from its central workflow if actual media is unavailable. Secondary informational pages can use the same compact navigation and centered heading with a shorter introduction, keeping the full staged demonstration for product-led pages.

**Avoid:** Do not replace the opening with a left-aligned text/sidebar layout or shrink the product into a small illustration beside the headline.

**Text style:** `display` — ritual 500 · 70px/1 · tracking -0.03em

### Understated proof strip

**Observed:** A short centered sentence introduces a horizontal row of logo plaques; dark 208px by 88px plaques have 16px corners, subtle 7% chalk edges and restrained top highlights. The area has 96px vertical padding.

**Transfer:** Use real customer or integration proof in a restrained monochrome strip. Keep it subordinate to the demonstration.

### Verb-led capability chapter

**Observed:** A centered 64px heading uses short punctuated verbs and colors the final verb blue. Capability card begins 64px below; two equal cards precede a broad horizontal card, with 24px column gaps and 20px row gaps. Each title is 32px with a paragraph 16px lower and a substantial blue-backed interface vignette.

**Transfer:** Group a few meaningful product operations into a compact verbal promise; vary card proportions to match the media rather than treating every capability as an identical icon tile.

**Text style:** `section-heading` — ritual 500 · 64px/1 · tracking -0.03em

### Offer and evidence chapter

**Observed:** A centered heading with a light-blue ending and one supporting line leads into Content card. Inside, the left half holds a short title, explanation and simple 16px feature list with 4px dot bullets; the right half is Luminous offer panel. The split uses a 48px gap and the outer grouping uses 32px padding.

**Transfer:** Use the left side to explain value and the right side for the decisive commercial or quantified proof. Do not require a discount to justify the highlighted treatment.

**Text style:** `section-heading` — ritual 500 · 64px/1 · tracking -0.03em

### Questions chapter

**Observed:** A centered 64px heading colors its final word light blue. A 128px gap precedes a 960px stack of Question row controls with faint separators and right chevrons. Chapter padding is 144px above and below.

**Transfer:** Write actual decision-blocking questions in a single column and retain the very quiet row treatment.

**Text style:** `section-heading` — ritual 500 · 64px/1 · tracking -0.03em

### Blue-lit closing and footer

**Observed:** Blue light field begins dark, then brightens under a centered two-line 64px closing question, Primary button and small reassurance. A broad Black plate follows with about 104px of separation and 96px of bottom clearance. Footer plate combines product identity, Email signup, two resource columns and a faintly ruled credits row.

**Transfer:** End with a question about the reader's desired result, repeat the same primary action, then let the luminous field frame a useful black footer rather than ending on a bare link list.

**Text style:** `section-heading` — ritual 500 · 64px/1 · tracking -0.03em

## Page flow

**Storyline:** Specific promise → substantial working demonstration → restrained credibility → capability explanations → decisive value proof → objections → result-oriented closing action and useful footer.

### Convert interest in a focused creative tool into a trial or purchase

1. **Promise** — Centered category-and-audience statement with one action and low-friction reassurance.
2. **Product demonstration** — Large translucent working application shell on an illuminated blue stage.
3. **Social proof** — Small introduction and subdued horizontal logo plaques.
4. **Capability chapters** — Short verb-led heading and mixed-width cards showing concrete operations.
5. **Value proof** — Included-value explanation beside a luminous price panel.
6. **Objection handling** — Narrow single-column accordion under an accented heading.
7. **Closing call** — Result-oriented question and repeated action over rising blue light.
8. **Utility ending** — Opaque black footer plate containing signup, links and ruled credits.

**Transfer:** Adapt the sequence to the buying decision. Keep the working scene, luminous emphasized panel and blue-lit black-plate ending as recurring devices without requiring a particular number of chapters.

## Writing

Practical, confident and sympathetic to people who care about the finish of their work. Claims are explained through concrete controls and outcomes rather than grand brand language.

**Do not copy:** Do not reuse the product name, studio marks, customer logos, embedded demo artwork, exact prices, discount claims, trial terms, compatibility requirements or unverified product promises. Source quotations below illustrate voice only.

- **Addressing the reader:** Address the reader as you and your; name the product directly when explaining behavior. Use imperatives to introduce an operation and plain statements to explain the result.
- **Rhythm:** Brief category headlines and punctuated verbs contrast with two- or three-sentence explanatory paragraphs. Conversion copy is short and literal; reassurance is a compact line of terms.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the category and its intended audience without a metaphor. | 4–7 words | “Screen recording for designers.” |
| Section lead | Short verbs or a simple promise, with the last word providing the payoff. | 3–6 words | “Record. Refine. Share.”<br>“Pay once own forever.” |
| Capability title | Directly describe the reader's control over the result. | 2–7 words | “Frame your work how you want.”<br>“Choreograph every interaction.” |
| Support | Explain the mechanism, then the concrete finished outcome. | 1–3 sentences | “Build your recording on a timeline instead of trying to perform it perfectly in real time.” |
| Primary action | Literal verb with platform or product context. | 1–4 words | “Download for macOS” |
| Reassurance | Plain commercial terms or privacy promise, no flourish. | 4–12 words | “Product updates only. No spam.” |
| Closing | Ask whether the reader is ready for the intended quality of outcome. | 8–14 words | “Ready to show your work the way you designed it?” |

**Words and phrasing to use:** your work; fine-tune; polished; smooth; control; timing; ready; included

**Avoid:** revolutionary; game-changing; unlock limitless potential; disrupt; magic; hustle

**Rules:**

- Explain what a user can set, change or produce before making a quality claim.
- Contrast a real friction with the product's mechanism, not with an exaggerated competitor caricature.
- Keep button labels literal and put eligibility or trial terms in the caption below.
- Use question headings for objections and a result-oriented question for the final invitation.

## Do's and Don'ts

### Do

- Keep the display and section headlines at weight 500 with -0.03em tracking.
- Center the opening in a 1194px frame with 32px side padding.
- Use one 54px-high blue action and a caption 16px below it.
- Give ordinary cards 18px corners and 1px low-alpha chalk borders.
- Show full working context in the large 1130px demonstration and isolate operations in smaller vignettes.
- Keep the emphasized panel's 4px perimeter visibly beveled.
- Use 144px desktop chapter padding to separate dense demonstrations.
- Preserve the broad black footer plate against the brightest blue field.

### Don't

- Do not use weight 700 or 800 to manufacture emphasis in the 64px section leads.
- Do not give every card the emphasized panel's blue rim; ordinary cards stay at a faint 1px edge.
- Do not turn the 16px-radius actions into fully rounded pills.
- Do not tint paragraphs blue; reserve chromatic text for short heading endings and offer labels.
- Do not flatten the translucent demonstration shell into an unframed rectangle.
- Do not add prominent colored category badges above every section; the main section leads are unlabelled.
- Do not replace the quiet 56px accordion controls with chunky filled cards.
- Do not introduce a white footer or alternating white marketing bands into the dark continuous canvas.

## Motion and responsive

### Motion

**Observed:**

- Declared reveal-up animation: 0.7s cubic-bezier(.16,1,.3,1), applied widely to content.
- Primary actions declare color, background-color, border-color, box-shadow, opacity and transform transitions at 0.15s cubic-bezier(.4,0,.2,1).
- A 44s linear infinite marquee and 2s pulse animations are declared. Reveal wrappers include reduced-motion overrides.

**Transfer:**

- Use the short control transition for the blue-to-slate hover treatment.
- Keep content reveals subordinate to the working demonstration; the settled scene must remain legible without movement.

**Unknown:**

- Exact scroll-trigger thresholds and demonstration playback choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Headline scale clamps from 40px to 70px; section headings clamp from 32px to 64px.
- The capability grid becomes two columns at the medium breakpoint; offer columns and the full navigation link group use the large breakpoint.
- Chapter padding steps from 80px through 112px to 144px. Header top spacing clamps from 16px to 50.4px.

**Transfer:**

- Stack capability and offer columns on narrow screens, preserving text before each demonstration.
- Keep the blue field and black footer plate relationship, reducing internal padding rather than removing the plate.
- Scale the whole application scene coherently so chrome and preview maintain their relationship; use focused vignettes for readable details.

**Unknown:**

- Mobile menu interaction and exact narrow-screen demonstration treatment are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
