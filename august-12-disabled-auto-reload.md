# August 12 Automatic-Charge Evidence — Auto-Reload Off at Capture

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

## Customer-visible processor correlation

Read-only customer-visible Stripe hosted-invoice records now independently map
each merchant document pair to a distinct successful payment chain:

| Amount | Payment object created (JST) | Invoice-payment state |
| --- | --- | --- |
| USD 49.88 | 2026-08-12 05:12:29 | Paid at 05:12:32 |
| USD 49.20 | 2026-08-12 05:55:28 | Paid at 05:55:30 |

Both chains use the same card-type Stripe payment-method object. The private
Stripe invoice, PaymentIntent, invoice-payment, and payment-method identifiers
are withheld from this public record but have been supplied in the existing
Anthropic, Link, and Stripe complaint threads.

**Evidence boundary:** these records prove two successful paid processor chains
and provide transaction-level correlation. They do not prove the Auto-reload
setting at either trigger, explain why Anthropic created the purchases, or
establish whether the charges were correct. Anthropic controls the historical
configuration, queue, threshold, trigger, and merchant-side refund records.

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

The same guide separately says that disabling usage credits restricts the
account to included-plan usage, that included limits continue to reset every
five hours, and that paid credits do not change that reset timing. It also says
the dashboard distinguishes included-plan use from paid-credit use and that a
notification and confirmation precede the switch to paid credits.

Auto-reload and usage-credit access are therefore distinct controls in
Anthropic's own model: Auto-reload governs automatic funding of the credit
balance, while usage-credit access governs whether an available paid balance
may be consumed. This record alleges that Auto-reload was off; it does not
allege that the separate usage-credit-access control was off.

That first-party guide establishes the intended customer control model and the
paid-plan classification. It does not prove this account's historical toggle
state or disclose whether already queued work survives a switch-off. Those
facts still require Anthropic's timestamped configuration and trigger records.

## Independent publication status

[Future Stack Reviews' Tier C, document-first July 17 report](https://future-stack-reviews.com/claude-fable-5-usage-credit-error-july-17/)
was updated on August 12 to cite Anthropic issue #85937 as one visible public
report. The update records the two reported amounts, the signed-in screenshot
taken after the charges, and the limitation that the capture does not establish
the Auto-reload state at either internal purchase trigger.

Future Stack Reviews expressly says it did not reproduce or verify the event,
holds no record of the account, and takes no position on whether the charges
were correct. Its update independently establishes publication and review of
the public report, not the account-level facts, a shared mechanism, refund
entitlement, or any return of funds.

## Separate incident and separate demand

This later disabled-Auto-reload incident does not change the earlier
automatic-only demand of **USD 1,600.38**. The later demand is exactly
**USD 99.08**. The arithmetic exposure across the separate tracks is
**USD 1,699.46**, but that figure is not one merged case demand.

The card block was a protective action, not an allegation of stolen credentials
and not a chargeback.

## Verified regulatory intake status

On August 12, one standalone FTC ReportFraud filing for this USD 99.08 incident
was accepted and entered Consumer Sentinel. The filing preserves the same proof
boundaries and does not merge this demand with the separate USD 1,600.38 track.
This is verified intake status only: it is not an FTC finding, investigation
confirmation, or individual-refund decision. The report number and private
submission record are withheld from this public page.

On the same date, one application covering only this separate USD 99.08 event
was sent through Japan's official [Specified Commercial Transactions Act
Article 60 procedure](https://www.caa.go.jp/policies/policy/consumer_transaction/specified_commercial_transactions/disobey_form/)
to the Consumer Affairs Agency. The submission preserved the screenshot and
causal-proof limitations and did not resend or enlarge the earlier USD 1,600.38
demand. This is filing status only, not an agency finding, investigation result,
individual-refund decision, or confirmation of a legal violation.

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

A July 20 r/ClaudeAI discussion contains conflicting anecdotal outcomes for
Auto-reload-off accounts. [One commenter](https://www.reddit.com/r/ClaudeAI/comments/1v216k9/comment/oyrxjso/)
said a Fable task continued after the available credits were exhausted and
generated a USD 40 charge even though Auto-reload was off. [Another
commenter](https://www.reddit.com/r/ClaudeAI/comments/1v216k9/comment/oys7tlt/)
said they repeatedly reached included-plan limits with Auto-reload off and had
never received an unexpected extra charge. Neither account supplies original
transaction documents or Anthropic's trigger-time records. The contradictory
reports do not prove this account's state, a common mechanism, or any aggregate
loss; they reinforce why the customer-facing control and the server-side
configuration, in-flight-task, trigger, and purchase logs must be reconciled
rather than inferred.

A current [r/claude report concerning August 9-10
transactions](https://www.reddit.com/r/claude/comments/1vkgdx3/i_just_got_fully_robbed_by_anthropic/)
alleges that Extra Usage re-enabled itself twice and that a customer-set spend
cap reverted to USD 20,000 after the reporter turned Extra Usage off and reset
the cap. The post shows a list of paid transactions and describes multiple
charges; several commenters describe other unexpected re-enablement or charge
experiences, while other commenters raise account or session compromise as an
alternative explanation. The post does not supply original merchant or
processor records, historical configuration logs, or Anthropic's trigger
records. It is a separate user's anecdotal report, not proof of this account's
state, a shared cause, aggregate loss, or refund entitlement. It strengthens
the case for immutable, timestamped configuration, session, trigger, and
purchase logs rather than inference from the current UI alone.
