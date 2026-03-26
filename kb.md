# The Oracle — Knowledge Base
## Product: Self-Serve Quoting
Last updated: March 2026

---

## PITCH & POSITIONING

**Topic: What is self-serve quoting?**
Self-serve quoting gives approved strategic brokers and GAs the ability to start, update, and submit carrier quotes directly inside ThreeFlow — without waiting on carrier turnaround. Strategic users access the same quoting tools carriers use today, all within the existing carrier workflow. No new system. No side workflows. Just execution where the work already lives.

**Topic: What problem does self-serve quoting solve?**
Strategic brokers are accountable for client timelines but have historically depended on carrier turnaround to move quotes forward. This creates three core problems: deadline stress when carriers are slow to respond, off-platform coordination that causes version control issues and misalignment, and time spent tracking quote status instead of advising clients. Self-serve quoting eliminates the waiting and brings execution back inside ThreeFlow.

**Topic: What are the core value propositions?**
There are three headline benefits. First, brokers can move faster when timelines matter — client deadlines don't move, and now strategic brokers don't have to wait on carrier turnaround to keep quotes progressing. Second, everything stays in one place — no more chasing documents over email or tracking updates across multiple sources. Third, brokers stay aligned with carriers — strategics work within the existing carrier quoting experience using the same tools and workflows, so carriers keep full visibility.

**Topic: How does self-serve quoting benefit ThreeFlow as a business?**
Self-serve quoting drives more quotes through the platform, reduces work that happens over email, and gives ThreeFlow clearer visibility across strategic accounts. It moves ThreeFlow from managing placements to helping make them happen — becoming part of the daily workflow for high-volume national brokers, not just a step in the process.

**Topic: Who is self-serve quoting for?**
Self-serve quoting is designed for national brokers and General Agents (GAs) — specifically approved strategic users at high-volume firms. The pilot is launching with Alliant Ben West Programs Team, The Cason Group, Brown & Brown (NMGA and local offices), and MMA - NC.

---

## FEATURE COMPARISONS

**Topic: Self-serve quoting vs. the old workflow**
Previously, strategic brokers coordinated quoting by emailing carriers, tracking updates manually, and collecting proposal documents off-platform. This created version control issues, back-and-forth delays, and higher risk of misalignment. With self-serve quoting, brokers start, update, and submit quotes directly inside ThreeFlow using the same tools carriers use — no email coordination, no manual tracking, no side workflows.

**Topic: What quoting methods are available to strategic users?**
Strategic users with the quote management permission have access to smart proposals, smart renewals, ThreeFlow Assist, copy plan design, and manual quoting. User defaults are not available in this first version.

**Topic: Smart proposals vs. manual quoting vs. ThreeFlow Assist**
Smart proposals use AI to extract rate and plan design information from uploaded proposal documents and populate the quote automatically. Manual quoting allows the strategic to enter or copy plan design data themselves. ThreeFlow Assist is an AI-assisted option that processes quotes but has a longer turnaround — up to 48 hours — making it less suited for time-sensitive workflows. Strategics are expected to primarily use smart proposals and manual quoting during the pilot.

**Topic: What's the difference between start quote and update quote?**
Start quote is used to initiate a new quote for a carrier that hasn't been quoted yet. Update quote is used to revise an existing in-progress quote. The update quote flow includes an additional "Caution: AI will overwrite edits" modal that requires the strategic to acknowledge that AI processing will remove previous edits before continuing. After that acknowledgment, the processing, review, and submission steps are identical to the start quote flow.

**Topic: Are smart renewals different from smart proposals?**
Smart renewals follow the same general flow as smart proposals but are used for renewing business rather than new coverage. The strategic accesses the carrier site from the product comparison page, and the Start Renewal or Update Renewal modal opens. The strategic can upload renewal documents or manually update data prior to submission. Note: attach renewal (processing renewals via email) is not available in this first version.

---

## OBJECTION HANDLING

**Topic: Won't carriers lose control of their quotes?**
No. Carriers retain full visibility and control over their quotes throughout the process. Self-serve quoting is built within the existing carrier quoting experience — strategics are authenticated into the carrier site and work within that same framework. Carriers can see all activity, edit broker-submitted quotes, and remain key partners in review and alignment.

**Topic: What if the AI makes mistakes when processing quotes?**
ThreeFlow explicitly warns users that AI can make mistakes. After smart proposal or ThreeFlow Assist processing completes, quotes are marked either "Ready to review" or "Action needed" — the strategic must review and confirm before submitting. The system does not auto-submit. If the quote has not been submitted within 1 hour of processing, the strategic receives a reminder email to review it.

**Topic: What if AI overwrites edits I've already made on an update?**
The update quote flow includes a mandatory "Caution: AI Will Overwrite Edits" modal. The strategic must check a box confirming they understand that AI processing will remove all previous edits before they can proceed. This is a deliberate speedbump to prevent accidental overwrites.

**Topic: What happens if something breaks mid-workflow?**
ThreeFlow has error handling built into the key failure points. If the API call fails when opening a quote, the broker stays on the product comparison page and sees a toast message with a "contact support" button. If the carrier dropdown fails to load, or if switching carriers fails, similar error toasts appear with retry instructions and a direct support contact option. Brokers can always revert to contacting the carrier directly if a technical issue blocks them.

**Topic: Is this a new system brokers have to learn?**
No. Strategic users access carrier quoting through the existing ThreeFlow product comparison page — the same place they already work. They click "Start Quote" for a specific carrier, get authenticated into that carrier's site, and use the same quoting tools carriers use today. The entry point and the tools are already familiar.

---

## HOW-TO GUIDES

**Topic: How do I start a quote using smart proposals?**
1. Finish setting up the marketing event on the broker site.
2. Navigate to the product comparison page and click "Start Quote" for the carrier you want to quote (e.g., Lincoln).
3. You'll be authenticated into the carrier site for that project. The Start Quote modal will open.
4. Upload your proposal document(s) (PDF, .doc, or .xls — max 20MB) and click "Send to ThreeFlow."
5. All products in the project will show a "Processing" status. While processing, you can start a quote for another carrier by selecting them from the carrier dropdown and clicking Go. Carriers are listed alphabetically.
6. Once processing completes, products will show either "Ready to review" or "Action needed."
7. Review rates and plan design. Use "Edit details" to correct any action needed items. You can also use copy plan design or enter data manually.
8. Click "Submit quote" when ready. You'll receive an email confirmation that the product has been submitted.
9. Click "Back" from the carrier site banner to return to the product comparison page. Your submitted quote will populate the correct carrier column.

**Topic: How do I update a quote using smart proposals?**
1. Navigate to the product comparison page and click "Update Quote" for the carrier.
2. You'll be authenticated into the carrier site. The "Caution: AI Will Overwrite Edits" modal will appear.
3. Check the box confirming you understand AI processing will remove existing edits, then click "Continue."
4. The update quote modal opens. Upload your updated proposal document and click "Send to ThreeFlow."
5. Follow the same processing, review, and submission steps as the start quote flow above.

**Topic: How do I switch between carriers while quoting?**
From the carrier site, use the carrier dropdown at the top of the page (labeled "Carrier quote") to select a different invited carrier, then click "Go." Carriers are listed alphabetically. You can switch carriers at any point during the workflow, including while documents are still processing for another carrier.

**Topic: What do the quote statuses mean?**
- **Processing** — ThreeFlow AI is extracting rate and plan design data from your uploaded document.
- **Ready to review** — AI successfully found and entered rates. Review before submitting — AI can make mistakes.
- **Action needed** — AI was unable to populate one or more required fields. You'll need to enter missing data manually before you can submit.
- **Submitted** — Quote has been submitted to the carrier.
- **In progress** — Quote is active but not yet submitted.

**Topic: What should I do if I get an "Action needed" status?**
Click "Edit details" next to the product showing "Action needed." The rates or plan design page will open and highlight the missing fields. Enter the required information manually, then return to the My quotes page and submit.

---

## FAQS

**Topic: Who can use self-serve quoting?**
Self-serve quoting is available to approved strategic users with the "quote management" permission. Access is controlled by ThreeFlow and is currently limited to pilot participants. If you believe you should have access and don't, contact your ThreeFlow account team.

**Topic: Does self-serve quoting work for both new business and renewals?**
Yes. Smart proposals support new business quoting and smart renewals support renewing business. Both follow similar workflows — upload a document or enter data manually, review AI output, and submit. Note: attach renewal (processing renewals via email) is not available in the current version.

**Topic: Will I get confirmation when a quote is submitted?**
Yes. You'll receive an email confirmation when a product is submitted. The quote edits screen also captures initial submission information including name, date, timestamp, and submitted products.

**Topic: What if ThreeFlow Assist is offered — should I use it?**
ThreeFlow Assist is optional and can be skipped. It has a longer processing time (up to 48 hours), which makes it less practical when you're working against a client deadline. For most self-serve quoting scenarios, smart proposals or manual quoting will be faster. If you accidentally send to ThreeFlow Assist and want to undo it, contact support.

**Topic: Can I quote multiple carriers at the same time?**
Yes. While documents are processing for one carrier, you can start a quote for another carrier in the same project using the carrier dropdown. This allows you to work through multiple carriers in parallel rather than waiting for each one to complete sequentially.

**Topic: Where do I go if something isn't working?**
Ask in the `#customer-support` Slack channel or use the "contact support" button that appears in error messages. For pilot-specific feedback, use `#temp-broker-self-serve-quoting-feedback`.
