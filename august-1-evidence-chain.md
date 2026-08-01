# August 1 Post-Reset Auto-Recharge Evidence Chain

Updated: 2026-08-01 16:02 JST

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

## Proof boundary

| Evidence | What it establishes | What it does not establish |
| --- | --- | --- |
| Original merchant invoices and receipts | Two successful Individual-plan automatic recharges; amounts; total; stated payment method | Precise included-limit reset time; request routing; credit-debit cause |
| Customer-observed reset-to-credit-drain sequence | The account-visible order of reset, continued credit use, recharge, and shutdown control | Anthropic's internal entitlement state or model-specific gate |
| Anthropic usage-credit documentation | Published rule that usage credits apply after included limits, session limits reset every five hours, and credits do not change reset timing | What Anthropic's servers recorded for this account at each disputed debit |
| Same-day reports #83036 and #83037 | Independently inspectable reports of credit-gate behavior despite visible plan allowance | This account's payment path, a shared root cause, or aggregate loss |
| Dual private delivery to Link and Anthropic | Both relevant parties have the original transaction records needed to investigate | Receipt acknowledgment, fault admission, refund approval, or settlement |

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
- Anthropic usage-credit documentation: https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans
- Same-day report #83036: https://github.com/anthropics/claude-code/issues/83036
- Same-day report #83037: https://github.com/anthropics/claude-code/issues/83037
- Evidence hub: https://coolak.github.io/anthropic-claude-billing-incident/
