# Topical Authority — weddingevent.co.id

## Role and boundary

`WeddingEvent.co.id` currently presents itself as a luxury wedding planner with a vendor list and broad service access across venue, decoration, tents, flowers, catering, cake, bridal, make-up, attire, transport, photography, entertainment, sound, invitations, souvenirs, and honeymoon. Repository and live-site evidence do not establish the operating legal entity, team credentials, direct inventory, named vendor agreements, geographic coverage, completed events, testimonials, prices, insurance, licenses, or responsibility for each advertised service.

Until those facts are documented, the safe role is **independent wedding-planning information, consultation, vendor-referral, and event-coordination/facilitation property**. Each commercial route must identify the legal counterparty and whether WeddingEvent.co.id acts as planner, organizer, coordinator, directory, referral intermediary, agent, reseller, or direct supplier. It must not claim to supply a vendor category, guarantee availability or outcomes, or describe vendors as “best,” “experienced,” “cheapest,” or vetted without dated evidence and a disclosed method.

## Evidence audited

- Canonical repository: `https://github.com/cfpages-lusmodigital/WeddingEvent.co.id.git`, branch `main`, commit `a77e87f362f46e30f14bd36c0d67847da1d9798c`.
- Static WordPress export: 2,861 tracked files, 12 tracked HTML routes, seven XML files, and one Markdown file before this plan.
- `sitemap-complete.xml` contains 12 URLs: six user-facing root pages and six technical/cache/staging/security paths. It contains no article URL.
- User-facing routes are `/`, `/tentang-kami/`, `/kontak-kami/`, `/blog/`, `/privacy-policy/`, and `/terms-and-conditions/`. The blog has no article entries and renders a PHP warning in the export.
- Homepage navigation links 15 untracked category routes: `/pelaminan`, `/tenda`, `/florist`, `/venue`, `/catering`, `/cake`, `/bridal`, `/make-up`, `/gaun`, `/mobil`, `/photographer`, `/mc-entertainment`, `/sound-system`, `/souvenir-invitation`, and `/honeymoon`.
- Homepage and about copy claim luxury planning, nationwide vendors, best reputation, experienced suppliers, dozens of options, cheapest honeymoon pricing, and end-to-end handling. No supporting vendor dossiers, contracts, price survey, case records, or portfolio provenance are present.
- Contact details conflict and appear to be template placeholders: the homepage and contact page show different United States phone/address details, while terms invoke Indonesian law. The live homepage observed during this audit matches the exported commercial copy.
- Privacy and terms pages are generic English templates dated 22 October 2019. They do not clearly name the legal controller, current processors, vendor data sharing, consultation-form retention, event-photo consent, refund ownership, or multi-vendor responsibility.
- The repository contains thousands of media assets and an unrelated hotel-template WXR export. Asset presence is not evidence of ownership, permission, vendor work, or completed wedding projects.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Broad planner/vendor claims, mixed direct-supplier language, placeholder contact details | expand | Transparent service hub plus WED-01 and WED-14 foundations | Legal entity, role by service, team, vendor method, service area, contacts, claims |
| `/tentang-kami/` | Generic company claims without entity/team evidence | manual review | Evidence-led company and operating-model page | Legal name, registration, address, responsible people, credentials, insurance |
| `/kontak-kami/` | Conflicting US placeholder contact details and “free consultation” claim | manual review | Verified contact and consultation-intake route | Current phone, email, address, hours, controller, consent, consultation terms |
| `/blog/` | Empty archive with PHP warning; not editorial coverage | expand | Authority hub linking all topic clusters | Build behavior, archive indexation, error removal, canonical |
| `/privacy-policy/` | Stale generic English policy; controller and vendor sharing unclear | manual review | WED-13 privacy governance and current legal policy | Controller identity, purposes, processors, retention, consent, rights, transfers |
| `/terms-and-conditions/` | Generic website terms; no planning/vendor/referral contract detail | manual review | WED-05 contracts plus service-specific terms | Counterparties, scope, payment, cancellation, force majeure, dispute process |
| 15 named vendor-category links | Linked service routes are absent from tracked export; names imply supply | manual review | Relevant WED-06 to WED-12 knowledge hubs and verified commercial routes | Route status, provider identity, inventory, availability, pricing, evidence |
| Six technical sitemap URLs | Cache, staging, log, security, and email-protection paths exposed as indexable content | noindex | None; remove from editorial sitemap | Live status, robots/meta controls, access restrictions, deployment rules |
| Gallery/media assets | Images lack documented authorship, consent, event context, and claim mapping | manual review | WED-13 media-consent and WED-14 evidence standards | License, creator, subjects' consent, event facts, editing, retention |

## Coverage matrix

| Completeness lens | Topic owners | Coverage decision |
|---|---|---|
| Definition, roles, governance, need recognition | WED-01, WED-14 | Separate couple, family, planner, organizer, coordinator, venue, and vendor roles |
| Requirements, priorities, guest count, budget | WED-02 | One integrated feasibility path before procurement |
| Timeline, sequencing, approvals, day-of control | WED-03 | Lifecycle from engagement to close-out |
| Venue, layout, capacity, facilities | WED-04 | Functional and accessibility-led selection, not venue listings |
| Procurement, vendors, proposals, contracts | WED-05 | Counterparty, scope, evidence, payment, cancellation, and dependency control |
| Food, beverage, cake, hygiene, dietary needs | WED-06 | Catering planning with qualified food-safety evidence |
| Decoration, flowers, stage, tent, power, sound | WED-07 | Visual design separated from structural/electrical/technical safety |
| Couple preparation, attire, make-up, ceremony | WED-08 | Personal readiness and cultural/religious confirmation without prescriptive claims |
| Guests, invitations, seating, accessibility | WED-09 | Inclusive end-to-end guest journey |
| Logistics, transport, lodging, deliveries | WED-10 | Movement, loading, storage, and contingency operations |
| Photography, video, entertainment, media rights | WED-11 | Creative selection, deliverables, consent, copyright, and backup |
| Weather, crowd, health, security, emergency | WED-12 | Risk registers and professional stop/escalation conditions |
| Privacy, family boundaries, children, data | WED-13 | Minimize data and publish media only with appropriate rights/consent |
| Claims, portfolio, testimonials, commercial scope | WED-14 | Evidence gates for every conversion claim |
| Geography and climate | WED-04, WED-07, WED-10, WED-12 | Climate effects are substantive; no city/province/region-swapped briefs |
| Sustainability and post-event lifecycle | WED-03, WED-06, WED-07, WED-10 | Waste, rentals, recovery, returns, donation, and close-out integrated into owner topics |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| WED-01 | Wedding planning foundations and roles | Establish goals, decision rights, and the help actually needed | planner vs organizer vs coordinator; couple/family roles; priorities; event format; guest assumptions; decision log; communication; cultural/religious advisers; when self-planning is viable | Role map, responsibility matrix, decision brief, expert review | Budget is owned by WED-02; vendor contracts by WED-05; commercial provider claims by WED-14 | 6 |
| WED-02 | Budget, priorities, and feasibility | Build a realistic, adjustable event budget | guest count; cost categories; fixed vs variable; contingency; cash flow; taxes/fees; family contributions; trade-offs; quote normalization; overruns; no-debt alternatives | Budget worksheet, scenario model, quote matrix, financial/editorial review | Does not publish price guarantees; contracts are owned by WED-05 | 6 |
| WED-03 | Timeline, workflow, and event-day coordination | Sequence decisions and control execution | planning horizon; milestones; dependencies; approvals; vendor deadlines; rehearsal; run sheet; command chain; handover; teardown; lost-and-found; final reconciliation | Critical-path diagram, milestone checklist, run-sheet template, RACI | Logistics movement belongs to WED-10; emergency response to WED-12 | 6 |
| WED-04 | Venue selection, layout, and facilities | Select a functional venue and test its constraints | capacity; event format; zoning; circulation; ceremony/reception; accessibility; toilets; power; water; ventilation; acoustics; loading; curfew; permits; weather exposure; site survey | Site-survey checklist, layout diagrams, capacity worksheet, venue records, accessibility/safety review | Vendor contracting belongs to WED-05; temporary structures and technical production to WED-07 | 6 |
| WED-05 | Vendor procurement, contracts, and payment | Compare vendors and create accountable agreements | identity; licenses/insurance where relevant; portfolio proof; scope; dependencies; substitutions; payment; tax; cancellation; refund; force majeure; change orders; dispute; vendor failure | Due-diligence checklist, bid matrix, contract RACI, qualified legal review | Does not endorse named vendors; site claim verification is owned by WED-14 | 6 |
| WED-06 | Catering, beverages, cake, and food safety | Plan quantities and service while protecting guests | service style; menu; portion assumptions; dietary needs; allergens; tasting; kitchen; cold/hot chain; water/ice; staffing; leftovers; cake; alcohol rules; waste | Quantity worksheet, menu matrix, allergen form, qualified food-safety review | No medical advice or universal portion/temperature claims; contracts belong to WED-05 | 6 |
| WED-07 | Decoration, flowers, tent, stage, lighting, and sound | Translate a concept into safe coordinated production | mood board; palette; flowers; backdrop; stage; tent; rigging; drape; furniture; lighting; sound; power; cables; flame/load/weather risks; setup; reuse; strike | Design brief, technical plan, load/power schedule, original photos, qualified structural/electrical/fire review | Venue selection belongs to WED-04; entertainment programming to WED-11 | 6 |
| WED-08 | Couple preparation, attire, beauty, and ceremony | Coordinate personal readiness without losing comfort or meaning | attire; fitting; footwear; make-up/hair trial; skin sensitivities; dressing schedule; rings/documents; ceremony sequence; family/cultural roles; rest; meals; emergency kit | Fitting timeline, trial checklist, ceremony worksheet, health/cultural expert review | Guest attire/communication belongs to WED-09; legal/religious validity requires proper authorities | 6 |
| WED-09 | Guest journey, invitations, seating, and accessibility | Create a clear, inclusive experience from invitation to departure | guest data; save-the-date; RSVP; plus-ones; children; seating; signage; language; mobility/sensory needs; toilets; prayer/nursing/quiet space; gifts; complaints | Guest-journey map, seating model, accessibility checklist, communication templates | Transport and lodging belong to WED-10; personal-data governance to WED-13 | 6 |
| WED-10 | Transport, accommodation, deliveries, and site logistics | Move people, goods, and vendors reliably | arrival/departure; parking; shuttles; driver rest; lodging blocks; accessibility; loading dock; delivery slots; inventory; storage; vendor meals; waste; return logistics; route disruption | Logistics map, delivery schedule, inventory/chain-of-custody log, operator review | Venue choice belongs to WED-04; weather and emergency escalation to WED-12 | 6 |
| WED-11 | Photography, video, entertainment, and creative deliverables | Commission creative work with clear expectations and rights | style; shot priorities; timeline; audio; music; MC; performers; licenses; guest consent; minors; deliverables; editing; backups; copyright; publication; accessibility | Creative brief, shot list, cue sheet, rights matrix, sample-deliverable review | Technical sound/power setup belongs to WED-07; privacy governance to WED-13 | 6 |
| WED-12 | Weather, safety, health, security, and contingency | Identify credible risks and assign response ownership | rain/heat/wind; crowd; fire; electrical; food illness; medical events; lost child; harassment; security; evacuation; emergency contacts; insurance; cancellation; drills; incident records | Risk register, trigger matrix, emergency map, qualified safety/medical/security/legal review | Not emergency or medical advice; technical controls remain with competent providers and authorities | 6 |
| WED-13 | Privacy, consent, family boundaries, and data governance | Protect guest, couple, child, and vendor information | RSVP data; IDs; dietary/health data; seating; payment; guest lists; children; photography consent; social sharing; vendor transfers; access; retention; breach; family boundaries | Data-flow map, consent matrix, retention schedule, qualified privacy/legal review | Creative deliverables belong to WED-11; commercial contracts to WED-05 | 6 |
| WED-14 | Planner services, portfolios, referrals, and claim evidence | Evaluate WeddingEvent.co.id or another planner without unsupported promises | planner scope; proposal; directory/referral model; vendor vetting; legal entity; team; experience; portfolio provenance; testimonials; price claims; availability; outcomes; disclosures; complaints | Service RACI, claim-evidence register, portfolio dossier, legal/editorial review | Neutral planning education stays in WED-01 to WED-13; no self-awarded “best” status | 6 |

## Related-domain opportunities

Owned properties focused on floristry, catering, venues, invitations, travel, transport, fashion, photography, audio, safety, or event structures may independently cover the same entities from their own perspectives. Cross-links should solve a reader task and disclose commercial relationships. They do not remove any useful wedding-planning topic from this domain and are not same-domain cannibalization.

## Consolidation plan

1. Correct the legal identity, role, contact details, service area, and controller information before expanding commercial acquisition pages.
2. Decide whether each of the 15 linked vendor routes is a neutral guide, verified directory, referral page, planner-managed service, reseller offer, or direct supply route. Do not mix those intents.
3. Remove technical/cache/staging/security paths from the editorial sitemap and restrict indexing/access as appropriate.
4. Replace the empty/erroring blog archive with a hub architecture for WED-01 through WED-14.
5. Audit every gallery asset for creator/license, event provenance, subject consent, edit history, and the exact claim it supports. Remove or neutralize unverified portfolio implications.
6. Replace generic privacy and terms templates with current, entity-specific policies and service/referral terms reviewed for Indonesian operations.
7. Preserve a future useful service URL only after reconciling its intent; do not create articles with the same slug as `/venue`, `/catering`, `/photographer`, or another commercial category.

## Internal-link architecture

WED-01 is the central planning hub. It routes feasibility decisions to WED-02, schedule ownership to WED-03, venue constraints to WED-04, and procurement to WED-05. Vendor-category journeys run from requirements to WED-05 due diligence, then to WED-06 through WED-11 for category-specific briefs. WED-12 safety and contingency, WED-13 privacy, and WED-14 commercial evidence are mandatory cross-checks at relevant decision points. Every commercial route links back to its neutral requirements guide and states its actual role.

## Evidence and editorial standards

- Date and source every volatile vendor, venue, availability, price, law, permit, safety, food, weather, accessibility, and service claim.
- Use primary authority, venue, vendor, manufacturer, contract, and qualified-expert evidence. A copied template, image filename, directory listing, backlink, or vendor logo is not proof.
- Name the legal provider, planner/facilitator role, contractual counterparty, payment recipient, refund owner, data controller, emergency owner, and responsible vendor for each service.
- Never promise a “perfect,” luxury, cheapest, stress-free, safe, on-time, available, or successful wedding. Never call a vendor best or experienced without a transparent dated method and evidence.
- Do not invent prices, guest-capacity rules, food portions, structural loads, electrical limits, weather thresholds, legal requirements, testimonials, case studies, or firsthand event experience.
- Structural, tent/rigging, electrical, fire, food-safety, medical, security, alcohol, accessibility, privacy, copyright, contract, and religious/legal-validity content requires current primary sources and qualified review.
- Identify images as illustrative unless verified event provenance and permissions exist. Obtain appropriate consent before publishing identifiable guests or children.

## First bounded publication cluster

Publish WED-01-01, WED-01-02, WED-02-01, WED-02-02, WED-03-01, WED-04-01, WED-05-01, WED-05-02, WED-06-01, WED-09-01, WED-09-04, WED-12-01, WED-13-01, WED-14-01, and WED-14-02. This cluster establishes planning roles, a workable brief and budget, timeline, venue survey, vendor/contract safeguards, guest and food assumptions, accessibility, core risk/privacy controls, and transparent commercial evaluation.

Before publication, fix the homepage/about/contact authority and placeholder data, assign canonical URLs, and reconcile the proposed informational slugs with all commercial routes. Measure indexation, impressions by distinct intent, budget/checklist completion, useful internal-link journeys, qualified consultation enquiries, informed drop-offs, consent completion, corrected claims, and same-domain query overlap.

## Definition of done

- 14 topic clusters contain exactly six distinct briefs each; validator reports zero errors and warnings.
- Proposed IDs, titles, and slugs are unique; no proposed slug collides with a tracked or linked route.
- No city, province, region, or place-name-swapped brief exists.
- Homepage, about, contact, legal, gallery, sitemap, and vendor-category claims have been reconciled with verified roles and evidence before the first cluster is published.
- Every article has a distinct primary intent, an explicit owner for excluded intent, useful related IDs, and an evidence format proportionate to risk.
- The first wave is internally connected, safe to publish after review, and measured beyond ranking.
