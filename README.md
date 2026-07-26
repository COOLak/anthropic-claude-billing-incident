# Anthropic / Claude Usage-Credit Billing Incident

This repository is a privacy-sanitized public evidence hub for an unresolved Anthropic / Claude billing issue.

## Short Summary

A high-usage Claude customer cannot reliably complete manual prepaid usage-credit purchases through Anthropic's billing flow. The manual purchase path fails or loses the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

The issue should not be handled as a generic card-decline problem. The reported contradiction is that recurring automatic charging works, but manual prepaid purchasing does not. After earlier generic card-decline guidance, the latest private support direction points toward specialized billing-team review, but support has not confirmed a human Billing Platform / payment-operations owner, written explanation, or restored manual purchase path.

## Public Evidence Links

- Hosted public incident page: https://coolak.github.io/anthropic-claude-billing-incident/
- Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/reporter-brief.html
- Billing owner action packet: https://coolak.github.io/anthropic-claude-billing-incident/owner-action.html
- Billing reconciliation matrix: https://coolak.github.io/anthropic-claude-billing-incident/reconciliation-matrix.html
- Public evidence hub: https://gist.github.com/COOLak/65af43d03d2b464d50c95cd4648ccf96
- Anthropic GitHub billing-pattern issue comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Reddit evidence thread: https://www.reddit.com/r/Anthropic/comments/1v5mz45/claude_autoreload_works_but_the_failed_1000for700/
- X thread: https://x.com/Coolak777/status/2080754353426833646
- LinkedIn post: https://www.linkedin.com/feed/update/urn:li:share:7486522880319442944/

## 2026-07-26 Public Documentation-Caveat Updates

To reduce misdiagnosis by users following third-party Anthropic API setup guides, privacy-sanitized documentation-caveat issues were filed where project docs tell users to purchase Anthropic credits or troubleshoot low-credit API errors. These links are route/context records, not proof of private account state.

- Anthropic-owned billing-pattern comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- BM Librarian docs caveat: https://github.com/hherb/bmlibrarian/issues/261
- Claude Computer Use Demo docs caveat: https://github.com/Engmhabib/Claude-Computer-Use-Demo/issues/1
- AI Content Describer docs caveat: https://github.com/cartertemm/AI-content-describer/issues/94
- Archive Studio docs caveat: https://github.com/mhumphries2323/Archive_Studio/issues/4
- AI Maker Space IDE docs caveat: https://github.com/AI-Maker-Space/Interactive-Dev-Environment-for-AI-Engineers/issues/15

## 2026-07-26 Independent Buyer-Guidance Update

OpenClaw Launch, an independent Claude/OpenClaw guide site, now warns readers to verify one-time Anthropic credit purchases and automatic reloads separately before relying on direct Anthropic Console billing as a sole production dependency. This is public buyer-guidance context, not proof of this customer's private account state.

- OpenClaw + Anthropic guide: https://openclawlaunch.com/guides/openclaw-anthropic
- Claude Managed Agents vs OpenClaw guide: https://openclawlaunch.com/guides/claude-managed-agents

## 2026-07-26 Hidden Billing-Mode / Support-Routing Evidence

Additional public Anthropic-owned issues show that Claude account state, support-visible plan state, credential precedence, and model entitlement can diverge in ways that route paid users to usage credits or metered API billing. These links are pattern context, not proof of this customer's private account state.

- Payment method and plan changes fail while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973
- `CLAUDE_CODE_OAUTH_TOKEN` silently overrides an active Max subscription and runs sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- `ANTHROPIC_API_KEY` silently routes interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- Stored `primaryApiKey` silently overrides an active Max subscription and causes unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713
- Xcode plugin `Default` model selection resolves to Fable and blocks on usage credits for an account without usage credits enabled: https://github.com/anthropics/claude-code/issues/81307
- Command/skill `model:` and `effort:` frontmatter overrides are silently ignored, undermining per-command cost-tiering and model routing controls: https://github.com/anthropics/claude-code/issues/81318
- Skill `model:` frontmatter from an Opus 1M session triggers `Extra usage required` / 429 behavior: https://github.com/anthropics/claude-code/issues/34296
- Large public Fable 5 thread where Max-plan users are routed to usage credits despite plan inclusion / remaining quota: https://github.com/anthropics/claude-code/issues/79337
- Public Fable 5 thread where Claude Code ignores active weekly Fable allowance and blocks on usage credits: https://github.com/anthropics/claude-code/issues/74051
- Public Fable 5 reports where Claude Code requires usage credits despite unused or low-used included quota: https://github.com/anthropics/claude-code/issues/80484 and https://github.com/anthropics/claude-code/issues/80409

## 2026-07-26 Anthropic-Owned Related-Case Comments

Privacy-sanitized related-case comments were posted on open Anthropic-owned billing / usage-credit issues where the failure shape overlaps with manual credit purchasing, credit-ledger reconciliation, or support-routing failures. These links are public route/context records, not proof of private account state.

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
- Xcode plugin default model routes to Fable / usage credits despite unavailable credits: https://github.com/anthropics/claude-code/issues/81307#issuecomment-5082567839

## Related Public Reports

These links are pattern context, not proof of this customer's private account records.

- Anthropic Help Center states that purchased credits should be immediately available and describes auto-reload behavior: https://support.claude.com/en/articles/8977456-how-do-i-pay-for-my-claude-api-usage
- Anthropic Help Center describes support as Fin first, then Product Support by email when escalation is required: https://support.claude.com/en/articles/9015913-how-to-get-support
- OpenClaw Launch guide warning readers to verify Anthropic one-time credit purchases and auto-reload separately before depending on direct Anthropic Console billing: https://openclawlaunch.com/guides/openclaw-anthropic
- OpenClaw Launch managed-agents guide warning that Claude Console billing relies on prepaid credits and separate one-time purchase / automatic reload paths: https://openclawlaunch.com/guides/claude-managed-agents
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
- GitHub issue about payment method / plan changes failing while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973
- GitHub issue about `CLAUDE_CODE_OAUTH_TOKEN` silently overriding an active Max subscription and running sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- GitHub issue about `ANTHROPIC_API_KEY` silently routing interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- GitHub issue about stored `primaryApiKey` silently overriding an active Max subscription and causing unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713
- GitHub issue about Max subscription being recognized on other Claude surfaces while Claude Code still requires usage credits: https://github.com/anthropics/claude-code/issues/80043
- GitHub issue about extra-usage crossover messaging not disclosing API-rate billing and `/usage-credits` falsely reporting unlimited despite an org spend cap: https://github.com/anthropics/claude-code/issues/74784
- GitHub issue about Claude Code rejecting requests for a monthly spend limit while usage settings showed Unlimited and other meters were not exhausted: https://github.com/anthropics/claude-code/issues/77819
- GitHub issue about the CLI telling users to top up usage credits when the actual blocker is a configured monthly extra-usage limit: https://github.com/anthropics/claude-code/issues/81309
- GitHub issue about `/model` redirecting to usage credits for Fable 5 despite visible Fable 5 weekly quota remaining on a Max plan: https://github.com/anthropics/claude-code/issues/80836
- GitHub issue about the Fable 5 model-switch dialog saying it is billed separately from the plan despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/79516
- GitHub issue about the model picker blocking Fable 5 behind usage-credit setup despite an active Max plan: https://github.com/anthropics/claude-code/issues/80889
- GitHub issue about setup-token / unattended Fable 5 sessions being gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334
- GitHub issue about a Team Premium seat being routed to usage credits for Fable 5 despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/80813
- GitHub issue about the Xcode plugin `Default` model resolving to Fable and requiring usage credits when credits were not enabled: https://github.com/anthropics/claude-code/issues/81307
- GitHub issue about setup-token auth losing Fable 5 entitlement and later surfacing server-side credit/rate-limit rejection: https://github.com/anthropics/claude-code/issues/79597
- GitHub issue with multiple Max-plan reports that Fable 5 is gated behind usage credits or server-side limit errors despite included quota, with local tests showing client consent only masks the server-side rejection: https://github.com/anthropics/claude-code/issues/80749
- GitHub issue with a large public thread about Max-plan users being routed to usage credits for Fable 5 despite plan inclusion / remaining quota: https://github.com/anthropics/claude-code/issues/79337
- GitHub issue about Claude Code ignoring active weekly Fable allowance and blocking Fable 5 on usage credits: https://github.com/anthropics/claude-code/issues/74051
- GitHub issue about Claude Code requiring usage credits for Fable 5 while `/usage` shows included weekly Fable quota unused: https://github.com/anthropics/claude-code/issues/80484
- GitHub issue about Fable 5 requiring usage credits on a Max 20x plan despite low used included allowance: https://github.com/anthropics/claude-code/issues/80409
- GitHub issue about selected Opus/Sonnet silently running or billing as Fable 5, consuming Fable limits or usage credits, and then failing to clear the Fable block through `/model`: https://github.com/anthropics/claude-code/issues/74379
- GitHub issue about `/model` set to Opus 4.8 while the backend served/billed Fable 5, then a Fable limit gated a long-running session: https://github.com/anthropics/claude-code/issues/74388
- GitHub issue about Dispatch locking sessions to Fable 5 with no working model switch, blocking paid usage available on other models: https://github.com/anthropics/claude-code/issues/79410
- GitHub issue about command/skill `model:` and `effort:` frontmatter overrides silently failing, removing a per-command model/cost-routing control: https://github.com/anthropics/claude-code/issues/81318
- GitHub issue about skill `model:` frontmatter from an Opus 1M session triggering `Extra usage required` / 429 behavior: https://github.com/anthropics/claude-code/issues/34296
- GitHub issue about subagents billing or counting against spend after a monthly spend limit was already hit, while failures were rolled up as a clean review result: https://github.com/anthropics/claude-code/issues/75757
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
