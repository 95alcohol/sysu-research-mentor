# SYSU Research Mentor

An evidence-aware research direction and mentor matching skill for students at Sun Yat-sen University (SYSU), as well as students exploring graduate opportunities across China.

It is designed for a problem that is usually much messier than "find a famous professor": turning unclear interests, career plans, practical constraints, and incomplete public information into a research decision that a student can inspect and revise.

## What It Helps With

- Explore roughly 20 understandable research directions, including relevant subfields.
- Match directions to a student's interests, preparation, goals, and preferred ways of working.
- Search SYSU or nationwide faculty pools, depending on the student's graduate-school plans.
- Build a source-linked mentor dossier covering official profiles, publications, group activity, admissions fit, research networks, and public student-experience signals.
- Identify documented international collaborations, exchange pathways, and overseas-facing networks for students considering study abroad.
- Check whether a mentor publicly recruits for the relevant degree type, program, and specialty.
- Draft a truthful, personalized first-contact email.
- Run a four-week laboratory observation and review process after contact.

## How It Works

1. **Student intake**
   Uses flexible questions with fixed options and an `Other` field. It captures academic background, interests, skills, time commitment, graduate plans, career goals, and work-style preferences.

2. **Direction map**
   Produces 18-24 plain-language research directions. Each direction explains the underlying questions, typical work, methods, prerequisites, fit rationale, and a low-cost way to test interest.

3. **Mentor research**
   Builds a broader candidate pool, normally 10-25 mentors when evidence permits. Profiles synthesize official sources, publication histories, projects, representative works, group scale, output patterns, admissions information, collaboration links, and stated uncertainty.

4. **Decision support**
   Produces a dated PDF dossier and highlights the two or three strongest matches outside the PDF. Recommendations explain both fit and the facts that still need direct verification.

5. **Outreach and review**
   Creates a personalized email without inventing experience, then supports a month-long review of mentorship, lab culture, workload, training, authorship/data practices, and career alignment.

## Evidence and Reputation Handling

The skill searches accessible official pages, public WeChat articles, Zhihu, Xiaohongshu, Douyin, and other relevant public sources for both favorable and unfavorable signals. Retained public posts record their source, date, link, claim category, and evidence grade.

It does **not** treat social-media claims as findings. Serious allegations, including publication-integrity or student-treatment concerns, are separated from confirmed records and checked against primary evidence such as journal notices, corrections, retractions, institutional statements, or other authoritative records. Unverified public posts may be shown as source-linked leads for the student to investigate, but they do not affect numerical rankings.

## Scope Rules

- If a student is focused on SYSU, the search prioritizes SYSU mentors.
- If a student can pursue recommendation-based admission or entrance exams but has not selected a target university, the search can expand nationwide.
- If a student is considering overseas study or work, the skill prioritizes documented international collaboration and student-accessible pathways rather than superficial signals.
- Work-style questions are treated as fit preferences, not personality diagnoses or moral judgments.

## Outputs

| Mode | Deliverable |
|---|---|
| Direction exploration | Student profile, direction map, and validation actions |
| Mentor screening | PDF dossier, comparison table, collaboration map, and top recommendations |
| Admissions check | Degree/program eligibility, official quota or proposed-admission evidence, and unknowns |
| Career path | SYSU/nationwide scope, overseas connections, and lab-style fit |
| Outreach | Personalized email, subject lines, attachment checklist, and follow-up |
| Lab review | Four-week observation plan, check-ins, and a final fit assessment |

## Skill Structure

```text
sysu-research-mentor/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── admissions.md
    ├── career-and-style.md
    ├── directions.md
    ├── email.md
    ├── intake.md
    ├── mentor-dossier.md
    ├── network.md
    ├── observation.md
    └── rubric.md
```

## Example Prompt

```text
Use $sysu-research-mentor to help me explore biomedical research directions.
I am a SYSU undergraduate interested in graduate school but have not decided
between staying in Guangzhou, applying nationally, or studying abroad.
I want to build strong research skills and can accept a demanding lab if the
mentoring and expectations are clear.
```

## Important Limitations

This skill supports decisions; it cannot guarantee that a faculty member is recruiting, has open capacity, will reply, or will be a good long-term mentor. Public information can be incomplete or outdated. Students should verify admissions availability, supervision arrangements, expectations, and laboratory conditions directly before committing.
