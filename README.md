# Anthropic / Claude Usage-Credit Billing Incident

This repository is a privacy-sanitized public evidence hub for an unresolved Anthropic / Claude billing issue.

## Short Summary

A high-usage Claude customer cannot reliably complete manual prepaid usage-credit purchases through Anthropic's billing flow. The manual purchase path fails or loses the advertised discounted checkout state, while automatic usage-credit top-ups from the same saved billing setup continue charging successfully.

The issue should not be handled as a generic card-decline problem. The reported contradiction is that recurring automatic charging works, but manual prepaid purchasing does not. After earlier generic card-decline guidance, the latest private support direction points toward specialized billing-team review, but support has not confirmed a human Billing Platform / payment-operations owner, written explanation, or restored manual purchase path. A fresh mailbox sweep at 2026-07-26 22:26 JST found Fin AI Agent auto-replies, failed-payment notices, and successful auto-recharge receipts, but no human Billing Platform / payment-operations response, credit reconciliation, refund, or restored manual purchase path.

## Public Evidence Links

- Hosted public incident page: https://coolak.github.io/anthropic-claude-billing-incident/
- Reporter brief: https://coolak.github.io/anthropic-claude-billing-incident/reporter-brief.html
- Billing owner action packet: https://coolak.github.io/anthropic-claude-billing-incident/owner-action.html
- Billing reconciliation matrix: https://coolak.github.io/anthropic-claude-billing-incident/reconciliation-matrix.html
- Public evidence hub: https://gist.github.com/COOLak/65af43d03d2b464d50c95cd4648ccf96
- Anthropic GitHub billing-pattern issue comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Anthropic GitHub banks-see-zero-attempts / support-routing comment: https://github.com/anthropics/claude-code/issues/54055#issuecomment-5083638516
- Reddit evidence thread: https://www.reddit.com/r/Anthropic/comments/1v5mz45/claude_autoreload_works_but_the_failed_1000for700/
- X thread: https://x.com/Coolak777/status/2080754353426833646
- LinkedIn post: https://www.linkedin.com/feed/update/urn:li:share:7486522880319442944/

## 2026-07-26 Latest Public Route Refresh

Between 2026-07-26 22:37 and 23:36 JST, existing Anthropic-owned GitHub comments were refreshed or extended in place with the 2026-07-26 22:26 JST support posture, later verified independent guide corroboration, and a fresh paid-account usage-meter/support-routing report. These are public route/context records, not proof of the customer's private account state.

- Central billing-pattern thread updated again at 23:27 JST with verified CrazyRouter/OpenClaw independent-guide corroboration: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Prepaid commit / zero-bank-auth thread refreshed at 22:37 JST: https://github.com/anthropics/claude-code/issues/73450#issuecomment-5081832536
- Banks-see-zero-attempts / support-routing thread refreshed at 22:40 JST: https://github.com/anthropics/claude-code/issues/54055#issuecomment-5083638516
- Fin auto-closes / organization-credit thread refreshed at 22:42 JST: https://github.com/anthropics/claude-code/issues/80178#issuecomment-5081875532
- Card-auth-succeeds / Anthropic-purchase-fails thread refreshed at 22:44 JST: https://github.com/anthropics/claude-code/issues/80055#issuecomment-5075426087
- Console Buy Credits path disabled / inconsistent billing-state thread refreshed at 22:51 JST: https://github.com/anthropics/claude-code/issues/62644#issuecomment-5081801725
- Payment-fails-across-cards / support-unresponsive thread refreshed at 22:57 JST: https://github.com/anthropics/claude-code/issues/56281#issuecomment-5081796693
- Balance-label / credit-ledger reconciliation thread added at 23:09 JST: https://github.com/anthropics/claude-code/issues/67083#issuecomment-5083828094
- Paid-plan usage-meter / reset-boundary / support-routing report linked at 23:36 JST: https://github.com/anthropics/claude-code/issues/81366#issuecomment-5083925229

## 2026-07-26 Public Documentation-Caveat Updates

To reduce misdiagnosis by users following third-party Anthropic API setup guides, privacy-sanitized documentation-caveat issues were filed where project docs tell users to purchase Anthropic credits or troubleshoot low-credit API errors. These links are route/context records, not proof of private account state.

- Anthropic-owned billing-pattern comment: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- BM Librarian docs caveat: https://github.com/hherb/bmlibrarian/issues/261
- Claude Computer Use Demo docs caveat: https://github.com/Engmhabib/Claude-Computer-Use-Demo/issues/1
- AI Content Describer docs caveat: https://github.com/cartertemm/AI-content-describer/issues/94
- Archive Studio docs caveat: https://github.com/mhumphries2323/Archive_Studio/issues/4
- AI Maker Space IDE docs caveat: https://github.com/AI-Maker-Space/Interactive-Dev-Environment-for-AI-Engineers/issues/15

## 2026-07-26 Independent Buyer-Guidance Updates

Independent Claude/Anthropic guide sites have started adding public buyer-guidance caveats that separate manual credit purchases from automatic reloads. These public caveats were directly fetched and verified on 2026-07-26. They are public buyer-guidance context, not proof of this customer's private account state.

- CrazyRouter Anthropic payment/billing guide, verified at 2026-07-26 23:20 JST, now includes a dedicated `Manual Prepaid Credit Purchase Fails but Auto-Reload Still Works` troubleshooting section and tells readers to check bank authorization attempts, document exact checkout evidence, and ask Anthropic support for billing/payment-operations escalation: https://crazyrouter.com/en/blog/anthropic-claude-api-payment-billing-guide-2026
- OpenClaw Launch guide warning readers to verify Anthropic one-time credit purchases and auto-reload separately before depending on direct Anthropic Console billing, verified at 2026-07-26 21:14 JST: https://openclawlaunch.com/guides/openclaw-anthropic
- OpenClaw Launch managed-agents guide warning that Claude Console billing relies on prepaid credits and separate one-time purchase / automatic reload paths, verified at 2026-07-26 21:14 JST: https://openclawlaunch.com/guides/claude-managed-agents

## 2026-07-26 Hidden Billing-Mode / Support-Routing Evidence

Additional public Anthropic-owned issues show that Claude account state, support-visible plan state, credential precedence, and model entitlement can diverge in ways that route paid users to usage credits or metered API billing. These links are pattern context, not proof of this customer's private account state.

- Payment method and plan changes fail while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973; related-context comment: https://github.com/anthropics/claude-code/issues/80973#issuecomment-5082755895
- `CLAUDE_CODE_OAUTH_TOKEN` silently overrides an active Max subscription and runs sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- `ANTHROPIC_API_KEY` silently routes interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- Stored `primaryApiKey` silently overrides an active Max subscription and causes unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713; related-context comment: https://github.com/anthropics/claude-code/issues/80713#issuecomment-5082771603
- Claude Code can silently route usage to API billing instead of an active Max subscription while giving incorrect auth confirmation: https://github.com/anthropics/claude-code/issues/62338; related-context comment: https://github.com/anthropics/claude-code/issues/62338#issuecomment-5083305010
- Additional auth/account-binding reports show environment variables, `ant auth login`, or `/status` can select or display a billing identity different from the expected subscription account: https://github.com/anthropics/claude-code/issues/77617; https://github.com/anthropics/claude-code/issues/60901; https://github.com/anthropics/claude-code/issues/74217
- Xcode plugin `Default` model selection resolves to Fable and blocks on usage credits for an account without usage credits enabled: https://github.com/anthropics/claude-code/issues/81307
- `CLAUDE_CODE_OAUTH_TOKEN` Fable 5 entitlement is gated behind "Requires usage credits" even though the same token/account is server-side entitled: https://github.com/anthropics/claude-code/issues/81350
- Paid Max usage meters and reset-boundary labels can diverge from observed activity while support routes to unresolved human follow-up: https://github.com/anthropics/claude-code/issues/81366; related-context comment: https://github.com/anthropics/claude-code/issues/81366#issuecomment-5083925229
- Max 20x account forced to usage credits for Fable 5 despite unused Fable weekly allowance: https://github.com/anthropics/claude-code/issues/79341
- Additional active-subscription / plan-included Fable reports show Claude Code prompting for API credits or usage credits despite active subscription, Max plan coverage, or visible covered quota: https://github.com/anthropics/claude-code/issues/78610; https://github.com/anthropics/claude-code/issues/79412; https://github.com/anthropics/claude-code/issues/79351; https://github.com/anthropics/claude-code/issues/79441
- Additional usage-credit-required / active-plan-validity reports show Claude Code requesting usage credits despite active or extended plan state, or misleading users about billing-cycle status: https://github.com/anthropics/claude-code/issues/78620; https://github.com/anthropics/claude-code/issues/78611; https://github.com/anthropics/claude-code/issues/78634
- Command/skill `model:` and `effort:` frontmatter overrides are silently ignored, undermining per-command cost-tiering and model routing controls: https://github.com/anthropics/claude-code/issues/81318
- Skill `model:` frontmatter from an Opus 1M session triggers `Extra usage required` / 429 behavior: https://github.com/anthropics/claude-code/issues/34296
- Background subagents can die on session-limit messages after heavy token spend, with public comments reporting orphaned charged work and failures even after purchased credits entered the flow: https://github.com/anthropics/claude-code/issues/74006; double-billing/orphaned-work comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879420506; paid-credits escalation comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879455343
- Spend-limit / overage reports show charges or overage-limit errors diverging from configured caps, available plan capacity, or true session-limit causes: https://github.com/anthropics/claude-code/issues/32544; https://github.com/anthropics/claude-code/issues/39678; https://github.com/anthropics/claude-code/issues/23579; https://github.com/anthropics/claude-code/issues/74851; https://github.com/anthropics/claude-code/issues/75730
- Manual usage-credit purchase can coincide with a subscription weekly-usage display dropping sharply while the reset date remains unchanged: https://github.com/anthropics/claude-code/issues/64555
- Extra usage credit balance can drop sharply despite the usage page showing zero extra-usage spend for the period: https://github.com/anthropics/claude-code/issues/44198
- Account credit from a Pro-to-Max upgrade can disappear mid-consumption while support and subscription attempts remain unresolved: https://github.com/anthropics/claude-code/issues/56338
- Displayed extra-usage credit balance can remain positive while enforcement blocks usage as if the balance is zero: https://github.com/anthropics/claude-code/issues/45925
- API/runtime entitlement can return `credit_balance_too_low` despite sufficient visible account credits, with a related public case comment now routed to the same ledger/entitlement owner map: https://github.com/anthropics/claude-code/issues/54839; related-context comment: https://github.com/anthropics/claude-code/issues/54839#issuecomment-5083286243
- Extra usage credits can be inaccessible or unrecognized despite available balance / enabled extra usage: https://github.com/anthropics/claude-code/issues/52138; https://github.com/anthropics/claude-code/issues/44720; https://github.com/anthropics/claude-code/issues/17694
- Stripe Link / PaymentIntent checkout failures can block plan-change or credit-purchase-like flows before issuer authorization: https://github.com/anthropics/claude-code/issues/79458; https://github.com/anthropics/claude-code/issues/61081; https://github.com/anthropics/claude-code/issues/72411
- API-credit purchases can fail through a zero-amount SetupIntent / 3D Secure path while subscription billing succeeds with the same card class: https://github.com/anthropics/claude-code/issues/45919; related-context comment: https://github.com/anthropics/claude-code/issues/45919#issuecomment-5083573544
- Legacy Anthropic-owned issue thread about inability to buy API credits: https://github.com/anthropics/claude-code/issues/25745
- Manual add-credit checkout can fail at the final "Almost done" step after showing "Adding credit to your account" and after customer-side bank confirmation: https://github.com/anthropics/claude-code/issues/75299; related-context comment: https://github.com/anthropics/claude-code/issues/75299#issuecomment-5083591021
- Manual buy/add-credit checkout controls can fail before purchase completion through disabled buttons, unresolved tax calculation, missing Pay Now controls, unclear add-funds flow, or stuck invoice retry loops: https://github.com/anthropics/claude-code/issues/75640; https://github.com/anthropics/claude-code/issues/66365; https://github.com/anthropics/claude-code/issues/54976; https://github.com/anthropics/claude-code/issues/73982; https://github.com/anthropics/claude-code/issues/54204
- PaymentIntent declines can fail before reaching the bank, causing card-decline messaging without bank-side processing: https://github.com/anthropics/claude-code/issues/58832
- Payment retry flows can continue returning "Payment failed" after funds are restored while later attempts do not reach the bank: https://github.com/anthropics/claude-code/issues/60232
- Multiple-card checkout failures can produce zero bank-side authorization attempts while the user-facing path loops back to nonresponsive support: https://github.com/anthropics/claude-code/issues/54055; related-context comment: https://github.com/anthropics/claude-code/issues/54055#issuecomment-5083638516
- Workflow fan-out can inherit a premium-tier default with no per-agent cost ceiling, consume pre-purchased credits, and trigger auto-purchased card charges: https://github.com/anthropics/claude-code/issues/68285
- Subagent fan-out can consume purchased overage and discard work when spend-limit termination hits, leaving tokens billed and zero deliverable returned: https://github.com/anthropics/claude-code/issues/78231
- Recursive agent spawning can burn through API credits without a default hard stop or user-visible safeguard: https://github.com/anthropics/claude-code/issues/72732
- Recursive subagent fan-out can cause significant unexpected API/Bedrock charges without sufficient cost visibility, hard caps, kill switch, or refund path: https://github.com/anthropics/claude-code/issues/72861
- Deep-research fan-out can burn quota to a spend/token limit, lose durable progress, and restart from zero on rerun, making the recovery action consume more paid quota: https://github.com/anthropics/claude-code/issues/79958
- Pro-plan headroom still routes to a 1M-context usage-credit purchase path, and the public issue reports purchased credits / visible balance still not reconciling to usable access: https://github.com/anthropics/claude-code/issues/65514; related-context comment: https://github.com/anthropics/claude-code/issues/65514#issuecomment-5082951967
- Max subscriber reports professional work blocked by weekly limits and being pushed to buy additional credits on top of the highest subscription tier: https://github.com/anthropics/claude-code/issues/76006
- Opus 4.8 1M context can require usage credits despite an active Max plan, then fall back to a smaller context: https://github.com/anthropics/claude-code/issues/70721
- Setup-token auth can gate Fable 5 behind usage credits on Max because entitlement scope is not available to the client: https://github.com/anthropics/claude-code/issues/79360
- Fable 5 can show contradictory Max-plan availability messages, with one surface saying usage credits are required while another says the plan includes it: https://github.com/anthropics/claude-code/issues/80382
- Fable 5 / native-1M sessions can silently clamp to a smaller context window after a usage-credit / long-context gate despite a Max plan: https://github.com/anthropics/claude-code/issues/73646
- VS Code can prompt a Max user to purchase Fable 5 credits despite low plan-included usage, then recover after the browser session refreshes entitlement: https://github.com/anthropics/claude-code/issues/77219
- Pro plan plus usage credits enabled can still be capped at a smaller Opus 4.8 context window instead of the documented 1M path: https://github.com/anthropics/claude-code/issues/70609
- Claude Code can default fresh Pro sessions to 1M context with no workaround, pushing users into usage-credit failure paths: https://github.com/anthropics/claude-code/issues/62063
- Opus 1M context on Max can require extra usage despite documentation saying it is included with subscription: https://github.com/anthropics/claude-code/issues/39841
- Apple-subscription Pro usage can still hit the 1M-context usage-credit-required error path: https://github.com/anthropics/claude-code/issues/69154
- API credit balance and subscription current balance use similar framing for separate billing systems, increasing reconciliation confusion: https://github.com/anthropics/claude-code/issues/67083; related-context comment: https://github.com/anthropics/claude-code/issues/67083#issuecomment-5083828094
- Large public Fable 5 thread where Max-plan users are routed to usage credits despite plan inclusion / remaining quota: https://github.com/anthropics/claude-code/issues/79337
- Public Fable 5 thread where Claude Code ignores active weekly Fable allowance and blocks on usage credits: https://github.com/anthropics/claude-code/issues/74051
- Public Fable 5 reports where Claude Code requires usage credits despite unused or low-used included quota: https://github.com/anthropics/claude-code/issues/80484; related-context comment: https://github.com/anthropics/claude-code/issues/80484#issuecomment-5082828463; https://github.com/anthropics/claude-code/issues/79413; related-context comment: https://github.com/anthropics/claude-code/issues/79413#issuecomment-5082842295; and https://github.com/anthropics/claude-code/issues/80409
- Model picker shows `$0.00` usage credits and demands purchase despite active Max plan with available balance: https://github.com/anthropics/claude-code/issues/80737; related-context comment: https://github.com/anthropics/claude-code/issues/80737#issuecomment-5082785354
- Fable 5 forces usage-credit fallback despite barely used Max plan Fable quota: https://github.com/anthropics/claude-code/issues/79576; related-context comment: https://github.com/anthropics/claude-code/issues/79576#issuecomment-5082802275

## 2026-07-26 Unauthorized Upgrade / Refund Support-Routing Evidence

A newly refreshed public Anthropic-owned thread reports unauthorized Pro-to-Max upgrades, account deletion or entitlement loss during cancellation/refund flows, Fin acknowledgments that manual review is needed, and no reliable human escalation for some affected users. Latest public thread activity also describes a July 21 same-date cluster, phantom usage, and an automated refund path that may expose only residual cash rather than prepaid annual-plan credit. This is support-routing and billing-state corroboration, not proof of this customer's private account state.

- Unauthorized plan upgrade / cancellation / refund support-routing thread: https://github.com/anthropics/claude-code/issues/68429
- Related-context comment asking Anthropic to correlate billing events, entitlement state, refund/cancellation state, and payment logs: https://github.com/anthropics/claude-code/issues/68429#issuecomment-5082650681

## 2026-07-26 Paid Invoice / Entitlement Sync Evidence

Additional open Anthropic-owned threads report paid invoices, active store subscriptions, or successful Max payments not mapping to usable Claude access. The public reports include account states stuck on Free or past_due, Claude Code subscription access blocked, and cancellation or support paths failing to reconcile backend state. This is pattern context for invoice/subscription/entitlement propagation, not proof of this customer's private records.

- Paid invoice remains past_due / Claude Code access blocked / cancellation page stuck: https://github.com/anthropics/claude-code/issues/64480
- Related-context comment asking Anthropic to reconcile invoice, subscription, entitlement, and auth-state records: https://github.com/anthropics/claude-code/issues/64480#issuecomment-5082666870
- Paid invoice shows Paid while account remains Free: https://github.com/anthropics/claude-code/issues/66558
- Active Max subscription downgrades to Free while payment/store state still shows paid: https://github.com/anthropics/claude-code/issues/56897
- Paid annual plan can be charged while the account shows Free and Fin/email support cannot escalate to a human: https://github.com/anthropics/claude-code/issues/75475
- Repeated unauthorized Pro-to-Max upgrade / denied second refund: https://github.com/anthropics/claude-code/issues/78577

## 2026-07-26 Anthropic-Owned Related-Case Comments

Privacy-sanitized related-case comments were posted on open Anthropic-owned billing / usage-credit issues where the failure shape overlaps with manual credit purchasing, credit-ledger reconciliation, or support-routing failures. These links are public route/context records, not proof of private account state.

- Billing-pattern / voided-payment state: https://github.com/anthropics/claude-code/issues/55982#issuecomment-4653847611
- Japan API-credit purchase failure: https://github.com/anthropics/claude-code/issues/80055#issuecomment-5075426087
- Prepaid usage-credit commit failure before bank authorization: https://github.com/anthropics/claude-code/issues/73450#issuecomment-5081832536
- Organization credit purchase path fails while subscription billing works: https://github.com/anthropics/claude-code/issues/80178#issuecomment-5081875532
- Add-funds / credit-payment path fails while Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598#issuecomment-5082036072
- Manual upgrade blocked by billing-address/support handoff: https://github.com/anthropics/claude-code/issues/62533#issuecomment-5082691924
- Auto-recharge malfunction and no human billing escalation path: https://github.com/anthropics/claude-code/issues/68773#issuecomment-5082050752
- Paid subscription and extra usage credits not reflected in usable account state: https://github.com/anthropics/claude-code/issues/80722#issuecomment-5082058658
- Subscription-to-API billing reroute / credit-ledger support failure: https://github.com/anthropics/claude-code/issues/81078#issuecomment-5082065752
- Subscription-to-API billing-mode/auth confirmation mismatch: https://github.com/anthropics/claude-code/issues/62338#issuecomment-5083305010
- Balance-label / credit-ledger reconciliation split: https://github.com/anthropics/claude-code/issues/67083#issuecomment-5083828094
- Subscription entitlement recognized elsewhere while Claude Code demands credits: https://github.com/anthropics/claude-code/issues/80043#issuecomment-5082085230
- Usage-credit crossover / spend-cap messaging mismatch: https://github.com/anthropics/claude-code/issues/74784#issuecomment-5082093660
- Unlimited spend-limit / monthly spend-limit rejection mismatch: https://github.com/anthropics/claude-code/issues/77819#issuecomment-5082106864
- Credit top-up prompt vs monthly extra-usage limit mismatch: https://github.com/anthropics/claude-code/issues/81309#issuecomment-5082131492
- Paid-plan usage-meter / reset-boundary / support-routing mismatch: https://github.com/anthropics/claude-code/issues/81366#issuecomment-5083925229
- Fable 5 model access redirects to usage credits despite quota remaining: https://github.com/anthropics/claude-code/issues/80836#issuecomment-5082138348
- Plan-included session quota routes to monthly spend-limit / credits path: https://github.com/anthropics/claude-code/issues/79167#issuecomment-5082151107
- Ambiguous out-of-usage-credits prompt drives unnecessary credit purchases: https://github.com/anthropics/claude-code/issues/67412#issuecomment-5082158047
- Paid invoice / account entitlement mismatch: https://github.com/anthropics/claude-code/issues/56895#issuecomment-5081963255
- Double-charge / entitlement downgrade mismatch: https://github.com/anthropics/claude-code/issues/61339#issuecomment-5081979218
- Subscription checkout merchant-side velocity/payment failure: https://github.com/anthropics/claude-code/issues/68941#issuecomment-5081861595
- API-credit purchase fails after bank-side authentication: https://github.com/anthropics/claude-code/issues/45361#issuecomment-5081790944
- Payment fails across cards while support remains unresponsive: https://github.com/anthropics/claude-code/issues/56281#issuecomment-5081796693
- Multiple-card failures with banks seeing zero attempts and no human support path: https://github.com/anthropics/claude-code/issues/54055#issuecomment-5083638516
- Valid-card API-credit purchase failure with Fin closure loop: https://github.com/anthropics/claude-code/issues/81345#issuecomment-5083439676
- Paid charges can coexist with failure-notification state, no provisioning, and Fin support closure/silence: https://github.com/anthropics/claude-code/issues/60923; related-context comment: https://github.com/anthropics/claude-code/issues/60923#issuecomment-5083556167
- Pro upgrade checkout unavailable across devices/days: https://github.com/anthropics/claude-code/issues/54752
- Console Buy Credits path disabled / inconsistent billing state: https://github.com/anthropics/claude-code/issues/62644#issuecomment-5081801725
- Added credits not reflected in usable credit/limit state: https://github.com/anthropics/claude-code/issues/78905#issuecomment-5081888192
- Sufficient visible credits still blocked by `credit_balance_too_low`: https://github.com/anthropics/claude-code/issues/54839#issuecomment-5083286243
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
- Paid yearly/gift subscription entitlement downgrades or reverts to Free: https://github.com/anthropics/claude-code/issues/62991; https://github.com/anthropics/claude-code/issues/48231; https://github.com/anthropics/claude-code/issues/46378
- Max upgrade or post-upgrade usage-limit entitlement fails to propagate: https://github.com/anthropics/claude-code/issues/55266; https://github.com/anthropics/claude-code/issues/58101
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
- CrazyRouter Anthropic payment/billing guide section on manual prepaid-credit checkout failures while auto-reload still works: https://crazyrouter.com/en/blog/anthropic-claude-api-payment-billing-guide-2026
- Reddit report about paid credit purchases charged or invoiced but not landing in the expected Claude or Console balance: https://www.reddit.com/r/Anthropic/comments/1t4bs6y/three_credit_purchases_havent_posted_to_my/
- GitHub issue about a paid Claude Max invoice/charge not producing the expected account entitlement: https://github.com/anthropics/claude-code/issues/56895
- GitHub issue about a paid Claude Max invoice staying past_due while Claude web/Desktop/Code access remained blocked and cancellation stayed stuck: https://github.com/anthropics/claude-code/issues/64480
- GitHub issue about a paid invoice showing Paid while the account remained on Free plan: https://github.com/anthropics/claude-code/issues/66558
- GitHub issue about active Max subscription / store payment state reverting to Free plan across Claude surfaces: https://github.com/anthropics/claude-code/issues/56897
- GitHub issues about paid yearly or gift subscription entitlements downgrading/reverting to Free plan state: https://github.com/anthropics/claude-code/issues/62991; https://github.com/anthropics/claude-code/issues/48231; https://github.com/anthropics/claude-code/issues/46378
- GitHub issue about a paid annual plan charge while the account remains on Free and Fin/email support fails to escalate to a human: https://github.com/anthropics/claude-code/issues/75475
- GitHub issue about a double-charge after a paid Claude Max plan was reportedly downgraded to Free mid-cycle: https://github.com/anthropics/claude-code/issues/61339
- GitHub issue about unauthorized plan upgrades, account deletion or entitlement loss during cancellation/refund flows, a July 21 same-date cluster, annual-credit refund ambiguity, and Fin support unable to reliably route affected users to a human billing reviewer: https://github.com/anthropics/claude-code/issues/68429
- GitHub issue about repeated unauthorized Pro-to-Max upgrades where a second refund was denied despite documentation: https://github.com/anthropics/claude-code/issues/78577
- GitHub issue about Claude Code still showing low credit balance after top-up: https://github.com/anthropics/claude-code/issues/31537
- GitHub issue about extra / prepaid usage-credit purchase failing before a bank authorization attempt reaches issuers: https://github.com/anthropics/claude-code/issues/73450
- GitHub issue about organization credits failing across payment methods while subscription billing reportedly works and Fin auto-closes tickets: https://github.com/anthropics/claude-code/issues/80178
- GitHub issue about Console API access being suspended while add-funds attempts fail at Anthropic and Fin auto-closes support: https://github.com/anthropics/claude-code/issues/79598
- GitHub issues about Stripe Link / PaymentIntent checkout failures blocking plan-change or credit-purchase-like flows before issuer authorization: https://github.com/anthropics/claude-code/issues/79458; https://github.com/anthropics/claude-code/issues/61081; https://github.com/anthropics/claude-code/issues/72411
- GitHub issue about API-credit purchases failing through a zero-amount SetupIntent / 3D Secure path while subscription billing succeeds with the same card class: https://github.com/anthropics/claude-code/issues/45919; related-context comment: https://github.com/anthropics/claude-code/issues/45919#issuecomment-5083573544
- GitHub issue about API-credit purchase failures in a legacy Anthropic-owned thread: https://github.com/anthropics/claude-code/issues/25745
- GitHub issue about a manual Pro Annual to Max upgrade being blocked by a billing-address changed error while Fin failed to reach a human support owner: https://github.com/anthropics/claude-code/issues/62533
- GitHub issue about automatic usage-credit recharge looping and Fin being unable to reach a human billing specialist: https://github.com/anthropics/claude-code/issues/68773
- GitHub issue about paid Claude Pro subscription plus extra usage credits not being reflected in usable account state while support remains unanswered: https://github.com/anthropics/claude-code/issues/80722
- GitHub issue about subscription usage being silently rerouted to API credit / pay-per-use billing with no effective human billing escalation: https://github.com/anthropics/claude-code/issues/81078
- GitHub issue about payment method / plan changes failing while Fin reports a paid Max account as Free: https://github.com/anthropics/claude-code/issues/80973; related-context comment: https://github.com/anthropics/claude-code/issues/80973#issuecomment-5082755895
- GitHub issue about `CLAUDE_CODE_OAUTH_TOKEN` silently overriding an active Max subscription and running sessions as metered Claude API usage: https://github.com/anthropics/claude-code/issues/79602
- GitHub issue about `ANTHROPIC_API_KEY` silently routing interactive and scheduled Claude Code sessions to API billing despite an active Max subscription: https://github.com/anthropics/claude-code/issues/78491
- GitHub issue about stored `primaryApiKey` silently overriding an active Max subscription and causing unnecessary Console credit purchases: https://github.com/anthropics/claude-code/issues/80713; related-context comment: https://github.com/anthropics/claude-code/issues/80713#issuecomment-5082771603
- GitHub issue about Claude Code silently routing usage to API billing instead of an active Max subscription while giving incorrect auth confirmation: https://github.com/anthropics/claude-code/issues/62338; related-context comment: https://github.com/anthropics/claude-code/issues/62338#issuecomment-5083305010
- GitHub issues about auth/account identity selecting or displaying a different billing source than the expected subscription account: https://github.com/anthropics/claude-code/issues/77617; https://github.com/anthropics/claude-code/issues/60901; https://github.com/anthropics/claude-code/issues/74217
- GitHub issue about Max subscription being recognized on other Claude surfaces while Claude Code still requires usage credits: https://github.com/anthropics/claude-code/issues/80043
- GitHub issues about active subscription or plan-included Fable state still prompting for API credits / usage credits: https://github.com/anthropics/claude-code/issues/78610; https://github.com/anthropics/claude-code/issues/79412; https://github.com/anthropics/claude-code/issues/79351; https://github.com/anthropics/claude-code/issues/79441
- GitHub issues about usage-credit-required / active-plan-validity mismatches: https://github.com/anthropics/claude-code/issues/78620; https://github.com/anthropics/claude-code/issues/78611; https://github.com/anthropics/claude-code/issues/78634
- GitHub issue about extra-usage crossover messaging not disclosing API-rate billing and `/usage-credits` falsely reporting unlimited despite an org spend cap: https://github.com/anthropics/claude-code/issues/74784
- GitHub issue about Claude Code rejecting requests for a monthly spend limit while usage settings showed Unlimited and other meters were not exhausted: https://github.com/anthropics/claude-code/issues/77819
- GitHub issue about the CLI telling users to top up usage credits when the actual blocker is a configured monthly extra-usage limit: https://github.com/anthropics/claude-code/issues/81309
- GitHub issues about spend-limit / overage-limit errors diverging from configured caps, available plan capacity, or true session-limit causes: https://github.com/anthropics/claude-code/issues/32544; https://github.com/anthropics/claude-code/issues/39678; https://github.com/anthropics/claude-code/issues/23579; https://github.com/anthropics/claude-code/issues/74851; https://github.com/anthropics/claude-code/issues/75730
- GitHub issue about background subagents dying on session-limit messages after heavy token spend, with public comments reporting orphaned charged work and failures after purchased credits entered the flow: https://github.com/anthropics/claude-code/issues/74006; double-billing/orphaned-work comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879420506; paid-credits escalation comment: https://github.com/anthropics/claude-code/issues/74006#issuecomment-4879455343
- GitHub issue about Pro-plan headroom still routing to a 1M-context usage-credit purchase path, where the public report says purchased credits / visible balance still did not unblock usable access: https://github.com/anthropics/claude-code/issues/65514; related-context comment: https://github.com/anthropics/claude-code/issues/65514#issuecomment-5082951967
- GitHub issue about account credit from a Pro-to-Max upgrade disappearing mid-consumption while browser subscription attempts and support routing failed: https://github.com/anthropics/claude-code/issues/56338
- GitHub issue about displayed extra-usage credit balance being ignored by enforcement, blocking usage as if the account had no credits: https://github.com/anthropics/claude-code/issues/45925
- GitHub issue about `/model` redirecting to usage credits for Fable 5 despite visible Fable 5 weekly quota remaining on a Max plan: https://github.com/anthropics/claude-code/issues/80836
- GitHub issue about the Fable 5 model-switch dialog saying it is billed separately from the plan despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/79516
- GitHub issue about the model picker blocking Fable 5 behind usage-credit setup despite an active Max plan: https://github.com/anthropics/claude-code/issues/80889
- GitHub issue about setup-token / unattended Fable 5 sessions being gated to usage credits despite subscription quota: https://github.com/anthropics/claude-code/issues/80334
- GitHub issue about a Team Premium seat being routed to usage credits for Fable 5 despite documented plan inclusion: https://github.com/anthropics/claude-code/issues/80813
- GitHub issue about the Xcode plugin `Default` model resolving to Fable and requiring usage credits when credits were not enabled: https://github.com/anthropics/claude-code/issues/81307
- GitHub issue about `CLAUDE_CODE_OAUTH_TOKEN` Fable 5 entitlement being gated behind usage credits despite the same token/account being server-side entitled: https://github.com/anthropics/claude-code/issues/81350
- GitHub issue about paid Max usage meters and reset-boundary labels diverging from observed activity while support routes to unresolved human follow-up: https://github.com/anthropics/claude-code/issues/81366
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
- GitHub issue about Opus 4.8 1M context requiring usage credits despite an active Max plan, then falling back to a smaller context: https://github.com/anthropics/claude-code/issues/70721
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
- GitHub issue about valid-card API-credit purchases failing after 3D Secure while banks see no decline attempt and Fin closes support without resolution: https://github.com/anthropics/claude-code/issues/81345
- GitHub issue about paid charges coexisting with failed-payment notification state, no provisioning, and Fin support closure/silence: https://github.com/anthropics/claude-code/issues/60923; related-context comment: https://github.com/anthropics/claude-code/issues/60923#issuecomment-5083556167
- GitHub issue about Pro upgrade checkout unavailable across multiple devices and days: https://github.com/anthropics/claude-code/issues/54752
- GitHub issues about Max upgrade or post-upgrade usage-limit entitlement failing to propagate: https://github.com/anthropics/claude-code/issues/55266; https://github.com/anthropics/claude-code/issues/58101
- GitHub issues about Stripe Link / PaymentIntent checkout failures before issuer authorization: https://github.com/anthropics/claude-code/issues/79458; https://github.com/anthropics/claude-code/issues/61081; https://github.com/anthropics/claude-code/issues/72411
- GitHub issue about zero-amount SetupIntent / 3D Secure API-credit purchase failure: https://github.com/anthropics/claude-code/issues/45919; related-context comment: https://github.com/anthropics/claude-code/issues/45919#issuecomment-5083573544
- GitHub issue about inability to buy API credits in a legacy Anthropic-owned thread: https://github.com/anthropics/claude-code/issues/25745
- GitHub issue about add-credit checkout failing at the final confirmation step after showing credit addition and customer-side bank confirmation: https://github.com/anthropics/claude-code/issues/75299; related-context comment: https://github.com/anthropics/claude-code/issues/75299#issuecomment-5083591021
- GitHub issues about manual buy/add-credit checkout controls failing before purchase completion through disabled buttons, unresolved tax calculation, missing Pay Now controls, unclear add-funds flow, or stuck invoice retry loops: https://github.com/anthropics/claude-code/issues/75640; https://github.com/anthropics/claude-code/issues/66365; https://github.com/anthropics/claude-code/issues/54976; https://github.com/anthropics/claude-code/issues/73982; https://github.com/anthropics/claude-code/issues/54204
- GitHub issue about PaymentIntent/card-decline handling failing before the attempt reaches the bank: https://github.com/anthropics/claude-code/issues/58832
- GitHub issue about payment retries failing after funds are restored while later attempts do not reach the bank: https://github.com/anthropics/claude-code/issues/60232
- GitHub issue about multiple-card checkout failures where banks reportedly saw zero attempts and support did not produce a human billing route: https://github.com/anthropics/claude-code/issues/54055; related-context comment: https://github.com/anthropics/claude-code/issues/54055#issuecomment-5083638516
- GitHub issue about Max upgrade payment failures across multiple cards while banks reportedly saw no decline and support was unresponsive: https://github.com/anthropics/claude-code/issues/56281
- GitHub issue about the Anthropic Console "Buy credits" button staying disabled with inconsistent tier and spend-limit state: https://github.com/anthropics/claude-code/issues/62644
- GitHub issue about a Claude plan upgrade failing while same-card extra usage credits succeeded on the same account: https://github.com/anthropics/claude-code/issues/57122
- GitHub issue about added usage credits not updating the usable credit/limit state in Claude Code: https://github.com/anthropics/claude-code/issues/78905
- GitHub issue about API/runtime access returning `credit_balance_too_low` despite sufficient visible account credits, now linked to the related public owner-routing comment: https://github.com/anthropics/claude-code/issues/54839; https://github.com/anthropics/claude-code/issues/54839#issuecomment-5083286243
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
- GitHub issues about extra usage credits being inaccessible, unrecognized, or unusable despite available balance / enabled extra usage: https://github.com/anthropics/claude-code/issues/52138; https://github.com/anthropics/claude-code/issues/44720; https://github.com/anthropics/claude-code/issues/17694
- Reddit report about paid credits showing in settings while Claude still treated the user as out of usage, plus support submission failure: https://www.reddit.com/r/Anthropic/comments/1st5uxf/claude_wont_recognize_my_paid_credits_support_is/
- Reddit report about extra usage-credit payment/invoice processing while credits were not applied and support did not produce a human follow-up: https://www.reddit.com/r/Anthropic/comments/1t82hd1/anthropic_support_not_responding_about_missing/
- GitHub issue about usage credits disappearing after a Pro renewal cycle: https://github.com/anthropics/claude-code/issues/23674
- GitHub issues about paid Max entitlement not being recognized by Claude surfaces after subscription/upgrade: https://github.com/anthropics/claude-code/issues/31012; https://github.com/anthropics/claude-code/issues/10832
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
