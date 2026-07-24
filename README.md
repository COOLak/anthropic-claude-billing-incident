# Anthropic / Claude Usage-Credit Billing Incident

This repository is a privacy-sanitized public evidence hub for an unresolved Anthropic / Claude billing issue.

## Short Summary

A high-usage Claude customer cannot reliably complete manual prepaid usage-credit purchases through Anthropic's billing flow. The manual purchase path fails or loses the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

The issue should not be handled as a generic card-decline problem. The reported contradiction is that recurring automatic charging works, but manual prepaid purchasing does not, and support has not produced a human Billing Platform / payment-operations owner or written explanation.

## Public Evidence Links

- Public evidence hub: https://gist.github.com/COOLak/65af43d03d2b464d50c95cd4648ccf96
- Anthropic GitHub billing-pattern issue comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Reddit evidence thread: https://www.reddit.com/r/Anthropic/comments/1v5mz45/claude_autoreload_works_but_the_failed_1000for700/
- X thread: https://x.com/Coolak777/status/2080754353426833646
- LinkedIn post: https://www.linkedin.com/feed/update/urn:li:share:7486522880319442944/

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
