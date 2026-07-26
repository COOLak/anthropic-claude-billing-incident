# Public Incident Brief

## Core Issue

Manual prepaid Claude usage-credit purchases fail or lose the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

Bank-side information reported by the customer says the failed manual prepay attempts do not appear as real authorization attempts, while successful automatic top-ups do go through.

## Why It Matters

Anthropic sells usage credits to customers who may depend on Claude for ongoing work. Automatic top-ups continuing to charge is not a fix. It is evidence that the billing platform can charge the account while the manual prepaid-credit path remains broken.

## Routes Already Advanced

- Claude Support / Fin billing thread.
- Anthropic support route.
- Latest support posture: specialized billing-team review is now the stated direction, and a direct human connection has been requested, but no human Billing Platform / payment-operations owner or fix is confirmed.
- FTC ReportFraud.
- San Francisco DA consumer mediation intake.
- San Francisco City Attorney business-practices complaint.
- Public evidence surfaces on Reddit, X, LinkedIn, GitHub, and a public gist.
- Privacy-sanitized media tips to several relevant outlets.

## Current Public Framing

Anthropic / Claude manual prepaid usage-credit purchases fail or lose discounted checkout state, while automatic top-ups from the same saved billing setup continue charging successfully. Support now points toward specialized billing-team review, but has not confirmed a human billing owner, written explanation, or restored purchase path.

Hosted public incident page: https://coolak.github.io/anthropic-claude-billing-incident/

Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/reporter-brief.html

Billing owner action packet: https://coolak.github.io/anthropic-claude-billing-incident/owner-action.html

Billing reconciliation matrix: https://coolak.github.io/anthropic-claude-billing-incident/reconciliation-matrix.html

## 2026-07-26 Public Documentation-Caveat Updates

To reduce misdiagnosis by users following third-party Anthropic API setup guides, privacy-sanitized documentation-caveat issues were filed where project docs tell users to purchase Anthropic credits or troubleshoot low-credit API errors. These links are route/context records, not proof of this customer's private billing records.

- Anthropic-owned billing-pattern comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- BM Librarian docs caveat: https://github.com/hherb/bmlibrarian/issues/261
- Claude Computer Use Demo docs caveat: https://github.com/Engmhabib/Claude-Computer-Use-Demo/issues/1
- AI Content Describer docs caveat: https://github.com/cartertemm/AI-content-describer/issues/94
- Archive Studio docs caveat: https://github.com/mhumphries2323/Archive_Studio/issues/4
- AI Maker Space IDE docs caveat: https://github.com/AI-Maker-Space/Interactive-Dev-Environment-for-AI-Engineers/issues/15

## 2026-07-26 Anthropic-Owned Related-Case Comments

Privacy-sanitized related-case comments were posted on open Anthropic-owned billing / usage-credit issues where the failure shape overlaps with manual credit purchasing, credit-ledger reconciliation, or support-routing failures. These links are public route/context records, not proof of this customer's private billing records.

- Billing-pattern / voided-payment state: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Japan API-credit purchase failure: https://github.com/anthropics/claude-code/issues/80055#issuecomment-5075426087
- Prepaid usage-credit commit failure before bank authorization: https://github.com/anthropics/claude-code/issues/73450#issuecomment-5081832536
- Organization credit purchase path fails while subscription billing works: https://github.com/anthropics/claude-code/issues/80178#issuecomment-5081875532
- Add-funds / credit-payment path fails while Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598#issuecomment-5082036072
- Auto-recharge malfunction and no human billing escalation path: https://github.com/anthropics/claude-code/issues/68773#issuecomment-5082050752
- Paid subscription and extra usage credits not reflected in usable account state: https://github.com/anthropics/claude-code/issues/80722#issuecomment-5082058658
- Subscription-to-API billing reroute / credit-ledger support failure: https://github.com/anthropics/claude-code/issues/81078#issuecomment-5082065752
- Subscription entitlement recognized elsewhere while Claude Code demands credits: https://github.com/anthropics/claude-code/issues/80043#issuecomment-5082085230
- Usage-credit crossover / spend-cap messaging mismatch: https://github.com/anthropics/claude-code/issues/74784#issuecomment-5082093660
- Unlimited spend-limit / monthly spend-limit rejection mismatch: https://github.com/anthropics/claude-code/issues/77819#issuecomment-5082106864
- Credit top-up prompt vs monthly extra-usage limit mismatch: https://github.com/anthropics/claude-code/issues/81309#issuecomment-5082131492
- Fable 5 model access redirects to usage credits despite quota remaining: https://github.com/anthropics/claude-code/issues/80836#issuecomment-5082138348
- Plan-included session quota routes to monthly spend-limit / credits path: https://github.com/anthropics/claude-code/issues/79167#issuecomment-5082151107
- Ambiguous out-of-usage-credits prompt drives unnecessary credit purchases: https://github.com/anthropics/claude-code/issues/67412#issuecomment-5082158047
- Paid invoice / account entitlement mismatch: https://github.com/anthropics/claude-code/issues/56895#issuecomment-5081963255
- Double-charge / entitlement downgrade mismatch: https://github.com/anthropics/claude-code/issues/61339#issuecomment-5081979218
- Subscription checkout merchant-side velocity/payment failure: https://github.com/anthropics/claude-code/issues/68941#issuecomment-5081861595
- API-credit purchase fails after bank-side authentication: https://github.com/anthropics/claude-code/issues/45361#issuecomment-5081790944
- Payment fails across cards while support remains unresponsive: https://github.com/anthropics/claude-code/issues/56281#issuecomment-5081796693
- Console Buy Credits path disabled / inconsistent billing state: https://github.com/anthropics/claude-code/issues/62644#issuecomment-5081801725
- Added credits not reflected in usable credit/limit state: https://github.com/anthropics/claude-code/issues/78905#issuecomment-5081888192
- Subscription entitlement not recognized and usage credits charged instead: https://github.com/anthropics/claude-code/issues/79332#issuecomment-5081901655
- Credit-pool accounting charges despite available allowance: https://github.com/anthropics/claude-code/issues/79460#issuecomment-5081913169
- Purchased usage credits unusable behind another control: https://github.com/anthropics/claude-code/issues/77703#issuecomment-5081808734
- Usage-credit accounting / allowance-consumption divergence: https://github.com/anthropics/claude-code/issues/80750#issuecomment-5081815383
- Paid entitlement / billing-ledger mismatch after paid Max state reverts to Free: https://github.com/anthropics/claude-code/issues/70714#issuecomment-5082322216
- Subscription billing mode / runtime API billing mismatch: https://github.com/anthropics/claude-code/issues/77376#issuecomment-5082327220
- Account identity / wrong-account billing-mode risk: https://github.com/anthropics/claude-code/issues/79427#issuecomment-5082335832
- Usage-credit controls / runaway billing after runtime change: https://github.com/anthropics/claude-code/issues/78772#issuecomment-5082340539
- Spend-limit enforcement failure while auto-reload charges continue: https://github.com/anthropics/claude-code/issues/73795#issuecomment-5082344918
- Paid credits / entitlement state and human-support silence: https://github.com/anthropics/claude-code/issues/79566#issuecomment-5082349846
- Fable 5 plan-inclusion copy / usage-credit routing contradiction: https://github.com/anthropics/claude-code/issues/79516#issuecomment-5082396668
- Model picker blocks Fable 5 behind usage-credit setup despite active Max plan: https://github.com/anthropics/claude-code/issues/80889#issuecomment-5082408796
- Setup-token / unattended sessions gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334#issuecomment-5082419553
- Team Premium seat routes Fable 5 to usage credits despite plan inclusion: https://github.com/anthropics/claude-code/issues/80813#issuecomment-5082430054

## Related Public Reports

These links are pattern context, not proof of this customer's private account records.

- Anthropic Help Center states that purchased credits should be immediately available and describes auto-reload behavior: https://support.claude.com/en/articles/8977456-how-do-i-pay-for-my-claude-api-usage
- Anthropic Help Center describes support as Fin first, then Product Support by email when escalation is required: https://support.claude.com/en/articles/9015913-how-to-get-support
- Reddit report about paid credit purchases charged or invoiced but not landing in the expected Claude or Console balance: https://www.reddit.com/r/Anthropic/comments/1t4bs6y/three_credit_purchases_havent_posted_to_my/
- GitHub issue about a paid Claude Max invoice/charge not producing the expected account entitlement: https://github.com/anthropics/claude-code/issues/56895
- GitHub issue about a double-charge after a paid Claude Max plan was reportedly downgraded to Free mid-cycle: https://github.com/anthropics/claude-code/issues/61339
- GitHub issue about Claude Code still showing low credit balance after top-up: https://github.com/anthropics/claude-code/issues/31537
- GitHub issue about extra / prepaid usage-credit purchase failing before a bank authorization attempt reaches issuers: https://github.com/anthropics/claude-code/issues/73450
- GitHub issue about organization credits failing across payment methods while subscription billing reportedly works and Fin auto-closes tickets: https://github.com/anthropics/claude-code/issues/80178
- GitHub issue about Console API access being suspended while add-funds attempts fail at Anthropic and Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598
- GitHub issue about automatic usage-credit recharge looping and Fin being unable to reach a human billing specialist: https://github.com/anthropics/claude-code/issues/68773
- GitHub issue about paid Claude Pro subscription plus extra usage credits not being reflected in usable account state while support remains unanswered: https://github.com/anthropics/claude-code/issues/80722
- GitHub issue about subscription usage being silently rerouted to API credit / pay-per-use billing with no effective human billing escalation: https://github.com/anthropics/claude-code/issues/81078
- GitHub issue about Max subscription being recognized on other Claude surfaces while Claude Code still requires usage credits: https://github.com/anthropics/claude-code/issues/80043
- GitHub issue about extra-usage crossover messaging not disclosing API-rate billing and `/usage-credits` falsely reporting unlimited despite an org spend cap: https://github.com/anthropics/claude-code/issues/74784
- GitHub issue about Claude Code rejecting requests for a monthly spend limit while usage settings showed Unlimited and other meters were not exhausted: https://github.com/anthropics/claude-code/issues/77819
- GitHub issue about the CLI telling users to top up usage credits when the actual blocker is a configured monthly extra-usage limit: https://github.com/anthropics/claude-code/issues/81309
- GitHub issue about `/model` redirecting to usage credits for Fable 5 despite visible Fable 5 weekly quota remaining on a Max plan: https://github.com/anthropics/claude-code/issues/80836
- GitHub issue about the Fable 5 model-switch dialog saying it is billed separately from the plan despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/79516
- GitHub issue about the model picker blocking Fable 5 behind usage-credit setup despite an active Max plan: https://github.com/anthropics/claude-code/issues/80889
- GitHub issue about setup-token / unattended Fable 5 sessions being gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334
- GitHub issue about a Team Premium seat being routed to usage credits for Fable 5 despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/80813
- GitHub issue about setup-token auth losing Fable 5 entitlement and later surfacing server-side credit/rate-limit rejection: https://github.com/anthropics/claude-code/issues/79597
- GitHub issue with multiple Max-plan reports that Fable 5 is gated behind usage credits or server-side limit errors despite included quota, with local tests showing client consent only masks the server-side rejection: https://github.com/anthropics/claude-code/issues/80749
- GitHub issue about Claude Code hitting the monthly spend-limit / credits path while normal session usage was only around 4% on a Max 5x plan: https://github.com/anthropics/claude-code/issues/79167
- GitHub issue about ambiguous "out of usage credits" messaging causing Max subscribers to buy credits unnecessarily: https://github.com/anthropics/claude-code/issues/67412
- GitHub issue about Claude Max subscription checkout failing with merchant-side velocity/payment handling while the card reportedly worked on other Stripe merchants: https://github.com/anthropics/claude-code/issues/68941
- GitHub issue about API-credit purchase failure after successful bank-side 3D Secure authentication: https://github.com/anthropics/claude-code/issues/45361
- GitHub issue about Max upgrade payment failures across multiple cards while banks reportedly saw no decline and support was unresponsive: https://github.com/anthropics/claude-code/issues/56281
- GitHub issue about the Anthropic Console "Buy credits" button staying disabled with inconsistent tier and spend-limit state: https://github.com/anthropics/claude-code/issues/62644
- GitHub issue about a Claude plan upgrade failing while same-card extra usage credits succeeded on the same account: https://github.com/anthropics/claude-code/issues/57122
- GitHub issue about added usage credits not updating the usable credit/limit state in Claude Code: https://github.com/anthropics/claude-code/issues/78905
- GitHub issue about Claude Max subscription entitlement not being recognized and usage credits being charged instead: https://github.com/anthropics/claude-code/issues/79332
- GitHub issue about usage-credit pool accounting charging Opus agent invocations despite available Fable usage credits: https://github.com/anthropics/claude-code/issues/79460
- GitHub issue about purchased usage credits remaining unusable behind a separate monthly spend-limit control: https://github.com/anthropics/claude-code/issues/77703
- GitHub issue about usage credits being consumed while included plan allowance reportedly remained available: https://github.com/anthropics/claude-code/issues/80750
- GitHub issue about paid Max entitlement reverting to Free while support has no confirmed human resolution: https://github.com/anthropics/claude-code/issues/70714
- GitHub issue about runtime/background billing going to API key billing instead of subscription context: https://github.com/anthropics/claude-code/issues/77376
- GitHub issue about wrong-account auth or billing-mode risk from shared Claude daemon state: https://github.com/anthropics/claude-code/issues/79427
- GitHub issue about possible usage-credit re-enabling and runaway billing after a Claude Code update: https://github.com/anthropics/claude-code/issues/78772
- GitHub issue about spend-limit enforcement failure while billing/auto-reload continues past the visible limit: https://github.com/anthropics/claude-code/issues/73795
- GitHub issue about paid credits, negative/phantom balance state, and no human billing response: https://github.com/anthropics/claude-code/issues/79566
- Reddit report about paid credits showing in settings while Claude still treated the user as out of usage, plus support submission failure: https://www.reddit.com/r/Anthropic/comments/1st5uxf/claude_wont_recognize_my_paid_credits_support_is/
- Hacker News discussion with a separate unresolved Anthropic billing-support complaint after promised human review: https://news.ycombinator.com/item?id=47693679

## What Would Count As Resolution

The case should not be treated as resolved unless Anthropic provides a working manual prepaid purchase path, applies an equivalent adjustment, or gives a written Billing Platform / payment-operations explanation that reconciles manual prepay failure with successful automatic top-ups.
