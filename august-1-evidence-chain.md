# August 1 Post-Reset Auto-Recharge Evidence Chain

Updated: 2026-08-18 21:12 JST

Status: unresolved. **USD 15.26 has been returned to the original payment
route; USD 980.41 remains unresolved.** No human transaction-by-transaction
billing decision has been confirmed.

## Machine-Readable Transaction Track

[Open the privacy-safe ten-transaction JSON ledger](https://coolak.github.io/anthropic-claude-billing-incident/automatic-charge-summary.json).

This page uses only track `august1_post_reset`: two automatic rows totaling
**USD 995.67**. The reset sequence is a customer observation and does not
independently prove the exact reset time or Anthropic's server-side entitlement
and routing state. The July 17 and August 12 tracks are separate, and manual
purchases remain excluded.

## Verified transaction record

Two original merchant invoice/receipt pairs document successful Claude
Individual-plan automatic extra-usage recharges:

| Receipt email delivered (JST) | Amount | Merchant description |
| --- | ---: | --- |
| 2026-08-01 07:50:52 | USD 496.75 | Auto recharge extra usage, Individual plan |
| 2026-08-01 12:25:00 | USD 498.92 | Auto recharge extra usage, Individual plan |
| **Total** | **USD 995.67** | **Two automatic recharges** |

[Open the privacy-redacted raster invoice excerpts](./august-1-redacted-payment-excerpts.png).
The sheet is assembled only from the line-item and total regions of the
original invoice renders. It contains no recoverable hidden PDF text or
overlaid redaction layer. It proves the automatic-recharge descriptions and
amounts, not the reset time or routing cause.

The documents identify Link as the payment method. They are automatic
recharges, not manual top-ups. Private invoice, receipt, payment-card, account,
support-case, and email identifiers are intentionally omitted.

## USD 15.26 partial refund verified; USD 980.41 remains

Anthropic returned **USD 15.26** to the original payment route on the August 1
automatic charge originally totaling **USD 498.92**. Anthropic's refund memo
identifies an automatic extra-usage reload charged during a hosted-Claude
service issue spanning **July 24 through August 12, 2026**.

### Public status archive does not identify that refund event

Anthropic's [official incident feed](https://status.claude.com/api/v2/incidents.json),
read on **August 18, 2026**, contains **20 separate incidents** whose UTC start
dates fall from July 24 through August 12, plus one Microsoft Office add-in
incident that began earlier and overlapped the opening boundary. None spans the
full July 24-through-August 12 period. A case-insensitive scan of the incident
names and update bodies found no reference to billing, payments, usage credits,
Auto-reload, recharges, invoices, refunds, subscriptions, entitlements, or
charges.

This public-archive result does **not** rule out an undisclosed internal or
account-level service issue and does not contradict the transaction-specific
USD 15.26 refund record. It means the public archive alone does not identify
the event named in the memo or explain the refund calculation. Anthropic should
identify the relevant public or internal incident, disclose the affected-account
criteria and calculation method, map the result to both August 1 automatic
charges, and return the remaining **USD 980.41** to the original payment method.

This transaction-mapped return is not resolution. The partially refunded charge
still has **USD 483.66** unresolved, the other August 1 charge of **USD 496.75**
remains entirely unresolved, and the incident's remaining balance is
**USD 980.41**. Private refund, credit-note, payment, and support identifiers are
withheld from this public record.

## Customer-observed sequence

1. Included subscription limits visibly reset before the first disputed
   recharge.
2. Claude Code nevertheless continued consuming usage credits instead of the
   reset included allowance.
3. Two automatic recharges completed, totaling USD 995.67.
4. Usage-credit depletion continued after the second recharge until usage
   credits were disabled to stop further losses.

This sequence is a first-party account observation. The private payment records
do not independently prove the exact reset timestamp or Anthropic's server-side
entitlement and routing decision.

## Private evidence delivery

All four original payment PDFs have now been delivered through both relevant
authenticated written channels:

- the controlling correct-account Link support case; and
- Anthropic's written support route, copied to its notices address.

The private identifiers for those messages and cases are not published. This
delivery record establishes that both the payment intermediary and Anthropic
have the original transaction documents available for investigation. It does
not establish that either party has acknowledged the billing defect, approved
a refund, or completed a reconciliation.

## Formal Stripe/Link complaint status

A formal written complaint has also been sent through Stripe's published
complaint route. It covers all sixteen original invoice and receipt PDFs for
the eight automatic Claude Individual-plan extra-usage transactions currently
quantified across July 17 and August 1. The complaint asks Stripe/Link to
preserve the transaction mappings, refer the matter to Anthropic where
appropriate, and provide a written transaction-by-transaction disposition.

Stripe Support acknowledged receipt one minute after submission and said it
would be in touch. That acknowledgment proves complaint intake only. It is not
an investigation result, fault finding, refund approval, reversal, settlement,
or final complaint decision. No substantive Stripe/Link decision or refund has
been confirmed.

The combined automatic-only refund demand is **USD 1,600.38**: **USD 604.71**
for July 17 plus **USD 995.67** for August 1. The separate July 17 manual
purchase is excluded, and potentially related adjacent-date transactions
remain unquantified. No bank or card chargeback has been filed.

### Combined automatic-charge reconciliation

| Disputed period | Automatic recharges | Verified amount | Returned to original payment methods | Scope boundary |
| --- | ---: | ---: | ---: | --- |
| July 17 | 6 | USD 604.71 | USD 0.00 | Entire-day claim; separate USD 100 manual purchase excluded |
| August 1 | 2 | USD 995.67 | USD 15.26 | USD 980.41 remains; automatic recharges only |
| **Combined quantified demand** | **8** | **USD 1,600.38** | **USD 15.26** | **USD 1,585.12 remains; manual top-ups excluded** |

Anthropic added a **USD 3.11 expiring account credit** for its own 30-minute
July 17 interval. That is not money returned to the original payment methods
and is not included in the verified **USD 15.26** original-payment refund total.

The transaction documents establish the eight automatic recharge objects and
amounts. [Anthropic's official incident
record](https://status.anthropic.com/incidents/g613ntyj2pwf) establishes an
erroneous July 17 requirement for usage credits on Fable 5, but the public
record does not independently map every July transaction to that error. The
August 1 reset sequence is a first-party account observation; its payment
records do not prove the reset timestamp or server-side routing cause.
Potentially related earlier dates and July 18 remain unquantified and outside
this total.

Stripe's Link terms generally place responsibility for product or service
refunds with the merchant. The complaint therefore targets Link's handling,
preservation, referral, and written transaction disposition; it does not allege
that Stripe caused Anthropic's entitlement or routing behavior.

## Latest authenticated Link support movement

On **August 15 JST**, authenticated Link Support confirmed that its written
support case and personal-data investigation remained open. Its initial
purchase list did not include either disputed August 1 automatic recharge—
**USD 496.75** or **USD 498.92**—and instead included the separate August 12
payments plus unrelated purchases. One written scope correction preserved the
fixed **USD 1,600.38** earlier-track demand, the separate **USD 99.08** later
incident, and the manual-purchase exclusions.

Link then stated that purchase refunds and invoices are best handled by
Anthropic, suggested contacting a card-issuing bank if the merchant remains
unresponsive, and said its written support case would remain open. One concise
same-thread response kept the unanswered Link-controlled August 1 mapping,
preservation, merchant-referral, case-status, and next-update questions pending.

This Link movement remains procedural routing only. Separately, Anthropic has
returned **USD 15.26** on one August 1 charge; that is not a
transaction-by-transaction disposition or final complaint response. No bank
contact, issuer dispute, or chargeback was initiated. The August 1 incident has
**USD 980.41** remaining within the fixed **USD 1,600.38** earlier track, whose
remaining balance is **USD 1,585.12**; the separate August 12 incident remains
**USD 99.08**.

## Proof boundary

| Evidence | What it establishes | What it does not establish |
| --- | --- | --- |
| Original merchant invoices and receipts | Two successful Individual-plan automatic recharges; amounts; total; stated payment method | Precise included-limit reset time; request routing; credit-debit cause |
| Customer-observed reset-to-credit-drain sequence | The account-visible order of reset, continued credit use, recharge, and shutdown control | Anthropic's internal entitlement state or model-specific gate |
| Anthropic usage-credit documentation | Published rule that usage credits apply after included limits, session limits reset every five hours, and credits do not change reset timing | What Anthropic's servers recorded for this account at each disputed debit |
| Same-day reports #83036 and #83037 | Independently inspectable reports of credit-gate behavior despite visible plan allowance | This account's payment path, a shared root cause, or aggregate loss |
| Same-day subscription-sync report #83093 | A separate user reported `credits_required` errors after an Apple-billed Max subscription was marked `subscription_status: "canceled"` in Anthropic's OAuth profile | The reporter's Apple-account status, this account's entitlement or payment path, a shared root cause, or aggregate loss |
| August 1-2 auto-recharge report #85912 | A separate Max/Cowork user alleges eleven automatic recharges totaling `USD 1,031.92` over 48 hours, no interactive Fable use during those two days, no spend alert, and no human support response for nine days | The reporter's account records, the alleged scheduled-task cause, this account's reset/payment chain, a shared root cause, or aggregate loss |
| Later August public auto-recharge and idle-usage reports | One r/Anthropic poster alleges more than `USD 480` in phantom usage and says Anthropic Support attributed multiple August 1 usage-credit top-ups within 31 minutes to an internal backend loop; a separate r/ClaudeAI poster alleges Max usage rose from `11%` to `100%` in about 31 minutes while idle, followed by an extra-usage auto-recharge invoice | Authenticity of the posters' private support, usage, or payment records; an Anthropic admission concerning this account; this account's reset/payment chain; a shared root cause; or aggregate loss |
| Fresh spending-cap and clustered-purchase report | A separate r/ClaudeCode poster alleges that a `USD 40` monthly overage cap was exceeded in two consecutive months, three purchase-notification emails arrived within seconds after a weekly limit was reached, the purchased credits were already exhausted, and a claimed human-support escalation remained unanswered for about a month | The reporter's original merchant, processor, account-setting, usage, or support records; the exact setting and trigger state; this account's reset/payment chain; a shared root cause; or aggregate loss |
| Later Max-plan credit-gate reports #83242 and #84694 | Separate August 2 and August 7 reports show Claude Code telling Max users that Fable required usage credits; #83242 says reauthentication cleared the gate | Any payment or credit consumption, the reporters' authoritative plan state, this account's payment chain, a shared root cause, or aggregate loss |
| August 12 five-hour quota-consumption reports #86033 and #85992 | One Max-plan reporter alleges five-hour quota consumption rose about 15–20 times above the prior baseline; one Pro-plan reporter alleges a full five-hour window exhausted within 3–10 minutes of a confirmed reset during lightweight work, reproduced twice | Any automatic purchase or payment, the reporters' complete account state, this account's August 1 reset/payment chain, a shared root cause, or aggregate loss |
| July 30 near-date public report | A separate Opus 4.6 user reported paid-credit use at 25% session and 44% weekly usage, without the usual limit notification | Screenshot authenticity, this account's reset/payment chain, a shared root cause, or aggregate loss |
| Additional July 24-30 public reports | Separate users alleged post-reset idle usage growth with recurring auto-reloads, rapid Max-limit depletion without active use, and paid-credit activation or consumption without expected warning | Account authenticity, transaction amounts beyond each source's own claim, a shared root cause, or this account's payment path |
| Privacy-redacted local timestamp bridge | 2,860 deduplicated response-usage records establish contemporaneous Claude Code activity immediately before and after both receipt-email deliveries | The reset state, paid-credit classification, recharge trigger, transaction causation, or provider-billed dollars |
| Dual private delivery to Link and Anthropic | Both relevant parties have the original transaction records needed to investigate | Fault admission, refund approval, or settlement |
| Formal Stripe/Link complaint and receipt acknowledgment | Stripe received a written complaint covering all sixteen originals and eight automatic transactions | Investigation result, fault finding, refund approval, reversal, settlement, or final decision |

## Independent near-date public signals and official-record gap

A same-day Anthropic tracker issue reports that a Max 20x Apple subscription
worked through July 30, then began returning `out_of_credits` /
`credits_required` errors on July 31 while Anthropic's OAuth profile allegedly
reported `has_claude_max: false` and `subscription_status: "canceled"`. The
poster says Apple Support separately confirmed the subscription remained
active and set to renew.

https://github.com/anthropics/claude-code/issues/83093

This is a separately authored public report, not verified account evidence.
It does not prove the reporter's Apple status, the August 1 customer's reset
or payment chain, a common root cause, or aggregate loss. Its limited
relevance is the explicit allegation of a server-side subscription-state
mismatch immediately preceding a `credits_required` response.

An Anthropic tracker issue filed August 11 describes a separate Max 20x/Cowork
account that allegedly generated eleven automatic recharges totaling
`USD 1,031.92` on August 1-2. The reporter says no interactive Fable session
was open during those two days, the first notification was the resulting stack
of charge emails, and the in-app human-support queue had produced no response
for nine days. The report attributes the spend to an allegedly hung persistent
scheduled-task session and separately lists fourteen charges totaling
`USD 1,288.35` through August 7.

https://github.com/anthropics/claude-code/issues/85912

This is a separately authored public claim, not verified account evidence. It
uses a different product surface and advances a different causal theory. It
does not prove the reporter's scheduled-task state, this customer's reset or
payment chain, a common root cause, or aggregate loss. Its limited relevance
is the independently alleged concentration of high-dollar automatic recharges
on August 1-2, absent spend warning, and unresolved human-support route.

Two later public Reddit posts describe separate but near-date allegations:

- An r/Anthropic poster alleges more than `USD 480` in phantom usage and says
  Anthropic Support reviewed the account and attributed multiple August 1
  usage-credit top-ups within 31 minutes to an internal backend loop, with
  some transactions voided and others paid.
- An r/ClaudeAI poster alleges that Max 20x usage rose from `11%` to `47%` and
  then `100%` in about 31 minutes while the account was idle, followed by both
  a Max invoice and an extra-usage auto-recharge invoice; the poster says no
  human support response had arrived.

Sources:

- https://www.reddit.com/r/Anthropic/comments/1vdtir3/massive_phantom_usage_bug_draining_promax_plans/
- https://www.reddit.com/r/ClaudeAI/comments/1vf6i4y/max_20x_usage_went_from_0_to_100_in_half_an_hour/

These are unverified third-party public claims. The claimed support finding
has not been independently authenticated and is not an Anthropic admission
about this account. Neither report proves the posters' private usage or
payment records, this customer's reset and recharge chain, a common root
cause, or aggregate loss. Their limited relevance is the independent public
allegation of clustered August 1 automatic funding and rapid idle usage, plus
the continuing gap in a timely written human billing response.

A later [r/ClaudeCode
post](https://www.reddit.com/r/ClaudeCode/comments/1vjrwhy/anyone_else_multiharnessing_due_to_token_limits/)
describes a separate spending-control and clustered-purchase allegation. The
poster says a monthly overage limit was set to `USD 40`, yet the account was
billed more than `USD 50` in two consecutive months; after a weekly limit was
reached, three purchase-notification emails allegedly arrived within seconds,
and the purchased credits were already exhausted by the time the poster
returned to the harness. The poster also says the support bot required three
phrasings before claiming to escalate the matter to a human, with no response
after about a month, and that overage credits were then disabled.

**Evidence boundary:** this is an unverified third-party public allegation.
No original merchant or processor record, authenticated support transcript,
or timestamped account-setting capture is available here. It does not prove
the exact cap, control, notification, purchase-trigger, or usage state; this
customer's August 1 reset and payment chain; a common root cause; aggregate
loss; or refund entitlement. Its limited relevance is the independently
alleged failure of a user-visible spending control, a burst of purchase
notifications after a limit event, rapid credit exhaustion, and a prolonged
gap in written human support.

Two later Anthropic tracker reports describe Max-plan users encountering a
Claude Code gate that said Fable required usage credits:

- August 2 report #83242:
  https://github.com/anthropics/claude-code/issues/83242
- August 7 report #84694:
  https://github.com/anthropics/claude-code/issues/84694

Report #83242 says logging out and back in cleared the gate. Neither report
establishes a completed paid-credit debit, automatic recharge, or payment.
They do not prove the reporters' authoritative plan state, this customer's
reset or transaction chain, a common root cause, or aggregate loss. Their
limited relevance is the post-August 1 recurrence of Max-plan versus
usage-credit gate messaging in Claude Code.

Two Anthropic tracker reports filed August 12 describe severe paid-plan
five-hour quota consumption:

- Max-plan report #86033:
  https://github.com/anthropics/claude-code/issues/86033
- Pro-plan report #85992:
  https://github.com/anthropics/claude-code/issues/85992

Report #86033 alleges that five-hour quota consumption rose roughly 15–20
times above the reporter's prior baseline beginning around August 8. Report
#85992 alleges that a full five-hour window exhausted within approximately
3–10 minutes after a confirmed reset during lightweight document work,
reproduced twice.

Neither report alleges an automatic purchase or payment. They do not prove the
reporters' complete account state, this customer's August 1 reset or payment
chain, a common root cause, or aggregate loss. Their limited relevance is the
independently reported paid-plan quota-meter behavior that Anthropic would need
to reconcile before explaining why this account continued into paid credits
and automatic recharges after the observed reset.

A separate r/Anthropic post published July 30 reports an Opus 4.6 Claude Code
session at approximately `25%` of its session limit and `44%` of its weekly
limit while a small prompt allegedly consumed `USD 4.60` in paid usage
credits. The poster says the transition occurred without the limit-reached
notification they had previously seen and that Claude Code would not continue
when usage credits were disabled. The poster repeatedly states that the
session was Opus 4.6 rather than Fable.

https://www.reddit.com/r/Anthropic/comments/1vaywsv/why_is_claude_using_usage_credits_when_i_havent/

This is an unverified third-party public report. It does not prove the August 1
customer's reset timestamp, payments, account state, or root cause. Its limited
relevance is that it independently alleges the same observable class of
included-limit-versus-paid-credit mismatch on the day immediately preceding
the disputed August 1 recharges and on a non-Fable model.

Three additional July 24-30 public reports describe nearby but distinct
observable patterns:

- A July 27 Max-plan user reported that usage began increasing again after a
  session reset while the account was allegedly idle, that enabled auto-reload
  produced charges of approximately `USD 60` every few hours, and that an
  automated support response initially declined a refund request.
- A July 30 commenter reported that Max usage had been decreasing without
  active use since the preceding Friday, allegedly exhausting the full Max
  allowance in about half an hour, while the support bot suggested purchasing
  usage credits and required extended interaction before routing a bug report.
- A July 24 commenter on Anthropic's promotional-credit rollout said accepting
  the credit appeared to enable paid-credit spending, go beyond subscription
  limits, and consume roughly half the promotional balance without warning.

Sources:

- https://www.reddit.com/r/Claude_reports/comments/1v81ons/rclaudeai_has_anyone_noticed_claude_max_usage/
- https://www.reddit.com/r/ClaudeAI/comments/1v86ls8/comment/p03r5rt/
- https://www.reddit.com/r/Anthropic/comments/1v1pid7/comment/oypda3o/

These are unverified third-party reports, not an incident census. They do not
prove that any source shares this customer's entitlement state, payment path,
or root cause. Their limited relevance is that they independently allege
post-reset or idle usage growth, rapid paid-plan depletion, automatic reloads,
and paid-credit behavior without the expected warning or support remedy during
the week surrounding the disputed August 1 transactions.

Anthropic's official status page currently says `No incidents reported` for
August 1. That is an official-record gap, not proof that no account-level
billing or entitlement defect occurred. The page tracks disclosed service
incidents; it does not provide this account's entitlement, routing, debit, or
payment ledger.

## Private local activity timestamp bridge

A privacy-redacted scan of the local Claude Code record for August 1 JST adds
a time-correlation layer without publishing prompts, responses, raw IDs,
credentials, account data, or filesystem paths:

- `2,545` JSONL files and `1,059,231` lines scanned;
- `6,482` raw response-usage records;
- `2,860` deduplicated records after removing `3,622` duplicate copies; and
- `0` parse errors.

The nearest deduplicated response-usage records bracket the first receipt-email
delivery by `17.757` seconds before and `7.494` seconds after, and the second by
`9.731` seconds before and `6.312` seconds after. This establishes
contemporaneous Claude Code activity across both receipt deliveries.

Receipt-email delivery is not the exact payment, credit-debit, or
auto-recharge-trigger timestamp. The local schema exposes response usage
counters but no field for included-plan headroom or reset bucket, paid-credit
classification, usage-credit balance transition, auto-recharge trigger,
invoice/payment join, or provider-billed dollars. The local record therefore
does not prove that the bracketed responses caused the transactions or
independently prove the reported reset state.

## Independent-verification gap

Anthropic's current help article says all four of the following:

1. usage credits are the continuation mechanism after included plan limits are
   reached;
2. the customer should see a notification when the included session limit is
   reached;
3. the Usage dashboard clearly distinguishes included-plan usage from paid
   credit consumption; and
4. included limits reset every five hours, with usage credits not changing
   that reset timing.

The public record does not yet contain a stable event-level key that joins the
account-visible state to the payment chain. That is the decisive independent-
verification gap—not the existence or amount of the two payments.

| Required join element | Current evidence state |
| --- | --- |
| Subscription entitlement and applicable included-limit buckets | Visible only inside the account and Anthropic's internal ledger; not independently joined to either payment |
| Exact reset timestamp and customer notification | Customer-observed; no public timestamped capture presently proves the exact transition |
| Claude Code request/session after reset | Customer-observed; no Anthropic-issued request key publicly joins it to a paid-credit debit |
| Usage-credit debit and balance transition | Held in Anthropic's account ledger; no stable public event key joins it to the reset or request |
| Auto-recharge trigger, invoice, and payment | Two original merchant transaction pairs prove the recharge objects and amounts; originals delivered privately |
| Correction or refund | No original-payment refund or human billing decision confirmed |

### Minimum independently reviewable packet

A reviewer could test the account-visible part of this chain without receiving
payment identifiers if a sanitized, timestamped capture showed:

1. the applicable included-limit buckets immediately before and after reset;
2. any notification that Claude says authorizes switching to usage credits;
3. the usage-credit balance immediately before and after a named Claude Code
   request or bounded session; and
4. the next matching recharge notification, with private identifiers redacted.

Even that packet would not prove Anthropic's server-side classification by
itself. Anthropic must disclose a safe reconciliation key—or a signed mapping
using its internal identifiers—that joins the request, entitlement decision,
paid-credit debit, recharge trigger, invoice, payment, and any correction.

## Records only Anthropic can supply

For each disputed debit and recharge, Anthropic should preserve and reconcile:

1. the effective subscription entitlement and every applicable included-limit
   bucket;
2. the exact reset timestamp and timezone;
3. the model or feature-specific gate Anthropic believes remained exhausted;
4. request-level included-plan-versus-paid-credit routing decisions;
5. usage-credit debit timestamps and amounts;
6. automatic-recharge trigger records;
7. invoice creation, payment authorization, capture, correction, and refund
   events; and
8. the safe processor references connecting those events.

Anthropic should also state which stable event or reconciliation key an
independent reviewer can use to verify the full chain without exposing card or
account identifiers.

## Requested resolution

- Refund the remaining **USD 980.41** to the original payment method or methods.
- Assign a human Billing Platform / payment-operations owner.
- Provide a transaction-level written reconciliation.
- Prevent automatic recharges while entitlement and included-limit state
  disagree or immediately after a limit reset.

## Scope

This August 1 record is separate from the July 17 mass usage-credit incident.
It does not alter the July 17 amounts or add any manual top-up. Earlier dates
and July 18 remain outside the quantified July 17 demand unless Anthropic's
transaction-level evidence establishes a connection.

## Public sources

- Dedicated Anthropic tracker: https://github.com/anthropics/claude-code/issues/83062
- Standalone X evidence post: https://x.com/Coolak777/status/2083460796391313844
- Standalone LinkedIn evidence post: https://www.linkedin.com/feed/update/urn:li:share:7489228962053935104/
- Anthropic usage-credit documentation: https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans
- Same-day report #83036: https://github.com/anthropics/claude-code/issues/83036
- Same-day report #83037: https://github.com/anthropics/claude-code/issues/83037
- Same-day subscription-sync / `credits_required` report #83093: https://github.com/anthropics/claude-code/issues/83093
- August 1-2 high-dollar auto-recharge / no-alert report #85912: https://github.com/anthropics/claude-code/issues/85912
- Later August phantom-usage / claimed backend-loop report: https://www.reddit.com/r/Anthropic/comments/1vdtir3/massive_phantom_usage_bug_draining_promax_plans/
- Later August idle Max-usage / auto-recharge report: https://www.reddit.com/r/ClaudeAI/comments/1vf6i4y/max_20x_usage_went_from_0_to_100_in_half_an_hour/
- August 2 Max-plan credit-gate report #83242: https://github.com/anthropics/claude-code/issues/83242
- August 7 Max-plan credit-gate report #84694: https://github.com/anthropics/claude-code/issues/84694
- August 12 Max-plan quota-consumption report #86033: https://github.com/anthropics/claude-code/issues/86033
- August 12 Pro-plan post-reset quota-exhaustion report #85992: https://github.com/anthropics/claude-code/issues/85992
- July 30 near-date Opus 4.6 report: https://www.reddit.com/r/Anthropic/comments/1vaywsv/why_is_claude_using_usage_credits_when_i_havent/
- July 27 post-reset idle-usage / auto-reload report: https://www.reddit.com/r/Claude_reports/comments/1v81ons/rclaudeai_has_anyone_noticed_claude_max_usage/
- July 30 rapid Max-limit depletion / support-bot report: https://www.reddit.com/r/ClaudeAI/comments/1v86ls8/comment/p03r5rt/
- July 24 promotional-credit activation / warning report: https://www.reddit.com/r/Anthropic/comments/1v1pid7/comment/oypda3o/
- Official Claude status page: https://status.claude.com/
- Stripe Japan complaints route: https://stripe.com/en-jp/complaints
- Link terms: https://link.com/jp/terms
- Link contracting entity for Japan residents: https://link.com/en-jp/terms/contracting-entity
- Evidence hub: https://coolak.github.io/anthropic-claude-billing-incident/
