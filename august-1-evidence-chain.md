# August 1 Post-Reset Auto-Recharge Evidence Chain

Updated: 2026-08-01 19:32 JST

Status: unresolved. No original-payment refund or human Anthropic billing
decision has been confirmed.

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

Stripe's Link terms generally place responsibility for product or service
refunds with the merchant. The complaint therefore targets Link's handling,
preservation, referral, and written transaction disposition; it does not allege
that Stripe caused Anthropic's entitlement or routing behavior.

## Proof boundary

| Evidence | What it establishes | What it does not establish |
| --- | --- | --- |
| Original merchant invoices and receipts | Two successful Individual-plan automatic recharges; amounts; total; stated payment method | Precise included-limit reset time; request routing; credit-debit cause |
| Customer-observed reset-to-credit-drain sequence | The account-visible order of reset, continued credit use, recharge, and shutdown control | Anthropic's internal entitlement state or model-specific gate |
| Anthropic usage-credit documentation | Published rule that usage credits apply after included limits, session limits reset every five hours, and credits do not change reset timing | What Anthropic's servers recorded for this account at each disputed debit |
| Same-day reports #83036 and #83037 | Independently inspectable reports of credit-gate behavior despite visible plan allowance | This account's payment path, a shared root cause, or aggregate loss |
| Privacy-redacted local timestamp bridge | 2,860 deduplicated response-usage records establish contemporaneous Claude Code activity immediately before and after both receipt-email deliveries | The reset state, paid-credit classification, recharge trigger, transaction causation, or provider-billed dollars |
| Dual private delivery to Link and Anthropic | Both relevant parties have the original transaction records needed to investigate | Fault admission, refund approval, or settlement |
| Formal Stripe/Link complaint and receipt acknowledgment | Stripe received a written complaint covering all sixteen originals and eight automatic transactions | Investigation result, fault finding, refund approval, reversal, settlement, or final decision |

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

- Refund the full **USD 995.67** to the original payment method or methods.
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
- Stripe Japan complaints route: https://stripe.com/en-jp/complaints
- Link terms: https://link.com/jp/terms
- Link contracting entity for Japan residents: https://link.com/en-jp/terms/contracting-entity
- Evidence hub: https://coolak.github.io/anthropic-claude-billing-incident/
