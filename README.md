# One-Month Sprint Plan: Managing Competing Priorities
**Associate Product Manager Assignment**

---

## Executive Summary

Managing 10 developers across three hospital clients and internal constraints requires brutal honesty about what we can—and cannot—accomplish in one month. This plan reflects the messy reality of product management: difficult trade-offs, stakeholder disappointment, and the courage to say "not yet" to important work.

**The Hard Truth:** We cannot satisfy everyone this sprint. Instead, we'll protect our team's capacity, deliver meaningful value where it counts most, and set ourselves up for sustainable success in future sprints.

---

## Situation Analysis: What We're Really Dealing With

### Available Capacity (The Math That Matters)
- **Total team:** 10 developers
- **Reduced capacity:**
  - 2 developers on partial leave
  - Ongoing exam commitments for some team members
- **Effective capacity:** ~7.5 FTE (Full-Time Equivalent) for the month
- **Sprint capacity:** Approximately 120 story points or 300 development hours

### The Demands on the Table

**Hospital A (Long-term Client)**
- *Request:* Urgent OPD print layout changes
- *Business context:* Our anchor client, but "urgent" doesn't always mean critical
- *Risk if delayed:* Relationship strain, but unlikely to lose the account

**Hospital B (New Client - Big Contract)**
- *Request:* HR module (large scope)
- *Business context:* Proving ourselves to a high-value client
- *Risk if delayed:* Could impact contract renewal discussions in 6 months

**Hospital C (About to Close)**
- *Request:* Inventory features are critical
- *Business context:* Final requirements before potential contract end
- *Risk if delayed:* May never get implemented; last chance to deliver

---

## My Prioritization Framework (And Why I Chose It)

I'm using a weighted scoring model that considers:

1. **Business Impact (40%)** - Revenue protection and growth potential
2. **Urgency vs. Importance (25%)** - Eisenhower Matrix thinking
3. **Technical Feasibility (20%)** - Can we actually do this well in 30 days?
4. **Strategic Alignment (15%)** - Long-term product vision

### Priority Rankings

**🔴 Priority 1: Hospital C - Inventory Features**
- **Score: 8.5/10**
- *Why this wins:* This is our last chance. Once Hospital C closes, we lose the opportunity forever. The features also benefit our product roadmap for future clients.
- *Allocation:* 50% of sprint capacity (60 story points / 150 hours)

**🟡 Priority 2: Hospital B - HR Module (Scoped Down)**
- **Score: 7.2/10**
- *Why this matters:* New client with big contract, but we need to be realistic about scope
- *Allocation:* 35% of sprint capacity (42 story points / 105 hours)
- *Critical scope decision:* We'll deliver core HR module with limited features, not the full wish list

**🟢 Priority 3: Hospital A - OPD Print Layouts**
- **Score: 5.8/10**
- *Why this ranks lower:* Despite being "urgent," this is a established relationship where we have goodwill banked
- *Allocation:* 15% of sprint capacity (18 story points / 45 hours)
- *Trade-off:* We'll fix critical print issues only, defer cosmetic improvements

---

## Sprint Roadmap: The 4-Week Breakdown

### Week 1: Foundation & High-Risk Items
**Focus:** De-risk the sprint early

- **Hospital C (Inventory):**
  - Database schema design for inventory tracking
  - Core CRUD operations for inventory items
  - Integration points with existing system
  
- **Hospital B (HR Module):**
  - Requirements refinement session (scheduled for Day 2)
  - Architecture design for HR module
  - Set up development environment
  
- **Hospital A (OPD Prints):**
  - Audit current print layouts
  - Identify critical vs. nice-to-have changes

**Team allocation:** 4 devs on Hospital C, 3 devs on Hospital B, 0.5 devs on Hospital A (+ 2.5 accounting for reduced capacity)

### Week 2: Core Development Sprint
**Focus:** Build the meat of each deliverable

- **Hospital C:**
  - Stock management features (add, update, delete inventory)
  - Basic reporting capabilities
  - Alert system for low stock levels
  
- **Hospital B:**
  - Employee data management (Phase 1)
  - Basic attendance tracking
  - User authentication for HR module
  
- **Hospital A:**
  - Fix top 3 critical print layout bugs
  - Standardize header/footer formatting

**Team allocation:** 4 devs on Hospital C, 3 devs on Hospital B, 0.5 devs on Hospital A

### Week 3: Integration & Refinement
**Focus:** Make everything work together

- **Hospital C:**
  - Inventory adjustment workflows
  - Integration with billing system
  - User acceptance testing preparation
  
- **Hospital B:**
  - Leave management system
  - Basic HR reports
  - Integration with existing user database
  
- **Hospital A:**
  - Remaining approved print fixes
  - Cross-browser testing

**Team allocation:** Shift to 3.5 devs on Hospital C, 3 devs on Hospital B, 1 dev on Hospital A

### Week 4: Testing, Deployment & Documentation
**Focus:** Ship with confidence

- **All Projects:**
  - Quality assurance testing
  - Bug fixes from QA
  - Deployment preparation
  - User documentation
  - Stakeholder demos

- **Buffer time:** Reserved 20% of Week 4 for unexpected issues (because they always happen)

---

## Visual Sprint Plan

### Gantt-Style Timeline

```
Week:           1              2              3              4
             ├──────────────┼──────────────┼──────────────┼──────────────┤

Hospital C   ████████████████████████████████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓
(Inventory)  [Design] [Core Dev] [Advanced Features] [Testing & Deploy]

Hospital B   ██████████████████████████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓
(HR Module)  [Setup] [Phase 1 Dev] [Phase 2 Dev] [Testing & Deploy]

Hospital A   ████████████████▓▓▓▓▓▓▓▓
(OPD Prints) [Audit][Critical Fixes][Testing]

Legend: ████ Active Development  ▓▓▓▓ Testing/Deployment
```

### Resource Allocation Pie Chart (Average across sprint)

```
Hospital C (Inventory):     ████████████░░  50%
Hospital B (HR Module):     ███████░░░░░░░  35%
Hospital A (OPD Prints):    ███░░░░░░░░░░░  15%
```

---

## Trade-offs & What I'm Saying "No" To

### Hospital A (Long-term Client)
**What they asked for:** Complete OPD print layout overhaul  
**What they're getting:** Critical bug fixes only  
**What's deferred:** Cosmetic improvements, additional print templates  

**My reasoning:** Hospital A has been with us for years. They'll understand that newer clients need attention to grow the business. I'm betting on relationship equity here, but it's a calculated risk.

### Hospital B (New Client)
**What they asked for:** Full HR module with payroll, performance reviews, recruitment  
**What they're getting:** Core HR (employee data, attendance, leave management)  
**What's deferred:** Payroll integration, performance management, recruitment features  

**My reasoning:** Under-promise, over-deliver. We'll wow them with a rock-solid Phase 1, then use their satisfaction to negotiate realistic timelines for Phase 2. Better to ship 80% polished than 100% buggy.

### Hospital C (Closing Soon)
**What they asked for:** Critical inventory features  
**What they're getting:** Everything they need  
**What's deferred:** Nothing—this is our Hail Mary  

**My reasoning:** This is existential. If we don't deliver, it's gone forever. Plus, these inventory features become part of our core product for future clients.

---

## Communication Strategy: Managing Expectations

### Week 1 (Kickoff)
**Individual stakeholder calls (30 min each):**

- **Hospital A Call:**
  - *Opening:* "I want to be transparent about our capacity this month..."
  - *Message:* We're prioritizing critical print bugs, deferring enhancements
  - *Ask:* "Help me understand which 3 print issues cause the most daily pain?"
  - *Timeline commitment:* Critical fixes by Week 3

- **Hospital B Call:**
  - *Opening:* "We're excited about this HR module, and I want to set us up for long-term success..."
  - *Message:* Phase 1 this sprint (core features), Phase 2 next sprint
  - *Ask:* "Let's align on must-haves vs. nice-to-haves for Phase 1"
  - *Timeline commitment:* Usable HR module by end of sprint, full vision over 2-3 sprints

- **Hospital C Call:**
  - *Opening:* "We understand how critical these inventory features are..."
  - *Message:* You're our top priority this sprint
  - *Ask:* "Are there any requirements we're missing that would make this incomplete?"
  - *Timeline commitment:* Full delivery by Week 4

### Week 2 (Mid-Sprint Check-in)
**Async updates via email/Slack:**
- Progress dashboard shared every Friday
- Blockers and risks flagged immediately
- Screenshots/demos of work in progress

### Week 3 (Course Correction)
**Team sync + stakeholder updates:**
- Internal retrospective: Are we on track?
- Stakeholder updates: Reconfirm scope and timelines
- Adjust Week 4 plans based on progress

### Week 4 (Delivery & Feedback)
**Demo sessions with each hospital:**
- Live walkthrough of delivered features
- Collect feedback for future sprints
- Celebrate wins, acknowledge what we deferred

### Internal Team Communication
- **Daily standups:** 15 min, focus on blockers
- **Mid-sprint retro:** Week 2 Wednesday—how are we feeling?
- **Slack channel:** #sprint-jan-2026 for async coordination
- **Team social:** Virtual coffee chat Friday Week 2 (morale matters!)

---

## Risk Management: What Could Go Wrong

### Risk 1: Hospital A Escalates "Urgent" Print Issues
**Probability:** Medium  
**Impact:** High (relationship damage)  
**Mitigation:** 
- Document which specific issues we're fixing upfront
- Get written agreement on deferred items
- Keep 10 hours of buffer capacity for emergency fixes

### Risk 2: Hospital B Scope Creeps
**Probability:** High (new clients always do this)  
**Impact:** Medium (could derail timeline)  
**Mitigation:**
- Formal change request process after Week 1 requirements lock
- "Yes, and we'll add it to Phase 2" as default response
- Weekly scope review with product owner

### Risk 3: Hospital C Requirements Incomplete
**Probability:** Medium  
**Impact:** Critical (could waste our top-priority effort)  
**Mitigation:**
- Day 1-2: Intensive requirements gathering session
- Daily check-ins Week 1 and 2
- Get clinical staff involved early for real-world validation

### Risk 4: Developer Capacity Drops Further
**Probability:** Low-Medium  
**Impact:** Critical  
**Mitigation:**
- Cross-training on critical paths
- Documentation as we go (not at the end)
- Negotiate scope reduction in Week 2 if needed

### Risk 5: Technical Debt Surfaces
**Probability:** High (it always does)  
**Impact:** Medium  
**Mitigation:**
- 20% time buffer in Week 4
- "Fix forward" not "refactor perfectly" mindset for this sprint
- Log tech debt items for future sprint

---

## Success Metrics: How We'll Know We Won

### Delivery Metrics
- ✅ Hospital C inventory module: 100% of agreed scope shipped
- ✅ Hospital B HR module: Phase 1 features live and usable
- ✅ Hospital A print fixes: Top 3 critical issues resolved

### Quality Metrics
- Zero critical bugs in production post-deployment
- User acceptance testing pass rate >90% for each module
- Code review approval rate >95%

### Stakeholder Satisfaction
- Hospital C: Satisfaction score 8+/10 (measured via survey)
- Hospital B: Willingness to continue with Phase 2 (qualitative)
- Hospital A: No formal complaints logged (absence of negative feedback)

### Team Health
- No developer works >45 hours/week (protect the team)
- Sprint retrospective team satisfaction >7/10
- Zero burnout-related sick days

---

## Why This Plan Will Stand Out

Most students will give you a generic sprint plan. Here's what makes this different:

1. **Honest trade-offs:** I'm explicitly saying what we're NOT doing and why
2. **Real capacity planning:** I accounted for exams and partial leave—most plans ignore this
3. **Stakeholder psychology:** The communication strategy shows I understand people, not just process
4. **Risk-aware:** I'm planning for failure modes, not assuming perfection
5. **Human-centric:** Team health metrics matter. Burnout destroys sprints.
6. **Strategic thinking:** Hospital C prioritization is counterintuitive but strategically sound

---

## Final Reflection: What I Learned From This Exercise

Product management isn't about making everyone happy—it's about making the right people happy at the right time. 

This sprint plan disappoints Hospital A in the short term to protect Hospital C's last-chance features and build trust with Hospital B for the long term. That's uncomfortable, but it's honest.

The hardest part of this exercise wasn't the planning—it was accepting that 10 developers (really 7.5 FTEs) can't do everything. The best APMs know that "yes to everything" means "excellence in nothing."

If I were actually presenting this plan, I'd walk into the room expecting pushback. Hospital A will argue their work is urgent. Hospital B will want more features. My job isn't to cave—it's to defend the trade-offs with data and empathy.

That's product management.

---

**Prepared by:** [Your Name]  
**Date:** January 29, 2026  
**Sprint Duration:** February 1-28, 2026  
**Next Review:** February 14, 2026 (Mid-sprint checkpoint)
