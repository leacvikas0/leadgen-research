# Hunter workflow — ₹15k wedding photographer portfolio (quality max)

> **Canonical docs copy:** `docs/HUNTER-WORKFLOW.md`  
> **System plan:** `docs/MASTER-PLAN.md` · **Resume:** `docs/SESSION-RESUME.md`

**ICP:** Working wedding/event photographers (India), need owned portfolio  
**Offer:** ₹15k productized portfolio (not couple-story / not venue)  
**Goal:** Gold leads only (NEED × ABILITY × TIMING), not volume

---

## Principle

```
Discovery (wide-ish)  →  Hard qualify  →  Pitch asset  →  Human approach
     cheap                   expensive      expensive         careful
```

Never skip qualify. A lead without a 1-line money/friction reason is not a lead.

---

## Stage 0 — Lock corridor (once per run)

| Input | Example |
|-------|---------|
| City / belt | Delhi NCR, Chandigarh, Jaipur, Bangalore… |
| Vertical | Wedding photographer only (v1) |
| Target count | 15–25 gold / week (manual+assisted), not 500 junk |
| Proof links | clara-elliot, karamjot-harleen |

---

## Stage 1 — Discover (where gold hides)

Ranked by quality density for *this* ICP:

| Rank | Source | What you look for |
|------|--------|-------------------|
| 1 | **Instagram** | City + wedding tags, hashtags, location tags, competitor followers |
| 2 | **WedMeGood / similar vendor lists** | Listed photographers in city (proves market; then check if owned site weak) |
| 3 | **Google** | `"wedding photographer [city]"`, Maps pack — then open site/IG |
| 4 | **YouTube / reels comments** | Shooters tagging themselves under venue content |
| 5 | **FB city wedding groups** | Occasional hand-raises (low volume, high intent) |
| 6 | Maps alone with empty website | **Discovery residue only** — never auto-qualify |

**IG discovery patterns (highest yield):**
- Search: `wedding photographer [city]`, location pages (venues)
- Hashtags: `#deliweddingphotographer` etc. (city-specific)
- Seed 5–10 known good shooters → their **liked / commented / collab** graph
- Venue tags: ONR-class venues, farmhouses, popular mandap hotels → tagged photographers

---

## Stage 2 — Score (gate: all three > 0)

Score 0–2 each. **Park if any dimension = 0.**

### NEED (do they lack a real portfolio home?)

| +2 | +1 | 0 |
|----|----|---|
| No site / Linktree / Drive / wa.me only | Site exists but broken, 2019, Wix default, no mobile, no work grid | Strong modern portfolio already |
| Bio says “DM for portfolio” | Domain in bio → parked / 404 | |

### ABILITY (can they pay ₹15k without pain?)

| +2 | +1 | 0 |
|----|----|---|
| Consistent wedding posts, real couple work, venues, teams | Mixed portraits + some weddings | Hobby, friends-only, empty grid |
| Mid+ positioning (packages vibe, second shooter, film partner) | Growing but thin proof | “Rates on DM” + no work |
| Reviews / Google presence / WedMeGood listing with real portfolio | — | Student / “starting out” |

*Proxy not vanity:* engagement on wedding posts > follower count alone.

### TIMING (why now?)

| +2 | +1 | 0 |
|----|----|---|
| Peak season −60–90d, “bookings open”, new brand name, just got good gear/reel push | Active posting, ads on IG, hiring second shooter | Dead account 6+ months |
| Public frustration: lost inquiry, “need website”, rebrand | Soft — wedding season always somewhere | Happy with Linktree forever (hard to know — default 1 if active) |

**Gold bar:** NEED ≥1, ABILITY ≥1, TIMING ≥1, total **≥4**, and at least one **hard** signal (no real site + real wedding volume).

---

## Stage 3 — Enrich (5 minutes max per gold)

For each survivor, capture:

```
name
ig_url
city
whatsapp / phone   (if public: WA.me, GBP, WedMeGood)
website_status     none | linktree | weak | none_in_bio
need_note          one line
ability_note       one line (e.g. "12 wedding posts / 90d, farmhouse shoots")
timing_note        one line
score_N / A / T
proof_hook         what WE will screenshot for outreach
status             new | drafted | sent | replied | won | dead
```

**Reach:** Prefer public WhatsApp / business number. No shady scrape-for-spam stacks. IG DM if only path.

---

## Stage 4 — Pitch asset (what makes quality outreach)

Before any message, prepare **one** of:

1. **Their gap:** “Bio = Linktree only” screenshot  
2. **Their work on *our* layout mock** (even static: their best 3 photos on portfolio frame) — highest convert  
3. **Peer proof:** Karamjot + Clara links (quality bar)  
4. Optional: competitor in same city with a clean site (FOMO)

No asset → don’t message. That’s the quality filter on *you*.

---

## Stage 5 — Approach (human send)

```
AI/system drafts  →  You send on WA or IG  →  Reply assist only
```

Sequence:
1. Personalized first touch (observation + proof + ₹15k offer optional on msg 2)
2. Soft ask: “2 min look at a mock?” or “link to what we ship”
3. If interest → share Clara/Karamjot + what ₹15k includes
4. Close: advance + asset checklist

**Not in v1:** bulk WA automation, unofficial account bots.

---

## End-to-end weekly loop

```
Mon    Lock city batch; IG + WedMeGood pass → raw list 40–60
Tue    Score N×A×T → keep 15–25 gold
Wed    Enrich + pitch assets (mocks for top 10)
Thu    Send 8–12 human messages
Fri    Follow-ups + replies; log outcomes
Sun    Review: which sources produced replies? kill weak sources
```

---

## System components (build order)

| # | Component | Job |
|---|-----------|-----|
| 1 | **Lead sheet** (CSV/Notion/Airtable) | Single source of truth + scores |
| 2 | **Scoring rubric** (above) | Same quality bar every time |
| 3 | **Manual SOP** (checklist) | You or VA can run without vibes |
| 4 | **Optional: assisted discovery** | Browser scripts / search lists — still human score |
| 5 | **Draft generator** | Fills WA/IG copy from lead fields + hooks |
| 6 | **Later: n8n/cron** | Reminders, status, not auto-spam |

**Quality path:** 1 → 2 → 3 first. Automation only multiplies a good rubric.

---

## Anti-patterns (kill)

- Empty Maps website field as “qualified”
- Follower count alone
- Messaging without a specific observation
- Mixing venues / clinics / random SMBs into this pipeline
- Promising Clara-class story site in the portfolio offer
- Volume targets that force score inflation

---

## Success metrics (honest)

| Metric | Target early |
|--------|----------------|
| Raw → gold rate | ~25–40% if discovery is IG-heavy |
| Gold → reply | Learn after 20 sends (baseline unknown) |
| Reply → paid | Track; optimize mock quality first |
| Time per gold lead | <10 min discover+score+enrich |

---

## v1 build recommendation

**This week:** Lead sheet + rubric + SOP + draft templates  
**Not yet:** Full multi-agent browser farm  

City locked → run first manual batch of 20 gold → then automate discovery assist.
