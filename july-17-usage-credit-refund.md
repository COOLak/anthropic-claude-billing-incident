# July 17 Mass Billing Incident: Full-Day $604.71 Refund Dispute

Updated: 2026-08-12 09:34 JST

Status: unresolved; human Billing Platform / payment-operations review requested

Classification: **Claude subscription / Individual-plan extra-usage credits.
This is not Console or API-workspace billing.**

Scope note: the disputed amount remains **$604.71**. The affected period may
potentially extend to earlier dates and July 18, but that has not yet been
established; adjacent-date charges remain outside the current total unless
Anthropic's transaction-level records connect them to the same incident.

Share card:

- PNG: https://coolak.github.io/anthropic-claude-billing-incident/july-17-share-card.png
- Accessible SVG: https://coolak.github.io/anthropic-claude-billing-incident/july-17-share-card.svg

Reporter-ready brief:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-reporter-brief.html

Public-safe receipt-delivery timeline:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-receipt-timeline.html

Privacy-safe request-window audit:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-request-window-audit.html

Public report matrix:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-mass-report-matrix.html

Anthropic-owned GitHub issue cluster:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-github-issue-cluster.html

Affected-user ledger checklist:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-ledger-checklist.html

Regulator-ready public-safe PDF:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-regulator-attachment.pdf

## Standalone Incident

This is a distinct July 17 mass billing incident. It is not part of the separate discounted manual-credit purchase failure.

Dedicated Anthropic-owned public tracker:

https://github.com/anthropics/claude-code/issues/81703

## Public-Safe Summary

Anthropic's status page acknowledged a July 17 incident in which users across Claude.ai, Claude Code, and other surfaces were erroneously required to use usage credits for an included model:

https://status.anthropic.com/incidents/g613ntyj2pwf

The same official machine-readable incident record classifies the incident's
impact as **major** and records this UTC progression:

- `18:32:32` — investigation opened; Claude Code and the other listed
  components changed from operational to partial outage;
- `18:36:40` — Anthropic described users being unable to select Fable 5 across
  Claude.ai, Claude Code, and other surfaces;
- `18:48:23` — a fix was applied and the listed components moved from partial
  outage to degraded performance while Anthropic monitored the result; and
- `19:43:35` — Anthropic marked the incident resolved and the listed components
  operational.

The listed components are Claude.ai, Claude API, Claude Code, and Claude
Cowork. That component scope does not reclassify this customer's disputed
objects: they remain Claude subscription / Individual-plan extra-usage-credit
transactions, not Console or API-workspace invoices. The incident's resolved
service status also does not establish payment reconciliation, an
original-method refund, or which private transactions were caused by the
incident.

An Anthropic email separately acknowledged that a July 17 configuration error caused some Claude usage to be billed to usage credits instead of the customer's included plan allowance. Anthropic limited its automated correction to 18:16–18:47 UTC and added a $3.11 account credit.

The customer did **not** claim that the problem lasted only 30 minutes. The
original support report used a broader July 7–18 range because the affected
date had not yet been isolated. The current refund request covers **all six
automatic-recharge invoices dated July 17, 2026 across the entire day**. The
separate same-day **$100.00 manual purchase is excluded**. It remains possible that the same
incident affected earlier dates and July 18, but that extension has not yet
been established.

Invoice records retained for Anthropic support show:

- seven payment records dated July 17 totaling **$704.71** in the gross chronology;
- six automatic extra-usage recharges totaling **$604.71**, which are the entire current quantified refund demand;
- one same-day **$100.00 manual usage-credit purchase**, expressly excluded from that demand; and
- continued access to included plan usage after extra usage and auto-reload were disabled.

A complete July 7–18 receipt reconstruction also located **$1,006.62** in
successful charges marked paid July 7–16 and **$191.73** marked paid July 18.
Those adjacent-period charges are preserved because the incident may
potentially extend to earlier dates and July 18. They are not included in the
current **$604.71** refund demand, and the possible extension is not treated as
established without transaction-level evidence tying the charges to the same
incorrect-routing mechanism.

That last fact is the central contradiction: if included plan capacity was genuinely exhausted, disabling extra usage should have stopped the work. Instead, the customer continued using the included plan normally.

Anthropic's own [usage-credit documentation](https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans) says paid credits are the continuation mechanism after included plan limits are reached and says the Usage dashboard clearly distinguishes included plan usage from paid credit consumption. The July 17 account behavior and contemporaneous public reports therefore require a transaction-level reconciliation against Anthropic's internal entitlement, debit, auto-reload, and payment records.

## Receipt-Delivery Timeline

All seven first-party receipt bodies say **Paid July 17, 2026**. Their Gmail delivery timestamps span from **July 17 09:59:43 UTC** to **July 18 04:47:33 UTC**, an elapsed **18h 47m 50s**.

Relative to Anthropic's 18:16–18:47 UTC correction window:

- one **$100.00** receipt email arrived before the window;
- one **$97.12** receipt email arrived inside the window; and
- five receipt emails totaling **$507.59** arrived after the window.

Thus **$607.59**, or **86.2%**, of the seven-receipt gross total appears in emails delivered outside the selected window. Of the current automatic-recharge dispute, **$507.59**, or **83.9%**, appears after the window.

Against Anthropic's official **major** incident record, which opens at
**18:32:32 UTC** and resolves at **19:43:35 UTC**, the six disputed automatic
receipt emails span **10h 13m 44s**. One receipt for **$97.12** arrived during
the official incident; five totaling **$507.59** arrived after Anthropic marked
the incident resolved, continuing through **04:47:33 UTC** the following day.
The first post-resolution receipt arrived **7m 58.533s** after resolution, and
the final one arrived **9h 3m 57.533s** after it.

Public-safe visual and table:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-receipt-timeline.html

An email delivery timestamp is not necessarily Anthropic's internal usage-credit debit, auto-recharge trigger, payment authorization, or invoice-creation timestamp. The timeline therefore supports a full transaction-level audit and does not claim that receipt delivery time proves incident causation by itself.

## Request-Metadata Window Audit

A privacy-redacted local Claude Code inventory contains **2,177**
deduplicated July 17 records spanning 00:00:06–23:46:50 UTC. Using
`[18:16, 18:47)` because Anthropic says included limits worked as intended
since 18:47, the records divide into:

- **1,241** before Anthropic's interval;
- **29** inside it; and
- **907** after it.

That places **2,148 records (98.67%)** and
**706,168,401 / 722,463,837 recorded counters (97.74%)** outside
Anthropic's selected interval.

The public aggregate audit records the bounded formulas, independent
row-by-row reproduction, and privacy controls:

https://coolak.github.io/anthropic-claude-billing-incident/july-17-request-window-audit.html

This proves day-spanning local request activity, not provider-billed dollars,
historical plan entitlement, included-versus-paid routing, credit debits,
auto-reload triggers, or request-to-invoice mapping. Only Anthropic's
authoritative historical ledgers can decide those questions.

## Payment-Processor Trace — Transactions Located, Root Cause Unresolved

All six July 17 automatic-recharge receipts, totaling **$604.71**, say `Payment method Link`. A subsequent human Link review under the correct Gmail-authenticated account located all six transactions and supplied their card-network/last-four and timestamp/status mappings privately. The earlier no-match result came from a different Link identity and is superseded.

This proves that the six wallet debits exist and can be traced to the correct account. It does **not** prove Anthropic's internal subscription entitlement, included-plan-versus-paid-credit routing, paid-credit debit, automatic-recharge trigger, or incident causation. Link stated that the PaymentIntent and charge identifiers remain merchant-side details that Anthropic must retrieve.

The corrected public update intentionally omits the Link case number, account emails, invoice IDs, card data, and private support transcript:

https://github.com/anthropics/claude-code/issues/81703#issuecomment-5104130764

## Subscription Classification and Evidence Boundary

The six disputed automatic-recharge receipts are Claude **Individual-plan**
extra-usage-credit objects associated with the subscription account. A seventh
record is a one-time manual usage-credit purchase and is excluded. These are not
Console or API-workspace invoices.

Local request metadata can independently establish timestamps, models, and
usage counters. It cannot determine whether Anthropic correctly classified a
request as included subscription usage or paid Individual-plan extra usage.
Only Anthropic's transaction-time subscription-entitlement and paid-credit
ledgers can resolve that question. Present-day local authentication state is
irrelevant and is not part of this claim.

Corrected Anthropic-tracker update:

https://github.com/anthropics/claude-code/issues/81703#issuecomment-5095891086

## Relevant Billing-Provider Relationship — Not Proof of Scope

Metronome's February 2025 [company announcement](https://metronome.com/blog/metronome-raises-50m-series-c-to-redefine-billing-as-a-growth-engine) publicly names Anthropic among companies that rely on its billing platform. Metronome's August 2025 [billing-correction guidance](https://metronome.com/blog/billing-mistakes-happen-what-matters-most-is-how-you-fix-them) says billing errors require repair across usage, invoices, credit ledgers, reporting, customer dashboards, and threshold logic, with correction records carrying timestamps, transaction IDs, and actor metadata.

This does **not** establish that Metronome handles Claude consumer usage credits, processed the six disputed automatic-recharge receipts, or caused the July 17 incident. It establishes a public provider relationship and a directly relevant correction standard: a small account credit is not evidence that the complete connected billing state was repaired. The caveated relationship and outreach record is preserved here:

https://github.com/anthropics/claude-code/issues/81703#issuecomment-5098669899

## Independent BBB Mechanism Report

Anthropic's current [BBB complaints page](https://www.bbb.org/us/ca/san-francisco/profile/marketing-software/anthropics-1116-950586/complaints) contains a separate June 29, 2026 `Billing Issues` complaint alleging that usage credits were deducted while included plan allowance remained and that a configured **$50** spending limit was exceeded to **$66**.

This is a third party's public allegation. BBB does not verify complaint accuracy, and the report does not prove this customer's **$604.71** amount or establish the same root cause. It does independently describe the same observable included-limit-to-paid-credit mechanism. The caveated source record is preserved here:

https://github.com/anthropics/claude-code/issues/81703#issuecomment-5097506527

## Related Anthropic Consumer Litigation — Separate Allegations

Two pending federal consumer cases provide broader context, but neither establishes the facts, amount, cause, or legal status of this July 17 dispute:

- [*Kahn v. Anthropic PBC*, No. 3:26-cv-05763 (N.D. Cal.)](https://dockets.justia.com/docket/california/candce/3%3A2026cv05763/472161), filed June 14, 2026. Plaintiff's counsel [describes the complaint](https://www.vacadaffanlaw.com/post/kahn-v-anthropic-pbc) as alleging that Anthropic misled consumers about the usage and value of its Max 5x and Max 20x plans.
- [*Pascual v. Anthropic, PBC*, No. 3:26-cv-07699 (N.D. Cal.)](https://dockets.justia.com/docket/california/candce/3%3A2026cv07699/474951), filed July 24, 2026. The public docket identifies a contract complaint; [Bloomberg Law reports](https://news.bloomberglaw.com/ip-law/anthropic-hit-with-consumer-deception-suit-over-reduced-service) that it alleges retained subscription fees after service reductions and defects.

These are allegations in pending cases, not findings of fact or liability. Neither case proves that this customer's July 17 usage was misrouted, proves the **$604.71** ledger, expands the refund demand, or establishes that the customer is a member of any proposed class. The July 17 matter remains a separate operational billing claim: usage credits allegedly consumed while included plan capacity remained, followed by six automatic recharges totaling **$604.71**, an excluded **$100 manual purchase**, and only a **$3.11** account credit.

## Why the $3.11 Credit Does Not Resolve the Claim

The $3.11 credit addresses only Anthropic's system-selected 30-minute incident window. It does not establish that usage-credit routing was correct during the rest of July 17, and it does not reconcile the six disputed automatic-recharge invoices issued that day.

The account credit is therefore treated as a partial automated correction, not settlement of the full refund request.

## Requested Remedy

Anthropic should assign a human Billing Platform / payment-operations owner and:

1. audit the full July 17 account ledger, not only 18:16–18:47 UTC;
2. reconcile included-plan entitlement, session/model routing, usage-credit debits, auto-reload triggers, and invoice creation transaction by transaction;
3. refund every July 17 charge caused by usage being routed to credits while included plan capacity remained;
4. return the refund to the original payment method rather than substituting an expiring account credit; and
5. identify any disputed invoice with timestamped usage and entitlement evidence.

## Current Support State

The existing private support conversation and formal dispute thread have been updated with the corrected scope, the six automatic-recharge invoice identifiers and amounts, the excluded manual-purchase record, the adjacent-period audit perimeter, and the demand for a full-day $604.71 refund. A human billing owner and complete refund have not yet been confirmed.

## Standalone Public Discussion

- Anthropic-owned incident tracker: https://github.com/anthropics/claude-code/issues/81703
- Official Claude Discord `#claude-code` thread (opening post removed; thread closed): https://discord.com/channels/1072196207201501266/1405658683798589481/threads/1531419428670148658
- Public record of the Discord moderation/support redirect: https://github.com/anthropics/claude-code/issues/81703#issuecomment-5097287377
- X update documenting the deleted/locked Discord route: https://x.com/Coolak777/status/2081864073705390304
- r/ClaudeCode update documenting the deleted/locked Discord route: https://www.reddit.com/r/ClaudeCode/comments/1v85cuh/comment/p05eg4a/
- r/Anthropic update documenting the deleted/locked Discord route: https://www.reddit.com/r/Anthropic/comments/1v85sj5/comment/p05eman/
- LinkedIn update surface: https://www.linkedin.com/feed/update/urn:li:activity:7487545319958732801/
- Facebook update: https://www.facebook.com/erik.j.gordon/posts/pfbid02TVCAUC7Bv9DXGKmk63PVMLrPeExuUQQjhBxL3FkEU1iMEM3Jv9w7Mpj1s9xMhunsl?comment_id=1536064538198709
- Trustpilot review separating the July 17 incident from the June purchase failure and recording the deleted/locked Discord route: https://www.trustpilot.com/reviews/6a2d7d4d7d52f4ee63ac06ed
- Sourced technical observability-boundary update: https://github.com/anthropics/claude-code/issues/81703#issuecomment-5095891086
- Metronome/Anthropic relationship and full-chain correction-standard update: https://github.com/anthropics/claude-code/issues/81703#issuecomment-5098669899
- Metronome announcement naming Anthropic among companies relying on its platform: https://metronome.com/blog/metronome-raises-50m-series-c-to-redefine-billing-as-a-growth-engine
- Metronome full-chain billing-correction guidance: https://metronome.com/blog/billing-mistakes-happen-what-matters-most-is-how-you-fix-them
- Independent BBB mechanism report and sourced tracker update: https://github.com/anthropics/claude-code/issues/81703#issuecomment-5097506527
- Twelve-source matrix and separate $200 public-report tracker update: https://github.com/anthropics/claude-code/issues/81703#issuecomment-5097881473
- Caveated BBB mechanism update on X: https://x.com/Coolak777/status/2081873301719421049
- r/ClaudeCode post body with corrected **$604.71** total and caveated BBB evidence: https://www.reddit.com/r/ClaudeCode/comments/1v85cuh/july_17_mass_billing_incident_anthropic/
- r/Anthropic post body with corrected **$604.71** total and caveated BBB evidence: https://www.reddit.com/r/Anthropic/comments/1v85sj5/was_your_full_july_17_usagecredit_ledger/
- Current BBB complaints page for Anthropic: https://www.bbb.org/us/ca/san-francisco/profile/marketing-software/anthropics-1116-950586/complaints
- Reporter-ready July 17 source brief: https://coolak.github.io/anthropic-claude-billing-incident/july-17-reporter-brief.html
- Privacy-safe request-window audit: https://coolak.github.io/anthropic-claude-billing-incident/july-17-request-window-audit.html
- Public report source matrix: https://coolak.github.io/anthropic-claude-billing-incident/july-17-mass-report-matrix.html
- Anthropic-owned GitHub issue cluster: https://coolak.github.io/anthropic-claude-billing-incident/july-17-github-issue-cluster.html
- Affected-user full-day ledger checklist: https://coolak.github.io/anthropic-claude-billing-incident/july-17-ledger-checklist.html
- Regulator-ready public-safe PDF: https://coolak.github.io/anthropic-claude-billing-incident/july-17-regulator-attachment.pdf
- X evidence thread: https://x.com/Coolak777/status/2081778624722829642
- X escalation to Anthropic's official accounts: https://x.com/Coolak777/status/2081782382630433006
- X evidence-card post: https://x.com/Coolak777/status/2081802843464556656
- X official-policy and source-matrix update: https://x.com/Coolak777/status/2081811444837048463
- r/ClaudeCode evidence discussion: https://www.reddit.com/r/ClaudeCode/comments/1v85cuh/july_17_mass_billing_incident_anthropic/
- r/ClaudeCode source-matrix update: https://www.reddit.com/r/ClaudeCode/comments/1v85cuh/comment/p042476/
- r/Anthropic full-day reconciliation discussion: https://www.reddit.com/r/Anthropic/comments/1v85sj5/was_your_full_july_17_usagecredit_ledger/
- Reply in the high-visibility July 17 incident thread: https://www.reddit.com/r/ClaudeCode/comments/1uz7oae/comment/p03d7tk/
- LinkedIn public activity: https://www.linkedin.com/in/erik-gordon-a4025656/recent-activity/all/
- Facebook public timeline: https://www.facebook.com/erik.j.gordon

## Contemporaneous July 17 Mass Reports

Public discussions posted during the incident show that the paid-credit impact was not isolated to one account:

Structured source matrix: https://coolak.github.io/anthropic-claude-billing-incident/july-17-mass-report-matrix.html

- Nine tightly clustered issues in Anthropic's own Claude Code tracker were opened between 18:17 and 19:24 UTC. Public reports include roughly 12%, 24% session / 28% weekly, 45%, and 50% included-usage positions, plus macOS/Linux/Windows and Claude Code/Claude.ai impact: https://coolak.github.io/anthropic-claude-billing-incident/july-17-github-issue-cluster.html
- A high-engagement r/ClaudeCode thread includes contemporaneous reports of unexpected Anthropic card notifications, usage credits reaching 105%, $50 in overages, a claimed $100 monthly usage-credit limit being consumed, and a second user who said the same happened with a $50 limit: https://www.reddit.com/r/ClaudeCode/comments/1uz7oae/its_happened/
- A separate r/ClaudeCode thread contains multiple reports that an included model suddenly required usage credits, including one user who said roughly half of the included usage remained: https://www.reddit.com/r/ClaudeCode/comments/1uz7rzw/usage_credits_are_required_for_this_model/
- An r/claude discussion includes reports that paid-credit charging started during the outage and one commenter who said $287 was consumed before they noticed: https://www.reddit.com/r/claude/comments/1uz7sk7/apparently_17_19_according_to_anthropic/
- A large r/ClaudeCode incident thread includes one public claim that $500 of usage credit was consumed when the service switched to credits, another report that the user's full Extra Usage budget was consumed without notice, and a separate report of a $6.32 charge despite the user saying plan capacity remained: https://www.reddit.com/r/ClaudeCode/comments/1uz7pmj/fable_gone/
- A contemporaneous r/claudexplorers report says the interface switched to “Now using credits” and charged $6.32 while plan capacity remained; a second user in the thread reported spending several dollars in Claude Code without a warning that usage was switching to credits: https://www.reddit.com/r/claudexplorers/comments/1uz88co/suddenly_lost_access_to_fable_on_subscription_i/
- A large r/claude discussion contains multiple reports of the “Usage credits are required” message appearing mid-session, including users who said they had 30% or substantial weekly plan capacity remaining: https://www.reddit.com/r/claude/comments/1uz7qw4/the_just_took_fable_off_max_plans/
- An r/Anthropic incident thread includes reports from Max 20x and Max 5x users that usage credits were suddenly required, including one commenter who said only about 6% of included usage had been consumed: https://www.reddit.com/r/Anthropic/comments/1uz7rsk/fable_5_issue/
- An r/ClaudeAI incident discussion shows 75% session usage, 11% weekly usage, and usage credits off in the original post; commenters said credits were nevertheless consumed during the outage, including one claim of about $8 spent after enabling credits to finish a task: https://www.reddit.com/r/ClaudeAI/comments/1uz7yea/i_dont_understand_the_pricing_anymore/
- A separate Max 20x report says the app burned usage credits while the account showed only 8% five-hour usage and 3% weekly usage: https://www.reddit.com/r/ClaudeAI/comments/1uz85wo/burning_extra_credits_before_quota_runs_out/
- A separate r/Anthropic poster claimed `$200` in credits disappeared without warning, later said the credits had not returned after model access returned, and reported that Fin redirected the debit-card credit complaint to Apple/iOS; this is an unverified third-party claim and is not included in this customer's `$604.71` total: https://www.reddit.com/r/Anthropic/comments/1uz8clo/i_thought_i_was_using_my_fable_usage_and_all_of_a/

These are third-party public reports, not proof of this customer's private ledger. They corroborate Anthropic's own statement that the incident affected users across Claude surfaces and justify a full-day, account-by-account reconciliation.

## Related Later/Unknown-Date Reports — Separate and Unverified

On July 28, a different GitHub participant reported being charged **EUR 2,932.51** from July 23 until a credit-card limit was reached on July 24 and said a promised human support reply never arrived:

https://github.com/anthropics/claude-code/issues/81703#issuecomment-5102988881

This is an unverified third-party claim from **July 23–24**, not a July 17 source. It is not included in this customer's **$604.71** ledger, does not prove the same mechanism or root cause, and may represent a distinct later incident. It is preserved as related pattern context because it independently alleges large automated billing and failed human escalation later in the same month.

Anthropic tracker issue [`#81941`](https://github.com/anthropics/claude-code/issues/81941) separately alleges **35** unexpected usage-credit charges totaling **EUR 1,809.55**, including repeated overnight charges about **4–6 minutes** apart while Claude reportedly also displayed weekly-limit blocks. The issue is open and bug-labeled but does not state the charge dates. It is an unverified self-report, is not included in this customer's **$604.71** ledger, and does not prove the same date, mechanism, or root cause.

## Corroborating Mechanism Reports

- Included allowance bypassed while usage credits are consumed: https://github.com/anthropics/claude-code/issues/80750
- Repeated auto-recharge billing and failed human escalation: https://github.com/anthropics/claude-code/issues/68773
- Extra Usage charged despite visible plan headroom: https://github.com/anthropics/claude-code/issues/32544

These reports corroborate the mechanism but do not replace the dedicated July 17 incident.

## Privacy Boundary

Exact invoice numbers, payment details, support identifiers, private screenshots, and private conversation text remain in the Anthropic support channel. They are intentionally not published here.
