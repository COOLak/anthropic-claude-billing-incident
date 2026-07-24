# Public Incident Brief

## Core Issue

Manual prepaid Claude usage-credit purchases fail or lose the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

Bank-side information reported by the customer says the failed manual prepay attempts do not appear as real authorization attempts, while successful automatic top-ups do go through.

## Why It Matters

Anthropic sells usage credits to customers who may depend on Claude for ongoing work. Automatic top-ups continuing to charge is not a fix. It is evidence that the billing platform can charge the account while the manual prepaid-credit path remains broken.

## Routes Already Advanced

- Claude Support / Fin billing thread.
- Anthropic support route.
- FTC ReportFraud.
- San Francisco DA consumer mediation intake.
- San Francisco City Attorney business-practices complaint.
- Public evidence surfaces on Reddit, X, LinkedIn, GitHub, and a public gist.
- Privacy-sanitized media tips to several relevant outlets.

## Current Public Framing

Anthropic / Claude manual prepaid usage-credit purchases fail or lose discounted checkout state, while automatic top-ups from the same saved billing setup continue charging successfully, and support has not produced a human billing owner or explanation.

Hosted public incident page: https://coolak.github.io/anthropic-claude-billing-incident/

Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/reporter-brief.html

Billing owner action packet: https://coolak.github.io/anthropic-claude-billing-incident/owner-action.html

## Related Public Reports

These links are pattern context, not proof of this customer's private account records.

- Anthropic Help Center states that purchased credits should be immediately available and describes auto-reload behavior: https://support.claude.com/en/articles/8977456-how-do-i-pay-for-my-claude-api-usage
- Anthropic Help Center describes support as Fin first, then Product Support by email when escalation is required: https://support.claude.com/en/articles/9015913-how-to-get-support
- Reddit report about paid credit purchases charged or invoiced but not landing in the expected Claude or Console balance: https://www.reddit.com/r/Anthropic/comments/1t4bs6y/three_credit_purchases_havent_posted_to_my/
- GitHub issue about Claude Code still showing low credit balance after top-up: https://github.com/anthropics/claude-code/issues/31537
- GitHub issue about a Claude plan upgrade failing while same-card extra usage credits succeeded on the same account: https://github.com/anthropics/claude-code/issues/57122
- Reddit report about paid credits showing in settings while Claude still treated the user as out of usage, plus support submission failure: https://www.reddit.com/r/Anthropic/comments/1st5uxf/claude_wont_recognize_my_paid_credits_support_is/
- Hacker News discussion with a separate unresolved Anthropic billing-support complaint after promised human review: https://news.ycombinator.com/item?id=47693679

## What Would Count As Resolution

The case should not be treated as resolved unless Anthropic provides a working manual prepaid purchase path, applies an equivalent adjustment, or gives a written Billing Platform / payment-operations explanation that reconciles manual prepay failure with successful automatic top-ups.
