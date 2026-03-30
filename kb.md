# The Oracle — Knowledge Base
## Product: Self-Serve Quoting (Benefits Insurance)
## Platform: ThreeFlow — Benefits Insurance Placement Platform
Last updated: March 2026

> **CRITICAL CONTEXT**: ThreeFlow is a **benefits insurance** platform used by brokers and carriers to manage group insurance placements. Self-Serve Quoting is specifically about **benefits insurance quoting** — dental, vision, life, disability, and similar group coverage products. This has absolutely nothing to do with freight, logistics, shipping, transportation, or any other industry.

---

## Table of Contents
1. [What is Self-Serve Quoting](#what-is-self-serve-quoting)
2. [Who Can Use It](#who-can-use-it)
3. [Pilot Program](#pilot-program)
4. [Value & Benefits](#value--benefits)
5. [How It Works](#how-it-works)
6. [Quoting Methods](#quoting-methods)
7. [Quote Statuses](#quote-statuses)
8. [Step-by-Step Guides](#step-by-step-guides)
9. [Error Handling](#error-handling)
10. [Common Questions & Misconceptions](#common-questions--misconceptions)
11. [Quick Reference](#quick-reference)

---

# What is Self-Serve Quoting

Self-Serve Quoting is a ThreeFlow feature that gives approved strategic brokers and General Agents (GAs) the ability to start, update, and submit carrier quotes for benefits insurance products directly inside ThreeFlow — without waiting on carrier turnaround.

Strategic users access the same quoting tools carriers use today, within the existing carrier workflow. There is no new system to learn, no side workflows, and no external tools required. Execution happens where the work already lives — inside ThreeFlow.

Self-Serve Quoting was built to solve three problems that strategic brokers face daily:
- Waiting on carrier turnaround while client deadlines approach
- Coordinating quotes over email, outside the platform, creating version control issues
- Spending time tracking quote status instead of advising clients

Other names this feature may be referred to as: strategic quoting autonomy, broker self-serve, broker quoting, self service quoting, SSQ, self quoting, broker quote management.

---

# Who Can Use It

Self-Serve Quoting is available to **approved strategic users** — national brokers and General Agents (GAs) at high-volume firms who have been granted the `quote management` permission by ThreeFlow.

Access is **not** available to:
- General broker population
- Carriers
- Users without the `quote management` permission
- Anyone outside the current pilot participant list

If someone believes they should have access but doesn't, they should contact their ThreeFlow account team. Attempting to modify URLs to access restricted pages will trigger a route guard and redirect to the My Quotes page.

Self-Serve Quoting applies to both **national brokers and GAs** — it is not limited to one audience type.

---

# Pilot Program

## Overview
Self-Serve Quoting launched as a pilot on **April 6, 2026**. The pilot runs for **8 weeks** through **May 30, 2026**. It is a P2 priority feature targeted at national brokers.

The pilot is not testing demand — brokers have already asked for this capability. The pilot is focused on validating whether the solution fully solves the problem, whether behavior shifts from carrier-dependent to self-serve, and what is required to make this the default workflow.

## Who is in the Pilot

The pilot is limited to four broker organizations:

**The Cason Group**
- Contact: Viri Schoenfeld
- Pilot users: Drew Brickwedde, Josh Gregory, Nate Parrish, Rob Giovanelli

**Alliant West — Programs Team**
- Contact: Laura Calnan
- Pilot users: Erica Smyth (additional users TBD)

**Brown & Brown (NMGA and local offices)**
- Contact: Viri Schoenfeld
- Pilot users: TBD

**MMA — NC (Marsh McLennan)**
- Contact: Addie Marinkovich (Green)
- Pilot users: Krissy Moscatelli, Liz Szychowicz, Abagail Bilyeu, Chris Kveseth, Angela Wright

## How to Get Access / Join the Pilot

Self-Serve Quoting is currently limited to the four pilot organizations listed above. It is not available to brokers outside this list yet. If a partner or broker wants access, they should be directed to their ThreeFlow account team or post in `#temp-broker-self-serve-quoting-feedback` to flag interest for future expansion. There is no self-service way to get access during the pilot.

## Pilot Volume Expectations

Approximately 1,000 coverages will be sent to market during the pilot, primarily driven by Brown & Brown. Early in the pilot, submission volume may be inconsistent as users learn the product. Utilization should increase over time.

## Pilot Feedback Channel

Slack channel for pilot feedback: `#temp-broker-self-serve-quoting-feedback`

---

# Value & Benefits

## For Strategic Brokers

**Move faster when timelines matter**
Client deadlines don't move. Strategic brokers no longer have to wait on carrier turnaround to keep quotes progressing. They can start, update, and submit quotes on their own timeline.

**Keep everything in one place**
No more chasing documents over email or tracking updates across multiple sources. Quotes, updates, and submissions stay inside ThreeFlow — one source of truth for everyone.

**Stay aligned with carriers**
Strategic brokers work within the existing carrier quoting experience, using the same tools and workflows carriers use. Carriers keep full visibility throughout the process.

## For Carriers

Carriers retain full visibility and control over their quotes at all times. Self-serve quoting helps brokers move faster while keeping all execution inside ThreeFlow. Quotes submitted by brokers on a carrier's behalf remain visible within the carrier's existing workflow. Carriers can edit broker-submitted quotes and remain key partners in review and alignment. Less back-and-forth means fewer version issues and clearer alignment.

## For ThreeFlow

Self-Serve Quoting drives more quotes through the platform, reduces work that happens over email, and gives ThreeFlow clearer visibility across strategic accounts. It moves ThreeFlow from managing placements to helping make them happen — becoming part of the daily workflow for high-volume national brokers rather than just a step in the process.

---

# How It Works

The Self-Serve Quoting workflow has four stages:

**Stage 1: Setup**
The broker finishes setting up the marketing event on the broker site.

**Stage 2: Start Quote**
The broker navigates to the product comparison page and clicks the "Start Quote" button for a specific carrier. The broker is then authenticated into the carrier site for that project and can begin quoting using smart proposals, ThreeFlow Assist, copy plan design, or manual entry.

**Stage 3: Process & Review**
Documents are processed by ThreeFlow AI (1–5 minutes). The broker reviews the AI output, corrects any Action Needed items, and confirms rates and plan design before submitting.

**Stage 4: Submit & Return**
The broker submits the quote. A confirmation email is sent automatically. The broker clicks Back to return to the product comparison page, where the submitted quote populates the correct carrier column. All edits and submissions are documented on ThreeFlow.

Brokers can work across multiple carriers simultaneously — while one carrier's documents are processing, they can start a quote for another carrier using the carrier dropdown.

---

# Quoting Methods

Strategic users with the `quote management` permission have access to the following quoting methods:

**Smart Proposals**
Uses ThreeFlow AI to extract rate and plan design information from an uploaded proposal document (PDF, .doc, or .xls — max 20MB) and automatically populate the quote. The fastest method for new business quoting.

**Smart Renewals**
Same process as smart proposals but used for renewing existing business rather than new coverage. The broker uploads renewal documents or enters data manually prior to submission. Note: attach renewal (processing renewals via email) is not available in v1.

**ThreeFlow Assist**
An AI-assisted quoting option with longer processing time — up to 48 hours. Not recommended for time-sensitive workflows. ThreeFlow Assist is optional and can be skipped entirely. If a broker accidentally sends to ThreeFlow Assist and wants to undo it, they must contact support.

**Copy Plan Design**
Allows the broker to populate missing values by copying plan design from an existing quote. Available on the plan design page via the "Populate missing values from" dropdown. Reduces manual entry for similar quotes across carriers.

**Manual Quoting**
The broker enters rates and plan design data manually on the carrier site. Used when AI output is incomplete or when specific fields need to be entered without AI assistance.

**User defaults are not available** for strategic users in v1.

---

# Quote Statuses

| Status | Meaning | What to do |
|---|---|---|
| Processing | ThreeFlow AI is extracting rate and plan design data from the uploaded document | Wait 1–5 minutes |
| Ready to review | AI successfully found and entered rates | Review carefully — AI can make mistakes — then submit |
| Action needed | AI could not populate one or more required fields | Click Edit details, enter missing data manually, then submit |
| Submitted | Quote has been submitted to the carrier | Nothing — done |
| In progress | Quote is active but not yet submitted | Review and submit |

If a quote has not been submitted within 1 hour of processing completing, the broker receives an automatic reminder email to review and submit.

---

# Step-by-Step Guides

## [GUIDE-001] Starting a Quote Using Smart Proposals

Use this for new coverage that has not been quoted yet for a carrier.

1. Finish setting up the marketing event on the broker site
2. Navigate to the product comparison page
3. Click **Start Quote** for the carrier you want to quote (e.g., Lincoln)
4. You will be authenticated into the carrier site. The Start Quote modal opens
5. Upload your proposal document(s) — PDF, .doc, or .xls, max 20MB
6. Click **Send to ThreeFlow**
7. All products show **Processing** status. While processing, you can start a quote for another carrier by selecting them from the carrier dropdown and clicking Go. Carriers are listed alphabetically
8. Once processing completes, products show **Ready to review** or **Action needed**
9. Review rates and plan design. Click **Edit details** to correct any Action Needed items. You can also use Copy Plan Design or enter data manually
10. Click **Submit quote**. An email confirmation is sent automatically
11. Click **Back** from the carrier site banner to return to the product comparison page. Your submitted quote populates the correct carrier column

## [GUIDE-002] Updating a Quote Using Smart Proposals

Use this to revise an existing in-progress quote.

1. Navigate to the product comparison page
2. Click **Update Quote** for the carrier
3. The **Caution: AI Will Overwrite Edits** modal appears
4. Check the box confirming you understand AI processing will remove all existing edits
5. Click **Continue**
6. Upload your updated proposal document and click **Send to ThreeFlow**
7. Follow the same processing, review, and submission steps as the start quote flow

**Warning**: AI processing in the update flow overwrites ALL previous edits including manual changes. This cannot be undone. If you want to preserve existing edits, enter the new data manually instead.

## [GUIDE-003] Starting or Updating a Renewal

Use this for renewing existing business.

1. Navigate to the product comparison page
2. Click **Start Renewal** or **Update Renewal** for the carrier
3. The renewal modal opens. Upload renewal documents or enter data manually
4. Follow the same processing, review, and submission steps as smart proposals

Note: Attach renewal (processing renewals via email) is not available in v1.

## [GUIDE-004] Switching Between Carriers

1. On the carrier site, locate the **Carrier quote** dropdown at the top of the page
2. Select the carrier you want to switch to
3. Click **Go**

Carriers are listed alphabetically. You can switch at any point during the workflow, including while documents are still processing for another carrier.

## [GUIDE-005] Fixing an Action Needed Status

1. Click **Edit details** next to the product showing Action Needed
2. The rates or plan design page opens with missing fields highlighted
3. Enter the required information manually
4. Return to the My Quotes page
5. Submit the quote

---

# Error Handling

## [ERROR-001] Cannot Open Quote

**What you see**: Clicked Start Quote or Update Quote but received an error instead of being taken to the carrier site.

**Error message**: "ThreeFlow was unable to open the quote. Try again; if the problem persists, contact support."

**What to do**: Retry once. If the problem persists, click the **contact support** button in the error message to email support directly.

## [ERROR-002] Carrier Dropdown Won't Load

**What you see**: Opened the carrier dropdown but no carriers appear.

**Error message**: "ThreeFlow was unable to show invited carriers. Try again; if the problem persists, contact support."

**What to do**: Retry once. If the problem persists, use the contact support button.

## [ERROR-003] Cannot Switch Carriers

**What you see**: Selected a carrier and clicked Go but nothing happened or an error appeared.

**Error message**: "ThreeFlow was unable to switch carriers. Try again; if the problem persists, contact support."

**What to do**: Retry once. If the problem persists, use the contact support button.

## [ERROR-004] Access Denied

**What you see**: Tried to access a page and got redirected, or clicked something and received an access error.

**Error message**: "You do not have access to view this content."

**What to do**: You have hit a route guard. You will be redirected to the My Quotes page. If you believe you should have access, contact your ThreeFlow account team. Do not attempt to modify the URL.

## [ERROR-005] Accidentally Sent to ThreeFlow Assist

**What you see**: Products are now waiting for ThreeFlow Assist processing (up to 48 hours) but you didn't intend to use it.

**What to do**: Contact support immediately via `#customer-support`. This cannot be self-serviced or undone by the broker.

---

# Common Questions & Misconceptions

## Is this a new system I have to learn?
No. Strategic users access carrier quoting through the existing ThreeFlow product comparison page — the same place they already work. The entry point and tools are already familiar. No new system, no new login, no new training required.

## Do carriers lose control when brokers submit quotes?
No. Carriers retain full visibility and control at all times. They can see all broker activity, edit broker-submitted quotes, and remain key partners in review and alignment. Nothing is hidden from carriers.

## Does AI auto-submit quotes?
No. ThreeFlow AI processes and populates quote data, but never auto-submits. Every quote shows either Ready to Review or Action Needed after processing. The broker must review and manually submit.

## Is ThreeFlow Assist the same as smart proposals?
No. Smart proposals process documents quickly (1–5 minutes) and are the recommended method for self-serve quoting. ThreeFlow Assist has a longer processing time (up to 48 hours) and is better suited for complex scenarios where the broker is willing to wait. ThreeFlow Assist is optional — it can always be skipped.

## Can I use self-serve quoting for renewals?
Yes. Smart renewals support renewing business. The workflow is the same as smart proposals. The only limitation is that attach renewal (processing renewals via email) is not available in v1.

## What if AI makes a mistake on my quote?
ThreeFlow explicitly warns that AI can make mistakes. After processing, review all rates and plan design carefully before submitting. Products that need attention are flagged as Action Needed. You can always correct AI output manually before submitting.

## Can I quote multiple carriers at the same time?
Yes. While one carrier's documents are processing, start a quote for another carrier using the carrier dropdown. Parallel quoting across multiple carriers is fully supported.

## Will I get confirmation when I submit?
Yes. An email confirmation is sent automatically when a product is submitted. The quote edits screen also captures name, date, timestamp, and submitted products.

## Who do I contact if something isn't working?
Ask in `#customer-support` on Slack or use the **contact support** button that appears in error messages. For pilot-specific feedback, use `#temp-broker-self-serve-quoting-feedback`.

---

# Quick Reference

## Key Actions

| Task | Where to start |
|---|---|
| Start a new quote | Product comparison page → Start Quote |
| Update an existing quote | Product comparison page → Update Quote |
| Start a renewal | Product comparison page → Start Renewal |
| Switch carriers mid-workflow | Carrier quote dropdown → select carrier → Go |
| Fix an Action Needed item | Edit details → enter missing fields → submit |
| Get help | #customer-support or contact support button |
| Pilot feedback | #temp-broker-self-serve-quoting-feedback |

## Quote Statuses at a Glance

| Status | Action needed? |
|---|---|
| Processing | Wait |
| Ready to review | Review then submit |
| Action needed | Enter missing data then submit |
| Submitted | None — done |
| In progress | Review and submit |

## Quoting Methods at a Glance

| Method | Best for | Speed |
|---|---|---|
| Smart proposals | New business, document available | Fast (1–5 min) |
| Smart renewals | Renewing business, document available | Fast (1–5 min) |
| Manual quoting | Rate-only updates, specific field changes | Immediate |
| Copy plan design | Similar quotes across carriers | Immediate |
| ThreeFlow Assist | Complex scenarios, not time-sensitive | Slow (up to 48 hrs) |
