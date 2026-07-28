# July 17 Request-Metadata Audit: 98.67% of Records Outside Anthropic's Correction Window

Updated: 2026-07-28

## Result

A privacy-redacted local Claude Code request-metadata inventory contains
**2,177** deduplicated July 17 records spanning **00:00:06–23:46:50 UTC**.
Segmented against Anthropic's selected **18:16–18:47 UTC** correction window:

| Segment | Records | Record share | Recorded usage counters |
|---|---:|---:|---:|
| Before 18:16 UTC | 1,241 | 57.01% | 409,513,130 |
| Inside [18:16, 18:47) UTC | 29 | 1.33% | 16,295,436 |
| After 18:47 UTC | 907 | 41.66% | 296,655,271 |
| Full inventory | 2,177 | 100.00% | 722,463,837 |
| **Outside Anthropic's interval** | **2,148** | **98.67%** | **706,168,401 (97.74%)** |

The half-open interval `[18:16, 18:47)` is used because Anthropic's correction
message says included limits worked as intended **since 18:47 UTC**.

## Counter detail

The local metadata records four distinct usage counters. They are telemetry
fields, not dollar values and not a provider billing ledger.

| Counter | Before | Inside | After | Full day | Outside share |
|---|---:|---:|---:|---:|---:|
| Input | 12,769 | 52 | 10,322 | 23,143 | 99.78% |
| Output | 1,379,057 | 52,453 | 1,130,682 | 2,562,192 | 97.95% |
| Cache creation | 41,420,936 | 560,259 | 24,773,033 | 66,754,228 | 99.16% |
| Cache read | 366,700,368 | 15,682,672 | 270,741,234 | 653,124,274 | 97.60% |
| **Total recorded counters** | **409,513,130** | **16,295,436** | **296,655,271** | **722,463,837** | **97.74%** |

## Verification

- Workbook formulas use bounded source ranges.
- Formula-error scan found no `#REF!`, `#DIV/0!`, `#VALUE!`, `#NAME?`, or
  `#N/A` cells.
- An independent row-by-row JavaScript aggregation exactly reproduced all
  segment counts and all four counter sums.
- The private source contains no prompts, responses, credentials, cookies,
  account identifiers, invoice identifiers, receipt identifiers, or raw
  request/session identifiers.
- The private workbook is not published.

## What this proves

The local request activity was not confined to Anthropic's selected 31-minute
correction window. **2,148 of 2,177 records** and **706,168,401 of 722,463,837
recorded counters** fall outside it.

## What this does not prove

This analysis does **not** establish:

- provider-billed dollars or cost per request;
- historical included-plan entitlement or weekly-limit headroom;
- included-plan versus paid-credit classification;
- paid-credit debits or automatic-reload triggers;
- request-to-invoice or request-to-payment mapping; or
- which request caused any of the seven July 17 receipts.

Only Anthropic controls the authoritative historical entitlement, routing,
credit-debit, recharge, invoice, payment, and correction ledgers. The result
supports a complete July 17 transaction-level reconciliation; it must not be
presented as proof that every outside-window request was billed incorrectly.

## Related public evidence

- Anthropic's official incident:
  https://status.anthropic.com/incidents/g613ntyj2pwf
- Dedicated Anthropic-owned tracker:
  https://github.com/anthropics/claude-code/issues/81703
- Public aggregate update:
  https://github.com/anthropics/claude-code/issues/81703#issuecomment-5105384412
- Seven-receipt timeline:
  https://coolak.github.io/anthropic-claude-billing-incident/july-17-receipt-timeline.html
- Full public-safe evidence brief:
  https://coolak.github.io/anthropic-claude-billing-incident/july-17-usage-credit-refund.html
