# Phoebe — pastel worlds at work

## Overview

Friendly automation presented as a bright, reassuring world rather than a technical control room. Deep teal grotesk display lettering and violet actions sit on white, with peach-pink skies, cyan cloud scenes and soft lavender accents. Illustrated environments and floating interface fragments make invisible work tangible, while compact cards sit within unusually airy sections. The style suits service software and human-facing AI products that need to feel capable without feeling clinical.

### Essentials

- A confident promise floats over a miniature world: centered 48px/1.1 bold display type, a 960px headline limit and a 1400px-wide pink-to-peach stage with 8px corners.
- Small actions keep the spectacular art approachable: default violet buttons are 36px high, 14px/20px at weight 600, padded 8px 16px and fully pill-shaped.
- Color is scenery, not the whole interface: white occupies most long-form sections, deep teal anchors headings and the footer, and saturated violet is concentrated in actions, icons and short labels.
- Operational magic becomes tangible through floating cards: cyan skies and cream-pink clouds back simplified interface fragments; use an original illustrated product world, or layered SVG clouds and one believable task notification when no rich media exists.
- Capabilities have a botanical personality: pale blue-gray cards with 8px corners and 16px padding carry small flower-like colored badges, a 16px tracked display label and 16px/26px explanatory text.
- Proof feels alive rather than monumental: compact 320px-wide testimonial cards move in two edge-faded rows, with short tinted outcome pills and a ruled attribution base.
- The experience resolves into daylight and deep teal: a cloud-framed outcome callout pairs compact actions above a full-width #002429 footer; retain the atmospheric device somewhere prominent on every marketing page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#5533ee` | `--color-violet` | action, link, accent | Primary buttons, links, graphic paths and functional icons. |
| Deep teal | `#002429` | `--color-ink` | text, background | Default heading ink and footer canvas. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cyan sky | `#71cff0` | `--color-cyan-sky` | background | Cloud-backed scenes and closing callout upper gradient. |
| Peach sky | `#ffde9e` | `--color-peach-sky` | background | Opening gradient stop at 50%, carrying through the lower stage. |
| Pink sky | `#ffadde` | `--color-pink-sky` | background | Upper opening gradient stop. |
| Lavender | `#e3e0ff` | `--color-lavender` | surface, accent | Integration pills, selected timeline stage and company statistics. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate teal | `#42595e` | `--color-body` | text | Paragraphs and support text. |
| Announcement black | `#000000` | `--color-black` | background, text | Slim announcement band and navigation text. |
| Near black | `#0a0a0a` | `--color-headline` | text | Opening promise and selected introductory display statements. |
| Secondary action ink | `#171717` | `--color-secondary-ink` | text | Text on light secondary actions. |
| Muted sage | `#829494` | `--color-muted` | text | Secondary context and company introduction support. |
| Soft slate | `#9eadb0` | `--color-soft` | text, accent | Tertiary labels and inactive process markers. |
| Teal mist edge | `#dbe3e3` | `--color-rule` | border, background | Section and card hairlines; lower stop of cloud callout gradient. |
| Cool gray edge | `#e5e7eb` | `--color-header-rule` | border | Navigation and recruitment list separators. |
| Blue-gray wash | `#f0f5f5` | `--color-surface` | surface | Capability cards, process rows and chart backing. |
| Secondary action gray | `#f5f5f5` | `--color-secondary-fill` | action, surface | Secondary audio or conversation action. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, proof cards and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| personal-assistant request illustrations | Request coral red | `#ff4234` | `--color-request-red` | surface | Floating task bubbles outside the product interface. |
| personal-assistant request illustrations | Request apricot | `#ffbb5b` | `--color-request-gold` | surface | Floating task bubbles. |
| personal-assistant request illustrations | Request salmon | `#fe8b6f` | `--color-request-salmon` | surface | Floating task bubbles. |
| personal-assistant request illustrations | Request pink | `#fd6f92` | `--color-request-pink` | surface | Floating task bubbles. |
| company statistics | Aubergine | `#1f125e` | `--color-stat-ink` | text | Large percentages and uppercase captions on lavender statistics. |
| personal-assistant request illustrations | Request green | `#96cd91` | `--color-request-green` | surface | Floating task bubbles. |
| company and culture pages | Ice blue | `#e3f7fc` | `--color-company-sky` | background | Lower company introduction gradient stop. |
| personal-assistant product pages | Warm off-white | `#fafaf8` | `--color-warm-panel` | surface | Comparison and floating-request stages. |

## Typography

- **PolymathDisplay** — Headlines, capability names, small scene labels and statistics. Rounded, tightly constructed geometric display sans with a broad friendly stance and distinctive compact joins. If unavailable, use **DM Sans**. Use 400, 600 and 700; retain normal tracking on large headings. Font stack: "PolymathDisplay", "DM Sans", system-ui, sans-serif.
- **MDSystem** — Body copy, navigation, actions, testimonials and supporting captions. Unobtrusive contemporary grotesk with open counters and a practical text rhythm. If unavailable, use **Inter**. Use 400–700; preserve relaxed paragraph leading. Font stack: "MDSystem", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | PolymathDisplay | 700 | 48px | 1.1 | normal | Default opening promise, centered and balanced across two lines. |
| heading | PolymathDisplay | 700 | 36px | 40px | normal | Section leads and closing outcome statement. |
| lead | MDSystem | 400 | 18px | 1.625 | normal | Supporting paragraphs below major promises. |
| timeline-label | PolymathDisplay | 400 | 18px | 1.375 | 0.01em | Stage names and day labels above the progress illustration. |
| body | MDSystem | 400 | 16px | 1.625 | normal | Capability descriptions, process details and expanded answers. |
| card-label | PolymathDisplay | 400 | 16px | 1.375 | 0.025em | Capability names and small benefit labels. |
| strip-label | PolymathDisplay | 400 | 16px | 1.5 | 0.025em | Trust-strip heading and process-step title. |
| quote | MDSystem | 500 | 16px | 1.375 | normal | Compact testimonial quotations. |
| integration | PolymathDisplay | 400 | 16px | 1.5 | 0.03em | Names in the lavender integration ticker. |
| button | MDSystem | 600 | 14px | 20px | normal | Default violet action and short emphatic links. |
| navigation | MDSystem | 500 | 14px | 20px | normal | Navigation, small outcome checklist and secondary actions. |
| small-bold | MDSystem | 700 | 14px | 20px | normal | Testimonial attribution and footer group labels. |
| small | MDSystem | 400 | 14px | 20px | normal | Footer links and short brand description. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and culture pages | company-display | PolymathDisplay | 700 | 60px | 1 | normal | Centered mission statement in a narrow introduction. |
| company statistics | stat | PolymathDisplay | 700 | 48px | 1 | normal | Large percentages on lavender cards. |
| personal-assistant product pages | assistant-display | PolymathDisplay | 600 | 48px | 1 | normal | Narrow centered promise and request-stage heading. |
| company and recruitment pages | list-title | MDSystem | 400 | 18px | 28px | normal | Recruitment row titles and plain editorial support. |
| company and culture pages | person | PolymathDisplay | 400 | 16px | 1.375 | 0.02em | Name and role in a portrait directory. |
| personal-assistant product pages | waitlist-button | MDSystem | 600 | 16px | 24px | normal | Larger rounded-rectangle signup action. |
| personal-assistant request illustrations | request | MDSystem | 500 | 16px | 1.4 | normal | Short first-person tasks inside illustrated speech bubbles. |
| company statistics | stat-caption | PolymathDisplay | 600 | 14px | 20px | normal, uppercase | Compact label below a percentage. |

**Notes:**

- Keep headline tracking normal; the display family's own construction supplies the tight, rounded silhouette. Small display labels instead open up to 0.01–0.03em.
- Use the display family for labels as well as headings, but the text grotesk for explanations and actions. Do not turn the whole site into one geometric font.
- Default section headings are 36px/40px at weight 700; the company introduction grows to 60px and the personal-assistant introduction uses a lighter 48px at weight 600.

## Layout

**Density:** Airy sections with compact internals: broad white pauses separate dense cards, short labels and small actions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap, action-pair gap and compact list rhythm. |
| 12px | Icon-to-checklist text gap and testimonial base padding. |
| 16px | Capability-card padding, card-grid gap and stacked component rhythm. |
| 20px | Desktop side padding inside main containers and testimonial padding. |
| 24px | Company stat padding and secondary grid rhythm. |
| 32px | Media-grid gaps and heading-to-grid spacing. |
| 40px | Mobile section padding and footer vertical padding. |
| 48px | Default opening stage top padding and split-section grid gap. |
| 64px | Cloud callout padding and company section vertical padding. |
| 80px | Default desktop major-section vertical padding. |
| 96px | Personal-assistant opening top padding. |

### Containers and grids

- **marketing-container**: max width 1280px · side padding 20px. Centered default section container; 1240px usable content at desktop.
- **opening-stage**: max width 1440px · side padding 20px. Near-full-width illustrated opening, leaving only a narrow white gutter.
- **capability-grid**: 3 columns · gap 16px. Equal cards arranged in two rows; each about 403px wide at desktop.
- **media-grid**: 3 columns · gap 32px. Square illustrated capability scenes over brief labels and descriptions.
- **split-section**: 2 columns · gap 48px. Square visual beside text and a two-by-two benefit matrix; also trust content beside FAQ.
- **company-column** (only for company and recruitment pages): max width 896px. Narrower measure for people, statistics and recruitment.
- **people-grid** (only for company and culture pages): 3 columns · gap 40px. 272px-wide portrait entries with 56px row gaps.
- **comparison-grid** (only for personal-assistant product pages): 2 columns · gap 16px. Two equal 616px illustrated panels.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-tags | 9999px (pill) |
|  | cards-and-media | 8px |
|  | timeline-shell | 12px |
| people directories | portraits | 50% |
| personal-assistant product pages | waitlist-action | 12px |
| personal-assistant request illustrations | request-bubbles | 22px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating-scene-card | `inset 0px 0px 0px 1px rgba(255,255,255,0.25)` | Subtle inner light on translucent interface fragments. |
|  | floating-result | `inset 0px 0px 0px 1px rgba(255,255,255,0.25), 0px 20px 25px -5px rgba(0,0,0,0.12), 0px 8px 10px -6px rgba(0,0,0,0.08)` | The oversized result capsule inside an illustrated scene, not ordinary content cards. |
| personal-assistant product pages | waitlist-glow | `0px 10px 15px -3px rgba(85,51,238,0.2), 0px 4px 6px -4px rgba(85,51,238,0.2)` | Signup action on white. |

### Surfaces

#### Canvas · level 0

**Use:** Main reading surface.

**CSS:** `background: #ffffff; color: #42595e`

#### Ruled chapter · level 0

**Use:** Separates major narrative blocks without changing the canvas.

**CSS:** `background: #ffffff; border-top: 1px solid #dbe3e3`

**Observed:** Content is inset in the marketing container rather than boxed as a giant card.

**Transfer:** Let white space and one hairline define each chapter.

#### Sunset stage · level 0

**Use:** Default opening illustration stage.

**CSS:** `background: linear-gradient(#ffadde 0%, #ffde9e 50%); border-radius: 8px; clip-path: inset(0px round 8px)`

**Observed:** Warm sky extends behind the text and merges into the large lower illustration.

**Transfer:** Keep the upper copy area visually calm; place detailed objects below the actions.

#### Capability wash · level 1

**Use:** Capability cards and process containers.

**CSS:** `background: #f0f5f5; border-radius: 8px; box-shadow: none`

#### Floating glass · level 2

**Use:** Interface fragments within illustrated scenes.

**CSS:** `background: rgba(255,255,255,0.77); border-radius: 8px; backdrop-filter: blur(32px); box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.25)`

**Observed:** Text remains dark teal; occasional companion cards reverse into dark translucent teal.

**Transfer:** Use sparingly on art, never as the default page-wide material.

#### Cloud callout · level 0

**Use:** Outcome-focused conversion scene.

**CSS:** `background: linear-gradient(#71cff0 0%, #dbe3e3 100%); border-radius: 8px; padding: 64px`

**Observed:** Soft sculpted clouds crowd the left and right edges while the center stays open for text.

**Transfer:** Layer the cloud construction described in imagery above this gradient.

#### Footer field · level 0

**Use:** Closing navigation and identity.

**CSS:** `background: #002429; padding: 40px 0px; color: #ffffff`

#### Company daylight · level 0

**Only for:** company and culture pages

**Use:** Mission statement and candid photo ribbon.

**CSS:** `background: linear-gradient(#ffffff, #e3f7fc); padding: 64px 0px`

#### Warm demo stage · level 0

**Only for:** personal-assistant product pages

**Use:** Before/after visual comparison and floating requests.

**CSS:** `background: #fafaf8; border-radius: 8px; overflow: hidden`

**Observed:** Large pale panels carry white mobile UI and colorful task objects without heavy outlines.

**Transfer:** Use the warmth to distinguish the individual-user product story from the default business narrative.

## Components

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: #ffffff; border-bottom: 1px solid #e5e7eb`

**Text style:** `navigation` — MDSystem 500 · 14px/20px

**Observed:** 69px desktop band: compact symbol-plus-word identity at left, five short links and a violet pill at right; inner row uses 20px side and 16px vertical padding. A separate 40px black announcement ribbon precedes it.

**States:** Declared: hover navigation text becomes rgba(0,0,0,0.5).

**Transfer:** Keep the navigation considerably smaller than the opening scene.

### Primary button

**Use:** Default marketing conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #5533ee; color: #ffffff; border-radius: 9999px; padding: 8px 16px; height: 36px; gap: 8px`

**Text style:** `button` — MDSystem 600 · 14px/20px

**Observed:** Short text-only pill. Pairs horizontally with a light secondary action.

**States:** Declared: hover background-color rgba(85,51,238,0.9); focus-visible outline transparent solid 2px, outline-offset 2px, box-shadow 0 0 #0000,0 0 #0000,0 0 #0000.

### Secondary button

**Use:** Low-pressure audio or product conversation action beside conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f5f5f5; color: #171717; border-radius: 9999px; padding: 8px 16px; height: 36px; gap: 8px`

**Text style:** `navigation` — MDSystem 500 · 14px/20px

**Observed:** Same compact height as the primary, lighter weight and no heavy outline. A separate case-study variant uses white with a thin mist border and an up-right arrow.

**States:** Declared: hover background-color hsl(0 0% 96.1%/.8); focus-visible outline transparent solid 2px, outline-offset 2px, box-shadow 0 0 #0000,0 0 #0000,0 0 #0000.

### Capability card

**Use:** Explain one assistant role or product ability.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 16px; background: #f0f5f5; border-radius: 8px`

**Text style:** `card-label` — PolymathDisplay 400 · 16px/1.375 · tracking 0.025em

**Observed:** Flower-like badge illustration first, then a compact display label and relaxed body paragraph separated by only 2px. The badge occupies a generous upper corner rather than a conventional tiny icon row.

**Transfer:** Create a distinct friendly object or flower silhouette for each capability.

### Proof card

**Use:** Customer testimony in moving rows.

**CSS:** `display: flex; flex-direction: column; width: 320px; padding: 20px; background: #ffffff; border: 1px solid #dbe3e3; border-radius: 8px; flex-shrink: 0`

**Text style:** `quote` — MDSystem 500 · 16px/1.375

**Observed:** Outcome pill at top, quotation below, attribution and small company mark at the bottom behind a thin top rule. Outcome pills are softly tinted pink, cyan, lavender or red with matching darker text and edges. Cards are 211px high in the desktop rows.

**States:** Declared: hover border-color rgba(85,51,238,0.4).

**Transfer:** Use real attributable customer language and narrow outcome labels; keep the rows visually varied.

### Integration pill

**Use:** Compact scrolling compatibility proof.

**CSS:** `background: #e3e0ff; color: #0a0a0a; border-radius: 9999px; padding: 6px 16px; margin: 0px 4px; white-space: nowrap; flex-shrink: 0`

**Text style:** `integration` — PolymathDisplay 400 · 16px/1.5 · tracking 0.03em

**Observed:** Text-only pills in a single horizontally overflowing strip, with white fades at both edges.

**Transfer:** Use actual compatible tools or supported surfaces, not a decorative cloud of buzzwords.

### FAQ row

**Use:** Address objections in a calm reading column.

**CSS:** `border-top: 1px solid #dbe3e3; padding: 20px 0px`

**Text style:** `body` — MDSystem 400 · 16px/1.625

**Observed:** Bold 16px/24px question spans the row; a small plus sits at the far right. Answer copy uses the body recipe. No individual card background; eight rows occupy the right side of a split trust section.

**Transfer:** Use a full-width text button within each row and keep the answer closely tied to the question.

### Footer

**Use:** Consistent end to all page types.

**CSS:** `background: #002429; color: #ffffff; padding: 40px 0px`

**Text style:** `small` — MDSystem 400 · 14px/20px

**Observed:** White identity and muted 45%-white descriptor at left, subdued trust marks beneath. Three link columns at right use 55%-white bold headings and white links. Bottom legal line is separated by a 10%-white rule. Desktop height is 313px; content has 16px side padding.

**States:** Declared: hover links gain underline.

**Transfer:** Retain the broad empty center and modest identity scale rather than adding giant closing typography.

### Stat card

**Only for:** company statistics

**Use:** Quantify a team's character with a compact standout treatment.

**CSS:** `display: flex; flex-direction: column; justify-content: center; gap: 24px; padding: 24px; min-height: 150px; background: #e3e0ff; color: #1f125e; border-radius: 8px`

**Text style:** `stat` — PolymathDisplay 700 · 48px/1

**Observed:** Large percentage above a short uppercase display caption; three equal cards within an 896px column, separated by 8px.

**Transfer:** Keep this treatment to a small set of genuinely meaningful facts.

### Recruitment row

**Only for:** company and recruitment pages

**Use:** List opportunities without card clutter.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 24px 16px; border-bottom: 1px solid #e5e7eb; margin: 0px -16px`

**Text style:** `list-title` — MDSystem 400 · 18px/28px

**Observed:** Title at left, location in the middle and violet Apply with a small chevron at right. Roles are grouped under modest display category headings. Desktop rows are 77px high.

**States:** Declared: hover background-color rgb(249 250 251/1).

### Waitlist button

**Only for:** personal-assistant product pages

**Use:** Primary signup in a sparse individual-user story.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #5533ee; color: #ffffff; border-radius: 12px; padding: 16px 32px; height: 56px; box-shadow: 0px 10px 15px -3px rgba(85,51,238,0.2), 0px 4px 6px -4px rgba(85,51,238,0.2)`

**Text style:** `waitlist-button` — MDSystem 600 · 16px/24px

**Observed:** Centered on white with more distance around it than the default compact action.

**States:** Declared: hover background-color rgba(85,51,238,0.9).

### Request bubble

**Only for:** personal-assistant request illustrations

**Use:** Humanize the range of tasks someone can delegate.

**CSS:** `display: flex; align-items: center; padding: 12px 16px; background: #ff4234; color: #ffffff; border-radius: 22px; max-width: 300px`

**Text style:** `request` — MDSystem 500 · 16px/1.4

**Observed:** Short task request with a pointed speech tail, slightly rotated and scattered around a centered headline. Red, pink, apricot, salmon and soft green variants share the same construction; tiny colored dots punctuate the stage.

**Transfer:** Write requests in the user's own first-person language and keep the center readable.

## Imagery and graphics

### Miniature service world

**Use:** Main illustrated opening object below the promise.

**Observed:** A stylized, softly lit neighborhood of pitched-roof houses, evergreen trees and pink foliage rises from the bottom edge. Cream, mint and peach architecture sits under a pink-gold sky. A floating white task notification bridges illustration and product behavior. Art occupies the lower half of the opening stage rather than sitting in a boxed screenshot.

**Transfer:** Choose an original miniature environment that represents the new customer's everyday world. The minimum version is a simple layered SVG landscape or relevant object cluster with warm light and one legible task notification.

**Build:** Create a wide SVG with three depth layers: low-contrast rounded cloud silhouettes behind, midground geometric buildings or product-relevant objects in cream and pastel teal, and darker teal foreground silhouettes. Use the Sunset stage gradient behind it. Add soft pink clusters at the outer lower edges and a white rounded notification with a violet icon tile near the central object. Keep the upper half clear.

### Daylight cloud scenes

**Use:** Signature product illustrations and outcome callout.

**Observed:** Cyan sky fades toward pale mist, framed by sculpted cream clouds with pink and lavender shadowing. Square scenes carry floating white and translucent teal interface fragments. The wide closing scene pushes clouds to the sides and leaves a clear center.

**Transfer:** Show one recognizable input and outcome on the same airy stage. Retain the dimensional cloud treatment even when simplifying the product UI.

**Build:** On a cyan-to-mist vertical gradient, layer overlapping SVG circles and irregular lobed paths at the lower left and right. Fill with cream-to-white gradients, add pink translucent shadow lobes and a low-opacity violet shadow at the bottom. Blur only the shadow layer by about 20px; preserve cloud contours. For a square scene, place two 8px-radius notification strips above a broad white capsule with a violet circle and thin looping arrow. For a wide callout, constrain clouds to the outer thirds.

### Botanical capability badges

**Use:** Small expressive anchors above card copy and selected section headings.

**Observed:** Pastel four-lobed flower backings hold small dimensional flowers or organic objects; pink, blue, yellow-green, coral and lavender alternate against pale gray cards.

**Transfer:** Use a family of original organic motifs keyed to capabilities. A clean vector rosette plus a simple dimensional object is sufficient.

**Build:** Union four overlapping circles into a rounded four-lobed SVG badge; fill with a muted pastel. Center a stem-and-petal or product-relevant organic symbol, using two or three tonal fills to suggest volume. Keep a consistent silhouette and vary the hue and inner object, not the visual weight.

### Progress illustration

**Use:** Make gradual adoption feel safe and visibly cumulative.

**Observed:** A 1222px-wide pale blue-gray chart carries a fine square grid, a smooth rising violet line and transparent violet area fill. Three stages sit above it inside a 12px bordered shell; the active stage is lavender. Tiny pill labels and a white vertical axis capsule provide context without conventional dashboard density.

**Transfer:** Use a qualitative or defensible measured progression suited to the new product; preserve the expansive curve and sparse annotation.

**Build:** Draw an SVG quadratic or cubic rising path over a pale grid. Close a duplicate path to the lower edge and fill with violet fading to zero alpha downward. Place one violet dot on the curve and a small violet caption pill nearby. Keep the grid low-contrast and labels restrained.

### Candid photo ribbon and people

**Only for:** company and culture pages

**Use:** Show the humans behind the system.

**Observed:** Unfiltered office, event and everyday team photography in mixed portrait and landscape proportions, all normalized to 320px height in an edge-overflowing ribbon with rounded corners. The directory switches to small circular portraits above names, roles, short past-experience lines and violet profile links.

**Transfer:** Use real imperfect workplace images with natural daylight; keep portraits informal and consistent in size rather than imposing a polished studio aesthetic.

### Personal assistant demonstrations

**Only for:** personal-assistant product pages

**Use:** Make individual-user relief immediately understandable.

**Observed:** A white mobile conversation mockup tilts slightly over a pink backing in the opening. A later before/after pair places overlapping calendar, email and task fragments on one warm off-white panel and one clean large conversation on the other. Red conversation accents are inside the UI, distinct from violet marketing actions.

**Transfer:** Use a readable mobile conversation relevant to the new user. Keep the before collage visibly busy and the after composition singular; simplify interface details rather than reproducing an entire app.

### Icons

**Observed:** Functional icons are usually 16px or 20px, violet or deep teal; outline variants use 2px round strokes. Benefit icons sit in 48px square lightly outlined containers with 8px corners. Tiny chevrons and plus signs remain visually subordinate to text.

**Transfer:** Use one rounded outline family for controls and benefits; reserve filled organic illustrations for expressive capability badges.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** A 40px black announcement strip and 69px white Navigation precede a near-full-width Sunset stage, inset 20px from the sides and 20px below the header. The 965px-tall stage starts with 48px top padding. Center the display promise across about two thirds of the stage, balanced into two lines with a 960px limit. A lead paragraph is constrained to about 553px below it with a 16px gap, followed by three compact checked outcomes. Primary button and Secondary button share a centered row with an 8px gap. Back-to-front layers are warm sky, distant clouds, miniature illustrated environment, and a floating task notification. Within the first 900px, the full promise, support, checklist, actions and upper portion of the world are visible; the lower illustration and scene controls continue below the fold. No logo wall or next section is visible yet.

**Transfer:** For a different product, make the promise about dependable work and stage an original everyday environment beneath it. If elaborate artwork is unavailable, use the miniature-world SVG construction with one credible notification. Company introductions instead use a narrower 60px mission statement over Company daylight and a candid ribbon; individual-user product pages use a 48px semibold promise on white, one larger signup action and a centered phone scene.

**Avoid:** Do not substitute a generic dashboard rectangle beside a left-aligned headline, or shrink the scene until the whole story fits above the fold.

**Text style:** `display` — PolymathDisplay 700 · 48px/1.1

### Heading pair and capability grid

**Observed:** Ruled chapter with 80px vertical container padding. Center a small botanical badge above a 36px heading, support 8px below, and an optional compact conversion action. Capability cards begin 32px below the heading group in a three-column, 16px-gap grid. A centered 24px/32px display statement can close the grid after a broad white pause.

**Transfer:** Group concrete responsibilities or abilities into a coherent family; use the closing statement to connect them into one system.

**Text style:** `heading` — PolymathDisplay 700 · 36px/40px

### Demonstrate the mechanism

**Observed:** Left column carries a 36px heading, short lead and three icon-led result facts; the wider right side is a pale process container with seven numbered rows. The active row expands into an illustrated scene and a small customer quotation, while other rows retain number, title and plus marker. Compact dark or violet labels punctuate the lighter fields.

**Transfer:** Explain a genuine end-to-end workflow using a modest row count suited to the content. Show the active step doing something rather than simply naming it.

### Square scene and benefit matrix

**Observed:** A 596px square Daylight cloud scene sits beside a text column. Above the 36px heading is a small botanical badge; below the lead is a two-by-two matrix of outlined icon tiles, tracked labels and body explanations.

**Transfer:** Use this for a compounding benefit, architectural advantage or learning loop that is difficult to convey through a screenshot.

### Visual surface grid

**Observed:** Centered heading and short lead introduce six square scenes in a three-column grid with 32px gaps. Each image is 392px square, followed by a small display label and body explanation. Integration pills follow in a narrower edge-faded strip.

**Transfer:** Show different places the product acts or meets users, using consistent lighting and image backing.

### Moving proof wall

**Observed:** A left-aligned heading and support line oppose an outlined case-study action. Two rows of Proof cards extend beyond the viewport with 16px gaps and soft edge masks. Outcome tags provide the first reading stop; ruled attribution bases provide the second.

**Transfer:** Use several short verified stories rather than one oversized quote; keep customer marks small and aligned with attribution.

### Adoption arc

**Observed:** Centered heading and support above a bordered 12px timeline shell. Three adjacent stage panels share the top, one lavender selected. Below is the expansive Progress illustration, with Previous and Next controls above the shell.

**Transfer:** Turn setup or adoption into a confidence-building progression. Do not imply numerical gains that cannot be supported.

### Trust and objections

**Observed:** Two equal columns separated by a 48px gap: a botanical illustration, heading, reassurance facts and violet text links on the left; a stack of FAQ rows on the right. All sits on the Ruled chapter surface.

**Transfer:** Pair concrete risk-reduction information with the questions a buyer actually asks.

### Daylight closing call

**Observed:** Cloud callout spans 1240px and is 261px high, centered in the marketing container. A 36px outcome headline, 18px support line and compact paired actions occupy the clear center. An 80px white pause leads into Footer. The individual-user variant is a 349px white ruled section with a centered 36px semibold heading and a Waitlist button; the company variant closes with a modest investor heading, three outlined name chips and one supporting line before Footer.

**Transfer:** Close with a near-future benefit stated as an accomplished outcome. Keep the cloud device in the default marketing story, and use the scoped simpler endings for their distinct page purposes.

**Text style:** `heading` — PolymathDisplay 700 · 36px/40px

### Company proof and directory

**Only for:** company and culture pages

**Observed:** A candid editorial photo grid follows the mission ribbon. Three lavender Stat cards introduce a narrower 896px column, followed by a three-column portrait directory. Recruitment row groups continue the same measure; a centered backer strip resolves the company content before Footer.

**Transfer:** Use only the people, facts and opportunities that advance a credible organizational story; the narrow column distinguishes this page type from the product's broad illustrated stages.

### Requests and comparison

**Only for:** personal-assistant product pages

**Observed:** A centered 36px section heading and short lead introduce two warm panels with small 18px display comparison labels. A later 1248px-wide, 500px-high Warm demo stage places a centered 48px semibold heading amid five colored Request bubbles, angled tails and sparse confetti dots.

**Transfer:** Contrast fragmentation with a single coherent conversation, then expand perceived usefulness through short user-authored requests.

## Page flow

**Storyline:** Promise → recognizable working world → capabilities and mechanism → proof of relief → confidence in adoption → objection handling → outcome-led action and compact footer.

### Default business-product landing page that sells dependable automation

1. **Promise** — Warm illustrated opening with a strong centered outcome, three proof checks and paired actions.
2. **Social proof** — Small trust label and horizontally moving customer marks.
3. **Capability chapters** — Botanical role cards, a numbered mechanism demonstration, a learning-loop scene and square surface illustrations.
4. **Customer proof** — Integration strip and two moving rows of compact outcome-tagged testimonials.
5. **Adoption confidence** — Three-stage timeline and rising violet progress curve.
6. **Objection handling** — Trust content beside ruled FAQ rows.
7. **Closing call** — Daylight cloud outcome banner above a deep teal footer.

**Transfer:** Adapt the relative emphasis to the product's complexity. Preserve the illustrated world, tangible task fragments, lively proof and daylight-to-teal resolution rather than every section or count.

### Company and recruitment story built on human credibility

1. **Mission** — Narrow large statement on an ice-blue gradient above a candid horizontal photo ribbon.
2. **Cultural proof** — Four editorial photos with linked, conversational captions.
3. **Quantified character** — Three bold percentage cards on lavender.
4. **Human proof** — Airy three-column circular-portrait directory with names, roles and short past-experience notes.
5. **Opportunity** — Categorized ruled recruitment rows.
6. **Institutional proof and ending** — Centered investor chips and a supporting sentence flow directly into the shared teal footer, without a large conversion banner.

**Transfer:** Favor real human specifics and a narrower column; do not import the product's long workflow demo into the organizational story.

### Individual-user product introduction focused on personal relief

1. **Promise** — White narrow opening, semibold heading, large violet signup action and a tilted phone on pink.
2. **Social proof** — Compact customer-mark ribbon.
3. **Problem and solution** — Two warm before/after panels contrast fragmented admin with one clean conversation.
4. **Breadth of utility** — Colored request bubbles orbit a centered capability invitation.
5. **Closing call** — Simple white ruled signup section and shared deep teal footer.

**Transfer:** Keep the story shorter and more conversational. Use the larger signup action only for this individual-user mode, not as the default global button.

## Writing

Confident, plain-spoken and warmly practical. Automation is described as a helpful coworker doing recognizable work, with relief and growth emphasized over technical spectacle.

**Do not copy:** Do not reuse Phoebe's name, logo, botanical artwork, customer marks, personal names, quotations, acquisition announcement, compliance status, integrations or numerical performance claims as assets or claims for another product. Source examples below illustrate voice only.

- **Addressing the reader:** Speak directly to you and your team. Refer to the product by name as an active teammate; use we sparingly outside company storytelling.
- **Rhythm:** Headlines are often full outcome-led sentences, about 7–15 words. Supporting copy mixes short pain statements with one longer explanation; actions remain 2–4 words. Questions sound like a real buyer talking.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the teammate and the continuing benefit in one clear sentence. | 10–15 words | “The AI teammate that keeps your home care agency running 24/7.” |
| Supporting line | Start with recognizable pressure; turn quickly toward relief. | 20–40 words | “Open shifts pile up. Schedulers burn out. Revenue walks out the door.” |
| Capability heading | Product name plus an active verb and an everyday metaphor. | 5–10 words | “[Brand] runs your back office on autopilot.”<br>“[Brand] gets smarter over time.” |
| User task | Short first-person request, not a feature taxonomy. | 3–8 words | “Find a shift for Thursday”<br>“Plan my route” |
| Objection | Ask the uncomfortable practical question directly. | 5–12 words | “Does [Brand] replace my schedulers?”<br>“What if my schedulers aren't tech-savvy?” |
| Closing line | Make the next stressful event feel already handled. | 8–14 words | “Your next callout will be covered before you see it.” |
| Primary action | Concrete short verb phrase, no elaborate sales language. | 2–4 words | “Get Started”<br>“Book a Demo”<br>“Join the waitlist” |

**Words and phrasing to use:** teammate; on autopilot; handles; fills; learns; nothing to replace; summary, not a task; hands-on or hands-off; busy work; before you see it

**Avoid:** revolutionary paradigm; synergistic platform; unprecedented intelligence; disrupt everything; enterprise-grade as a substitute for specifics

**Rules:**

- Describe work through its input, action and useful result.
- Make each capability explanation concrete enough to picture as a small scene.
- Pair strong promises with attributable proof or a clear operating mechanism.
- Use familiar metaphors lightly; keep technical architecture out of the main promise.
- Company captions may be casual and culturally specific, while product copy stays broadly understandable.

## Do's and Don'ts

### Do

- Use 48px/1.1 weight-700 display type for the default opening and 36px/40px weight-700 for section leads.
- Keep default actions at 36px high with 8px 16px padding and fully rounded ends.
- Keep most chapters white with 1px #dbe3e3 separators and 80px desktop vertical padding.
- Repeat 8px corners across the illustrated stage, capability cards and media.
- Place 16px/26px body copy beneath small tracked display labels in capability cards.
- Give cloud scenes a clear center and place detailed imagery below or around the text.
- Keep the footer deep teal with small white links and subdued group headings.
- Use 320px testimonial cards, 16px row gaps and edge fading to maintain the lively proof treatment.

### Don't

- Do not use the 56px rounded-rectangle signup button as the ordinary business CTA; it belongs to the individual-user variant.
- Do not fill ordinary content cards with saturated violet; use #f0f5f5 and reserve violet for emphasis.
- Do not add large blurred drop shadows to standard cards; their distinction comes from washes and hairlines.
- Do not replace the 16px tracked display labels with uppercase monospace labels.
- Do not turn the footer into a giant wordmark billboard; its desktop treatment is a compact 313px band.
- Do not make culture imagery glossy or uniformly studio-lit; its credibility comes from candid everyday framing.
- Do not use intricate dashboard chrome as the hero's main image; show a readable task inside a broader world.
- Do not tighten paragraph leading to headline proportions; 16px body uses 26px and 18px lead uses 29.3px.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 0.15s cubic-bezier(0.4,0,0.2,1).
- Two testimonial tracks declare 52s linear infinite scrolling; a marquee declares 45s linear infinite movement.
- The illustrated opening has selectable scene controls; process and timeline content expose step-selection controls.

**Transfer:**

- Use linear continuous movement for proof strips, not for headline entrances.
- Keep task-scene changes localized inside the illustrated stage so the reading hierarchy stays stable.

**Unknown:**

- Exact scene-transition timing and automatic playback behavior are not established.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- CSS width breakpoints are 640px, 767px, 768px, 1024px and 1440px.
- Capability-grid classes specify one column, then two at the small breakpoint and three at the large breakpoint.
- Main section padding changes from 40px to 80px at the large breakpoint; opening heading changes from 36px to 48px there.
- Desktop navigation links are hidden below the large breakpoint.
- Request stage declares 800px height on narrow screens and 500px from the medium breakpoint.

**Transfer:**

- On narrow screens keep the opening promise above the scene and preserve the warm sky-to-world layering; reduce the object's lateral spread rather than compressing text.
- Stack comparison panels and split sections while retaining each panel's original background and visual identity.
- Keep continuous strips horizontally clipped and edge-faded rather than squeezing every pill into a wrapping cloud.

**Unknown:**

- Mobile menu construction, exact mobile typography outside declared classes and phone-specific artwork framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
