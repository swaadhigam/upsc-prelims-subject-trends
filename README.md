# UPSC Prelims subject trends, 2015–2026

How many questions each subject got in **UPSC Civil Services Prelims, General Studies Paper I**, every year from 2015 to 2026, plus how the question formats changed over the same twelve papers. 1,200 questions, each classified one by one.

Maintained by [Swaadhigam](https://swaadhigam.com). The same numbers, with charts and every question listed under its subject, are at:

- [UPSC Prelims subject-wise questions and weightage, 2015–2026](https://swaadhigam.com/upsc/prelims-subject-wise-questions)
- [UPSC Prelims 2026 analysis: subjects and question formats](https://swaadhigam.com/upsc/prelims-2026-analysis)
- [Every Prelims GS Paper I, 2015–2026, question by question](https://swaadhigam.com/pyq/prelims)

## Files

| File | What it holds |
|---|---|
| `data/subject_counts_wide.csv` | One row per subject, one column per year (2015–2026). Each year's column adds up to 100. |
| `data/subject_counts_long.csv` | The same data, one row per `year, subject, questions`, ready for charting tools and pandas. |
| `data/question_formats_wide.csv` | Question formats per year. Numbered-list, Statement-I / Statement-II and single-sentence questions add up to 100 each year. "How many" and case-based questions are counted inside them. |

## A few things the data shows

- **Economy** carried 12 to 26 of the 100 questions a year, and topped or tied for the top in 7 of the 12 papers (Polity led in 2017, 2021 and 2023; Polity and Geography tied in 2024; Science & Technology led in 2026).
- **Polity** swings the most: 5 questions in 2016, 22 in 2017, 17 in 2025 and 7 in 2026.
- **Current-affairs** questions went from 1 in 2020 to 14 in 2026.
- **2026** set three case-based ethics questions (51–53), the first in any of the twelve papers. It also dropped the "How many of the above" format, which had 45 questions in 2023.

## How the questions were counted

Every question of the official GS Paper I, 2015 to 2026, is tagged to the chapter of the GS syllabus it tests:
- A question gets exactly one subject. Where it carries more than one chapter tag, the tag with the highest confidence decides.
- The tags were assigned with AI assistance against a fixed list of syllabus chapters.

UPSC publishes no subject-wise split, so every count, including this one, is somebody's classification. A question on a constitutional body's role in elections can fairly be counted as Polity or as current affairs. That is why counts from different sources differ by a few questions. Ours can be checked: [each year's paper](https://swaadhigam.com/pyq/prelims) lists every question under the subject it was counted in.

The three 2026 ethics questions (51–53) are counted from the official paper.

**Source:** Union Public Service Commission, [previous question papers](https://www.upsc.gov.in/examinations/previous-question-papers), Civil Services (Preliminary) Examination, General Studies Paper I, 2015–2026.

## Using the data

Free to use, share and adapt under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), with credit. Suggested citation:

> Swaadhigam (2026). *UPSC Prelims subject trends, 2015–2026.* https://swaadhigam.com/upsc/prelims-subject-wise-questions

Found a question you would count differently? Open an issue with the year and question number.

## Related

- [upsc-syllabus-tree](https://github.com/swaadhigam/upsc-syllabus-tree): the UPSC GS, CSAT, Essay and Optional syllabus as a topic tree, linked to free study notes.
