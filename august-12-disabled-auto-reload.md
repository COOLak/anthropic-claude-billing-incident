# August 12 Disabled Auto-Reload Charge Evidence

Two original Anthropic invoice/receipt pairs document Claude Individual
`Auto-recharge credits` of **USD 49.88** and **USD 49.20**, totaling
**USD 99.08**. The customer states Auto-reload was disabled before both
transactions and blocked the funding card after the second charge.

## Verified merchant-document record

| Receipt email delivered (JST) | Amount | Merchant line item |
| --- | ---: | --- |
| 2026-08-12 05:13:57 | USD 49.88 | `Auto-recharge credits` |
| 2026-08-12 05:56:55 | USD 49.20 | `Auto-recharge credits` |
| **Total** | **USD 99.08** | **Two completed automatic purchases** |

The private originals establish the two completed automatic credit-purchase
objects, amounts, stated line items, and payment method. They are not manual
top-ups and are not Anthropic Console or API-workspace invoices. Private
identifiers are omitted from this public record.

## Signed-in disabled-state capture

The signed-in Claude Billing capture at
[`august-12-auto-reload-disabled.jpg`](./august-12-auto-reload-disabled.jpg)
was taken at **2026-08-12 06:20 JST**, approximately 24 minutes after the
second receipt email arrived. The visible **Turn on** button establishes that
the customer-facing Auto-reload control was off when captured.

**Evidence boundary:** this post-charge screenshot does not independently
prove the earlier disable timestamp or the setting state at each internal
recharge trigger. Anthropic controls the historical setting-change,
configuration-version, queue, threshold-evaluation, authorization, capture,
retry, and refund logs required to establish that sequence.

## Authenticated July 27 first-party email record

An authenticated Claude email was delivered on **2026-07-27 16:00:22 UTC**
(**2026-07-28 01:00:22 JST**), fifteen days before the two August 12 receipt
emails. Its first-party sender domain passed DKIM, SPF, and DMARC. Its exact
Subject header is:

> We turned off auto-reload on your Claude Code account

The body does **not** repeat or confirm that setting-change statement. Instead,
it describes Anthropic's July 17 billing correction and the USD 3.11 account
credit. That subject/body mismatch matters: the Subject header is first-party,
pre-charge evidence consistent with the customer's account, but the message is
not conclusive proof of a successful user-requested disable action or that the
disabled state persisted through either August 12 internal trigger.

A Gmail search covering July 26 through August 12 found no later Anthropic
email stating that Claude Auto-reload had been enabled. That absence is not
proof that no re-enable event occurred, because Anthropic's notification
behavior is not established. Anthropic must reconcile the authenticated
message header with its authoritative setting-change and billing-worker logs.

## Anthropic's documented control model

Anthropic's current
[paid-plan usage-credit guide](https://support.claude.com/en/articles/12429409-manage-usage-credits-for-paid-claude-plans)
describes usage credits as part of paid Claude plans, says Auto-reload can be
enabled to make an automatic purchase when the balance falls below a
customer-set threshold, lists Auto-reload settings as a spending control, and
says usage credits apply to Claude Code.

That first-party guide establishes the intended customer control model and the
paid-plan classification. It does not prove this account's historical toggle
state or disclose whether already queued work survives a switch-off. Those
facts still require Anthropic's timestamped configuration and trigger records.

## Separate incident and separate demand

This later disabled-Auto-reload incident does not change the earlier
automatic-only demand of **USD 1,600.38**. The later demand is exactly
**USD 99.08**. The arithmetic exposure across the separate tracks is
**USD 1,699.46**, but that figure is not one merged case demand.

The card block was a protective action, not an allegation of stolen credentials
and not a chargeback.

## Requested records and remedy

1. Refund USD 49.88 and USD 49.20, totaling USD 99.08, to the original payment
   method.
2. Confirm that Auto-reload is disabled across the relevant Claude Individual
   account and organization.
3. Preserve and disclose the setting-change audit log and the trigger, queue,
   authorization, capture, retry, invoice, and refund records.
4. State the exact disable-action and internal purchase-trigger timestamps.
5. Explain how both purchases executed if the control was disabled at their
   trigger times, or provide timestamped evidence that it was enabled.

Written communication only. No call or meeting is requested or authorized.

## Related public reports

- Dedicated issue for this August 12 incident:
  https://github.com/anthropics/claude-code/issues/85937

- Earlier disabled-Auto-reload charge report:
  https://github.com/anthropics/claude-code/issues/14857
- Extra-usage re-enable and spend-limit report:
  https://github.com/anthropics/claude-code/issues/25647
- Open consumer auto-recharge-loop and escalation report:
  https://github.com/anthropics/claude-code/issues/68773
- Closed API/prepaid-credit drain report:
  https://github.com/anthropics/claude-code/issues/29108
- Closed API/prepaid-credit follow-up:
  https://github.com/anthropics/claude-code/issues/53292

These are separate users' reports. They do not prove this account's historical
setting state, transactions, a shared root cause, or aggregate loss. Issues
#29108 and #53292 describe credit consumption after an API-key/session event,
not completed Claude Individual automatic purchase objects. Issue #68773 is a
broader open consumer auto-recharge-loop and support-escalation thread; the
August 12 incident documented here is the narrower disabled-control and
completed-purchase sequence.
