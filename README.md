# CPA shortage data

U.S. schools awarded 55,152 accounting bachelor's and master's degrees in
2023-24, down 6.6%, while BLS projects about 115,300 accountant and auditor
openings a year through 2035. NASBA counted 650,667 actively licensed CPAs in
August 2026. This repository has those figures and the rest of the pipeline
data in one CSV, each linked to its AICPA, NASBA or BLS source.

## Files

| File | What it is |
|---|---|
| `data/statistics.csv` | 39 statistics, one per row: `id`, `statistic`, `value`, `unit`, `period`, `source_name`, `source_url`, `notes`. Numbers are plain so they sort and sum. Rows with unit `text` hold an answer in words, such as a survey's top issue. |
| `CITATION.cff` | Citation details for this collection. |

## Key figures

| Statistic | Value | Period | Source |
|---|---|---|---|
| Accounting graduates, bachelor's plus master's | 55,152 (down 6.6%) | 2023-24 | [AICPA](https://www.aicpa-cima.com/news/article/accounting-firms-report-strong-hiring-outlook-aicpa-report-finds) |
| Accounting bachelor's degrees | 40,817 (down 3.3%) | 2023-24 | [AICPA](https://www.aicpa-cima.com/news/article/accounting-firms-report-strong-hiring-outlook-aicpa-report-finds) |
| 4-year undergraduate accounting enrollment | 205,180 (up 8.9%) | Spring 2026 | [AICPA](https://www.aicpa-cima.com/news/article/u-s-accounting-undergraduate-enrollment-continues-to-outpace-growth-rate-for-business-majors-overall) |
| New CPA exam candidates | 42,626 / 28,082 | 2023 / 2024 | [AICPA](https://www.aicpa-cima.com/news/article/accounting-firms-report-strong-hiring-outlook-aicpa-report-finds) |
| Cumulative pass rate, FAR | 42% | 2025 | [AICPA](https://www.aicpa-cima.com/professional-insights/article/the-new-cpa-exam-two-years-in) |
| Actively licensed CPAs, 53 of 55 jurisdictions | 650,667 | Aug 27 2026 | [NASBA](https://nasba.org/licensure/how-many-cpas/) |
| Median age, employed accountants and auditors | 44.7 | 2025 | [BLS CPS](https://www.bls.gov/cps/cpsaat11b.htm) |
| Accountants and auditors aged 55 and over | 479,000 of 1,766,000 (27.1%, our math) | 2025 | [BLS CPS](https://www.bls.gov/cps/cpsaat11b.htm) |
| Bookkeeping clerks aged 55 and over | 501,000 of 1,254,000 (40.0%, our math) | 2025 | [BLS CPS](https://www.bls.gov/cps/cpsaat11b.htm) |
| Average yearly openings, accountants and auditors | 115,300 | 2025 to 2035 | [BLS OOH](https://www.bls.gov/ooh/business-and-financial/accountants-and-auditors.htm) |
| Top issue, CPA firms of every size but sole practitioners | Finding qualified staff | 2024 | [AICPA PCPS](https://www.aicpa-cima.com/news/article/staffing-irs-service-problems-and-leadership-development-are-top-issues-for) |
| States that adopted the bachelor's plus experience path | Half of the states | Nov 2025 | [AICPA](https://www.aicpa-cima.com/advocacy/article/state-policy-trends-shaping-accounting-in-2026) |

## How to use it

1. Open `data/statistics.csv` in Excel or Google Sheets. Filter on the `id`
   prefix for one group: `pipeline`, `exam`, `workforce`, `firms` or
   `licensure`.
2. Check `unit` and `period` before quoting. Enrollment is counted by spring
   term; degrees by academic year.
3. Quote the original source next to each number, then cite this collection.

## Openings against graduates

One rough way to see the gap. This comparison is ours, not a published ratio.

| Measure | Figure | Source |
|---|---|---|
| Accountant and auditor openings a year, 2025 to 2035 | 115,300 | BLS OOH |
| Accounting bachelor's and master's graduates, 2023-24 | 55,152 | AICPA |
| New CPA exam candidates, 2024 | 28,082 | AICPA |

Openings include replacing people who retire or change jobs, and not every
opening is filled by an accounting graduate, so the gap is not a precise
shortage count.

## Notes on the data

- Every figure was checked against its primary source on November 4, 2026.
- A licensed CPA and an employed accountant are different counts. NASBA counts
  licenses; BLS counts people working in the occupation. There is no official
  count of CPAs by age.
- The BLS CPS 2025 annual averages leave out October.
- The 55 and over shares are our math from the BLS table and say so in the
  `notes` column. None of these are ZeraBooks figures.

## Learn more

The same figures with context: [CPA shortage statistics](https://www.zerabooks.com/research/cpa-shortage-statistics) on zerabooks.com. Wages, jobs and firm counts: [Accounting and bookkeeping statistics 2026](https://www.zerabooks.com/research/accounting-bookkeeping-statistics-2026).

## License

The content and data in this repository are licensed under
[CC BY 4.0](LICENSE). Free to use and adapt with credit to ZeraBooks.
The underlying figures belong to the AICPA, NASBA and BLS.

Maintained by [ZeraBooks](https://www.zerabooks.com).
