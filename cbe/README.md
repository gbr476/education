# Credit by Examination (CBE) — Texas

Notes on testing out of math courses (Algebra 1, Algebra 2, Precalculus) via Texas
Credit by Examination, for a home-schooled 8th grader entering a public school district.

**This is a plain-language summary of the rules, not legal advice.** Because so much
rides on *local district policy*, the district's own **EHDC (LOCAL)** policy is the
document that actually governs a given student's case.

### Local files in this directory

- [`tea-credit-by-exam-faq.pdf`](./tea-credit-by-exam-faq.pdf) — TEA's official Credit by Exam FAQ (Jan 2022). The 22 Q&A that most of this summary rests on.
- [`tea-mathematics-faq.pdf`](./tea-mathematics-faq.pdf) — TEA Mathematics FAQ; course sequencing & prerequisite rules (§74.11).
- [`tea-mathematics-prerequisite-tables.pdf`](./tea-mathematics-prerequisite-tables.pdf) — the actual per-course prerequisite chains (shows Precalculus requires Algebra 2 + Geometry). Directly relevant to Q1/Q2.
- [`19-tac-74.24-rule-text.md`](./19-tac-74.24-rule-text.md) — key provisions of the governing rule §74.24 (+ §74.11), quoted with citations. No official PDF exists anymore — TEA retired the per-chapter PDFs; the SOS now serves the rule as HTML only.
- [`uths-calculator.pdf`](./uths-calculator.pdf) — UT High School calculator policy for CBEs. **All high-school math CBEs require a graphing calculator (TI-84 recommended); CAS calculators (TI-89, TI-Nspire CAS) are prohibited; memory must be cleared to factory default.** Applies to every math exam below.
- [`uths-individual-request-proctor-form.pdf`](./uths-individual-request-proctor-form.pdf) — UT High School proctor rules + individual (home-school) request form. **A parent may NOT proctor;** approved proctors are a counselor, registrar, school administrator, certified teacher/substitute, campus librarian, or education officer — home-schoolers test at a local high school or a college/university testing center (or via UT's Proctorio remote proctoring). Form is an older revision (fee shown is out of date); the proctor eligibility is the current rule.

### Subject-specific exam materials (UT High School CBE study guides)

Per-course study guides live in each math subject's `cbe/` folder. UT splits each course
into two semester exams (**A** = first semester, **B** = second semester); **both must be
passed for the full year of credit**.

- Algebra 1 → [`/git/school/math/algebra1/cbe/`](../math/algebra1/cbe/)
- Geometry → [`/git/school/math/geometry/cbe/`](../math/geometry/cbe/)
- Algebra 2 → [`/git/school/math/algebra2/cbe/`](../math/algebra2/cbe/)
- Precalculus → [`/git/school/math/precalculus/cbe/`](../math/precalculus/cbe/)

Source for all study guides: UT High School CBE — <https://highschool.utexas.edu/credit_by_exam>

## Index

- [The two kinds of CBE (the key distinction)](#the-two-kinds-of-cbe-the-key-distinction)
- [Fixed statewide rules](#fixed-statewide-rules)
- [Q1: Can the district deny multiple math exams?](#q1-can-the-district-deny-him-taking-algebra-1-algebra-2-and-precalculus)
- [Q2: Does failing a lower exam block a higher one?](#q2-if-he-fails-algebra-2-is-he-blocked-from-precalculus)
- [Q3: Can he leave a class after passing its CBE?](#q3-if-hes-already-enrolled-and-passes-the-cbe-can-he-leave-the-class)
- [Action items](#action-items)
- [Sources](#sources)

---

## The two kinds of CBE (the key distinction)

Which type applies changes the passing score, the graduation-exam obligation, and the
whole strategy.

| | **No prior instruction** (acceleration) | **With prior instruction** (credit recovery) |
|---|---|---|
| Passing score | **80%** | **70%** |
| Result | Earns credit; for a course with a STAAR End-of-Course (EOC) exam (e.g. Algebra I), **exempts him from the EOC** | Earns credit *per local policy*, but he **still owes the STAAR EOC** for graduation |
| Rule | §74.24(c)(8), (c)(11) | §74.24(c)(12); FAQ #21–22 |

For a home-schooled child testing out of courses he studied on his own — **before
enrolling** in the district — this is the *no-prior-instruction / 80%* path, which is
the better one. "Prior instruction" is **defined by the local district**, but sitting
in and attending the class is generally treated as prior instruction.

## Fixed statewide rules

- The district **must** offer CBE — it's a state mandate (TEC §28.023(a); FAQ #3).
- The district **cannot charge** for it (§74.24(a)(3); FAQ #8).
- **4 testing windows/year** (one per calendar quarter); a specific exam may be taken
  **once per window** (§74.24(a); FAQ #9).
- **No more than 2 attempts** per specific high-school course (§74.24(c)(9); FAQ #12).
- CBEs must cover **all assessable TEKS** for the course; STAAR itself can't be used as
  a CBE (FAQ #7). Approved providers include **UT Austin** and **Texas Tech**.

## Q1: Can the district deny him taking Algebra 1, Algebra 2, and Precalculus?

**No — it cannot deny the *opportunity* to take CBEs; that's mandated.** But two real
limits apply to taking *all three*:

- **Availability** — the district must approve at least four exams *per course* "to the
  extent available" (§74.24(c)(1)). Algebra 1, Algebra 2, and Precalculus CBEs are all
  offered by UT Austin / Texas Tech, so this shouldn't be a barrier.
- **Course sequence / prerequisites (the real constraint)** — Under §74.11 prerequisites
  are course-specific, **not one long chain** (per the Math Prerequisite Tables):
  - **Algebra II** → only prerequisite is **Algebra I**.
  - **Geometry** → only prerequisite is **Algebra I**. (So Geometry and Algebra II are
    *parallel* — either order, or concurrently; Geometry is **not** required before Algebra II.)
  - **Precalculus** → requires **all three: Algebra I, Geometry, and Algebra II**.

  A student can't be placed past a prerequisite he hasn't met *unless* the district
  accepts "demonstrated equivalent knowledge" (§74.11(j)).

**Practical answer:** he can pursue all three. To earn **Algebra 2** credit by exam he
first needs **Algebra 1** credit. To earn **Precalculus** credit by exam he needs credit
for **Algebra 1, Geometry, *and* Algebra 2** — so **Geometry can't be skipped on the way
to Precalculus** (he'd need to test out of, or take, Geometry too), though it need not
come *before* Algebra 2. The district controls scheduling and can insist prerequisites be met.

## Q2: If he fails Algebra 2, is he blocked from Precalculus?

**Not by the CBE rule directly — but effectively yes for *credit* purposes, via
prerequisites.**

- Failing the Algebra 2 CBE = **no Algebra 2 credit**. Precalculus requires Algebra 2 as
  a prerequisite (§74.11), so without that credit he generally **can't earn Precalculus
  credit by exam** either.
- Escape hatch: §74.11(j) lets a district accept "**equivalent knowledge as determined
  by the school district**" instead of the prerequisite — a **local decision**.
- §74.24(c)(10): if he fails the CBE *before the year he'd normally take that course*, he
  must **actually complete the course** to earn its credit. Failing isn't permanent — he
  gets up to 2 CBE attempts, then it's the classroom route.

**Bottom line:** don't count on skipping a failed level. Plan for him to pass each rung.

## Q3: If he's already enrolled and passes the CBE, can he leave the class?

**A local scheduling decision — state rule doesn't spell out mid-year schedule changes.**
Earning the credit satisfies the course requirement, so a district would normally adjust
his schedule (move him up / give an alternate). Whether and when they release him
mid-semester is up to the campus.

**The trap to avoid:** once he's *enrolled in and attending* the class, the district will
likely treat the CBE as "**with prior instruction**" — the **70% credit-recovery** path —
so for an EOC course he'd **still owe the STAAR EOC** for graduation.

**Recommendation:** have him test out **before enrolling** in each course (use a summer or
fall window). That keeps him on the *no-prior-instruction / 80%* track — earns the credit,
exempts him from the EOC, and sidesteps the "can he leave the class" question entirely.

## Action items

Ask the district (counselor or Advanced Academics / GT coordinator) for:

1. Their **EHDC (LOCAL)** policy and the **CBE testing-window calendar**.
2. Which **approved exams** they use for Algebra 1, Algebra 2, Geometry, Precalculus
   (UT Austin vs. Texas Tech vs. district-built).
3. **In writing:** how they define "prior instruction," how they handle
   **prerequisites/sequence** for a student testing out, and how they'll **exit him from
   a class** if he earns credit — ideally confirming he can test out *before* enrolling so
   he stays on the 80% / EOC-exempt path.

## Sources

- 19 TAC §74.24 — Credit by Examination: <https://www.law.cornell.edu/regulations/texas/19-Tex-Admin-Code-SS-74-24>
- TEA — Credit by Examination page: <https://tea.texas.gov/curriculum-and-instruction/learning-support-and-programs/credit-examination>
- TEA — Credit by Exam FAQ (PDF, saved locally as `tea-credit-by-exam-faq.pdf`): <https://tea.texas.gov/academics/learning-support-and-programs/cbe-faqs-2021-2022.pdf>
- TEA — Mathematics FAQ landing page (course sequencing & prerequisites, §74.11): <https://tea.texas.gov/educators/subject-areas/mathematics/mathematics-frequently-asked-questions> (PDF: `math-faq-6-4-26-0.pdf`, saved locally)
- TEA — Mathematics Prerequisite Tables (PDF, saved locally): <https://tea.texas.gov/educators/subject-areas/mathematics/mathematics-prerequisites.pdf>
- 19 TAC §74.24 full text (Cornell LII / eLaws — no official PDF; SOS portal is HTML only): <http://txrules.elaws.us/rule/title19_chapter74_sec.74.24>
- Governing statute: Texas Education Code §§ 25.007 and 28.023

_Rules current as of the TEA FAQ dated January 2022; confirm nothing has changed with the district before relying on specifics._
