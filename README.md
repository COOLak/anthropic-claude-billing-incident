# Anthropic / Claude Usage-Credit Billing Incident

This repository is a privacy-sanitized public evidence hub for an unresolved Anthropic / Claude billing issue.

## Short Summary

A high-usage Claude customer cannot reliably complete manual prepaid usage-credit purchases through Anthropic's billing flow. The manual purchase path fails or loses the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

The issue should not be handled as a generic card-decline problem. The reported contradiction is that recurring automatic charging works, but manual prepaid purchasing does not. After earlier generic card-decline guidance, the latest private support direction points toward specialized billing-team review, but support has not confirmed a human Billing Platform / payment-operations owner, written explanation, or restored manual purchase path.

## Public Evidence Links

- Hosted public incident page: https://coolak.github.io/anthropic-claude-billing-incident/
- Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/reporter-brief.html
- Billing owner action packet: https://coolak.github.io/anthropic-claude-billing-incident/owner-action.html
- Public evidence hub: https://gist.github.com/COOLak/65af43d03d2b464d50c95cd4648ccf96
- Anthropic GitHub billing-pattern issue comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Reddit evidence thread: https://www.reddit.com/r/Anthropic/comments/1v5mz45/claude_autoreload_works_but_the_failed_1000for700/
- X thread: https://x.com/Coolak777/status/2080754353426833646
- LinkedIn post: https://www.linkedin.com/feed/update/urn:li:share:7486522880319442944/

## Related Public Reports

These links are pattern context, not proof of this customer's private account records.

- Anthropic Help Center states that purchased credits should be immediately available and describes auto-reload behavior: https://support.claude.com/en/articles/8977456-how-do-i-pay-for-my-claude-api-usage
- Anthropic Help Center describes support as Fin first, then Product Support by email when escalation is required: https://support.claude.com/en/articles/9015913-how-to-get-support
- Reddit report about paid credit purchases charged or invoiced but not landing in the expected Claude or Console balance: https://www.reddit.com/r/Anthropic/comments/1t4bs6y/three_credit_purchases_havent_posted_to_my/
- GitHub issue about Claude Code still showing low credit balance after top-up: https://github.com/anthropics/claude-code/issues/31537
- GitHub issue about API-credit purchase failure after successful bank-side 3D Secure authentication: https://github.com/anthropics/claude-code/issues/45361
- GitHub issue about Max upgrade payment failures across multiple cards while banks reportedly saw no decline and support was unresponsive: https://github.com/anthropics/claude-code/issues/56281
- GitHub issue about the Anthropic Console "Buy credits" button staying disabled with inconsistent tier and spend-limit state: https://github.com/anthropics/claude-code/issues/62644
- GitHub issue about a Claude plan upgrade failing while same-card extra usage credits succeeded on the same account: https://github.com/anthropics/claude-code/issues/57122
- GitHub issue about purchased usage credits remaining unusable behind a separate monthly spend-limit control: https://github.com/anthropics/claude-code/issues/77703
- GitHub issue about usage credits being consumed while included plan allowance reportedly remained available: https://github.com/anthropics/claude-code/issues/80750
- Reddit report about paid credits showing in settings while Claude still treated the user as out of usage, plus support submission failure: https://www.reddit.com/r/Anthropic/comments/1st5uxf/claude_wont_recognize_my_paid_credits_support_is/
- Hacker News discussion with a separate unresolved Anthropic billing-support complaint after promised human review: https://news.ycombinator.com/item?id=47693679

## Current Status

Anthropic billing remains unresolved based on the public evidence currently available. A real fix would require at least one of:

- a working manual prepaid usage-credit purchase path at the advertised discounted terms;
- an equivalent credit or discount adjustment applied by Anthropic;
- a written Billing Platform / payment-operations explanation of why manual prepay failed while automatic top-ups worked;
- assurance that the failed or stuck manual purchase state did not consume discount eligibility, create hidden payment debt, or penalize the account.

## Privacy Boundary

This repository intentionally omits:

- card endings or full payment card details;
- bank names;
- payment processor object IDs;
- invoice or receipt identifiers;
- raw browser/network logs;
- screenshots;
- payment URLs;
- one-time codes;
- private support-thread bodies;
- addresses, identity documents, or document numbers;
- agency report numbers.

Sensitive evidence should only be shared through safer channels with authorized reviewers or reporters when necessary.
