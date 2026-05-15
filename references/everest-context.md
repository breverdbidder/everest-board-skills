# Everest Context — Required Reading for Every Advisor

Every `eb-*` persona reads this file **before** generating any output for `/eb:boardroom`, `/eb:brief`, or any other deliberation surface.

## Company Stack

**Everest Capital USA** (parent) operates two paired AI-powered proptech platforms:
- **BidDeed.AI** — FL foreclosure + tax-deed auction intelligence (256K+ auction records across 67 counties)
- **ZoneWise.AI** — FL zoning + parcel intelligence (10.5M parcels, 67 counties, choropleth-grade)

**Mandatory pairing rule:** BidDeed.AI and ZoneWise.AI are **always referenced together**. Foreclosures and tax deeds are always paired. Patents are filed under Ariel Shapira as individual inventor, not the entity.

**Positioning:** "Agentic AI ecosystem" — NEVER "SaaS." Critical for valuation.

## Founder

**Ariel Shapira** — Solo founder, 20+ years in FL distressed RE. 20 minutes/day oversight maximum. Direct, no softening, action-oriented. Observes Shabbat (no work Friday sunset through Saturday havdalah).

Family: wife **Mariam** (FL broker / GC / insurance licenses via Property360, Kenstrekt, Protection Partners), son **Michael** (16, competitive sprint swimmer, D1 recruiting trajectory).

## Operating Constraints

- **$10/task cost ceiling** across all meters (LLM API, scrape, etc.)
- **Windows 10** local machine (PowerShell, OpenSSH, no bash-isms)
- **Default infra:** Supabase + GitHub Actions only. Hetzner only for proven Supabase+GHA gaps (long Playwright sessions, autonomous CC overnight, GPU)
- **House brand:** Navy #1E3A5F / Orange #F59E0B / Inter / bg #020617
- **Honesty V3 Protocol:** Every claim tagged VERIFIED / UNTESTED / INFERRED / ASSUMED / UNKNOWN. Wrong VERIFIED = 3x penalty logged in `honesty_violations` table.
- **EG14 Gate:** 14-point quality checklist on every deliverable, with critical points at 1 / 6 / 8 / 11
- **License Discipline (R5):** MIT / Apache2 / BSD / ISC = FORK-OK. AGPL / GPL / SSPL / BUSL = poison.
- **Zero-HITL mandate:** Chat (AI Architect) executes autonomously. Surface only after 3 failed retry attempts, with: problem, attempts, recommendation.

## Buyer Personas (for offer / sales advisors)

**Primary FL distressed-RE investor profile:**
- $500K – $5M annual deployable capital
- 5-50 properties acquired/year via foreclosure or tax-deed auctions
- Currently using: PropertyOnion (RealAuction reseller, 41/43 counties), county clerk portals manually, Excel
- Pain: 7-county pain limit, data freshness arbitrage (PropertyOnion has 7/15 sites frozen since July 2024)
- Buy-trigger: trusted local intelligence + verifiable track record

**Secondary ZoneWise enterprise profile:**
- FL muni planning departments, land-use attorneys, large RE brokerages
- Pain: 67-county manual zoning research takes weeks
- Buy-trigger: API + automated parcel-to-zoning intelligence

## Competitive Stance

**Primary wedge against PropertyOnion / Daveco Properties:** Data-freshness arbitrage. 7 of Daveco's 15 active sites have data frozen since July 2024. Active CI v6.5 dossier maintained.

**Differentiator:** Agentic AI ecosystem (BidDeed + ZoneWise pairing) vs single-product scraper resellers.

## Current Priorities

1. **ZoneWise GTM blocked on Marketing OS Hub v0** (8 tenants, AWS SES + Mixpost Lite)
2. **625 Ocean St coastal development** (Satellite Beach, Brevard County, permit deadline June 25, 2026)
3. **Multiple FL LLC entities** under Everest Capital of Brevard LLC umbrella
4. **Michael's swim recruiting** — LCM Futures Championships (July 29-Aug 1, 2026), 50 Free gap 0.76s

## Methodology

**The Everest Ascent™** — 12-stage acquisition / development / exit methodology. Trademarked. Used in all customer-facing positioning.

**The Shapira Triangle V4.0** — ML stack (XGBoost + LightGBM + CatBoost → Random Forest meta-learner) for FL auction prediction. 82.6% accuracy / 0.8832 AUC on 256K+ records. Canonical terminology: "Anchor Bidder" (PlaintiffSubclass / CertHolderSubclass).

---

**This file is the ground truth.** Personas that contradict it without explicit override will fail EG14 critical point 1 (factual grounding) and earn a `honesty_violations` row.

**Version:** 1.0.0 | **Last updated:** 2026-05-15 | **Fork branch:** personas/legends-overlay
