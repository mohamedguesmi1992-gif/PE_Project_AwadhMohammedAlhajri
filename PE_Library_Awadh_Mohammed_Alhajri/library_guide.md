# Library Guide - Learner Support Desk

**Owner:** Awadh Mohammed Alhajri  
**Last updated:** 2026_10_15

This library is for guided Scenario B1 in the training program. It includes five tested, reusable prompts, one block of seven invented facts, and five rules for responsible use. The templates are for drafting, summarizing, sorting, rewriting tone and flagging refund exceptions. The reply and complaint-summary prompts are v2 after retesting; their earlier v1 copies are kept in _archive/. A human reviewer checks every result.

## How to use a template

1. Open [the index](library_index.md) and select the template that matches the task. Copy only that template's **Copyable template** section into a new AI conversation.
2. Replace each required variable with an invented, masked input. Keep variable names unchanged. Load [Center Facts v1](blocks/TC-Facts-v1_2026_10_15.md) wherever [CENTER_FACTS] appears. Never send an actual person's name, password, bank details, contact information or case reference into the tool.
3. Set [LANGUAGE] to Arabic, English, Automated, Bilingual or Mixed. Automated uses the input's main language. Use each template's default values when an optional value is absent. Do not guess a required value.
4. Run two different fills and one edge case for each template in separate fresh chats. Check the sample outputs against the seven facts, not against assumptions.
5. Score the five RACE prompt criteria, six template criteria and five output criteria. For every full-score real run, capture a readable screenshot showing the prompt and response. Place it on that template's page of [the test report](Test_Results_Report.pdf).
6. Before using a reply, the reviewer verifies numbers, source facts, promises, masking and completeness; only authorized staff can make eligibility, payment or refund-exception decisions.

## Ownership and controls

Awadh Mohammed Alhajri is responsible for file names, dates and reviewing revisions. The authorized service desk reviewer remains responsible for any external communication. The source files in templates/ are text-only Markdown and can be shared without exposing real work data.

This library uses invented training policies; it is not an operational service policy.
