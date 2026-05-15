# Everest Board — Named-Operator Personas (Legends Overlay)

Fork of [`alirezarezvani/claude-skills`](https://github.com/alirezarezvani/claude-skills) with 8 named-operator persona overlays grafted onto the 21-component boardroom architecture.

## What this is

The upstream `cs-*` (chief-of-staff prefix) advisors are excellent functional roles — CFO, CMO, CRO, etc. They are **role-shaped**. This overlay adds **operator-shaped** advisors named after specific business operators whose voices and frameworks are well-known and consistent:

| Persona | File | Replaces (in Everest context) | Lane |
|---|---|---|---|
| Alex Hormozi | `eb-hormozi-advisor.md` | cs-cmo (offer) + cs-cro (deal arch) | Offer engineering, value equation, LTV |
| Grant Cardone | `eb-cardone-advisor.md` | cs-cro (activity) | 10X volume, follow-up cadence, omnipresence |
| Seth Godin | `eb-godin-advisor.md` | cs-cmo (positioning) | Purple cow, smallest viable market, story |
| Gary Vaynerchuk | `eb-garyvee-advisor.md` | cs-cmo (content) + cs-cco (community) | Document don't create, atomization, personal brand |
| Jordan Belfort | `eb-belfort-advisor.md` | cs-cro (closing) | Straight line, looping, certainty transfer |
| Russell Brunson | `eb-brunson-advisor.md` | cs-cmo (funnel) + cs-cpo (packaging) | Value ladder, perfect webinar, attractive character |
| Dan Kennedy | `eb-kennedy-advisor.md` | cs-cmo (copy) + cs-cco (customer) | Direct response, magnetic marketing, affluent buyer |
| Tony Robbins | `eb-robbins-advisor.md` | executive-mentor (founder coach) | State management, six needs, ultimate success formula |

## Why not just use cs-*

The functional roles assume a generic B2B SaaS founder context. Everest Capital USA's reality is FL distressed-RE acquisitions, agentic-AI proptech, and a solo founder with 20-minute-daily oversight. The named operators ship with strong opinionated voices that survive the domain transfer — and `references/everest-context.md` grounds them in the actual stack.

## How they work with the upstream boardroom

These personas plug into the unchanged upstream `/cs:boardroom` 6-phase pipeline (rebranded `/eb:boardroom` in this fork):

1. **Briefing** — Chief of Staff distributes brief
2. **Phase 2 ISOLATION** — Each persona produces independent position
3. **Cross-Examination** — Personas critique each other on owned dimensions
4. **Devil's Advocate** — Robbins runs `/em:challenge` on the leading option
5. **Synthesis** — Voted memo + dissent column
6. **Hand-off** — Founder decision

## License + attribution

- Upstream: MIT (alirezarezvani/claude-skills @ commit 0796e1d70a9de786a4f88c859124b357b94425f3)
- This overlay: MIT (Ariel Shapira / Everest Capital USA)
- The 8 named operators' frameworks are summarized in this overlay as a paraphrased educational interpretation; original quotes and copyrighted training material are NOT reproduced.

## Branch + provenance

Branch: `personas/legends-overlay`
Fork created: 2026-05-15 17:54 UTC via `extensions.http` from Supabase
Fork commit base: `0796e1d70a9de786a4f88c859124b357b94425f3`
EXTREP audit trail: `extrep_intake.id = 2c6d1326-d607-439f-9bce-964dabc711af`
RepoEval: ADOPT 92/100 · EG14 12/14 · Tier 0 PERMISSIVE_FREE

---

**Version:** 1.0.0 | **Status:** Production-ready overlay
