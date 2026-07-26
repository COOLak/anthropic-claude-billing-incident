# Public Incident Brief

## Core Issue

Manual prepaid Claude usage-credit purchases fail or lose the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

Bank-side information reported by the customer says the failed manual prepay attempts do not appear as real authorization attempts, while successful automatic top-ups do go through.

## Why It Matters

Anthropic sells usage credits to customers who may depend on Claude for ongoing work. Automatic top-ups continuing to charge is not a fix. It is evidence that the billing platform can charge the account while the manual prepaid-credit path remains broken.

## Routes Already Advanced

- Claude Support / Fin billing thread.
- Anthropic support route.
- Latest support posture: specialized billing-team review is now the stated direction, and a direct human connection has been requested, but no human Billing Platform / payment-operations owner or fix is confirmed. A fresh mailbox sweep at 2026-07-26 18:41 JST found no new human billing-owner response or resolution.
- FTC ReportFraud.
- San Francisco DA consumer mediation intake.
- San Francisco City Attorney business-practices complaint.
- Public evidence surfaces on Reddit, X, LinkedIn, GitHub, and a public gist.
- Privacy-sanitized media tips to several relevant outlets.

## Current Public Framing

Anthropic / Claude manual prepaid usage-credit purchases fail or lose discounted checkout state, while automatic top-ups from the same saved billing setup continue charging successfully. Support now points toward specialized billing-team review, but has not confirmed a human billing owner, written explanation, or restored purchase path. A fresh mailbox sweep at 2026-07-26 18:41 JST found no new human billing-owner response or resolution.

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

## 2026-07-26 Independent Buyer-Guidance Update

OpenClaw Launch, an independent Claude/OpenClaw guide site, now warns readers to verify one-time Anthropic credit purchases and automatic reloads separately before relying on direct Anthropic Console billing as a sole production dependency. This is public buyer-guidance context, not proof of this customer's private billing records.

- OpenClaw + Anthropic guide: https://openclawlaunch.com/guides/openclaw-anthropic
- Claude Managed Agents vs OpenClaw guide: https://openclawlaunch.com/guides/claude-managed-agents

## 2026-07-26 Hidden Billing-Mode / Support-Routing Evidence

Additional public Anthropic-owned issues show that Claude account state, support-visible plan state, credential precedence, and model entitlement can diverge in ways that route paid users to usage credits or metered API billing. These links are pattern context, not proof of this customer's private billing records.

- Payment method and plan changes fail while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973; related-context comment: https://github.com/anthropics/claude-code/issues/80973#issuecomment-5082755895
- `CLAUDE_CODE_OAUTH_TOKEN` silently overrides an active Max subscription and runs sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- `ANTHROPIC_API_KEY` silently routes interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- Stored `primaryApiKey` silently overrides an active Max subscription and causes unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713; related-context comment: https://github.com/anthropics/claude-code/issues/80713#issuecomment-5082771603
- Xcode plugin `Default` model selection resolves to Fable and blocks on usage credits for an account without usage credits enabled: https://github.com/anthropics/claude-code/issues/81307
- Max 20x account forced to usage credits for Fable 5 despite unused Fable weekly allowance: https://github.com/anthropics/claude-code/issues/79341
- Command/skill `model:` and `effort:` frontmatter overrides are silently ignored, undermining per-command cost-tiering and model routing controls: https://github.com/anthropics/claude-code/issues/81318
- Skill `model:` frontmatter from an Opus 1M session triggers `Extra usage required` / 429 behavior: https://github.com/anthropics/claude-code/issues/34296
- Background subagents can die on session-limit messages after heavy token spend, with public comments reporting orphaned charged work and failures even after purchased credits entered the flow: https://github.com/anthropics/claude-code/issues/74006; double-billing/orphaned-work comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879420506; paid-credits escalation comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879455343
- Pro-plan headroom still routes to a 1M-context usage-credit purchase path, and the public issue reports purchased credits / visible balance still not reconciling to usable access: https://github.com/anthropics/claude-code/issues/65514; related-context comment: https://github.com/anthropics/claude-code/issues/65514#issuecomment-5082951967
- Large public Fable 5 thread where Max-plan users are routed to usage credits despite plan inclusion / remaining quota: https://github.com/anthropics/claude-code/issues/79337
- Public Fable 5 thread where Claude Code ignores active weekly Fable allowance and blocks on usage credits: https://github.com/anthropics/claude-code/issues/74051
- Public Fable 5 reports where Claude Code requires usage credits despite unused or low-used included quota: https://github.com/anthropics/claude-code/issues/80484; related-context comment: https://github.com/anthropics/claude-code/issues/80484#issuecomment-5082828463; https://github.com/anthropics/claude-code/issues/79413; related-context comment: https://github.com/anthropics/claude-code/issues/79413#issuecomment-5082842295; and https://github.com/anthropics/claude-code/issues/80409
- Model picker shows `$0.00` usage credits and demands purchase despite active Max plan with available balance: https://github.com/anthropics/claude-code/issues/80737; related-context comment: https://github.com/anthropics/claude-code/issues/80737#issuecomment-5082785354
- Fable 5 forces usage-credit fallback despite barely used Max plan Fable quota: https://github.com/anthropics/claude-code/issues/79576; related-context comment: https://github.com/anthropics/claude-code/issues/79576#issuecomment-5082802275

## 2026-07-26 Unauthorized Upgrade / Refund Support-Routing Evidence

A newly refreshed public Anthropic-owned thread reports unauthorized Pro-to-Max upgrades, account deletion or entitlement loss during cancellation/refund flows, Fin acknowledgments that manual review is needed, and no reliable human escalation for some affected users. Latest public thread activity also describes a July 21 same-date cluster, phantom usage, and an automated refund path that may expose only residual cash rather than prepaid annual-plan credit. This is support-routing and billing-state corroboration, not proof of this customer's private billing records.

- Unauthorized plan upgrade / cancellation / refund support-routing thread: https://github.com/anthropics/claude-code/issues/68429
- Related-context comment asking Anthropic to correlate billing events, entitlement state, refund/cancellation state, and payment logs: https://github.com/anthropics/claude-code/issues/68429#issuecomment-5082650681

## 2026-07-26 Paid Invoice / Entitlement Sync Evidence

Additional open Anthropic-owned threads report paid invoices, active store subscriptions, or successful Max payments not mapping to usable Claude access. The public reports include account states stuck on Free or past_due, Claude Code subscription access blocked, and cancellation or support paths failing to reconcile backend state. This is pattern context for invoice/subscription/entitlement propagation, not proof of this customer's private records.

- Paid invoice remains past_due / Claude Code access blocked / cancellation page stuck: https://github.com/anthropics/claude-code/issues/64480
- Related-context comment asking Anthropic to reconcile invoice, subscription, entitlement, and auth-state records: https://github.com/anthropics/claude-code/issues/64480#issuecomment-5082666870
- Paid invoice shows Paid while account remains Free: https://github.com/anthropics/claude-code/issues/66558
- Active Max subscription downgrades to Free while payment/store state still shows paid: https://github.com/anthropics/claude-code/issues/56897
- Repeated unauthorized Pro-to-Max upgrade / denied second refund: https://github.com/anthropics/claude-code/issues/78577

## 2026-07-26 Anthropic-Owned Related-Case Comments

Privacy-sanitized related-case comments were posted on open Anthropic-owned billing / usage-credit issues where the failure shape overlaps with manual credit purchasing, credit-ledger reconciliation, or support-routing failures. These links are public route/context records, not proof of this customer's private billing records.

- Billing-pattern / voided-payment state: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Japan API-credit purchase failure: https://github.com/anthropics/claude-code/issues/80055#issuecomment-5075426087
- Prepaid usage-credit commit failure before bank authorization: https://github.com/anthropics/claude-code/issues/73450#issuecomment-5081832536
- Organization credit purchase path fails while subscription billing works: https://github.com/anthropics/claude-code/issues/80178#issuecomment-5081875532
- Add-funds / credit-payment path fails while Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598#issuecomment-5082036072
- Manual upgrade blocked by billing-address/support handoff: https://github.com/anthropics/claude-code/issues/62533#issuecomment-5082691924
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
- Fable quota unused in `/usage` while Claude Code CLI routes to usage-credit purchase path: https://github.com/anthropics/claude-code/issues/80484#issuecomment-5082828463
- Pro-plan Fable quota still has headroom while Claude Code blocks on usage credits turned off: https://github.com/anthropics/claude-code/issues/79413#issuecomment-5082842295
- Fable 5 draws on usage credits despite a 20x Max subscription: https://github.com/anthropics/claude-code/issues/79548#issuecomment-5082909783
- Model picker demands credit purchase despite active Max plan with available balance: https://github.com/anthropics/claude-code/issues/80737#issuecomment-5082785354
- Usage-credit fallback blocks Fable despite Max plan quota remaining: https://github.com/anthropics/claude-code/issues/79576#issuecomment-5082802275
- Paid entitlement / billing-ledger mismatch after paid Max state reverts to Free: https://github.com/anthropics/claude-code/issues/70714#issuecomment-5082322216
- Paid Pro organization/auth entitlement mismatch: https://github.com/anthropics/claude-code/issues/72027#issuecomment-5082705256
- Paid Pro subscription-auth state not recognized: https://github.com/anthropics/claude-code/issues/69786#issuecomment-5082718810
- Active Pro subscription blocked by Max/Pro OAuth gate: https://github.com/anthropics/claude-code/issues/77444#issuecomment-5082733594
- Subscription billing mode / runtime API billing mismatch: https://github.com/anthropics/claude-code/issues/77376#issuecomment-5082327220
- Account identity / wrong-account billing-mode risk: https://github.com/anthropics/claude-code/issues/79427#issuecomment-5082335832
- Unauthorized upgrade / refund automation / July 21 cluster support-routing mismatch: https://github.com/anthropics/claude-code/issues/68429#issuecomment-5082650681
- Paid invoice / past_due / entitlement-auth sync mismatch: https://github.com/anthropics/claude-code/issues/64480#issuecomment-5082666870
- Usage-credit controls / runaway billing after runtime change: https://github.com/anthropics/claude-code/issues/78772#issuecomment-5082340539
- Spend-limit enforcement failure while auto-reload charges continue: https://github.com/anthropics/claude-code/issues/73795#issuecomment-5082344918
- Paid credits / entitlement state and human-support silence: https://github.com/anthropics/claude-code/issues/79566#issuecomment-5082349846
- Fable 5 plan-inclusion copy / usage-credit routing contradiction: https://github.com/anthropics/claude-code/issues/79516#issuecomment-5082396668
- Model picker blocks Fable 5 behind usage-credit setup despite active Max plan: https://github.com/anthropics/claude-code/issues/80889#issuecomment-5082408796
- Setup-token / unattended sessions gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334#issuecomment-5082419553
- Team Premium seat routes Fable 5 to usage credits despite plan inclusion: https://github.com/anthropics/claude-code/issues/80813#issuecomment-5082430054
- Xcode plugin default model routes to Fable / usage credits despite unavailable credits: https://github.com/anthropics/claude-code/issues/81307#issuecomment-5082567839
- Fable 5 incorrectly requires usage credits on Max 20x despite available weekly allowance: https://github.com/anthropics/claude-code/issues/79341#issuecomment-5082388373
- Fable 5 draws on usage credits despite a 20x Max subscription: https://github.com/anthropics/claude-code/issues/79548#issuecomment-5082909783

## Related Public Reports

These links are pattern context, not proof of this customer's private account records.

- Anthropic Help Center states that purchased credits should be immediately available and describes auto-reload behavior: https://support.claude.com/en/articles/8977456-how-do-i-pay-for-my-claude-api-usage
- Anthropic Help Center describes support as Fin first, then Product Support by email when escalation is required: https://support.claude.com/en/articles/9015913-how-to-get-support
- OpenClaw Launch guide warning readers to verify Anthropic one-time credit purchases and auto-reload separately before depending on direct Anthropic Console billing: https://openclawlaunch.com/guides/openclaw-anthropic
- OpenClaw Launch managed-agents guide warning that Claude Console billing relies on prepaid credits and separate one-time purchase / automatic reload paths: https://openclawlaunch.com/guides/claude-managed-agents
- Reddit report about paid credit purchases charged or invoiced but not landing in the expected Claude or Console balance: https://www.reddit.com/r/Anthropic/comments/1t4bs6y/three_credit_purchases_havent_posted_to_my/
- GitHub issue about a paid Claude Max invoice/charge not producing the expected account entitlement: https://github.com/anthropics/claude-code/issues/56895
- GitHub issue about a paid Claude Max invoice staying past_due while Claude web/Desktop/Code access remained blocked and cancellation stayed stuck: https://github.com/anthropics/claude-code/issues/64480
- GitHub issue about a paid invoice showing Paid while the account remained on Free plan: https://github.com/anthropics/claude-code/issues/66558
- GitHub issue about active Max subscription / store payment state reverting to Free plan across Claude surfaces: https://github.com/anthropics/claude-code/issues/56897
- GitHub issue about a double-charge after a paid Claude Max plan was reportedly downgraded to Free mid-cycle: https://github.com/anthropics/claude-code/issues/61339
- GitHub issue about unauthorized plan upgrades, account deletion or entitlement loss during cancellation/refund flows, a July 21 same-date cluster, annual-credit refund ambiguity, and Fin support unable to reliably route affected users to a human billing reviewer: https://github.com/anthropics/claude-code/issues/68429
- GitHub issue about repeated unauthorized Pro-to-Max upgrades where a second refund was denied despite documentation: https://github.com/anthropics/claude-code/issues/78577
- GitHub issue about Claude Code still showing low credit balance after top-up: https://github.com/anthropics/claude-code/issues/31537
- GitHub issue about extra / prepaid usage-credit purchase failing before a bank authorization attempt reaches issuers: https://github.com/anthropics/claude-code/issues/73450
- GitHub issue about organization credits failing across payment methods while subscription billing reportedly works and Fin auto-closes tickets: https://github.com/anthropics/claude-code/issues/80178
- GitHub issue about Console API access being suspended while add-funds attempts fail at Anthropic and Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598
- GitHub issue about a manual Pro Annual to Max upgrade being blocked by a billing-address changed error while Fin failed to reach a human support owner: https://github.com/anthropics/claude-code/issues/62533
- GitHub issue about automatic usage-credit recharge looping and Fin being unable to reach a human billing specialist: https://github.com/anthropics/claude-code/issues/68773
- GitHub issue about paid Claude Pro subscription plus extra usage credits not being reflected in usable account state while support remains unanswered: https://github.com/anthropics/claude-code/issues/80722
- GitHub issue about subscription usage being silently rerouted to API credit / pay-per-use billing with no effective human billing escalation: https://github.com/anthropics/claude-code/issues/81078
- GitHub issue about payment method / plan changes failing while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973; related-context comment: https://github.com/anthropics/claude-code/issues/80973#issuecomment-5082755895
- GitHub issue about `CLAUDE_CODE_OAUTH_TOKEN` silently overriding an active Max subscription and running sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- GitHub issue about `ANTHROPIC_API_KEY` silently routing interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- GitHub issue about stored `primaryApiKey` silently overriding an active Max subscription and causing unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713; related-context comment: https://github.com/anthropics/claude-code/issues/80713#issuecomment-5082771603
- GitHub issue about Max subscription being recognized on other Claude surfaces while Claude Code still requires usage credits: https://github.com/anthropics/claude-code/issues/80043
- GitHub issue about extra-usage crossover messaging not disclosing API-rate billing and `/usage-credits` falsely reporting unlimited despite an org spend cap: https://github.com/anthropics/claude-code/issues/74784
- GitHub issue about Claude Code rejecting requests for a monthly spend limit while usage settings showed Unlimited and other meters were not exhausted: https://github.com/anthropics/claude-code/issues/77819
- GitHub issue about the CLI telling users to top up usage credits when the actual blocker is a configured monthly extra-usage limit: https://github.com/anthropics/claude-code/issues/81309
- GitHub issue about background subagents dying on session-limit messages after heavy token spend, with public comments reporting orphaned charged work and failures after purchased credits entered the flow: https://github.com/anthropics/claude-code/issues/74006; double-billing/orphaned-work comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879420506; paid-credits escalation comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879455343
- GitHub issue about workflow fan-out inheriting a premium-tier default with no per-agent cost ceiling, consuming pre-purchased credits, and triggering auto-purchased card charges: https://github.com/anthropics/claude-code/issues/68285
- GitHub issue about subagent fan-out consuming purchased overage and discarding work when spend-limit termination hits, leaving tokens billed and zero deliverable returned: https://github.com/anthropics/claude-code/issues/78231
- GitHub issue about Pro-plan headroom still routing to a 1M-context usage-credit purchase path, where the public report says purchased credits / visible balance still did not unblock usable access: https://github.com/anthropics/claude-code/issues/65514; related-context comment: https://github.com/anthropics/claude-code/issues/65514#issuecomment-5082951967
- GitHub issue from a Max subscriber reporting professional work blocked by weekly limits and being pushed to buy additional credits on top of the highest subscription tier: https://github.com/anthropics/claude-code/issues/76006
- GitHub issue about `/model` redirecting to usage credits for Fable 5 despite visible Fable 5 weekly quota remaining on a Max plan: https://github.com/anthropics/claude-code/issues/80836
- GitHub issue about the Fable 5 model-switch dialog saying it is billed separately from the plan despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/79516
- GitHub issue about the model picker blocking Fable 5 behind usage-credit setup despite an active Max plan: https://github.com/anthropics/claude-code/issues/80889
- GitHub issue about setup-token / unattended Fable 5 sessions being gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334
- GitHub issue about a Team Premium seat being routed to usage credits for Fable 5 despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/80813
- GitHub issue about the Xcode plugin `Default` model resolving to Fable and requiring usage credits when credits were not enabled: https://github.com/anthropics/claude-code/issues/81307
- GitHub issue about setup-token auth losing Fable 5 entitlement and later surfacing server-side credit/rate-limit rejection: https://github.com/anthropics/claude-code/issues/79597
- GitHub issue with multiple Max-plan reports that Fable 5 is gated behind usage credits or server-side limit errors despite included quota, with local tests showing client consent only masks the server-side rejection: https://github.com/anthropics/claude-code/issues/80749
- GitHub issue about the VS Code extension prompting for usage credits on Fable 5 while the browser showed Max-plan Fable allowance untouched: https://github.com/anthropics/claude-code/issues/79386
- GitHub issue about Fable 5 being forced to usage credits on Max 20x despite unused Fable weekly allowance and low current usage: https://github.com/anthropics/claude-code/issues/79341
- GitHub issue about Fable 5 drawing on usage credits despite a 20x Max subscription: https://github.com/anthropics/claude-code/issues/79548; related-context comment: https://github.com/anthropics/claude-code/issues/79548#issuecomment-5082909783
- GitHub issue about a Max plan being unable to switch to Fable because Claude Code requires usage credits: https://github.com/anthropics/claude-code/issues/80706
- GitHub issue with a large public thread about Max-plan users being routed to usage credits for Fable 5 despite plan inclusion / remaining quota: https://github.com/anthropics/claude-code/issues/79337
- GitHub issue about Claude Code ignoring active weekly Fable allowance and blocking Fable 5 on usage credits: https://github.com/anthropics/claude-code/issues/74051
- GitHub issue about Claude Code requiring usage credits for Fable 5 while `/usage` shows included weekly Fable quota unused: https://github.com/anthropics/claude-code/issues/80484; related-context comment: https://github.com/anthropics/claude-code/issues/80484#issuecomment-5082828463
- GitHub issue about Fable 5 usage-credit gating on a Pro plan while weekly Fable quota still shows headroom: https://github.com/anthropics/claude-code/issues/79413; related-context comment: https://github.com/anthropics/claude-code/issues/79413#issuecomment-5082842295
- GitHub issue about Fable 5 requiring usage credits on a Max 20x plan despite low used included allowance: https://github.com/anthropics/claude-code/issues/80409
- GitHub issue about the model picker showing `$0.00` usage credits and demanding purchase despite active Max plan with available balance: https://github.com/anthropics/claude-code/issues/80737; related-context comment: https://github.com/anthropics/claude-code/issues/80737#issuecomment-5082785354
- GitHub issue about Fable 5 forcing usage-credit fallback despite barely used Max plan Fable quota: https://github.com/anthropics/claude-code/issues/79576; related-context comment: https://github.com/anthropics/claude-code/issues/79576#issuecomment-5082802275
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
- GitHub issue about an individual paid Pro subscriber being blocked from Claude Code by organization/auth entitlement mismatch despite active billing: https://github.com/anthropics/claude-code/issues/72027
- GitHub issue about a paid Pro subscription not being recognized by Claude Code subscription auth despite paid invoice state: https://github.com/anthropics/claude-code/issues/69786
- GitHub issue about an active individual Pro subscription being blocked by the Claude Code Max/Pro OAuth gate: https://github.com/anthropics/claude-code/issues/77444
- GitHub issue about runtime/background billing going to API key billing instead of subscription context: https://github.com/anthropics/claude-code/issues/77376
- GitHub issue about wrong-account auth or billing-mode risk from shared Claude daemon state: https://github.com/anthropics/claude-code/issues/79427
- GitHub issue about possible usage-credit re-enabling and runaway billing after a Claude Code update: https://github.com/anthropics/claude-code/issues/78772
- GitHub issue about spend-limit enforcement failure while billing/auto-reload continues past the visible limit: https://github.com/anthropics/claude-code/issues/73795
- GitHub issue about paid credits, negative/phantom balance state, and no human billing response: https://github.com/anthropics/claude-code/issues/79566
- Reddit report about paid credits showing in settings while Claude still treated the user as out of usage, plus support submission failure: https://www.reddit.com/r/Anthropic/comments/1st5uxf/claude_wont_recognize_my_paid_credits_support_is/
- Hacker News discussion with a separate unresolved Anthropic billing-support complaint after promised human review: https://news.ycombinator.com/item?id=47693679

## What Would Count As Resolution

The case should not be treated as resolved unless Anthropic provides a working manual prepaid purchase path, applies an equivalent adjustment, or gives a written Billing Platform / payment-operations explanation that reconciles manual prepay failure with successful automatic top-ups.
