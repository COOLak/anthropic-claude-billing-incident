# July 17 Incident: Anthropic-Owned GitHub Issue Cluster

Updated: 2026-07-28 02:48 JST

Customer-case classification: **Claude subscription / Individual-plan
extra-usage credits. This is not Console or API-workspace billing.**

Scope note: the disputed amount remains **$604.71**. The affected period may
potentially extend to earlier dates and July 18, but that has not yet been
established; adjacent-date charges remain outside the current total unless
Anthropic's transaction-level records connect them to the same incident.

Anthropic's official status record acknowledges the July 17, 2026 incident. This page adds a contemporaneous source trail from Anthropic's own `anthropics/claude-code` issue tracker.

## Evidence Boundary

- These are public customer reports filed in an Anthropic-owned repository, not company-authored findings.
- Several issues were marked as duplicates, which is evidence of clustering rather than nine independent root causes.
- Issue and comment counts are not a unique-user count.
- The issue bodies establish access, entitlement, and usage-credit-gate symptoms. They generally do not prove payment-method charges, refund amounts, or any combined loss.
- Feedback IDs, usernames, screenshots, and other reporter identifiers are intentionally omitted here.
- Some source reports use API-related terminology for their own symptoms. That
  language does not reclassify this customer's subscription dispute.

## Issue Burst

Nine closely related issues were opened between `18:17:40` and `19:24:29` UTC on July 17:

| Issue | Opened UTC | Publicly stated context | Public state / evidentiary value |
| --- | --- | --- | --- |
| [#78610](https://github.com/anthropics/claude-code/issues/78610) | 18:17:40 | Active subscription usage reportedly remained; comments describe mid-conversation interruption, `45%` and `50%` remaining, missing usage meter, macOS/Windows, and web/Claude Code impact | Open; 13 comments; strongest same-minute multi-user cluster |
| [#78611](https://github.com/anthropics/claude-code/issues/78611) | 18:29:14 | Original report said “I have limits”; a comment said the account was not close to its limit | Open; labeled duplicate; five comments |
| [#78614](https://github.com/anthropics/claude-code/issues/78614) | 18:33:50 | Usage credits were required mid-session even though included access was expected to continue | Open; labeled duplicate and `area:cost` |
| [#78615](https://github.com/anthropics/claude-code/issues/78615) | 18:34:27 | Original report said usage was around `12%`; a second user reported the same issue on Windows 11 | Closed later as a duplicate of #78614 |
| [#78616](https://github.com/anthropics/claude-code/issues/78616) | 18:34:57 | Max plan showed `24%` session and `28%` weekly usage while the model required credits | Open; labeled duplicate and `area:cost` |
| [#78620](https://github.com/anthropics/claude-code/issues/78620) | 18:44:11 | Included access was expected through July 19; comments recorded the credit gate and its apparent fix | Open; labeled duplicate and `area:cost` |
| [#78623](https://github.com/anthropics/claude-code/issues/78623) | 18:49:16 | New Claude Code sessions requested API credits before the announced metering date | Closed by the reporter after the transient issue appeared fixed |
| [#78633](https://github.com/anthropics/claude-code/issues/78633) | 19:22:03 | The reporter said the same failure appeared in Claude Code and Claude.ai while another included model still worked | Open; labeled duplicate and `area:cost`; comments add Linux and continuing-impact reports |
| [#78634](https://github.com/anthropics/claude-code/issues/78634) | 19:24:29 | Usage credits were required two days before the expected billing change | Open; labeled `area:cost` |

## What This Establishes

The tracker record independently corroborates:

1. an abrupt, tightly clustered July 17 event;
2. affected reports across macOS, Linux, Windows, Claude Code, and Claude.ai;
3. multiple reports with stated included-plan headroom, including approximately `12%`, `24%` session / `28%` weekly, `45%`, and `50%` usage positions;
4. mid-session interruption and disappearance of the included-model usage meter; and
5. issue deduplication around the same “usage credits required” failure.

The tracker record does **not** answer how many affected accounts incurred credit debits, auto-reloads, invoices, or payment-method charges. Only Anthropic's internal entitlement, usage-credit, and payment records can establish that.

## Relationship to the Official Incident

The issue burst overlaps Anthropic's status timeline. A public comment on [#78610](https://github.com/anthropics/claude-code/issues/78610#issuecomment-5006539538) records the `18:48 UTC` status update that Anthropic had applied a fix for the erroneous usage-credit requirement.

The public issue cluster therefore provides a customer-side chronology around the company acknowledgment, while the official status page remains the authoritative company statement:

https://status.anthropic.com/incidents/g613ntyj2pwf

## Questions Only Anthropic Can Resolve

1. How many accounts encountered the credit gate while included entitlement remained?
2. How many of those accounts had usage credits enabled?
3. How many credit debits, auto-reloads, invoices, or payment-method charges occurred?
4. Did Anthropic reconcile every affected account's complete July 17 ledger or only a narrow incident window?
5. Why do some account corrections appear as expiring account credit instead of refunds to the original payment method?

## Related Resources

- Full July 17 evidence brief: https://coolak.github.io/anthropic-claude-billing-incident/july-17-usage-credit-refund.html
- Public report matrix: https://coolak.github.io/anthropic-claude-billing-incident/july-17-mass-report-matrix.html
- Reporter verification brief: https://coolak.github.io/anthropic-claude-billing-incident/july-17-reporter-brief.html
- Dedicated $604.71 tracker: https://github.com/anthropics/claude-code/issues/81703
