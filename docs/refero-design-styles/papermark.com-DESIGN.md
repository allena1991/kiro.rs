# Papermark — cinematic business confidence

## Overview

A businesslike grotesk identity with the atmosphere of a film opening and the restraint of a financial report. Dark photographic scenes give way to white product demonstrations, warm stone testimonials and near-black proof chapters. Natural portraits and architectural photography carry the human story, while spare metrics and sharply framed interfaces make it suitable for serious software, infrastructure and professional services. The overall rhythm is spacious, with compact navigation and denser comparison tools.

### Essentials

- A cinematic promise, not a dashboard hero: full-bleed darkened workplace footage fills an 863px stage beneath a 37px announcement; left-aligned 92px/1.05 medium grotesk type sits over it, with a narrow 17px support paragraph and a bottom trust strip. Use a genuine workplace still when film is unavailable.
- Headlines are broad and light in appearance rather than heavy: display weight 500, -0.02em tracking at 92px; section statements use 34.6px/1.22 and quotes 37.4px/1.34. Large claims coexist with unusually small 26px chapter headings.
- Actions look like compact business controls: 4px corners, 14px medium labels, 14px 22px padding, and white solid versus transparent outlined buttons on dark scenes; never default to pill-shaped CTAs.
- Color belongs to evidence, not decoration: the default landing palette is predominantly black, white and warm stone (#f5f3ee and #ececea), with emerald #08a87a concentrated in a single data visualization. Orange #fb7a00 belongs to pricing selections, technical links and scoped conversion bands rather than every section.
- The product is staged like a luminous exhibit: a 1280px × 720px near-black frame with 6px corners holds a smaller 1075px × 605px white interface, soft white backlight and a broad 0px 30px 80px shadow. Recreate a credible working interface if finished product media is unavailable.
- Proof has an editorial scale change: combine numbered four-column metric cells, 66.2px tight figures with small baseline units, a stone-backed portrait quote, and a dark photographic rail with one 619px-wide panel beside 206px-wide panels. Preserve these devices while adapting their frequency and placement.
- The finish is an understated black invitation, not a second hero: a 232px horizontal band uses a 37.4px closing line and two actions, then a six-column resource footer with 13px muted links and a small outlined live-status badge.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial emerald | `#08a87a` | `--color-emerald` | accent, surface | Top portions of the large marketing data bars; not a general button color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text, action | Light canvas, interface surfaces and foreground on dark chapters. |
| Black | `#000000` | `--color-black` | background, text, border, action | Strong text, editorial rules, impact chapter and default footer. |
| Deep chapter black | `#0a0a0a` | `--color-security-dark` | background | Subtle differentiation of adjacent dark credibility chapters. |
| Near-black ink | `#0b0b0b` | `--color-ink` | background, text, action | Hero and product-stage backing; primary text on warm light surfaces. |
| Utility ink | `#111827` | `--color-utility-ink` | text, surface, action | Technical card headings, selected filters and calculator total panel. |
| Photographic charcoal | `#1a1a1a` | `--color-photo-base` | surface | Backing for photographic story cards. |
| Chart charcoal | `#1c1c1c` | `--color-chart-base` | surface | Base portions of the editorial data bars. |
| Question ink | `#1f2937` | `--color-faq-ink` | text | Accordion question labels. |
| Body gray | `#4b5563` | `--color-body-ink` | text, border | Body copy and stronger technical-card outlines. |
| Muted gray | `#6b7280` | `--color-muted` | text | Secondary heading clauses and light-theme footer text. |
| Control edge | `#d1d5db` | `--color-control-edge` | border, text | Filter borders, technical-panel edges and pale support text on dark utility openings. |
| Fine edge | `#e5e7eb` | `--color-edge` | border | Card outlines and status badge edge. |
| Portrait stone | `#ececea` | `--color-stone` | background | Portrait-and-quote band. |
| Warm paper | `#f5f3ee` | `--color-warm-paper` | background | Large typographic capability interlude. |
| Table stripe | `#f3f4f6` | `--color-table-stripe` | surface, border | Comparison stripes, plan headers, faint customer-card outlines and inactive controls. |
| Cool paper | `#f9fafb` | `--color-cool-paper` | background, surface | Technical inset panels and customer metric bands. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#22c55e` | `--color-status` | accent | 8px operational indicator in the footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing, comparison, security and customer-library pages | Conversion orange | `#fb7a00` | `--color-orange` | accent, background, action, border, link | Selected plans, check icons, technical links and isolated conversion bands. |
| comparison feature demonstrations | Active feature wash | `#fff7ed` | `--color-orange-wash` | surface | Pale backing of the selected feature row. |

## Typography

- **__articulat_c65e33** — Display headlines, quotes, financial proof figures, utility headings and footer headings. Open, clean grotesk with a medium cut that looks light at display scale. If unavailable, use **Inter**. Use weight 500 and preserve the role-specific negative tracking. Font stack: "__articulat_c65e33", Inter, system-ui, sans-serif.
- **Inter** — Body copy, navigation, actions, chapter headings and small utility text. Neutral modern sans with compact, legible small text and straightforward figures. Font stack: "Inter", -apple-system, system-ui, sans-serif.
- **ui-sans-serif** (only for pricing calculators) — Large calculator total. Plain system sans numerals, distinct from the editorial display figures. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | __articulat_c65e33 | 500 | 92px | 1.05 | -0.02em | size clamp(48px, 6.4vw, 92px) | Main cinematic promise. |
| metric | __articulat_c65e33 | 500 | 66.2px | 0.92 | -0.03em | size clamp(44px, 4.6vw, 76px) | Financial or operational proof figures in numbered columns. |
| capability-list | __articulat_c65e33 | 500 | 43.2px | 1.2 | -0.01em | fixed | Vertically moving capability words on warm paper. |
| heading | Inter | 500 | 40px | 1.15 | -0.015em | size clamp(28px, 2.8vw, 40px) | Editorial data-visualization headline. |
| quote | __articulat_c65e33 | 500 | 37.4px | 1.34 | -0.005em | size clamp(26px, 2.6vw, 38px) | Large customer quotation next to a portrait. |
| closing | __articulat_c65e33 | 500 | 37.4px | 1.2 | -0.01em | size clamp(28px, 2.6vw, 38px) | Single closing invitation. |
| statement | Inter | 500 | 34.6px | 1.22 | -0.018em | size clamp(24px, 2.4vw, 36px) | Introductory product definition with a darker first clause and faded continuation. |
| chapter | Inter | 500 | 26px | 1.25 | -0.005em | fixed | Compact credibility chapter heading; a 1.15 line-height variant belongs to the photographic story rail. |
| metric-unit | __articulat_c65e33 | 500 | 17.3px | 0.92 | -0.01em | size clamp(15px, 1.2vw, 22px) | Small muted unit on the baseline of the metric. |
| lede | Inter | 400 | 17px | 1.55 | normal | fixed | Narrow hero support paragraph. |
| body | Inter | 400 | 16px | 1.5 | normal | fixed | Explanatory paragraphs. |
| button | Inter | 500 | 14px | 1.5 | normal | fixed | Landing conversion labels. |
| footer-heading | __articulat_c65e33 | 500 | 14px | 20px | -0.01em | fixed | Footer column labels. |
| footer-link | Inter | 400 | 13px | 24px | normal | fixed | Footer links and short brand description. |
| trust-label | Inter | 500 | 12px | 1.5 | 0.14em, uppercase | fixed | Small trust-strip heading. |
| status-label | Inter | 400 | 11px | 16px | normal | fixed | Live status badge text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing calculators | calculator-total | ui-sans-serif | 400 | 96px | 1 | normal | fixed | Total anchored low in the dark calculation panel. |
| customer-library and comparison pages | library-display | __articulat_c65e33 | 500 | 72px | 1 | -0.01em | fixed | Centered customer-library and alternative-page promise. |
| customer-library pages | library-metric | Inter | 400 | 72px | 1 | normal | fixed | Three centered aggregate figures. |
| pricing and security pages | utility-display | __articulat_c65e33 | 500 | 60px | 1 | -0.01em | fixed | Pricing opening and centered security-panel opening. |
| utility, comparison and customer-library pages | heading-pair | __articulat_c65e33 | 500 | 36px | 40px | -0.01em | fixed | Section heading followed immediately by a gray continuation at equal size. |
| pricing pages | plan-price | Inter | 500 | 36px | 40px | normal | fixed | Tier pricing figure. |
| customer-library and technical pages | card-heading | __articulat_c65e33 | 500 | 30px | 1.2 | -0.01em | fixed | Story-card titles and technical chapter leads. |
| security pages | technical-heading | __articulat_c65e33 | 500 | 20px | 28px | -0.01em | fixed | Technical feature-card heading. |
| comparison and security pages | question | __articulat_c65e33 | 500 | 16px | 28px | -0.01em | fixed | Accordion questions. |
| utility and customer-library pages | control | Inter | 500 | 14px | 20px | normal | fixed | Filter chips and utility-page actions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium weight does most of the work. Do not replace the apparent lightness of large Articulat headlines with bold display cuts.
- Tracking tightens from -0.01em utility headings to -0.02em hero type and -0.03em editorial metrics. Body and action tracking stays normal.
- Equal-sized black and gray clauses are a recurring hierarchy device; support need not always be a smaller paragraph.
- The rolling aggregate counter is an oversized numeral artwork separate from the ordinary type hierarchy; keep its full number legible and its units economical.

## Layout

**Density:** Airy editorial chapters around compact controls and information-dense comparison tools.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Chip wrapping, icon-to-label groups and compact control stacks. |
| 12px | Action groups and footer-heading separation. |
| 16px | Heading-to-support separation in utility sections. |
| 24px | Standard card padding and technical grids. |
| 32px | Technical card padding, portrait-card gaps and inset utility-container gutters. |
| 36px | Hero support-to-action gap and metric-cell side padding. |
| 48px | Heading-to-card-grid separation and customer-story grid gap. |
| 64px | Portrait-to-quote gap and utility section padding. |
| 80px | Desktop outer gutters and footer top/bottom padding. |
| 90px | Closing-band vertical padding. |
| 110px | Intro statement top space and product-stage bottom clearance. |
| 120px | Metric-band bottom clearance and dark-story bottom padding. |
| 160px | Large credibility and capability chapter padding. |
| 180px | Warm capability-interlude bottom space. |

### Containers and grids

- **editorial-container**: max width 1600px · side padding 80px. Default outer shell; yields a 1280px content span at 1440px desktop width.
- **portrait-quote**: max width 1440px · 2 columns · gap 64px · side padding 80px. A 480px portrait column beside flexible quote text.
- **metric-columns**: 4 columns · gap 0px. Four equal numbered proof cells, separated by hairlines.
- **footer-grid**: 6 columns · gap 32px. One brand-and-status column plus five link groups.
- **utility-container** (only for pricing, comparison and security pages): max width 1280px · side padding 32px. Inset utility composition with 1216px usable content.
- **story-library** (only for customer-library pages): max width 1152px · 2 columns · gap 48px. Equal-width photographic stories with titles below.
- **technical-grid** (only for security and comparison pages): 3 columns · gap 24px. Technical capability cards; two columns when copy needs more width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | product-frame | 6px |
|  | cards | 8px |
|  | portrait | 12px |
| pricing and comparison tools | segmented-controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product-stage | `0px 30px 80px 0px rgba(0, 0, 0, 0.18)` | Large black product frame on white. |
|  | product-screen | `0px 10px 60px 0px rgba(0, 0, 0, 0.4)` | White screen inside the black exhibit. |
| comparison pages | light-card | `0px 1px 2px 0px rgba(0, 0, 0, 0.05)` | Fine outlined feature and quotation cards. |

### Surfaces

#### White canvas · level 0

**Use:** Product proof, metrics and utility content.

**CSS:** `background: #ffffff; color: #0b0b0b`

#### Dark chapter · level 0

**Use:** Cinematic opening and editorial data chapter.

**CSS:** `background: #0b0b0b; color: #ffffff`

**Observed:** Adjacent credibility chapter uses deeper #0a0a0a; impact chapter and closing use pure black. Thin white alpha rules mark transitions.

**Transfer:** Use sustained dark stretches rather than alternating every individual card.

#### Warm capability paper · level 0

**Use:** Typographic capability interlude.

**CSS:** `background: #f5f3ee; padding: 160px 0px 180px`

#### Portrait stone · level 0

**Use:** Human testimonial chapter.

**CSS:** `background: #ececea; padding: 100px 0px 90px`

#### Product backlight · level 1

**Use:** White halo behind the exhibited interface.

**CSS:** `position: absolute; inset: 6%; background: radial-gradient(closest-side, rgba(255, 255, 255, 0.96), rgba(255, 255, 255, 0.6) 40%, rgba(255, 255, 255, 0) 75%); filter: blur(60px)`

**Observed:** Soft neutral light stays inside the black product frame, beneath the white screen.

**Transfer:** Match a diffuse white glow rather than adding colored neon.

#### Technical inset · level 1

**Only for:** security pages

**Use:** Secondary details below a main technical grid.

**CSS:** `background: #f9fafb; border: 1px solid #d1d5db; border-radius: 4px; padding: 24px; max-width: 768px`

**Observed:** Left-aligned, narrower than the parent section; small checks precede stacked detail rows.

#### Orange conversion band · level 0

**Only for:** comparison and customer-library pages

**Use:** An isolated decision point after substantial proof.

**CSS:** `background: #fb7a00; color: #000000; border-radius: 8px`

**Observed:** Centered library variant is 1280px wide with 128px vertical padding; comparison ending also uses a full-width orange field. A compact pricing variant uses 4px corners and a horizontal heading/action arrangement.

**Transfer:** Limit this broad saturated treatment to a deliberate conversion moment.

#### White utility navigation · level 2

**Only for:** utility and customer-library pages

**Use:** Sticky navigation over white content.

**CSS:** `background: rgba(255, 255, 255, 0.75); backdrop-filter: blur(16px); height: 80px`

## Components

### Navigation

**Use:** Persistent desktop orientation.

**CSS:** `height: 80px; background: rgba(10, 10, 10, 0.475); backdrop-filter: saturate(1.05153) blur(5.2px); display: flex; align-items: center`

**Observed:** Sticky top bar with wordmark left, compact links and dropdown chevrons across the middle, login and a small black action right. Labels use 14px Inter regular. It starts translucent and dark over the film and changes to white or dark to suit later content.

**Transfer:** Use the editorial-container alignment; keep the logo compact rather than turning navigation into another headline.

### Primary button

**Use:** Default action on the cinematic opening and black closing band.

**CSS:** `background: #ffffff; color: #0b0b0b; border: 1px solid transparent; border-radius: 4px; padding: 14px 22px; display: flex; align-items: center; gap: 10px`

**Text style:** `button` — Inter 500 · 14px/1.5

**Observed:** A right chevron accompanies the label; adjacent reassurance is plain muted text. The light-page inverse is near-black with white text and a 20px label line height.

**States:** Declared: hover background #f0efeb; background, color and border-color transition 0.2s.

### Secondary button

**Use:** Alternative action next to a solid button on dark surfaces.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.7); border-radius: 4px; padding: 14px 22px; display: flex; align-items: center; gap: 10px`

**Text style:** `button` — Inter 500 · 14px/1.5

**Observed:** Closing pair is side by side with a 12px gap. Smaller chapter-link versions use 10px 16px or 10px 18px padding; light-background versions use a black alpha outline.

**States:** Declared: hover background rgba(255, 255, 255, 0.08); background, color and border-color transition 0.2s.

### Product exhibit

**Use:** Dominant working-product demonstration on white.

**CSS:** `background: #0b0b0b; border-radius: 6px; box-shadow: 0px 30px 80px 0px rgba(0, 0, 0, 0.18); position: relative; overflow: hidden; aspect-ratio: 16 / 9`

**Observed:** A smaller white screen floats inside the frame with generous even black margins. The screen has its own 6px corners and darker soft shadow; a Product backlight sits behind it.

**Transfer:** Show one coherent task at useful scale, not a pile of tiny floating feature windows.

### Photographic story card

**Use:** Editorial customer proof rail.

**CSS:** `background-color: #1a1a1a; background-size: cover; background-position: 50% 50%; border-radius: 4px; height: 540px; position: relative; overflow: hidden`

**Observed:** One expanded story is about three times as wide as its neighbors. White text is pinned toward the lower left; the large title is 32px/40px and neighboring labels are 20px/25px. A black gradient overlay deepens from 20% at the top to 45% at 60% height and 60% at the bottom.

**Transfer:** Use buildings, workplaces or actual team context; keep the bottom text readable without putting it in a separate card footer.

### Footer columns

**Use:** Default landing-page ending.

**CSS:** `background: #000000; color: #ffffff; padding: 80px 0px`

**Text style:** `footer-link` — Inter 400 · 13px/24px

**Observed:** One brand column carries a small monogram, two-line description, compact credibility marks, social links and the Operational badge. Five further link columns use Footer-heading labels and 65%-white links. A faint top rule separates copyright and language controls below. White variant uses gray links and black labels.

**States:** Declared: hover link color #ffffff on dark; #000000 on light.

### Operational badge

**Use:** Small service-health signal in the footer brand column.

**CSS:** `border: 1px solid #e5e7eb; border-radius: 6px; padding: 4px 12px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `status-label` — Inter 400 · 11px/16px

**Observed:** Compact outlined label with an 8px green dot at the right and a pulsing halo; foreground follows the footer theme.

### Question row

**Only for:** comparison and security pages

**Use:** Objection handling without bulky cards.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 0px; color: #1f2937`

**Text style:** `question` — __articulat_c65e33 500 · 16px/28px · tracking -0.01em

**Observed:** Rows occupy about 77px including wrapper spacing and hairline division. A 16px down-chevron sits at the far right; opening rotates it by 180 degrees. Questions remain left aligned.

**States:** Declared: hover text-decoration-line none; all transition 0.15s cubic-bezier(0.4, 0, 0.2, 1).

### Technical card

**Only for:** security pages

**Use:** Specific capabilities explained in compact grids.

**CSS:** `border: 1px solid #4b5563; border-radius: 8px; padding: 32px`

**Text style:** `technical-heading` — __articulat_c65e33 500 · 20px/28px · tracking -0.01em

**Observed:** A short medium heading precedes a 16px/24px paragraph by 12px. Cards remain visually flat; some sections use two wide columns, others three narrower columns.

**States:** Declared: hover border-color #fb7a00.

### Filter chip

**Only for:** customer-library pages

**Use:** Wrapping story filters and category labels.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #d1d5db; border-radius: 4px; padding: 8px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Filter rows wrap and center with 8px gaps. Selected filter is dark with light text. Smaller story tags use 4px 12px padding, retaining rectangular corners.

**States:** Declared: hover background-color hsl(220 14.3% 95.9%) and color hsl(220.9 39.3% 11%); focus-visible outline transparent solid 2px with 2px offset.

### Feature selector

**Only for:** comparison feature demonstrations

**Use:** Connect a product image to a numbered capability list.

**CSS:** `background: #fff7ed; border: 2px solid #fb7a00; border-radius: 8px; padding: 12px; text-align: left; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05)`

**Observed:** Selected row has an orange numbered square, orange 14px heading and 12px support line. Inactive rows are white with gray outlines; a small orange text link appears under an expanded item. Rows are roughly 66px tall, separated by 8px.

**Transfer:** Use a compact, finite feature set paired with a matching demonstration rather than unrelated illustrations.

### Plan grid

**Only for:** pricing pages

**Use:** Connected tiers with directly comparable content.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); border: 1px solid #000000; border-radius: 4px; overflow: hidden`

**Observed:** Shared black vertical rules, no gaps. Light-gray plan header, 24px content padding, 36px Inter prices, aligned bottom actions. Recommended plan uses the orange action and a small orange popularity badge; other actions are near-black.

**Transfer:** Keep the shared frame and consistent action baseline even when feature-list lengths differ.

## Imagery and graphics

### Cinematic workplace scene

**Use:** Default landing opening.

**Observed:** Full-bleed live-action office scene: an older professional at a desk on the phone, with other workers and office equipment behind. Low-key blue-green shadows and natural highlights stay visible beneath dark overlays. The human subject occupies the middle/right while the left stays readable for text.

**Transfer:** Commission or choose natural footage of the new audience doing real work. Minimum equivalent is a sharp, non-posed workplace still with depth, darkened enough for white type.

**Build:** Use a cover-fit video or still on the entire hero. Add a full-field black translucent veil and a bottom-heavy black gradient; tune alpha to retain face and room detail while ensuring white text contrast. Place the copy and trust strip above both. Do not synthesize a generic neon background.

### Luminous product stage

**Use:** Signature product proof scene.

**Observed:** A bright, flat interface is centered within a broad black surround on white. The interface has a warm sidebar, sparse tabular rows and a soft lower fade; the frame remains the dominant shape rather than a device mockup.

**Transfer:** Render a realistic core task in a white rectangular interface with restrained UI detail. Minimum version is one populated list or result view with a clear title, navigation and realistic rows.

**Build:** Use Product exhibit as a 16:9 wrapper. Center a white screen occupying about 84% width and 84% height; apply 6px corners and the Product-screen shadow. Put Product backlight below it. Keep the white page visible outside the black frame.

### Portrait testimony

**Use:** Human proof in the stone band and testimonial collections.

**Observed:** Natural-color, sharply focused portraits with ordinary indoor or neutral studio backgrounds. The signature band uses a 480px square, 12px corners, and a much wider text column. Comparison cards pair landscape portrait crops with white quote bodies; a masonry wall mixes portraits with smaller social quotations.

**Transfer:** Use real customers in their own setting, retain natural skin tones and avoid duotone filters. If portraits are unavailable, use an attributed text quotation and a modest organization mark rather than artificial faces.

### Architectural story rail

**Use:** Dark editorial proof chapter.

**Observed:** Office buildings, corporate architecture and business interactions fill tall panels. Cool natural colors are heavily shaded; one panel expands horizontally while all remain 540px tall.

**Transfer:** Use context that substantiates a customer story, not generic abstract stock. Keep the same shaded, full-height panel treatment.

### Editorial bar landscape

**Use:** Signature data-led proof on dark.

**Observed:** Fourteen tightly spaced rectangular bars form a rising and falling landscape, each split into charcoal lower and emerald upper portions. Tiny low-contrast labels and faint horizontal guides keep attention on the silhouette.

**Transfer:** Visualize a meaningful process, usage curve or result for the new product. If no suitable time series exists, show a clearly labelled illustrative workflow distribution rather than inventing performance claims.

**Build:** Build a flex row with 6px gaps, aligned bottoms, within a 1280px × 380px chart bounded by rgba(255,255,255,0.08) horizontal rules. Reserve 64px at left for axis labels. Use #1c1c1c bars with absolutely positioned #08a87a caps; vary total heights to peak near the middle. Use small 10px muted-white labels and no rounded corners.

### Customer story photography

**Only for:** customer-library pages

**Use:** Two-column case-study library.

**Observed:** Large 4:3 natural photos of founders, teams and workplaces; rounded image edges, a small white organization-mark plaque in the upper right, category chips underneath and a 30px title below. Unlike the dark rail, these photographs keep their natural saturation.

**Transfer:** Use real-world imagery with consistent aspect ratio rather than forcing all customers into matching studio portraits.

### Icons

**Observed:** Primarily outline SVGs with 2px round strokes at 16px or 24px. Chevrons are small and sit after labels or at accordion edges; technical chapter icons are orange. Social symbols and certification marks are compact solid or supplied graphics.

**Transfer:** Choose a consistent round-stroke outline set for controls. Keep external marks subordinate and separate from the interface icon language.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** A slim 37px white announcement tops an 863px dark scene so the complete opening ends at the first 900px viewport boundary. Behind everything is cover-fit workplace footage, then shading, then a translucent 80px navigation band. The content is anchored to the 80px left gutter: a small credibility line above a 92px/1.05 single-line promise spanning a little over half the page, followed by a narrow roughly 408px support paragraph, a white Primary button and inline reassurance. The human subject remains visible behind and to the right. Near the bottom, a spaced uppercase trust label and rating precede a monochrome organization-logo row with an outlined customer link. All of the headline, paragraph, action, photographic subject and trust band are visible within 900px; the product interface starts below the fold.

**Transfer:** Use a short outcome promise with enough empty image area for text. Without film, use a naturally lit workplace still and retain the same dark hierarchy. Comparison and customer-library openings instead use centered 72px black headlines on white; pricing uses a left-aligned 60px headline with compact proof above it; security uses a centered 60px white headline inside an inset dark panel with small credibility marks.

**Avoid:** Do not replace this composition with centered gradient type above a floating dashboard, or hide the entire trust strip below the first screen.

**Text style:** `display` — __articulat_c65e33 500 · 92px/1.05 · tracking -0.02em

### Definition and product exhibit

**Observed:** White canvas with a 34.6px two-tone statement restricted to about half the content width. A broad Product exhibit follows, separated by ample whitespace; it shows a whole credible work surface rather than decorative fragments.

**Transfer:** Define what the product is and why it matters, then show one completed or in-progress core task.

**Text style:** `statement` — Inter 500 · 34.6px/1.22 · tracking -0.018em

### Numerical authority

**Observed:** An oversized aggregate counter leads into four equal metric columns across 1280px. A small uppercase line and date-like caption flank the top rule. Cells use muted sequence numbers, organization marks, tight 66.2px figures with baseline units, and brief gray context; vertical rules appear only between cells.

**Transfer:** Use verified throughput or outcomes. Keep the figure/unit contrast and report-like column construction even if the metrics are not financial.

**Text style:** `metric` — __articulat_c65e33 500 · 66.2px/0.92 · tracking -0.03em

### Moving capability interlude

**Observed:** Warm capability paper holds a small left-side introduction, a tall center list of 43.2px terms and a compact outlined exploration action at the right. The visible list is about 378px tall, with 54px rows; one term is dark while others fade toward black at 22% opacity.

**Transfer:** Use short audience needs or workflows as the list. Retain the text-as-image scale and fading emphasis rather than converting it into feature cards.

**Text style:** `capability-list` — __articulat_c65e33 500 · 43.2px/1.2 · tracking -0.01em

### Stone portrait quotation

**Observed:** Portrait stone supports a 480px square photo left and a large Quote text block right with 64px between. Attribution and role are smaller, with an organization mark below and a fine pager near the bottom.

**Transfer:** Feature one specific, credible customer statement. Keep it conversational and visually substantial without adding a large quotation-mark ornament.

**Text style:** `quote` — __articulat_c65e33 500 · 37.4px/1.34 · tracking -0.005em

### Dark proof rail

**Observed:** Dark chapter with a compact 26px heading and outlined story link sharing a row, 48px before the Photographic story card rail. One broad active card is followed by three narrow cards with 14px gaps; a subdued logo strip sits underneath.

**Transfer:** Choose a small set of stories with different outcomes. Let the imagery and asymmetry provide drama rather than increasing title weight.

**Text style:** `chapter` — Inter 500 · 26px/1.25 · tracking -0.005em

### Credibility chapter

**Observed:** A near-black band with 160px vertical padding. Compact left heading and wider right support paragraph sit above five evenly divided credibility items. Pale marks, short labels and small detail links occupy the lower row; very faint vertical rules separate them.

**Transfer:** Show appropriate standards, integrations or externally supported trust signals for the new product. Preserve the subdued monochrome presentation.

**Text style:** `chapter` — Inter 500 · 26px/1.25 · tracking -0.005em

### Data as editorial artwork

**Observed:** A 40px white multiline heading occupies roughly half the width above Editorial bar landscape. The chart spans the full editorial content width with a 48px heading gap and restrained labels.

**Transfer:** Explain what the visualization lets a reader understand, not simply that analytics exist.

**Text style:** `heading` — Inter 500 · 40px/1.15 · tracking -0.015em

### Equal-scale heading pair

**Observed:** A 36px black statement continues in gray at the same size, either on the same line or immediately below. Cards or controls follow after 40px–48px. It is used for calculators, testimony, feature summaries and FAQ introductions.

**Transfer:** Use the first clause for the section's purpose and the gray clause for the invitation or explanatory qualification.

**Text style:** `heading-pair` — __articulat_c65e33 500 · 36px/40px · tracking -0.01em

### Technical capability chapter

**Observed:** On White canvas, an orange outline icon accompanies a 30px lead, followed by an explanatory paragraph and a 24px-gap Technical card grid. A narrower Technical inset may follow 32px below. Chapter separation is a faint horizontal rule rather than a colored band.

**Transfer:** Organize detailed capabilities by a reader's question. Keep specifications concrete and avoid turning every subtopic into an oversized marketing headline.

**Text style:** `card-heading` — __articulat_c65e33 500 · 30px/1.2 · tracking -0.01em

### Comparison and calculator tools

**Observed:** Plan grid precedes a left-control/right-total calculator. Orange marks the selected plan, black outlines mark selected term controls, and a dark 400px-wide total panel places its 96px figure near the bottom. A longer feature table uses a shared black frame, gray alternate rows around 80px tall and black category bands.

**Transfer:** Make pricing logic and differences inspectable. Preserve the flat tabular construction instead of replacing the comparison with detached elevated cards.

**Text style:** `plan-price` — Inter 500 · 36px/40px

### Customer proof library

**Observed:** Centered Library-display opening, wrapping Filter chips, then a 1152px two-column image/title grid with 48px gaps. Smaller text-only customer cards follow with faint edges and 24px padding. Organization-logo fields and a three-column pale metric band precede a centered Orange conversion band.

**Transfer:** Let visitors scan authentic stories by outcome or audience; make card titles report the result rather than repeat a generic endorsement.

**Text style:** `library-display` — __articulat_c65e33 500 · 72px/1 · tracking -0.01em

### Closing invitation and resource ending

**Observed:** A black 232px invitation band with a thin top edge aligns a Closing line left and Primary button plus Secondary button right. Footer columns follow without changing the black field. Comparison and customer-library variants finish with an orange invitation before the black footer. Pricing ends its comparison table directly into a white footer; security ends its FAQ directly into the same white footer, with no extra conversion hero.

**Transfer:** Use a specific next-step invitation when the narrative calls for one; preserve the compact horizontal default and the useful resource footer. Keep tool and reference page endings more utilitarian.

**Text style:** `closing` — __articulat_c65e33 500 · 37.4px/1.2 · tracking -0.01em

## Page flow

**Storyline:** Outcome promise → concrete product understanding → credible proof → deeper capability or decision support → next step → useful resource ending.

### Flagship product landing

1. **promise** — Cinematic workplace opening with one short outcome and bottom trust strip.
2. **product demonstration** — Two-tone definition and a luminous framed work surface.
3. **quantified proof** — Rolling aggregate followed by numbered four-column metrics.
4. **capability chapters** — Moving type interlude, portrait testimony, dark photographic rail and subdued credibility chapter.
5. **product understanding** — One broad emerald-and-charcoal data visualization.
6. **closing call** — Horizontal black invitation followed by the black resource footer.

**Transfer:** Balance emotional workplace context with report-like proof; adapt the chapter sequence to the new product's strongest evidence.

### Competitive evaluation

1. **promise** — Centered white opening with large category-comparison headline, two actions and a compact testimonial.
2. **product demonstration** — Logo band and large framed interface.
3. **social proof** — Three portrait quote cards.
4. **decision support** — Credibility panel, compact plan comparison and explanatory tier cards.
5. **capability chapters** — Numbered feature selector beside interface media, benefit grid, masonry customer quotations and alternating text/media rows.
6. **objection handling** — Fine-rule FAQ.
7. **closing call** — Broad orange invitation with two actions, then black footer.

**Transfer:** Use transparent differences, inspectable product examples and authentic switching reasons rather than merely repeating competitor names.

### Plan selection and purchasing clarity

1. **promise** — Left-aligned utility opening with compact organization proof.
2. **pricing** — Connected four-tier Plan grid and billing controls.
3. **decision support** — Interactive calculation with a dark oversized total.
4. **enterprise route** — Compact orange horizontal invitation.
5. **comparison** — Long alternating-row table with black category bands and persistent comparison headings.
6. **resource ending** — White six-column footer directly after the table.

**Transfer:** Prioritize clear pricing mechanics and detailed comparisons over an added cinematic ending.

### Technical trust and policy reference

1. **promise** — Inset charcoal opening with credibility marks, category label and centered utility headline.
2. **orientation** — Compact anchor-chip navigation.
3. **capability chapters** — Repeated technical icon/heading/paragraph groups, bordered grids and narrow supporting panels.
4. **compliance detail** — Evidence-oriented standards and rights chapters, then related policy links.
5. **objection handling** — Narrower FAQ.
6. **resource ending** — White footer without a conversion band.

**Transfer:** Use this restrained, text-heavy variant for technical due diligence, replacing the categories with those relevant to the new product.

### Customer outcome discovery

1. **promise** — Centered two-line library headline and support line.
2. **orientation** — Wrapping rectangular category filters.
3. **social proof** — Large natural-photo story grid, then smaller text-only customer cards.
4. **breadth of adoption** — Organization-logo fields and three centered aggregate metrics on pale gray.
5. **closing call** — Inset orange centered invitation followed by black resource footer.

**Transfer:** Favor authentic environments and outcome-led titles; use filters only when they help navigate a substantial collection.

## Writing

Confident, practical and commercially literate. Short benefit statements carry the marketing, while detailed supporting text names concrete controls, actions and outcomes rather than poetic abstractions.

**Do not copy:** Do not reuse Papermark names, logos, customer identities, quotations, competitor assertions, certification claims or business metrics. All numerical proof, compliance statements and testimonials require the new product's own substantiation. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your for decisions and benefits. Use we sparingly for commitments, and the product name for clear category definitions.
- **Rhythm:** A very short opening promise contrasts with a single explanatory support paragraph. Section titles are brief; case-study titles can be longer and outcome-specific. Technical descriptions use plain declarative sentences and concise lists.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Direct commercial outcome, active verb, little qualification. | 3–8 words | “Close Deals Faster.”<br>“Find the plan that works for you” |
| Supporting line | Identify audience, task and reason to trust in one plain sentence. | 15–30 words | “Trusted by businesses to share and track documents globally”<br>“Control exactly who can access your documents and what they can do with them.” |
| Primary action | Low-friction verb plus concrete next step. | 2–4 words | “Start for free”<br>“Book a Demo” |
| Customer-story title | Name the actor and an observable result; include a number only when it is meaningful. | 8–18 words | “How Destro AI closed its $8M seed round with [Brand]” |
| Capability explanation | Name the control, then describe the user consequence. | One heading and one short paragraph | “File & Folder Level Permissions”<br>“Granular access at file and folder level, with inherited permissions for consistency.” |
| Closing invitation | Invite the reader's next real task rather than restate the whole value proposition. | 6–10 words | “Run your next deal on [Brand].” |

**Words and phrasing to use:** share; track; control; visibility; your team; real impact; exactly; secure; custom; unlimited when demonstrable

**Avoid:** revolutionary; magic; game-changing; unlock limitless potential; excessive financial jargon; vague AI superlatives

**Rules:**

- Lead with the audience's task or outcome, then explain the mechanism.
- Write technical details explicitly enough to support a purchase decision.
- Keep reassurance beside the action, not hidden in a long paragraph.
- Use first-person testimony in the customer's own voice, with attribution.
- Use sentence case for headings; reserve spaced uppercase for small trust labels.
- Maintain grammatical polish rather than reproducing informal spelling errors or untranslated category strings.

## Do's and Don'ts

### Do

- Keep the default hero at 92px/1.05 with medium weight and a narrow 17px support column.
- Use 80px desktop editorial gutters and 32px inner utility gutters deliberately.
- Retain 4px button corners and 14px medium labels.
- Create a 6px-cornered black product exhibit with a smaller luminous white screen.
- Put 66.2px proof figures beside 17.3px baseline units instead of equally sizing number and unit.
- Use 160px vertical chapter space to make major dark credibility sections feel editorial.
- Keep stone portrait testimony natural in color and separated from text by 64px.
- Use 13px/24px muted footer links under 14px medium headings.

### Don't

- Do not turn every section title into a 60px headline; 26px chapter heads are part of the hierarchy.
- Do not make orange a full-page default or emerald a general CTA color.
- Do not apply 24px rounded corners to controls; the core actions use 4px.
- Do not add luminous colored shadows around cards; the product backlight is white.
- Do not place broad paragraph copy across the entire hero width; its support column is about 408px.
- Do not separate pricing tiers with decorative gaps and giant shadows; they share a 1px black frame.
- Do not shade customer-library photos with the dark story-rail overlay; those two image treatments have different jobs.
- Do not inflate the footer status badge into a large trust card; it is an 11px label with an 8px indicator.

## Motion and responsive

### Motion

**Observed:**

- Declared button background, color and border-color transitions are 0.2s on the landing controls.
- Declared story-card flex-grow transition is 0.6s cubic-bezier(0.2, 0.6, 0.2, 1).
- Declared chart bar height transition is 1s, cap height 0.7s, both cubic-bezier(0.2, 0.7, 0.25, 1); cap includes a 350ms added delay.
- Declared marquees use 30s and 38s linear infinite cycles; the operational halo uses a 1s ping.
- Navigation declares 0.35s background-color, box-shadow and backdrop-filter transitions.

**Transfer:**

- Keep movement tied to the signature devices: workplace film, shifting capability words, expanding story rail and rising bar landscape.
- Let the completed chart and selected story remain readable rather than making every proof element continually move.

**Unknown:**

- Exact triggers, hover-versus-timed story selection, counter timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px, 1400px and 1536px; landing CSS additionally includes 480px and 980px.
- Display and several editorial roles use the clamp formulas recorded in the typography recipes.
- Footer classes declare two columns initially, three at the medium breakpoint and six at the large breakpoint.
- Pricing tier classes declare one column initially, two at the medium breakpoint and four at the extra-large breakpoint.

**Transfer:**

- As design guidance, preserve the portrait before its quote when stacking, and keep the black product frame visible around the smaller screen.
- As design guidance, reduce editorial gutters toward 16px on narrow screens while preserving the type-scale clamps and solid/outlined action hierarchy.
- As design guidance, keep the story rail's active story distinct when narrowing the layout rather than compressing all titles into narrow unreadable strips.

**Unknown:**

- Actual mobile compositions, navigation menus and overflow behavior were not observed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
