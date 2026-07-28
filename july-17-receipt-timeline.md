# July 17 Receipt-Delivery Timeline: $704.71 Across 18h 47m 50s

Updated: 2026-07-28 09:28 JST

Status: public-safe account evidence; original-payment refund unresolved

Classification: **Claude subscription / Individual-plan extra-usage credits.
This is not Console or API-workspace billing.**

Scope note: the disputed amount remains **$704.71**. The affected period may
potentially extend to earlier dates and July 18, but that has not yet been
established; adjacent-date charges remain outside the current total unless
Anthropic's transaction-level records connect them to the same incident.

## What the Receipt Evidence Shows

All seven first-party Anthropic/Stripe receipt emails contain the statement **Paid July 17, 2026**. Together they total **$704.71**.

The mailbox delivery timestamps span from **2026-07-17 09:59:43 UTC** to **2026-07-18 04:47:33 UTC**—an elapsed span of **18 hours, 47 minutes, 50 seconds**.

Compared with Anthropic's stated automated correction window of **18:16–18:47 UTC**:

- one receipt email totaling **$100.00** arrived before the window;
- one receipt email totaling **$97.12** arrived during the window; and
- five receipt emails totaling **$507.59** arrived after the window.

Therefore, **$607.59**, or **86.2%** of the seven-receipt total, appears in receipt emails delivered outside Anthropic's stated window.

## Public-Safe Timeline

| Receipt-email delivery (UTC) | Amount | Type | Relation to 18:16–18:47 UTC |
|---|---:|---|---|
| July 17 09:59:43 | $100.00 | One-time credit purchase | Before |
| July 17 18:33:49 | $97.12 | Automatic extra-usage recharge | Inside |
| July 17 19:51:34 | $108.46 | Automatic extra-usage recharge | After |
| July 17 21:08:28 | $95.21 | Automatic extra-usage recharge | After |
| July 17 21:48:33 | $101.05 | Automatic extra-usage recharge | After |
| July 17 22:50:04 | $97.51 | Automatic extra-usage recharge | After |
| July 18 04:47:33 | $105.36 | Automatic extra-usage recharge; receipt body says Paid July 17 | After |
| **Total** | **$704.71** | **Six automatic recharges + one purchase** | **$607.59 outside** |

## What This Does Not Prove

An email delivery timestamp is not necessarily the internal usage-credit debit, auto-recharge trigger, payment authorization, or invoice-creation timestamp. This timeline therefore does not claim that each charge was caused by the acknowledged incident solely because its receipt email arrived outside Anthropic's stated window.

It does prove that:

1. all seven first-party receipt bodies classify the payments as Paid July 17;
2. the account's receipt evidence cannot be reconciled by pointing only to one 31-minute interval; and
3. Anthropic must produce the underlying transaction timestamps and entitlement-routing ledger to establish which charges were correct.

## Required Reconciliation

For each of the seven receipts, Anthropic should disclose:

1. the usage event or events that triggered the paid-credit debit;
2. included-plan entitlement immediately before the debit;
3. the exact paid-credit debit timestamp;
4. the exact auto-recharge trigger and payment timestamps;
5. invoice creation and receipt delivery timestamps; and
6. whether the charge has been refunded to the original payment method.

## Privacy Boundary

This public timeline intentionally excludes receipt numbers, invoice numbers, payment-method details, account identifiers, download links, and private support text. Those records remain available for private verification.

## Related Public Evidence

- Anthropic's official incident: https://status.anthropic.com/incidents/g613ntyj2pwf
- Dedicated Anthropic-owned tracker: https://github.com/anthropics/claude-code/issues/81703
- Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/july-17-reporter-brief.html
- Full evidence brief: https://coolak.github.io/anthropic-claude-billing-incident/july-17-usage-credit-refund.html

## Public Discussion

- X receipt-timeline update: https://x.com/Coolak777/status/2081898318754677167
- r/ClaudeCode incident thread: https://www.reddit.com/r/ClaudeCode/comments/1v85cuh/july_17_mass_billing_incident_anthropic/
- r/Anthropic ledger-reconciliation thread: https://www.reddit.com/r/Anthropic/comments/1v85sj5/was_your_full_july_17_usagecredit_ledger/

The two Reddit links are existing incident posts edited in place to add this receipt timeline. No duplicate Reddit post or correction comment was created for this update.
