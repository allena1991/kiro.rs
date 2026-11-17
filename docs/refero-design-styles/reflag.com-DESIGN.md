# Reflag — the developer workbench

## Overview

A near-black, documentation-like marketing style with the confidence of a well-made developer tool. Bright grotesk headings, cool grey sans-serif explanations and monospace annotations sit beside dark interface demonstrations. The composition is orderly and fairly dense, with restrained color inside the product rather than theatrical backgrounds; it suits technical products that can demonstrate their value directly.

### Essentials

- A marketing page that behaves like a field manual: a persistent 176px left navigation rail, a 944px reading column and a 224px right annotation gutter at desktop.
- One blunt promise above a working demonstration: 80px/1.1 semibold grotesk, -0.02em tracking, then a 398px explanation-and-benefits column beside a 496×279px video.
- White pills are small islands of conversion: 35px high, 48px radius, 17px medium labels and 14.4px horizontal padding, not oversized sales buttons.
- The page stays almost entirely charcoal: #09090b canvas, #0e0e11 panels, #22232a hairlines and white headings; chromatic detail belongs mainly to interfaces and a 6px green status dot.
- Proof is staged as an actual workbench: pair 448×277px detail illustrations with full-column demonstrations around 944×589px, framed by 1px borders and 8px corners. If no finished product exists, draw a credible dark workflow panel rather than decorative abstract art.
- Technical marginalia and human proof share a monospace voice: 14px/1.4 notes in the right gutter and 22px/1.4 testimonial statements, with small portraits and restrained attribution. Include both the annotated demonstration device and a human proof statement.
- End with utility rather than spectacle: a terminal-style quick-start/copy affordance at left and small monospace trust links at right, following proof or practical objection handling.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#48bb78` | `--color-status` | accent | Tiny operational-status indicator, never a large promotional fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright white | `#ffffff` | `--color-white` | text, action | Headlines, feature labels and primary button fill. |
| Near-black canvas | `#09090b` | `--color-canvas` | background, text | Continuous page background and inverse button text. |
| Recessed panel | `#0e0e11` | `--color-panel` | surface | Code panels and bordered cards. |
| Media backing | `#101114` | `--color-media` | surface | Backing for product videos; the visible interface may be darker. |
| Integration charcoal | `#121316` | `--color-tile` | surface | Integration logo tiles. |
| Charcoal rule | `#22232a` | `--color-edge` | border | Panel outlines, section rules and annotation connectors. |
| Utility slate | `#65687b` | `--color-utility` | text | Footer utilities and low-priority icons. |
| Secondary slate | `#787c91` | `--color-subtle` | text | Inactive section anchors and secondary information. |
| Explanation grey | `#8f92a3` | `--color-muted` | text, link | Supporting paragraphs, annotations and secondary links. |
| Navigation silver | `#d8d9df` | `--color-nav` | text | Default navigation text and tiny external-link arrows. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| code examples | Code-number slate | `#3c3d49` | `--color-line-number` | text | Line numbers within technical examples. |

## Typography

- **Overused Grotesk** — Marketing headings. Compact, rounded grotesk with a friendly but forceful semibold silhouette. Font stack: "Overused Grotesk", Arial, sans-serif.
- **Geist** — Body copy, navigation, actions and feature captions. Clean contemporary sans-serif with a technical, compact texture. Font stack: "Geist", Arial, sans-serif.
- **Geist Mono** — Technical annotations, quotations, code and utility text. Matter-of-fact monospace that gives human quotes a developer-native tone. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Overused Grotesk | 600 | 80px | 1.1 | -0.02em | Main landing-page promise; one line when the copy allows. |
| heading | Overused Grotesk | 600 | 44px | 1.2 | -0.01em | Section leads above thin horizontal rules. |
| quotation | Geist Mono | 400 | 22px | 1.4 | -0.02em | Standalone customer proof. |
| body | Geist | 400 | 20px | 1.5 | -0.01em | Support paragraphs and secondary inline links. |
| feature-caption | Geist | 500 | 20px | 1.5 | -0.01em | Short explanations immediately above product illustrations, with inline linked nouns. |
| navigation | Geist | 500 | 17px | 1.5 | -0.01em | Persistent navigation links. |
| button | Geist | 500 | 17px | 1.2 | -0.012em | White pill actions. |
| quote-small | Geist Mono | 400 | 17px | 1.4 | -0.02em | Dense two-column testimonial collection. |
| answer | Geist | 400 | 17px | 1.5 | -0.012em | FAQ answers and testimonial attributions. |
| annotation | Geist Mono | 400 | 14px | 1.4 | -0.014em | Right-gutter technical notes. |
| utility | Geist Mono | 500 | 14px | 1.5 | -0.014em | Footer trust links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail and pricing pages | page-title | Overused Grotesk | 600 | 56px | 1.15 | -0.01em | Compact topic title followed by an explanatory paragraph. |
| pricing pages | plan-title | Geist | 600 | 28px | 1.2 | -0.01em | Plan names. |
| pricing pages | question | Geist | 600 | 20px | 1.5 | -0.01em | FAQ questions. |
| comparison tables and section navigation | detail | Geist | 500 | 15px | 1.5 | -0.013em | Comparison rows and nested section anchors. |
| technical onboarding sections | code | Geist Mono | 400 | 14px | 1.5 | -0.014em | Readable quick-start examples. |

**Notes:**

- Headlines use the grotesk, not the body sans. The largest headline tightens to -0.02em while section and topic headings use -0.01em.
- Monospace is not restricted to code: it distinguishes annotation and testimonial voices. Keep ordinary descriptions in the sans-serif.
- Headings are sentence case, with no uppercase eyebrow system.

## Layout

**Density:** Comfortable at section scale but compact within navigation, examples and comparison rows.

### Spacing

**Spacing system:**

- **grid** 8px — Primary spacing rhythm; the core declared steps are 8px, 16px, 32px, 48px and 64px.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and integration grid spacing within details. |
| 16px | Caption-to-media gaps, tile gutters and support beneath heading rules. |
| 24px | Hero benefit-group spacing and navigation group separation. |
| 32px | Hero headline-to-content gap, plan padding and quotation inset. |
| 48px | Feature-grid gutters and chapter internal spacing. |
| 64px | Separation between major sections and top page padding. |

### Containers and grids

- **page-shell**: max width 1248px · side padding 64px. Main shell sits to the right of the navigation. Desktop has 64px left inset and a distinct 224px reserved right gutter, leaving a 944px reading column at a 1440px viewport.
- **navigation-rail**: max width 176px. Sticky full-height left rail, with 32px outer left margin and logo followed by grouped links; social links sit near its foot.
- **feature-grid**: 2 columns · gap 48px. Two equal 448px media cards within the reading column.
- **integration-grid**: 5 columns · gap 16px. Five equal logo tiles per row, including a subdued browse-all tile.
- **quote-measure**: max width 660px · side padding 32px. Standalone quotation inset from the main content edge.
- **plan-grid** (only for pricing pages): 3 columns · gap 16px. Three equal 304px cards.
- **faq-grid** (only for pricing pages): 2 columns · gap 80px. Two 432px columns of visible questions and answers.

## Corner radius

| Element | Radius |
| --- | --- |
| panels | 8px |
| primary-button | 48px |
| portraits | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous background across chapters and footer.

**CSS:** `background: #09090b`

**Observed:** No alternation between bright marketing bands.

**Transfer:** Use hierarchy, spacing and rules to separate sections.

#### Media frame · level 1

**Use:** Full product demonstrations.

**CSS:** `background: #101114; border: 1px solid #22232a; border-radius: 8px; overflow: hidden`

**Observed:** Wide landscape scenes retain the dark application's own interface; no browser chrome is added outside it.

**Transfer:** Place a real workflow or a focused reconstruction inside the frame.

#### Recessed card · level 1

**Use:** Quick-start panels and plan cards.

**CSS:** `background: #0e0e11; border: 1px solid #22232a; border-radius: 8px; box-shadow: none`

**Observed:** Only a slight luminance lift from the canvas.

**Transfer:** Keep the boundary subtle rather than simulating elevation.

#### Logo tile · level 1

**Use:** Integration ecosystem.

**CSS:** `background: #121316; border-radius: 8px`

**Observed:** Centered mostly white logos in a regular low-contrast matrix.

**Transfer:** Keep each logo optically balanced rather than equally stretched.

## Components

### Primary button

**Use:** One clear conversion action.

**CSS:** `display: flex; align-items: center; background: #ffffff; color: #09090b; border: 2px solid rgba(255, 255, 255, 0.02); border-radius: 48px; padding: 0px 14.4px; height: 35px; column-gap: 8px`

**Text style:** `button` — Geist 500 · 17px/1.2 · tracking -0.012em

**Observed:** A compact text-only pill; pricing repeats the same treatment across all plans rather than coloring a recommended tier.

**States:** Declared: hover background-color #e9e9ed and outline 0px; active outline 0px. Focus-visible treatment is unknown.

### Rail link

**Use:** Primary navigation.

**CSS:** `display: flex; align-items: center; padding: 1.6px 0px; gap: 8px; color: #d8d9df; transition: color 50ms`

**Text style:** `navigation` — Geist 500 · 17px/1.5 · tracking -0.01em

**Observed:** Stacked links in groups with the brand above; current destinations turn white and detail pages insert nested section anchors.

**States:** Declared: hover color white and outline 0px; active outline 0px. Focus-visible treatment is unknown.

### Section rule heading

**Use:** Start a new capability chapter.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 16px 0px 8px; border-bottom: 1px solid #22232a`

**Text style:** `heading` — Overused Grotesk 600 · 44px/1.2 · tracking -0.01em

**Observed:** Left-aligned title sits directly above a full reading-column hairline; support appears below, not inside a colored badge.

### Feature caption link

**Use:** Link the actionable noun within a short media caption.

**CSS:** `color: #ffffff; padding-right: 12px; text-decoration: underline`

**Text style:** `feature-caption` — Geist 500 · 20px/1.5 · tracking -0.01em

**Observed:** The linked phrase stays inline in a sentence. A tiny diagonal arrow follows external or deeper technical links; ordinary internal links can omit the arrow.

**Transfer:** Link the mechanism or tool name, not the entire sentence.

### Integration tile

**Use:** Show compatible tools or ecosystems.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #121316; border-radius: 8px; padding: 32px`

**Observed:** A mostly white centered wordmark or symbol. The last tile of each row offers a low-contrast underlined browse link.

**Transfer:** Use authentic integrations relevant to the new product.

### Product media card

**Use:** Explain a single capability through a close-up.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; border-radius: 8px; overflow: hidden`

**Text style:** `feature-caption` — Geist 500 · 20px/1.5 · tracking -0.01em

**Observed:** Caption above a dark detail illustration, not text inside a padded card. Cards pair in a two-column grid; their illustration carries the border.

### Gutter annotation

**Use:** Add technical context without burdening the main explanation.

**CSS:** `display: flex; flex-direction: column; gap: 8px; color: #8f92a3; width: 168px`

**Text style:** `annotation` — Geist Mono 400 · 14px/1.4 · tracking -0.014em

**Observed:** Sits outside the main media's right edge in a 224px gutter. A short horizontal rule connects the media to the note; small relevant tool icons can sit above it.

### Standalone testimonial

**Use:** Human proof between demonstration chapters or before the ending.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 32px; padding: 4.8px 32px`

**Text style:** `quotation` — Geist Mono 400 · 22px/1.4 · tracking -0.02em

**Observed:** A faint vertical rule anchors the left, a short quote occupies no more than 660px, and a tiny circular portrait precedes the sans-serif name and muted job/company. An organization logo can lead the quote.

### Utility footer link

**Use:** Compact trust and operational ending.

**CSS:** `color: #65687b; transition: color 50ms`

**Text style:** `utility` — Geist Mono 500 · 14px/1.5 · tracking -0.014em

**Observed:** Right-aligned inline group with 24px gaps. The status link has a 6px green dot. On the left, a terminal prompt, quick-start command and copy icon form the final conversion affordance.

**States:** Declared: hover color #8f92a3 and outline 0px; active outline 0px. Focus-visible treatment is unknown.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial entry points.

**CSS:** `background: #0e0e11; border: 1px solid #22232a; border-radius: 8px; padding: 32px`

**Text style:** `plan-title` — Geist 600 · 28px/1.2 · tracking -0.01em

**Observed:** Plan title, restrained price, compact warm checkmark list, then a Primary button aligned with neighboring plans at the bottom. Three equal-height cards; no colorful featured-plan banner.

## Imagery and graphics

### Dark workflow demonstrations

**Use:** Main product proof in opening and capability chapters.

**Observed:** Actual dark application screens, editor code, task lists and dialogs occupy most of each image. Full-width demonstrations are near a 1.6:1 ratio; the opening video is 16:9 with a small white play affordance. Screens remain front-facing and legible, with muted grey interface framing and selective teal, amber or violet details.

**Transfer:** Show the equivalent working state of the new product, including meaningful sample data and a focused task. A minimum viable substitute is a carefully drawn dark interface with one convincing interaction; preserve the framing and annotation gutter.

### Capability detail illustrations

**Use:** Paired explanatory cards.

**Observed:** 448×277px charcoal rectangles isolate a control, small timeline, message exchange, chart or network diagram. Interiors use fine edges, small text and sparse cyan or amber detail; some diagrams fade toward their edges rather than floating above bright backplates.

**Transfer:** Isolate one mechanism from the product for each card. Keep a straight-on view, dark backing and clear visual hierarchy rather than a collage.

**Build:** Use an 8px rounded charcoal rectangle with a 1px #22232a edge. Arrange two or three nested dark control rows with fine outlines and one highlighted control or short data series. For a network view, draw thin SVG longitude/latitude curves and a few orthogonal cyan connections; for a chart, use narrow muted cyan bars. Fade peripheral labels with opacity instead of adding glow.

### Logo and portrait proof

**Use:** Opening customer strip, ecosystem matrix and quotations.

**Observed:** Customer logos form a subdued horizontal strip under the opening; integration logos are brighter white inside charcoal tiles. Testimonial portraits are small circular color images, not large editorial photography.

**Transfer:** Use relevant real organizations and consented portraits with equal optical weight. Keep imagery subordinate to product proof.

### Icons

**Observed:** Small, mostly solid monochrome symbols; 20px interface/social icons, 8px diagonal link arrows and 14px copy icons. Benefit rows each begin with a compact symbol. Pricing uses warm-toned checks and muted crosses.

**Transfer:** Use a consistent compact icon family with simple filled or fine geometric forms. Reserve colorful tool icons for contextual technical notes, not navigation decoration.

## Section recipes

How recurring sections are built.

### First screen: Workbench opening

**Observed:** A sticky left rail establishes the navigation frame. The main content begins with 64px top padding and a white 80px/1.1 grotesk promise spanning the reading column. Beneath it, a 48px-gap grid splits into a 398px text column and a roughly 498px media frame: muted 20px support, five compact icon-led benefit lines, then Primary button on the left; a dark 16:9 video on the right. A subdued customer-logo strip closes the opening. Layers are simply Canvas, bordered media, readable content and the white action/play affordances. Within the first 900px, the entire promise, support, benefits, action, video and logo strip are visible, followed by the next Section rule heading and the beginning of its paired cards; deeper demonstrations continue below.

**Transfer:** Write a short outcome promise and show a credible working view beside a handful of concrete benefits. Without finished media, construct a dark representative workflow panel. Topic and pricing pages instead use the scoped 56px page-title and a paragraph, moving directly into their explanation or plan grid.

**Avoid:** Do not center the opening into a generic full-width billboard, replace the rail with a desktop top navbar, or put a glowing abstract object where the workflow belongs.

**Text style:** `display` — Overused Grotesk 600 · 80px/1.1 · tracking -0.02em

### Ruled capability chapter

**Observed:** Section rule heading, muted support line, then 48px to a two-column Product media card grid or full-width Media frame. Chapters are separated by 64px. Full demonstrations carry Gutter annotation outside the reading column.

**Transfer:** Group related mechanisms under one benefit-led title. Mix full workflow proof with close-up details rather than making every chapter the same grid.

### Ecosystem matrix

**Observed:** Section rule heading followed by three rows of five Logo tiles with 16px gaps; the last position in each row is a browse-all link.

**Transfer:** Organize authentic compatibility into useful categories. Preserve the monochrome tiled treatment rather than adding unrelated logo decoration.

### Practical quick start

**Observed:** A ruled 44px heading introduces an inline sign-up link, a short command panel and a larger Recessed card code example with 12px padding, 14px/1.5 mono text and line numbers. A Gutter annotation explains compatibility.

**Transfer:** Show the smallest meaningful path to value. For non-code products, replace source code with a concise operational checklist or reproducible setup sequence in the same restrained panel.

### Human proof and utility ending

**Observed:** Standalone testimonial gives breathing room around its monospace statement. A denser alternative is a two-column quote collection with 17px/1.4 quotations, 16px insets and small portrait attributions. The Utility footer link group and terminal-style shortcut finish the page with no oversized closing sales banner.

**Transfer:** Close on real user confidence or resolved objections, followed by the compact utility line. Keep practical entry into the product available at the very bottom.

### Plan comparison and open questions

**Only for:** pricing pages

**Observed:** Compact page-title and supporting line with a small monthly/annual switch. Three Plan cards lead into a long comparison matrix with matching three-column alignment, sticky plan labels, 40px feature rows, subtle horizontal rules and category headings. A short comparison-link paragraph precedes FAQs in two columns with 80px gap; answers remain visible. Utility footer follows.

**Transfer:** Use the same sober visual language for commercial decisions. Let feature availability and clear answers carry the persuasion instead of visual tier inflation.

**Text style:** `page-title` — Overused Grotesk 600 · 56px/1.15 · tracking -0.01em

### Numbered workflow guide

**Only for:** procedural product-detail pages

**Observed:** Compact page-title and support lead into numbered 44px chapter headings. Two-column detail illustrations establish entry methods, full-width annotated demonstrations explain complex steps, and standalone quotations punctuate the workflow. A final capability grid and testimonial precede the utility ending. Nested navigation marks the current chapter with white text and a slim white marker against a charcoal vertical rule.

**Transfer:** Use numbered chapters only for a real sequence. Adapt the mechanism and number of stages to the new product, retaining the media-plus-marginalia construction.

**Text style:** `heading` — Overused Grotesk 600 · 44px/1.2 · tracking -0.01em

## Page flow

**Storyline:** Outcome promise → concrete workflow proof → capability detail → human confidence → practical adoption or objection handling → utility ending.

### Broad product landing page

1. **Promise** — Oversized single-line outcome above split benefits and video, followed by subdued customer logos.
2. **Capability chapters** — Ruled benefit headings alternate paired detail media and annotated full-width workflows.
3. **Ecosystem proof** — A regular logo matrix makes compatibility tangible.
4. **Adoption** — Customer statement, practical quick-start command and readable code example.
5. **Social proof** — Two-column collection of short monospace testimonials.
6. **Utility ending** — Terminal-style shortcut and compact operational/legal links.

**Transfer:** Use the split workbench opening as the default; select capability chapters that demonstrate the new product rather than prescribing a fixed section count.

### Commercial decision page

1. **Pricing** — Compact title, billing switch and three equal plan cards.
2. **Comparison** — Long ruled matrix aligned to persistent plan labels.
3. **Objection handling** — Alternatives paragraph followed by two columns of visible FAQ answers.
4. **Utility ending** — Shared compact terminal and trust links.

**Transfer:** Keep the product palette and side rail while allowing much denser table text.

### Focused capability landing page

1. **Promise** — 56px title and a candid paragraph framing a specific workflow problem.
2. **Product demonstration** — Paired capability details expand into two full-width annotated interface demonstrations.
3. **Social proof** — A standalone monospace customer statement.
4. **Capability chapter** — A benefit-led heading and full-width workflow show who gains autonomy.
5. **Closing confidence** — Another standalone customer statement immediately precedes the shared utility footer.

**Transfer:** Explain one difficult workflow deeply; the closing quote can conclude the argument without adding a new CTA billboard.

### Procedural product explainer

1. **Promise** — Compact topic heading and one-sentence explanation.
2. **Workflow chapters** — Numbered ruled headings, paired entry-method illustrations and full-width annotated demonstrations.
3. **Social proof** — Customer quotations separate the larger chapters.
4. **Capability breadth** — A two-column collection of supporting mechanisms and a link to the complete comparison.
5. **Closing confidence** — Logo-led testimonial then the compact utility footer.

**Transfer:** Tell a real sequence with section navigation, then broaden to secondary capabilities without overwhelming the opening.

## Writing

Direct, technically fluent and lightly conversational. Claims focus on fewer interruptions, better workflow and concrete mechanisms, with occasional dry phrasing rather than grandiose aspiration.

**Do not copy:** Do not reuse Reflag branding, logos, customer identities, quotes, product commands, proprietary artwork or factual performance, compatibility and pricing claims. Source examples illustrate tone only; write verified equivalents for the new product.

- **Addressing the reader:** Address the reader as you, often through an imperative. The product can speak as we or our, but usually the action or outcome leads.
- **Rhythm:** Short sentence-case headings, concise support lines and fragment-like media captions. Detail-page introductions can be a compact argumentative paragraph. Technical specifics are welcome; hype and exclamation are rare.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category and attach a plain-language automation outcome. | 4–7 words | “Feature flags on autopilot” |
| Supporting line | State the mechanism and the practical benefit in one sentence. | 8–16 words | “TypeScript feature management that gets you back to building, faster.”<br>“Hand off busy work so you can stay in flow.” |
| Capability heading | Describe an experience or the friction removed, not a specification list. | 4–9 words | “Flags you’ll enjoy using”<br>“Skip interruptions for another “quick request” |
| Media caption | Action plus named mechanism, with the link placed on the mechanism. | 4–14 words | “Grant early-access or run betas.”<br>“Our GitHub integration automatically removes old flags. Just approve the PR.” |
| Primary action | Short, familiar verb phrase. | 2–3 words | “Get started”<br>“Free trial” |

**Words and phrasing to use:** built for; get started; works with; automatically; just; workflow; self-serve; stay in flow

**Avoid:** revolutionary; unleash limitless potential; game-changing; enterprise-grade excellence; the ultimate solution

**Rules:**

- Pair the benefit with something the reader can see in the adjacent media.
- Use real technical nouns instead of replacing every mechanism with vague ease-of-use claims.
- Allow a slightly wry everyday phrase in a headline, but keep instructions literal.
- Write annotations as useful technical context, not as a second sales paragraph.

## Do's and Don'ts

### Do

- Keep the primary reading column at 944px with a separate 224px annotation gutter on wide desktop layouts.
- Use 80px/1.1 display type for the default landing promise and 44px/1.2 for capability chapters.
- Keep paragraphs at 20px/1.5 in cool grey while media captions are 20px medium white.
- Use 8px panel corners and 1px #22232a borders without raised-card shadows.
- Pair close-ups at 448×277px with 48px grid gutters.
- Retain the 35px white pill and short verb-led label for the primary action.
- Use monospace quotes as well as technical notes to tie human proof to the workbench aesthetic.
- Finish with compact operational links and a practical entry shortcut rather than an additional decorative scene.

### Don't

- Do not spread bright accent colors across marketing bands; the charcoal canvas must remain dominant.
- Do not turn all 8px cards into large 24px rounded bento containers.
- Do not replace the 17px navigation with uppercase, widely tracked labels.
- Do not inflate the 35px action into a tall, gradient-filled hero button.
- Do not add heavy drop shadows or glass blur to bordered product frames.
- Do not style testimonials as large serif editorial quotes; preserve the 22px or 17px mono voice.
- Do not highlight a paid plan with a saturated fill when all plans use the same recessed charcoal treatment.
- Do not shrink the actual product into a tiny decorative thumbnail; full-width workflows are the primary proof.

## Motion and responsive

### Motion

**Observed:**

- Navigation and footer link color transitions are declared at 50ms. Primary buttons declare a 0.1s transition and a silver hover background.
- Other declarations include height/transform 50ms, a switch thumb left transition of 0.2s and switch background-color 0.2s.

**Transfer:**

- Keep navigation feedback brisk and visually small. Product video carries the demonstrative motion; the surrounding layout stays sober.

**Unknown:**

- Autoplay behavior, video timing, scroll animation choreography and focus-visible presentation are not established.

### Responsive

**Observed:**

- Stylesheet width breakpoints are 479px, 767px, 768px, 991px and 1280px. Declared side-padding tokens include 54px for tablet and 34px for mobile landscape.

**Transfer:**

- On narrow layouts, move gutter annotations directly below their associated media and stack the split hero and paired cards.
- Preserve the practical terminal-style ending when footer groups wrap. Treat a collapsed rail and smaller heading scale as adaptation decisions, keeping the workbench hierarchy intact.

**Unknown:**

- Exact mobile navigation, heading sizes, table overflow and breakpoint-specific stacking behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
