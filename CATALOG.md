# Design reference catalog

Source: `design-md/<name>/DESIGN.md` (84 designs, cloned from VoltAgent/awesome-design-md, 2026-10-28).
Each DESIGN.md holds tokens (colors, type, spacing, radii) plus prose on atmosphere, components and do/don'ts. They are *analyses of* real brands, so use them for structure, palette logic and type pairing. Never copy a brand's name, logo, or proprietary typeface into client work.

Format: **name** — character · viable niches.

## How to pick

| Client need | Start with |
|---|---|
| Trust, clinical, professional services (dental, law, accounting, medical) | cal, hp, ibm, sap, oracle, airtable, oura, cohere |
| Premium / luxury / high-ticket | bugatti, lamborghini, ferrari, bmw, apple, tesla, spacex |
| Warm, human, approachable local business | claude, lovable, zapier, intercom, pinterest, starbucks, mastercard |
| Real estate, hospitality, travel | airbnb, oura, apple, bmw, starbucks |
| Dev-tool / SaaS / AI product | linear.app, vercel, supabase, cursor, raycast, resend, warp |
| Finance / fintech / insurance | stripe, wise, mercury, revolut, coinbase, nerdwallet |
| Editorial / news / blog / magazine | wired, theverge, aljazeera |
| Retro or novelty | dell-1996, nintendo-2001 |

## Quick caveats for our projects
- **Hebrew / RTL:** none of these were designed RTL. Most use proprietary Latin-only faces, so the type pairing must be re-solved with a Hebrew-capable family (Heebo, Assistant, Rubik, Frank Ruhl Libre for serif). Layout ideas carry over; mirrored nav, uppercase tracking and negative letter-spacing need re-checking.
- **Uppercase + wide tracking** (bugatti, lamborghini, spacex, ferrari, vodafone) does not exist in Hebrew; the premium feel must come from space, photography and weight instead.
- **Photo-dependent systems** (apple, tesla, bugatti, lamborghini, ferrari, runwayml, spacex, airbnb, dji, nike) fail without strong photography. Check the client has it before choosing one.

---

## 1. Developer tools, infrastructure, AI platforms
- **linear.app** — near-black, single lavender accent, hairline-bordered panels, dense and quietly luxurious · B2B SaaS, project/ops tools, agencies selling "craft".
- **vercel** — black/white duet, one multi-color mesh gradient as the only decoration, mono labels · dev platforms, technical consultancies, hosting.
- **supabase** — white/near-black, single emerald CTA, product UI composited over hero · open-source/data products, technical startups.
- **cursor** — warm cream canvas, one orange CTA, pastel timeline chips only inside product visuals · AI/dev tools wanting an anti-dark-mode, editorial feel.
- **raycast** — chrome mirrors the product: near-black, hairlines, command-palette cards · productivity/utility apps, keyboard-first tools.
- **warp** — warm charcoal, Inter plus an occasional serif italic, terminal mockups · developer/CLI products, AI coding agents.
- **resend** — pure black, off-white text, editorial serif headline as the signature · developer APIs wanting a more literary tone.
- **posthog** — cream canvas, hand-drawn hedgehog mascots, single yellow-orange pill · playful dev/analytics products with a personality brand.
- **sentry** — violet-midnight, lime accents, sticker mascots, chunky display · dev tools that want to feel irreverent.
- **replicate** — warm cream, hot orange accent, very large display type · ML/indie-hacker platforms, model galleries.
- **composio** — near-black, one electric blue, 2×2 terminal-panel hero with spotlight glow · agent/integration infrastructure.
- **voltagent** — unrelenting black, single electric green, code-editor hero, dark feature-card grid · agent frameworks, docs-as-marketing.
- **opencode.ai** — everything in monospace, cream canvas, ASCII `[+]` bullets, README feel · CLI/terminal-native products.
- **ollama** — near-nothing: white, one black pill, inline install snippet, mascot · single-command open-source tools.
- **expo** — white with sky wash, black CTA, device-mockup hero · mobile/dev platforms.
- **together.ai** — alternates black hero and white research/docs bands, three-color gradient as sole chrome · AI infrastructure, research-heavy products.
- **mintlify** — sky-gradient marketing heroes plus dense 3-column docs layout, green accent · documentation products, API companies.
- **sanity** — dark-first, 112px display, mono eyebrows, one coral CTA · headless CMS, content platforms.
- **hashicorp** — black ground, per-product accent colors as identity tokens · multi-product enterprise infra, portfolio companies.
- **clickhouse** — black with electric yellow, yellow stat numbers · databases, data/analytics, performance-oriented B2B.
- **mongodb** — dark deep-teal bands with green pills plus white docs surfaces, 3-tier pricing · database/cloud with learning content.
- **webflow** — near-black and white, five-color accent system mapped to product categories · site/no-code builders, multi-product suites.
- **framer** — pure black artboard, tight-tracked display, gradient spotlight tiles · design/builder tools, portfolio-style showcases.
- **figma** — monochrome frame broken by oversized pastel panels, "sticky note" joy · design/collab tools, creative software.
- **lovable** — parchment background, humanist type, opacity-based grays · AI app builders, friendly SaaS.
- **minimax** — white marketing with black pills plus vivid gradient model cards, 3-column docs · AI model providers.
- **mistral.ai** — sunset gradients over mountain photography, cream surfaces, orange CTA · AI company with strong brand storytelling.
- **x.ai** — black, white pill outlines, dusk gradients, tracked mono captions · austere frontier-tech / "engineered-cosmic".
- **cohere** — white editorial space, green-black bands, mineral surfaces · enterprise AI, serious B2B.
- **claude** — cream, serif display, coral CTA, navy product surfaces · warm, humanist AI/knowledge products; also a strong base for premium service sites.
- **elevenlabs** — off-white, light display weight, pastel gradient orbs, no hard accent · voice/audio/creative AI, calm editorial brands.
- **runwayml** — cinematic full-bleed media, single sans, black pills · creative/media tools where imagery is the product.

## 2. Productivity and collaboration SaaS
- **notion** — navy hero with sticky-note dots, purple pill, pastel feature cards, 4-tier pricing · all-in-one workspace, mid-market SaaS.
- **airtable** — white, dark ink, full-bleed signature color cards, long-scroll explainers · workflow/ops software.
- **cal** — white, black CTAs, product UI inside soft cards, navy footer · scheduling/booking products; also local-service booking sites.
- **slack** — aubergine, cream-lavender gradients, pastel-mesh heroes with UI mockups · team comms, community products.
- **miro** — canary yellow wordmark, pastel tints echoing sticky notes, comparison tables · whiteboard/collab tools, pricing-heavy pages.
- **intercom** — cream, charcoal, one orange for the AI brand, product-led · customer-service/support SaaS.
- **zapier** — warm cream, coffee ink, one orange CTA, confident-warm · automation/integration platforms.
- **superhuman** — indigo hero with portrait, quiet white body, teal closing band · premium productivity, high-end newsletter feel.
- **clay** — claymation 3D illustration, saturated single-color cards · GTM/sales-data tools, brands that want illustration-led identity.

## 3. Finance, fintech, crypto, payments
- **stripe** — navy ink, indigo, gradient mesh in top third, tabular figures · payments, financial infrastructure, premium B2B.
- **wise** — heavy near-black display (900), lime accent, sage neutrals · money transfer, consumer fintech with warmth.
- **mercury** — ink-violet night homepage plus pale product pages, light-weight type · business banking, startup finance.
- **revolut** — black, cobalt-violet, wide saturated product palette · neobank, multi-product fintech.
- **coinbase** — white, single blue, calm weight-400 display, dark editorial heroes · institutional crypto, finance with trust focus.
- **binance** — near-black, yellow CTAs, dark marketing / light transactional flip · trading platforms, dense data UIs.
- **kraken** — white with purple, 12px radii, whisper shadows · crypto/fintech wanting trustworthy light mode.
- **mastercard** — putty-cream, circular masks, orbit arcs, orange · payments/networks, editorial corporate storytelling.
- **nerdwallet** — green ladder, near-square corners, hairlines, comparison tables · comparison, lead-gen, insurance/loans/affiliate sites.
- **1win** — near-black, heavy Inter, green+blue CTAs, dense game tiles · iGaming/betting (only if the client is actually in that space).
- **mydealz** — green, stacked white-card feed, hot/cold voting · deals/coupon communities, dense listing feeds.

## 4. Enterprise and corporate
- **ibm** — Carbon: white, flat-square corners, light-weight display, single blue · large enterprise, engineering, government-adjacent.
- **sap** — white, two greys + one blue, app-frame chrome, 8px/12px corners · enterprise software, ERP-style portals.
- **oracle** — warm grey ladder, charcoal actions, red only on wordmark, gold rule · conservative corporate, data/legal-heavy firms.
- **hp** — white paper, electric blue, chevron decorations · hardware/consumer-enterprise product catalogs.
- **nvidia** — black and white chapters, violently saturated green, 2px angular radii · hardware, engineering, performance brands.
- **vodafone** — editorial hero bands, massive uppercase display, scarlet CTA, weight 800 · telecom, utilities, high-street retail.
- **meta** — white, product-merchandising cards, cobalt buy button, pill CTAs · hardware commerce, configurators.
- **oura** — cream-and-earth palette, editorial serif plus grotesque, one action blue, photography-led · wellness, health, clinics, premium consumer health. **Strong fit for medical/dental.**

## 5. Consumer products, commerce, marketplaces, media
- **airbnb** — white, one Rausch pink, pill search, photography, modest weights · marketplaces, hospitality, rentals, real estate listings.
- **apple** — museum-gallery product tiles alternating light/dark, one blue · premium hardware or single-product launches; needs great photography.
- **dji** — studio renders in square tiles, single engineering blue, sticky purchase bar · gadget/hardware stores, product configurators.
- **shopify** — two tracks: cinematic black hero, cream-mint transactional · e-commerce platforms, merchant-facing services.
- **nike** — towering uppercase campaign type, near-monochrome retail chrome, 8px-grid product cards · sportswear/retail, bold brand campaigns.
- **pinterest** — masonry grid, cream chrome, red CTA, pill buttons · inspiration/discovery, galleries, portfolios.
- **spotify** — immersive near-black, content-first, pill-and-circle geometry · media players, dashboards where content provides the color.
- **playstation** — alternating black/white/blue chapters like a trailer · entertainment, gaming, launches.
- **starbucks** — four-tier green, cream, 50px pills, floating order button · cafés, restaurants, loyalty/ordering experiences.
- **uber** — black-and-white duet, single pill shape, 4:3 editorial illustrations · on-demand services, logistics, booking apps.
- **jobright** — spring-mint with black, condensed bold headings, job ticker · recruitment, job boards, high-energy startups.

## 6. Automotive and luxury
- **bugatti** — pure black, wide-tracked white uppercase, photography only, no accent · ultra-luxury; very few clients qualify.
- **lamborghini** — true black, gold relief, 120px uppercase, cinematic video · supercar/luxury experiences, black-tie events.
- **ferrari** — near-black, one racing red, cinematic editorial, 8px token ladder · luxury, heritage, motorsport.
- **bmw** — cream-white, corporate blue, navy hero bands, card grid for models · premium automotive, configurator flows; a measured luxury register.
- **bmw-m** — near-black, uppercase, tricolor stripe, motorsport photography · performance/sport sub-brands.
- **tesla** — radical subtraction, 100vh photo heroes, one blue · tech-forward product with a single hero product.
- **renault** — black/white, Sunlight Yellow, diamond mark · mainstream automotive, mobility.
- **spacex** — black, full-bleed rocket/video heroes, uppercase D-DIN, ghost pills · aerospace, mission-driven, defense-adjacent.

## 7. Editorial and publishing
- **wired** — black wordmark on white, tall narrow display serif, humanist serif body · magazine, long-form blogs, thought-leadership.
- **theverge** — near-black, acid mint + ultraviolet, StoryStream feed with dashed rail · tech/culture news, loud young media.
- **aljazeera** — flat white paper, dense Roboto stacks, orange eyebrow bars, LIVE red · hard-news portals, information-dense sites.

## 8. Retro and novelty
- **dell-1996** — black page frame, flat color-block ribbon cards, Helvetica Black, GIF stickers · parody/retro campaigns, nostalgia microsites.
- **nintendo-2001** — brushed periwinkle, beveled metal panels, amber glow, circuit fields · Y2K nostalgia, gaming/event microsites.

---

## Shortlist for upcoming work
- **Dental / medical / clinic (lead-finder niches):** oura (warm, trustworthy, serif+sans), cal (clean, booking-first), cohere (editorial calm), airbnb (photo-led warmth).
- **Law / accounting / advisory:** ibm, sap, oracle (gravitas), mercury or stripe (modern premium).
- **High-ticket local services (renovation, architecture, real estate):** apple, bmw, airbnb, pinterest (portfolio/gallery).
- **Booking/appointment funnels:** cal, airbnb, uber.
- **Anything needing fast credibility with a small build:** ollama / opencode.ai (minimal) or lovable / claude (warm).
