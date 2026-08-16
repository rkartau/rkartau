# Docka — Maritime Lead Sources & Outbound Pipeline Plan

*Research compiled 2026-08-16. Goal: build a valid, contactable base of ship agency companies, shipowners/managers, and port-call decision-makers for Docka's sales pipeline.*

---

## 1. Reality check on the "100,000 contacts" target

Before sources: the target number needs adjusting, because the market is smaller than that — and that's good news, not bad.

- There are roughly **10,000–15,000 ship agency companies** worldwide (FONASBA's national associations cover most of the organized market). *(Refined in §2.)*
- There are roughly **~25,000–50,000 registered shipowner/manager companies**, but a much smaller core of active commercial operators. S&P's Sea-web claims ~240,000 maritime company records total across *all* company types — agents, owners, managers, suppliers, everyone. *(Refined in §3.)*
- A "100k valid personal emails" list can only be built by scraping/buying junk data. It would be mostly invalid (destroying your sender domain within days), and mass-harvesting named individuals' emails violates GDPR for an Estonian-based sender and gets outreach domains blacklisted.

**The realistic, better target:** ~15k–40k *companies* as the account universe, and **licensed, verified contacts for the top few thousand accounts you can actually work** — segmented by country so every send is legal. A tight base of 5,000 valid, role-relevant contacts will outperform 100,000 scraped addresses on every metric that matters (deliverability, reply rate, and not getting fined).

---

## 2. Ship agency companies — where the data lives

**Population estimate: ~5,000–10,000 addressable ship agency companies worldwide** (triangulated from national association member counts, ITIC insurance membership, and free directory sizes — no authoritative census exists). ~600+ of them are FONASBA Quality Standard accredited; ~2,500–6,000 appear in free web directories.

### Best sources, ranked

1. **FONASBA membership list → national association member directories** (free, authoritative). FONASBA covers **73 countries** (52 full national associations + ~21 associate/candidate). FONASBA itself publishes association-level contacts only; the *company-level* data lives with the national associations — and most publish member directories publicly:
   - Italy: Federagenti — ~500 companies via 16 territorial associations (144 ports)
   - Germany: ZVDS — ~230 companies via local port associations
   - Brazil: FENAMAR — 500+ companies across 15 state unions
   - Mexico: AMANAC — 120+ agencies (claims 93% of Mexican ship calls)
   - Plus Netherlands (VRC/shipagents.nl), Portugal (AGEPOR), France (AMCF), Spain (ASECOB port associations), Poland, Sweden, Canada (shipfed.ca) etc.
   - Closed exceptions: UK's ICS (member list on request only), South Africa's SAASOA (login-gated)
2. **FONASBA Quality Standard approved-companies list** — 600+ accredited companies in 44 countries, public, pre-qualified. The best "start here" list.
3. **Free web directories for bulk fill-in** (check ToS before automated collection): MarineVesselTraffic (~6,100 port-agent companies with address/phone/fax), MagicPort, Marine Insight 360 (~2,600 agents), Infomarine, PortServiceFinder, MGN.
4. **Findaport (Shipping Guides Ltd)** — paid, 9,000+ ports with per-port agent contacts, maintained professionally; official data-licensing available. Cleanest *licensed* route to per-port agent contacts.
5. **Lloyd's List Directories / Intelligence** — paid; company directory claims 95k+ owners/operators with 113k offices (all maritime company types); worth it only if you also want port-call activity data to prioritize accounts.

Note: **Wilhelmsen (~2,200 port locations) and GAC (300+ offices)** are the two giant global agency networks — they're competitors/partners and major accounts themselves, not directories of independents.

---

## 3. Shipowners and ship managers — where the data lives

*(Section pending — being researched.)*

---

## 4. Getting named contacts + emails legally (licensed providers)

No mainstream B2B data vendor publishes a maritime-specific contact count — they all filter by industry codes, and maritime depth is unverified (the industry is full of private, family-run firms that thin out in generic databases). Maritime-specialist platforms (Sea-web, Lloyd's List Intelligence) are strong on **companies and ownership** but are not person-level email databases.

**The working pattern: maritime source for the account list → licensed B2B provider for the people and emails.**

| Provider | Best for | Contacts claimed | Price ballpark | GDPR posture | API |
|---|---|---|---|---|---|
| **Cognism** | EU/UK contacts — strongest compliance paperwork | ~200M+ EU records claimed | ~$15k–25k/yr (est.) | Best-in-class: documented legitimate-interest assessments, Art. 14 notifications to data subjects, DNC scrubbing, ISO 27701 | Yes |
| **Kaspr** (Cognism-owned) | Budget EU option, LinkedIn overlay | 120M+ EU contacts | ~€45–99/mo | Same data foundation as Cognism; notification program | Limited |
| **Apollo.io** | Rest-of-world volume + built-in sequencing | ~270M | Free–$49+/user/mo | Weaker EU posture — use for non-EU | Yes, good |
| **Lusha** | Cheap per-seat, decent certs | 290M+ | ~$29–37/user/mo | ISO 27701 + SOC 2 | Yes |
| **UpLead** | Pay-per-verified-contact, 95% accuracy guarantee | 160M+ | $74–149/mo credit-based | Claims compliance, thin detail | Yes |
| **Dealfront** | DACH + Nordics (German/Danish/Norwegian shipping) | 400M contacts / 60M companies | from ~€141/mo | EU-native, register-sourced, "GDPR-first" | Yes |
| **ZoomInfo** | Enterprise budget only | 260M+ | ~$15k–40k/yr | Has notification program; expensive | Yes |

**Avoid:** static "maritime email list" CSV brokers (iInfoTanks etc.) — no data provenance, no lawful-basis documentation, no suppression sync. Classic GDPR trap for EU buyers, and the accuracy claims don't survive contact-verification testing.

**LinkedIn Sales Navigator:** use it manually to *identify* the right people at target accounts (port captains, ops managers, DPA/designated persons, agency ops directors) — then pull their email from a licensed provider. Automated scraping/export of LinkedIn is a ToS breach that gets accounts banned; extensions like Kaspr surface their own licensed data while you browse, which is the safer pattern.

---

## 5. The legal frame (what you can send, where)

Two separate layers:

1. **GDPR (holding the data):** legitimate interest (Art. 6(1)(f)) covers B2B prospecting with role-relevant corporate contacts — but you must have a documented Legitimate Interest Assessment on file, give notice at first contact (Art. 14 — a line about data source + privacy-notice link in email #1), honor objections permanently, and sign a proper license with the data provider. Buying from a "compliant" vendor does not transfer compliance — you're an independent controller.
2. **ePrivacy (sending the email):** each country implemented cold-email rules differently. This decides your channel per country:

| Regime | Countries (maritime-relevant) | Channel |
|---|---|---|
| **Opt-out — cold B2B email OK** (identify yourself + working unsubscribe) | **Estonia**, UK, USA, Netherlands, France, Sweden, Finland, Singapore | Email sequences allowed |
| **Opt-in — cold B2B email effectively banned** | **Germany, Denmark, Italy, Spain, Poland, Greece**, Norway (named individuals), Canada, Japan, Korea, China, UAE | LinkedIn outreach, phone, referrals, events |

Greece being opt-in matters: it's the largest shipowning nation. Plan for **Posidonia, SMM, Nor-Shipping, Seatrade events** + referral-led outreach there, not cold email.

**Sender hygiene (non-negotiable):** separate sending domain with SPF/DKIM/DMARC, gradual warmup, pre-send verification of every address (ZeroBounce/NeverBounce class), bounce rate kept under ~2–3%, one-click unsubscribe, global suppression list synced across all tools, purge non-responders after 12–24 months.

---

## 6. Recommended pipeline build (concrete steps)

1. **Account universe (companies, not people):** pull ship agency companies from FONASBA-affiliated national association directories + port directories, and owners/managers from Equasis/Sea-web-class sources. Company-level records are legal-person data — low GDPR exposure. Target: 15k–40k accounts, tagged by segment, fleet/port relevance, and country.
2. **Prioritize:** score accounts by fit for Docka (ports served, fleet size, segment). Work top-down — you cannot personalize to 100k anyway.
3. **People layer, licensed only:** Cognism/Kaspr for EU accounts, Apollo/Lusha/UpLead for rest-of-world. Verify every email before it enters a sequence. Before buying any subscription, run a **sample test**: give each vendor 100 known maritime companies and measure how many role-relevant contacts they actually return.
4. **Country routing in the CRM:** every contact tagged by country; email sequences fire only for opt-out countries; opt-in countries auto-route to LinkedIn/phone/event workflows. Germany, Denmark, Italy, Spain, Poland, Greece hard-blocked from cold-email sequences.
5. **Compliance kit before campaign #1:** written LIA, Art. 14 notice text in first-touch template, provider due-diligence file (DPA + lawful-basis statement), suppression infrastructure.
6. **First-party engine in parallel:** maritime events, webinars, content — the only clean route into the opt-in countries at scale, and the highest-converting leads you'll get anywhere.

---

*Sections 2–3 source tables and the full source list are appended below.*
