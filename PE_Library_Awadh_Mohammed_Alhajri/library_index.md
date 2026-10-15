# Training Center Prompt Library - Index

**Owner:** Awadh Mohammed Alhajri  
**Scenario:** B1 - Learner Support Desk at a Training Center  
**Version:** v2  
**Updated:** 2026_10_15

## Five templates

| Template | Task | Variables | Version | Evidence status |
|---|---|---|---|---|
| [TC-Reply-Inquiry](templates/TC-Reply-Inquiry-v2_2026_10_15.md) | Answer a learner’s question | [INQUIRY], [LANGUAGE], [TONE], [MAX_WORDS], [CENTER_FACTS] | v2 | Pass: 5/5 prompt, 6/6 template, 5/5 output |
| [TC-Summarize-Complaint](templates/TC-Summarize-Complaint-v2_2026_10_15.md) | Condense a learner’s complaint | [MESSAGE], [LANGUAGE], [TONE], [MAX_WORDS], [CENTER_FACTS] | v2 | Pass: 5/5 prompt, 6/6 template, 5/5 output |
| [TC-Classify-Request](templates/TC-Classify-Request-v1_2026_10_15.md) | Sort incoming requests | [INQUIRY], [CATEGORIES], [LANGUAGE], [MAX_WORDS], [CENTER_FACTS] | v1 | Pass: 5/5 prompt, 6/6 template, 5/5 output |
| [TC-Soften-Staff-Draft](templates/TC-Soften-Staff-Draft-v1_2026_10_15.md) | Soften a staff draft | [DRAFT], [LANGUAGE], [TONE], [MAX_WORDS], [CENTER_FACTS] | v1 | Pass: 5/5 prompt, 6/6 template, 5/5 output |
| [TC-Flag-Refund-Exception](templates/TC-Flag-Refund-Exception-v1_2026_10_15.md) | Refund exception note | [REQUEST], [LANGUAGE], [TONE], [MAX_WORDS], [CENTER_FACTS] | v1 | Pass: 5/5 prompt, 6/6 template, 5/5 output |


## Shared reference

- [Training Center Facts v1](blocks/TC-Facts-v1_2026_10_15.md): the seven invented Scenario B1 facts.
- [Responsible-use rules v1](rules/TC-Rules-v1_2026_10_15.md): data, verification, fairness, policy and human decision.
- [How to use this library](library_guide.md).
- [Test Results Report](Test_Results_Report.pdf).

## Language choices

Arabic | English | Automated (default) | Bilingual | Mixed.

## Change log

| Date | Change |
|---|---|
| 2026_10_15 | Started the final project from the Day 4 library pattern and the guided training-center scenario. |
| 2026_10_15 | Added five new TC templates, one shared facts block and five checkable responsible-use rules. |
| 2026_10_15 | Added five genuine run screenshots, completed the additional fills and edge cases, and reviewed the corrected test responses. |
| 2026_10_15 | Released v2 of the reply and complaint-summary templates; archived v1 copies. All five templates now pass the required criteria. |

Five tested templates meet the 5/5 prompt, 6/6 template and 5/5 output checklists based on the recorded runs. Approval here means the template is suitable for the training library; a human reviewer still approves each outbound reply.
