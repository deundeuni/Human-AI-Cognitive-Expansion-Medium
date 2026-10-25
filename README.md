# Human-AI: Cognitive Expansion Medium — English Summary

> **The Korean document ([`README.ko.md`](./README.ko.md)) is the original and the one that counts.** This is a medium-length summary so English readers can see what the note is and how careful (or not) it tries to be. It is not a full translation. Some tone and nuance will be lost, and if anything here differs from the Korean text, the Korean text wins.

**Subtitle:** Can AI be a "cognitive expansion medium"? Evidence for benefits, evidence for risks, and the conditions, written down together.
**Type:** Idea White Paper (Track 2), a literature-organizing note · **Organizer:** deundeuni · **Version:** v1.0.2 (2026-10-24) · **License:** CC BY 4.0

---

## 1. What this is, and what it is not

*Reading order: the Korean document is long. The five-line summary, the "how to read" section, and section 13 (what could not be confirmed) are enough to grasp its character; then pick the parts you care about and check numbers against the original sources.*

This is a casual, honest scribble that happened to grow long. A non-expert tried to line up public papers, statistics, and official documents around one question: *can generative AI be seen not only as a one-way tool but as a mediator that sits between a person's thinking and the result, and changes the thinking along the way? Under what conditions, and with what risks?*

- It claims **no originality**. The ideas belong to their original authors (Latour, Verbeek, Vygotsky, Clark & Chalmers, Engelbart, Licklider, Akata et al., and others). The organizer only arranged them.
- It is **not** an academic paper, a theory proposal, a patent claim, or legal advice. Everything is AS-IS, with no warranty.
- The organizer is **not a domain expert**. Mistakes are possible. Please check the original sources before relying on anything. The source list can be wrong too (bibliographic details or links may be off), so open the originals before citing.
- **A subjective viewpoint is built in.** This note started from the organizer's own question, so the choice of what to search for and what to include reflects the organizer's perspective. Counter-evidence is placed next to supporting evidence on purpose, but the selection is still one person's, not a complete or neutral survey.
- **AI use, stated plainly.** AI tools were used as a means of extending the organizer's thinking, and for literature search, drafting, structuring, and checking against sources. Like a driver-assistance feature (an analogy, not evidence), the AI did a good part of the actual work, while the questions asked, what to include or leave out, how verification labels are assigned, whether to place counter-evidence alongside, final approval, and responsibility rest with the organizer. Concretely, the organizer set the question, kept changing the search direction, asked for counter-evidence and verification labels, obtained original papers and reports and supplied them for checking, and decided what went in. Errors and overstatements were rechecked with several AI tools; items that could not be confirmed are marked by label.

## 2. The structure it describes (an example, not a proven method)

A person is the hub for direction and final checking. Several AIs take turns on a first draft, an error check, and a different viewpoint. AIs do not chain into each other automatically; everything passes through the person, who rewrites the shared brief each round. Three operating principles:

| Principle | Meaning | Where it shows up in the "common brief" |
|---|---|---|
| **Direction first** | Purpose, reasons, and red lines are set by the person before anything else. | Goal, red lines |
| **Common brief** | One shared document handed to every AI, so they work from the same context. | The whole template: goal / audience / premises / red lines / verification-level rules / mode / known limits |
| **Mode tagging** | "Confirmed" (only what a human verified) vs. "exploratory" (just looking at possibilities, not a decision). | Verification-level rules, mode |

The "mediator" framing is closer to a metaphor than a strict definition, and the loop itself is the organizer's hypothesis, not a tested method. Whether this loop actually reduces errors in real use has **not been shown** (see section 6).

## 3. How to read the labels

Every source carries a label saying how much of it was actually checked.

| Label (Korean original) | Meaning |
|---|---|
| `[1차, 본문 확인]` | Primary source, full text checked against the claim |
| `[1차]` | Primary source or official document checked |
| `[1차-발췌]` | Checked through an official excerpt; full text not reachable |
| `[1차, 본문 일부·초록·요약 확인]` | Primary source; the checked range is stated |
| `[프리프린트]` | Preprint, not yet peer reviewed |
| `[2차]` | Secondary source (press, commentary, summary) |
| `[기억 기준]` / `[미확인]` | Title/bibliography only, or not verified |

Anything the organizer *inferred* is marked as "organizer's inference (not evidence)" and kept in its own block. Analogies are marked "analogy, not evidence".

## 4. What the literature says (very short, each with its catch)

**Same AI, different outcomes depending on how it is used**
- In a large school study, answer-only use lowered later exam scores without AI (about 17%); hint-style design avoided that loss but did not produce a gain (Bastani et al., PNAS 2025). *Catch:* one setting; the final analysis count is not stated in the main text.
- In an idea-generation experiment, a model-led style raised idea quality but reduced diversity and the user's sense of ownership, while a person-led style kept both (Maier et al., preprint). *Catch:* idea generation only; quality rose in both styles; abstract-level check.

**Benefits do exist, with conditions**
- A well-designed AI tutor beat in-class active learning in one intro physics course (Kestin et al., Sci Rep 2025; median post-test 4.5 vs 3.5). *Catch:* one course, first-time topics, a platform built carefully by the instructor, and one author was that instructor.
- A short professional writing task got faster by about 37% with higher scores (Noy & Zhang, working paper 2023). *Catch:* short task, and 68% submitted the AI draft unedited. The journal version was not read.
- Developers finished a coding task about 56% faster (Peng et al., preprint, authors affiliated with the tool makers). *Catch:* wide confidence interval; success rate did not differ significantly; code quality not measured.
- Overall: gains tend to appear for short, closed tasks, new topics, and good guidance, mostly on short-term measures. Whether they carry over to long-term learning or whole jobs is unknown.

**Human + AI is not automatically better**
- A meta-analysis found human+AI combinations were on average worse than the better of the two alone; decision tasks showed a significant loss, content-creation tasks did not (Vaccaro et al., Nat Hum Behav 2024). *Catch:* possible publication bias and differences in study design.
- "A human is overseeing it" does not by itself make things safe (e.g., Green 2022).
- People can overestimate their own performance when working with AI: in two online studies (Fernandes et al., 2026), participants who solved logic problems with AI scored about 3 points higher than a non-AI comparison but overestimated their own score by about 4 points. *Catch:* a quasi-experiment, correlational reading, and AI literacy was self-reported.

**Asking several AIs**
- Letting copies of a model debate raised benchmark accuracy (Du et al., ICML 2024). *Catch:* benchmark tasks, mostly copies of the same model; confident facts were hard to change.
- But different models' mistakes often overlap, more so for models from the same developer or architecture (Kim et al., ICML 2025). *Catch:* multiple-choice and résumé-screening tasks only.
- So "ask more AIs" may help or may just repeat the same blind spot. Not shown for open-ended, real-world use.
- How people actually check: in a consumer survey (F-Secure, April 2026, US and UK, n=1,500; vendor survey, self-reported), 29.9% of AI users check answers regularly, 34.6% sometimes, 35.5% rarely or never; 35.3% had used AI to fact-check AI, which the report itself calls not independent evidence. A US survey (Ad Council Research Institute with Google, n=1,503, May 2025; read through the institute's blog post, not the paper) found about three in four check at least sometimes and 13% always; some compare answers across several AI tools, but no share is given. *Catch:* both are self-reported surveys, and neither says how common multi-AI comparison is or whether it reduces errors.

**Time, background, and groups**
- A five-month field experiment with 640 entrepreneurs found no average effect distinguishable from zero; lower performers did somewhat worse, higher performers somewhat better, with weak statistical support (Otis et al., Management Science 2026).
- Surveys show gaps in use and confidence by gender, education, and country (Savoldi et al.; HEPI; others). *Catch:* self-reported, correlational, mostly non-random samples. They show differences, not causes.

**Responsibility (not legal advice, varies by country)**
- If you publish under your own name, much of the duty to check stays with you (for example, sanctions over fabricated citations in *Mata v. Avianca*, 2023), while rules that share responsibility with providers are starting to appear.
- The note does not claim an AI "has intent" or "lacks desire" on its own; it relies on how official frameworks describe this and is careful not to overclaim.

**Teaching thinking**
- Critical-thinking teaching existed before AI and shows small average effects, larger when practice, dialogue, and mentoring are combined (a 2015 meta-analysis, read only through a secondary summary). Whether such training improves AI use has **not** been measured.

## 5. How this note was made (a factual record, not a claim of effect)

- Sources: the organizer set the question and used AI tools to find candidates; original papers supplied by the organizer were checked first.
- Labels: each source is labeled by whether the full text or only an abstract or summary was checked (section 3).
- Numbers: figures and judgments were compared with the original text, and mismatches were corrected, including wrong readings found while building this note.
- Cross-checking: AI tools re-reviewed drafts, but that is not independent verification; the final check rests on comparison with the originals and the organizer's review.
- Inclusion: papers that fit the organizer's question were sought, with a preference for those whose originals could be obtained, and counter-evidence was placed alongside supporting evidence. Search terms and excluded papers were not recorded.
- Limits: there is no systematic search protocol and no expert review. Some checks, such as confirming that every link opens, remain.
- The organizer routinely works this way and works on the premise that it can be wrong. This is the organizer's own statement, not evidence.
- This is one case of applying the structure in section 2. It is only a case; whether the approach reduces errors is not confirmed here.

## 6. What could not be confirmed (the most important part)

1. Whether cross-checking with several AIs reduces errors in real use (open-ended questions, beginners).
2. The effect of the "human as hub" loop itself.
3. How long-term use changes ways of thinking.
4. Whether background *causes* differences in AI-use ability.

Also: many sources were read only at abstract level, some are preprints, and a few are secondary summaries. A handful of recent papers on human-checked, AI-assisted literature work are listed as *related references only*. None of them tests the way of working described here, and none should be read as proof that it is right. As a rough scale (v1.0.2): of 74 source entries in section 12 of the Korean document, 32 carry at least one weaker label (abstract, preprint, secondary, excerpt, or partial check), and section 13 lists 28 unverified items. Entries can hold several sources, so these are approximate counts. The full list of unverified items is in section 13 of the Korean document, and section 12 there lists all sources with their labels.

## 7. The organizer's own inferences (kept separate, not evidence)

Section 9 of the Korean document contains a block of the organizer's inferences, for example: how a person uses AI is shaped by many things (environment, habits, education); responsibility stays attached to people and organizations, not to the AI; and more convenience probably calls for more care. Each is labeled as an inference that does not conflict with the confirmed sources *so far*. That is a weaker claim than "no errors", and the Korean text uses that exact wording on purpose.

**The organizer's stance (not an inference, not evidence):** This note started because a non-expert was curious. There may be mistakes, so please check the sources yourself. Whether this way of working suits other people, the organizer does not know either.

## 8. Where to go next

- Full document with all sources, labels, and caveats: [`README.ko.md`](./README.ko.md) (Korean)
- If you spot a wrong number, a mislabeled source, or a missing counter-example, please open an issue. Corrections are the most useful thing a reader can do for this note.
