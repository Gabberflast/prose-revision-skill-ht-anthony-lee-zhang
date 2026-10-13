---
name: prose-revision-skill-ht-anthony-lee-zhang
description: "Revise draft prose by designing the reader's path through the ideas the user already wants to express. The goal is clear logical movement supported by natural, elegant language: idea flow first, linguistic flow second. Prose revision is different from proofreading. Prose revision takes a relatively unpolished draft and gets the prose into good shape. Proofreading takes a close-to-done draft and catches mistakes, typos, obvious phrasing problems, and final copy-editing issues. Prose revision logically comes first."
---

# Prose Revision

## The reader's path

Treat revision as designing the route a reader takes through the argument. Walk the draft the way a reader would, one sentence at a time, and at each step ask: what does the reader understand now, what are they expecting or wondering because of what they just read, and does the next sentence meet that expectation or set up the right next one?

A well-revised passage gets the reader to the intended understanding without three kinds of trouble:

- **Leaps** — a step the reader cannot make from what they have been given, because a connection or premise was left implicit.
- **Detours** — material that pulls the reader off the route without paying off where they are.
- **Backtracking** — having to reread or reinterpret earlier sentences because something needed to understand them arrives only later.

Aim for the shortest path the reader can reliably follow, which is not the same as the fewest words. Sometimes the fix is cutting a detour; sometimes it is adding a bridging sentence that makes explicit a step the author skipped. Most of the work is ordering, connecting, and weighting the ideas. Wording, transitions, and rhythm come afterward, and their job is to keep the reader on the route.

Everything below follows from this: idea flow before linguistic flow, structure before wording, larger units before smaller ones.

## Default stance

Assume the user usually has the right set of ideas and wants help discovering the best path through them. Revise aggressively at the level of order, emphasis, sentence boundaries, transitions, and paragraph shape, while preserving the substantive claims. The rule of thumb: aggressive on structure, conservative on content.

The reader's path runs through every level — sentence, paragraph, section, and whole — and the same discipline applies at each: get the ideas into the right order, and let each unit do one clear job, before smoothing the language inside it. The largest levels come first, because a paragraph that presupposes something established only later forces backtracking that no sentence-level work can fix.

Before diagnosing structure, note the intended audience, the piece's purpose, and the desired tone, since the path depends on what this reader already knows. Preserve the author's voice and register: the goal is the author's ideas made easier to follow, not a generic "clean" style imposed on top of them. When audience, purpose, or tone are not stated, infer them from the text; ask only when the ambiguity is consequential and cannot be resolved from context.

Do not add or subtract ideas by default, and do not change their strength. A bridging sentence that makes explicit a step the author already relies on is not a new idea; add one when the reader would otherwise have to leap, and say that you did. Add a genuinely new idea, remove an idea, or move an idea out of its unit only when it is clearly necessary for the path to work — and make that intervention explicit. Preserve hedges and claim strength with the same care: do not turn "suggests" into "shows" or drop a load-bearing "may" for the sake of cleaner prose. Sharper wording must not quietly sharpen the claim.

If the draft is already clear and well-ordered, say so and make only minimal changes. Do not manufacture edits to look productive. "This already works; here are two small tightenings" is a valid response.

Treat an awkward sentence as evidence of a possible break in the path, not merely a bad-English problem. A sentence is often awkward because it is trying to do two jobs at once, because the previous sentence did not prepare the reader for it, or because the unit's logical order is not yet right.

## Workflow

1. Read the target prose and enough surrounding context to understand the argument and its intended reader.
2. For anything longer than a paragraph, check the larger route first: the order of paragraphs and sections, and whether each unit sets up the next. Fix that before working inside individual paragraphs.
3. Identify each unit's intended job: the claim, contrast, mechanism, qualification, implication, or transition it needs to deliver.
4. Walk the reader's path and mark each leap, detour, and backtrack. Common sources: missing connective tissue or a skipped step (leaps); asides, tangents, and qualifications that arrive before the claim they qualify (detours); buried main claims, ideas used before they are introduced, and a final sentence that belongs earlier (backtracking); and overloaded sentences that ask the reader to hold too much at once.
5. If the idea structure is what breaks the path, explain that structural problem first. Do not try to solve structural confusion with surface polish.
6. Rearrange and repack the existing ideas into a route the reader can follow. Only then make the language smoother, cleaner, and more elegant.
7. Offer revised versions when alternatives genuinely help, distinguished by how much they restructure (see Output style). Keep explanations concise and focused on how the revision changes the reader's path.
8. If the user asks you to apply edits, edit the source file rather than a generated copy, and preserve notation, citations, labels, author notes, and technical claims unless the user explicitly asks to change them. For academic or technical prose, make an explicit pass to protect precise terminology, claim strength, and technical claims.

## What to improve

Prioritize changes that make the reader's path shorter and more reliable:

- Order the units so each one sets up the next, and put the main point where it can organize what follows.
- Make each sentence answer the expectation the previous one created, or deliberately create the next one.
- Split sentences that are doing multiple logical jobs; combine sentences when separation makes the logic choppy.
- Move qualifications after the claim they qualify, unless the qualification must come first for accuracy.
- Add transitions only after the underlying relation between ideas is clear.
- Replace vague connective language ("also," "moreover") with the actual logical relation: contrast, mechanism, implication, caveat, example, or consequence.
- Prefer precise, economical wording once the path is sound.

## Output style

For short interactive requests, usually provide:

1. A brief diagnosis of where the reader's path breaks.
2. One to three revised versions. When a single revision is clearly best, give just that one; when alternatives make a real tradeoff, offer two or three, distinguished by how much they restructure:
   - **Light** — same order, cleaner sentences.
   - **Moderate** — resequenced ideas, adjusted emphasis.
   - **Full** — unit rebuilt around the main claim.
3. A one-line note on the tradeoff, or on why a single version suffices.

For documents longer than about three pages, provide a structured revision report (diagnosis plus prioritized changes) unless the user asks for direct edits. Address the larger route first, then work section by section, flagging the highest-leverage fixes first.

Keep line-level proofreading (typos, minor grammar) out of prose-revision responses unless it materially affects flow or clarity.

## Worked example

**Draft:**
"While it is important to note that the results are preliminary, and although the sample size was admittedly small, we found that the treatment group showed improvement, which was something we had hoped for, and this improvement was statistically significant."

**Diagnosis (walking the path):** The reader meets two caveats before learning what they are caveats about, so they must hold them with nothing to attach them to and mentally reapply them once the result appears — backtracking. The note about what the authors hoped for is a detour: it pulls attention to the authors' expectations without helping the reader understand the result. And the key detail, statistical significance, arrives last, after the reader has already formed a picture of a weaker finding.

**Revised** (one version suffices here — the fix is unambiguous):
"The treatment group showed a statistically significant improvement. This result is preliminary and rests on a small sample."

**Why it works:** The reader now gets the claim first, in full, and each caveat attaches to a claim they already hold, so nothing needs reinterpreting. The detour is cut — an explicit removal, justified because it gave the reader nothing they needed. The claim's strength is preserved exactly: "statistically significant improvement" is neither softened nor inflated.

The same diagnosis scales up: a claim buried at the end of a paragraph, or a paragraph placed before the one it depends on, sends the reader backtracking one level higher.
