# The Oracle — Knowledge Base
## Product: Self-Serve Quoting (Benefits Insurance)
## Platform: ThreeFlow — Benefits Insurance Placement Platform
Last updated: March 2026

> **IMPORTANT**: ThreeFlow is a benefits insurance platform. Self-Serve Quoting is specifically about insurance benefits quoting for brokers, GAs, and carriers. This has nothing to do with freight, logistics, shipping, or any other industry.

---

## Table of Contents
1. [Product Overview](#product-overview)
2. [Pilot Details](#pilot-details)
3. [Permission & Access](#permission--access)
4. [Process Guides](#process-guides)
5. [Step Variations & Edge Cases](#step-variations--edge-cases)
6. [Error Scenarios](#error-scenarios)
7. [Common Misconceptions](#common-misconceptions)
8. [Q&A Library](#qa-library)
9. [Quick Reference](#quick-reference)

---

# Product Overview

## What is Self-Serve Quoting?

**Definition**: Self-Serve Quoting gives approved strategic brokers and General Agents (GAs) the ability to start, update, and submit carrier quotes directly inside ThreeFlow — without waiting on carrier turnaround.

**Key point**: Strategic users access the same quoting tools carriers use today, within the existing carrier workflow. No new system. No side workflows. Execution happens where the work already lives.

**Common terminology**:
- Self-Serve Quoting
- Strategic quoting autonomy
- Broker self-serve
- SSQ (informal)

## What problem does it solve?

Three core problems eliminated:
1. **Deadline stress** — Brokers no longer wait on carrier turnaround to keep quotes progressing
2. **Off-platform coordination** — No more emailing carriers, tracking updates manually, or collecting documents outside ThreeFlow
3. **Status chasing** — Time spent tracking progress is replaced by time spent advising clients

## What are the core value propositions?

**For strategic brokers:**
- Move faster when timelines matter — client deadlines don't move, carrier turnaround no longer blocks progress
- Keep everything in one place — quotes, updates, and submissions stay inside ThreeFlow
- Stay aligned with carriers — work within the existing carrier quoting experience using the same tools

**For carriers:**
- Full visibility into all broker-submitted quotes
- Remain key partners in review and alignment
- Less back-and-forth means fewer version issues and clearer alignment

**For ThreeFlow:**
- More quotes move through the system
- Less work happens over email
- Clearer visibility across strategic accounts
- Moves from managing placements to helping make them happen

## Who is this for?

**Primary audience**: National brokers and General Agents (GAs) — specifically approved strategic users at high-volume firms.

**Current pilot participants**:
- Alliant Ben West Programs Team
- The Cason Group
- Brown & Brown (NMGA and local offices)
- MMA - NC

**Not available to**: General broker population, carriers, or unapproved users. Access is controlled via the `quote management` permission.

---

# Pilot Details

## [PILOT-001] Pilot Overview

**Launch date**: April 6, 2026
**Duration**: 8 weeks (April 6 — May 30, 2026)
**Priority**: P2
**Audience**: National brokers
**Slack channel for feedback**: `#temp-broker-self-serve-quoting-feedback`

## [PILOT-002] Pilot Participants

| Broker | Contact | Pilot Users |
|---|---|---|
| The Cason Group | Viri Schoenfeld | Drew Brickwedde, Josh Gregory, Nate Parrish, Rob Giovanelli |
| Alliant West - Programs Team | Laura Calnan | Erica Smyth + additional users TBD |
| Brown & Brown (NMGA) | Viri Schoenfeld | TBD |
| MMA - NC | Addie Marinkovich (Green) | Krissy Moscatelli, Liz Szychowicz, Abagail Bilyeu, Chris Kveseth, Angela Wright |

## [PILOT-003] How to Join the Pilot

**Question**: My partner/broker wants to use Self-Serve Quoting. How do they get access?

**Answer**: Self-Serve Quoting is currently limited to approved pilot participants only. Access is not available to the general broker population yet. Direct them to their ThreeFlow account team or post in `#temp-broker-self-serve-quoting-feedback` to flag interest for future expansion.

## [PILOT-004] Pilot Volume Expectations

**Expected volume**: ~1,000 coverages will be sent to market during the pilot, primarily driven by Brown & Brown.

**What to expect**:
- Early in the pilot, submission volume may be inconsistent as users learn the product
- Irregular spikes or drop-offs are expected — volume is not linear
- Utilization should increase over time as users become more familiar

## [PILOT-005] Pilot Exit Criteria

The pilot is considered successful when:
1. Brokers can independently start, submit, and update quotes without assistance
2. Brokers report the quoting workflow is clear and usable
3. Brokers primarily use the intended quoting workflow rather than manual or external processes
4. Brokers understand where quote data originates
5. Pilot brokers successfully run meaningful quoting volume through ThreeFlow

---

# Permission & Access

## [ACCESS-001] Who Can Use Self-Serve Quoting?

**Permission required**: `quote management`

**Who has it**: Approved strategic users only. Access is controlled by ThreeFlow and currently limited to pilot participants.

**Question**: I think I should have access but don't. What do I do?

**Answer**: Contact your ThreeFlow account team. Do not attempt to modify URL or access pages directly — route guards will redirect you to the My Quotes page and show an access error.

## [ACCESS-002] What Can Strategic Users Do?

Strategic users with `quote management` permission can:
- Start quotes (new coverage)
- Update quotes (existing coverage)
- Submit quotes to carriers
- Switch between carrier quotes in the same project
- Use smart proposals, smart renewals, ThreeFlow Assist, copy plan design, and manual quoting

Strategic users **cannot**:
- Access user defaults (not available in v1)
- Process renewals via email (attach renewal not in scope for v1)
- Access carrier-only functionality

## [ACCESS-003] Carrier Visibility

**Question**: Can carriers still see what brokers are doing?

**Answer**: Yes. Carriers retain full visibility and control. All broker activity is visible within the carrier's existing workflow. Carriers can edit broker-submitted quotes and remain key partners in review and alignment.

---

# Process Guides

## [PROCESS-001] Starting a Quote (Smart Proposals)

**When to use**: New coverage that hasn't been quoted yet for a carrier.

**Steps**:
1. Finish setting up the marketing event on the broker site
2. Navigate to the product comparison page
3. Click **Start Quote** for the specific carrier (e.g., Lincoln)
4. You'll be authenticated into the carrier site. The Start Quote modal opens
5. Upload proposal document(s) — PDF, .doc, or .xls, max 20MB
6. Click **Send to ThreeFlow**
7. All products show **Processing** status. While processing, start quotes for other carriers using the carrier dropdown — carriers listed alphabetically
8. Once processing completes, products show **Ready to review** or **Action needed**
9. Review rates and plan design. Use **Edit details** for action needed items. Optionally use copy plan design or manual entry
10. Click **Submit quote**. Email confirmation sent automatically
11. Click **Back** from carrier site banner to return to product comparison page. Submitted quote populates the correct carrier column

**Note**: If the quote has not been submitted within 1 hour of processing, a reminder email is sent automatically.

## [PROCESS-002] Updating a Quote (Smart Proposals)

**When to use**: Revising an existing in-progress quote.

**Steps**:
1. Navigate to the product comparison page
2. Click **Update Quote** for the carrier
3. The **Caution: AI Will Overwrite Edits** modal appears
4. Check the box confirming AI processing will remove existing edits
5. Click **Continue**
6. Upload updated proposal document and click **Send to ThreeFlow**
7. Follow the same processing, review, and submission steps as start quote

**Warning**: AI processing in the update flow will overwrite ALL previous edits. This cannot be undone. Review carefully before proceeding.

## [PROCESS-003] Smart Renewals

**When to use**: Renewing existing business (not new coverage).

**How it differs from smart proposals**:
- Access via product comparison page → Start Renewal or Update Renewal modal
- Same upload and review process as smart proposals
- Can upload renewal documents or manually update data prior to submission

**Not available**: Attach renewal (processing renewals via email) is not in scope for v1.

## [PROCESS-004] Switching Between Carriers

**How**: Use the **Carrier quote** dropdown at the top of the carrier site page → select carrier → click **Go**

**When**: Any point during the workflow, including while documents are still processing for another carrier

**Note**: Carriers are listed alphabetically in the dropdown.

## [PROCESS-005] Submitting a Quote

**After review**:
- Click **Submit quote** — email confirmation sent automatically
- Quote edits screen captures: name, date, timestamp, submitted products
- Click **Back** from carrier site banner to return to product comparison page
- Submitted quote populates the correct carrier column

---

# Step Variations & Edge Cases

## [EDGE-001] Multiple Carriers, Same Project

**Scenario**: Broker needs to quote multiple carriers simultaneously.

**Answer**: While documents are processing for one carrier, start a quote for another carrier using the carrier dropdown. This allows parallel quoting across multiple carriers without waiting for each to complete sequentially.

## [EDGE-002] ThreeFlow Assist Offered During Flow

**Scenario**: ThreeFlow Assist option appears during quoting.

**Answer**: ThreeFlow Assist is optional and can be skipped. It has up to 48-hour processing time — not practical for time-sensitive workflows. For most self-serve quoting scenarios, smart proposals or manual quoting will be faster.

**Warning**: If you accidentally send to ThreeFlow Assist and want to undo it, contact support. You cannot self-service this reversal.

## [EDGE-003] Action Needed After Processing

**Scenario**: Products show **Action needed** status after processing completes.

**Answer**:
1. Click **Edit details** next to the product showing Action needed
2. Rates or plan design page opens with missing fields highlighted
3. Enter required information manually
4. Return to My Quotes page and submit

## [EDGE-004] Quote Not Submitted After Processing

**Scenario**: Processing completed but quote hasn't been submitted.

**Answer**: A reminder email is sent automatically after 1 hour. Review and submit from the carrier site. Do not re-upload documents — the data is already processed.

## [EDGE-005] Updating a Quote That Already Has Manual Edits

**Scenario**: Quote has manual edits and a new proposal document arrives.

**Warning**: Using **Update Quote** with AI will overwrite ALL previous manual edits. If you want to preserve existing edits, enter the new data manually instead of using the AI update flow.

## [EDGE-006] Copy Plan Design

**When to use**: Completing quotes faster by copying plan design from an existing quote.

**How**: Available on the plan design page — use **Populate missing values from** dropdown to select a plan design to copy.

**Benefit**: Reduces manual entry for similar quotes across carriers.

---

# Error Scenarios

## [ERROR-001] Cannot Open Quote from Product Comparison Page

**Symptom**: Clicked Start Quote or Update Quote but nothing happened, or received an error.

**Error message**: "ThreeFlow was unable to open the quote. Try again; if the problem persists, contact support."

**Action**: Retry once. If it persists, use the **contact support** button in the error message — this emails support directly.

## [ERROR-002] Carrier Dropdown Fails to Load

**Symptom**: Opened carrier dropdown but carriers don't appear.

**Error message**: "ThreeFlow was unable to show invited carriers. Try again; if the problem persists, contact support."

**Action**: Retry once. If it persists, contact support via the button in the error message.

## [ERROR-003] Carrier Switch Fails

**Symptom**: Selected a new carrier from dropdown and clicked Go, but nothing happened or error appeared.

**Error message**: "ThreeFlow was unable to switch carriers. Try again; if the problem persists, contact support."

**Action**: Retry once. If it persists, contact support via the button in the error message.

## [ERROR-004] Access Denied / Route Guard

**Symptom**: Tried to access a page and got redirected, or clicked something and received an access error.

**Error message**: "You do not have access to view this content."

**Action**: You've hit a route guard. You'll be redirected to the My Quotes page for the project/carrier you were already accessing. If you believe you should have access, contact your ThreeFlow account team — do not attempt to modify the URL.

## [ERROR-005] ThreeFlow Assist Accidentally Triggered

**Symptom**: Sent products to ThreeFlow Assist unintentionally. Now waiting up to 48 hours.

**Action**: Contact support — this cannot be self-serviced. Use the `#customer-support` Slack channel or email support directly.

---

# Common Misconceptions

## [MISC-001] "Self-Serve Quoting is a new system I have to learn"

**Reality**: No new system. Strategic users access carrier quoting through the existing ThreeFlow product comparison page — the same place they already work. The entry point and tools are already familiar.

## [MISC-002] "Carriers lose control when brokers submit quotes"

**Reality**: Carriers retain full visibility and control. They can see all activity, edit broker-submitted quotes, and remain key partners in review and alignment. Nothing is hidden from carriers.

## [MISC-003] "AI-submitted quotes are final and don't need review"

**Reality**: AI can make mistakes. ThreeFlow explicitly warns users after processing. Every quote shows either **Ready to review** or **Action needed** — the strategic must review and confirm before submitting. The system never auto-submits.

## [MISC-004] "I can use Self-Serve Quoting for email-based renewals"

**Reality**: Attach renewal (processing renewals via email) is not available in v1. Renewals must be uploaded as documents or entered manually on the carrier site.

## [MISC-005] "User defaults work the same as for carriers"

**Reality**: User defaults are not available for strategic users in v1. This may slow down strategics who rely on defaults for repetitive data entry — this is a known limitation being evaluated post-pilot.

## [MISC-006] "ThreeFlow Assist is the fastest quoting method"

**Reality**: ThreeFlow Assist has up to 48-hour processing time. For time-sensitive workflows, smart proposals or manual quoting are faster. ThreeFlow Assist is optional and can be skipped entirely.

---

# Q&A Library

**Q: What is self-serve quoting?**
A: Self-serve quoting lets approved strategic brokers and GAs start, update, and submit carrier quotes directly inside ThreeFlow without waiting on carrier turnaround. It uses the same quoting tools carriers use today — no new system required.

**Q: Who can use self-serve quoting?**
A: Approved strategic users with the `quote management` permission. Currently limited to pilot participants: Alliant Ben West Programs Team, The Cason Group, Brown & Brown (NMGA), and MMA - NC.

**Q: Does this apply to GAs?**
A: Yes. Self-serve quoting is designed for both national brokers and General Agents (GAs) who are approved strategic users.

**Q: What quoting methods are available?**
A: Smart proposals, smart renewals, ThreeFlow Assist, copy plan design, and manual quoting. User defaults are not available in v1.

**Q: Does self-serve quoting work for renewals?**
A: Yes — smart renewals support renewing business. Note: attach renewal (processing via email) is not available in v1. Documents must be uploaded or data entered manually.

**Q: Will I get confirmation when a quote is submitted?**
A: Yes. Email confirmation sent automatically. The quote edits screen also captures name, date, timestamp, and submitted products.

**Q: What do the quote statuses mean?**
- **Processing** — AI is extracting rate and plan design data from your uploaded document
- **Ready to review** — AI found and entered rates. Review before submitting — AI can make mistakes
- **Action needed** — AI couldn't populate required fields. Enter missing data manually before submitting
- **Submitted** — Quote submitted to carrier
- **In progress** — Quote active but not yet submitted

**Q: Can I quote multiple carriers at the same time?**
A: Yes. While one carrier's documents are processing, start a quote for another carrier using the carrier dropdown. Parallel quoting across multiple carriers is supported.

**Q: What if I need help during the pilot?**
A: Ask in `#customer-support` or use the contact support button in any error message. For pilot-specific feedback, use `#temp-broker-self-serve-quoting-feedback`.

---

# Quick Reference

| Task | Where to start |
|---|---|
| Start a new quote | Product comparison page → Start Quote |
| Update existing quote | Product comparison page → Update Quote |
| Switch carriers | Carrier dropdown → select carrier → Go |
| Fix action needed | Edit details → enter missing fields → submit |
| Get help | #customer-support or contact support button |
| Pilot feedback | #temp-broker-self-serve-quoting-feedback |

| Status | Meaning | Action needed? |
|---|---|---|
| Processing | AI working | Wait |
| Ready to review | AI succeeded | Review then submit |
| Action needed | AI incomplete | Enter missing data then submit |
| Submitted | Done | None |
| In progress | Not yet submitted | Review and submit |
