# Master plan — Powerful India lead-gen system

**Codename:** Lead Gen System (working)  
**Owner:** Vikas  
**Updated:** 2026-07-23  

---

## 1. Vision

A durable system that:

1. **Finds** high-quality buyers for premium web products (not random “no website” SMBs)  
2. **Scores** them with NEED × ABILITY × TIMING (+ reach)  
3. **Approaches** with specific proof and money angles (human-send, AI-draft)  
4. **Learns** which sources, angles, and offers convert  
5. **Expands** vertical-by-vertical without rebuilding philosophy each time  

End-state shape (orchestration, not one god-agent):

```
┌─────────────┐   ┌──────────┐   ┌──────────┐   ┌─────────┐   ┌────────────┐
│  Discover   │ → │ Qualify  │ → │  Enrich  │ → │  Draft  │ → │ Human send │
│  (multi-src)│   │ N×A×T    │   │ reach+   │   │ approach│   │ + reply AI │
└─────────────┘   └──────────┘   └──────────┘   └─────────┘   └────────────┘
        ↑                                                      │
        └──────────────── learn / feedback ────────────────────┘
```

---

## 2. Principles (non-negotiable)

| # | Principle |
|---|-----------|
| 1 | **Quality over volume** — gold leads, not CSV dumps |
| 2 | **Deep benefit or intent** — platform tax, ads leak, season, hand-raise — not “credibility” lectures |
| 3 | **Composite signals** — single “no website” is never enough |
| 4 | **Proof before pitch** — mock, screenshot, ₹ math, peer demo |
| 5 | **Human send on WA/IG** — no bulk unofficial spam architecture |
| 6 | **Vertical playbooks** — same engine, different ICP/offer/source weights |
| 7 | **Docs survive restarts** — plan + decisions + current task always current |
| 8 | **Test before empire** — one vertical closed-loop before multi-agent farm |

---

## 3. Product ladder (what we sell)

| Tier | Product | Ticket (intent) | Proof / notes |
|------|---------|-----------------|---------------|
| **A** | Creative portfolio (photo first) | **₹15k** | Current test; productized |
| **B** | Wedding *story* site (couple or flagship) | ₹40k–1L+ | Clara / Karamjot class |
| **C** | Venue / hospitality site | Higher | ONR class; OTA/direct angles |
| **D** | Later: coaching, D2C store, etc. | varies | Only after A–C learnings |

Sales rule: **never sell tier B at tier A price.**

---

## 4. Phased roadmap

### Phase 0 — Foundation (docs + research) ✅ mostly done

- [x] Multi-angle research (demand, signals, selling)  
- [x] Synthesis + hunter workflow for photographers  
- [x] Portfolio proof reviewed (Clara, Karamjot, ONR)  
- [x] Decisions locked (₹15k, ICP, quality rules)  
- [x] Docs folder for continuity  
- [ ] City lock for first live batch  

### Phase 1 — Task 0 live test (CURRENT)

**Photographer portfolio hunter + approach test**

Deliverables:

1. Lead sheet + rubric  
2. City discovery SOP  
3. Draft templates  
4. First gold batch + sends  
5. Outcome log → go/no-go on ICP  

See `CURRENT-TASK.md`.

### Phase 2 — Delivery productization

So closes don’t create chaos:

- Portfolio template (1-day class delivery)  
- Client asset checklist  
- Deploy path (Pages)  
- Scope PDF (in/out)  

### Phase 3 — Systemize hunter

- Assisted discovery (browser/tools) still human-scored  
- Draft generator from lead fields  
- Optional n8n: status, reminders, not auto-spam  
- Dashboard/sheet hygiene  

### Phase 4 — Expand verticals (playbooks)

Add one at a time using same engine:

| Priority (from research) | Vertical | Core angle |
|--------------------------|----------|------------|
| 1 | Wedding photographers | Portfolio / IG rented |
| 2 | Homestays / boutique stays | OTA commission save |
| 3 | Wedding vendors (MUA, decor) | Listing tax + portfolio |
| 4 | Multi-batch coaching | Season + landing |
| 5 | Specialty clinics | Trust + appointment URL |

Each vertical = sources + score weights + offer + message pack.

### Phase 5 — Approach intelligence

- Reply assist  
- Objection library (nephew, IG enough, Justdial, price)  
- Mock generator (their photos on template)  
- Referral loop post-delivery  

### Phase 6 — Multi-agent scale (only after proof)

- Specialized agents: discover / score / enrich / write  
- Orchestrator (n8n or custom)  
- Strict quality gates so scale doesn’t trash brand  
- Metrics: gold rate, reply rate, close rate, source ROI  

---

## 5. Architecture (target)

```
                    ┌──────────────────────┐
                    │   Lead store (SSOT)  │
                    │  sheet / DB later    │
                    └──────────┬───────────┘
           discover│          │score/enrich
                    v          v
              ┌─────────┐  ┌─────────┐
              │ Sources │  │ Rubric  │
              │ IG,WMG, │  │ N×A×T   │
              │ Google  │  └────┬────┘
              └────┬────┘       │
                   └─────► gold queue
                              │
                         pitch asset
                              │
                         draft agent
                              │
                         human send ──► outcomes ──► learn
```

**v1 storage:** CSV or Notion is enough.  
**v2:** DB + UI if volume justifies.

---

## 6. Quality bar (global)

A lead is **gold** only if:

1. Clear **NEED** (gap we fix with our product)  
2. Clear **ABILITY** (can pay ticket without fantasy)  
3. Clear **TIMING** or strong activity proxy  
4. **REACH** path that isn’t “illegal blast”  
5. One-sentence **hook** for personalization  

Anything less = raw or parked.

---

## 7. Approach bar (global)

| Do | Don’t |
|----|--------|
| Specific observation | “Dear business owner” |
| Show proof (demo / mock / ₹) | Feature dump |
| One soft ask | Essay |
| Hinglish/plain OK | Corporate spam English |
| Human identity | Fake agency army |

---

## 8. Metrics that matter

| Metric | Why |
|--------|-----|
| Raw → gold % | Discovery quality |
| Time per gold lead | System efficiency |
| Gold → reply % | Message + ICP fit |
| Reply → paid % | Offer + trust |
| Source attribution | Double down / kill |
| Delivery hours per ₹15k | Unit economics |

Ignore vanity: total scraped rows, follower counts alone.

---

## 9. Risk register

| Risk | Mitigation |
|------|------------|
| Cheap brand if underpriced | ₹15k locked; ladder to story/venue |
| Scope creep on portfolio | Written in/out; 1 revision |
| Spam / ban on WA | Human send; low volume; personalized |
| Wrong ICP (hobby shooters) | Ability gate strict |
| Restart amnesia | docs/ SESSION-RESUME + CURRENT-TASK |
| Building agents before offer works | Phase 1 live test first |

---

## 10. Repo / folder map

```
C:\Users\silen\Downloads\projects\leadgen-research\
  docs\                 ← plans, decisions, resume (YOU ARE HERE)
  findings-*.md         ← research evidence
  SYNTHESIS.md
  portfolio-ss\         ← proof screenshots
  (future) app\ or tools\  ← scripts, sheet templates, agents
```

---

## 11. Definition of “system is working”

Not “we have scrapers.” Working means:

1. Repeatable gold list for a locked ICP  
2. Repeatable approach that gets **real conversations**  
3. At least some **paid closes** at sustainable delivery hours  
4. New vertical can be added by **playbook**, not full rethink  
5. A cold session can resume from **docs alone** in &lt;10 minutes  

---

## 12. Immediate focus

→ **Phase 1 / Task 0** only: photographer ₹15k test.  
→ Do not start multi-agent farm until Task 0 outcomes exist.  
→ See `CURRENT-TASK.md` + `SESSION-RESUME.md`.
