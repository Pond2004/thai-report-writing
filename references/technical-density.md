
# Technical Writing Density

## When to use

Load this skill whenever you invoke `writing-clearly-and-concisely` on a technical document: API references, design specs, RFCs, runbooks, schema docs, configuration references, architecture notes, and issue-tracker tickets (Jira, Linear, GitHub/GitLab issues). A ticket's description, requirements, and acceptance criteria are technical prose a reader relies on for precision, so create and update them under this skill too. It refines one Strunk rule for the technical case and reinforces the rules that matter most there. The two skills work together: the general writing skill supplies the rules; this skill governs how to apply the concision rule when the reader needs precision.

## "Omit needless words" is about density, not length

Strunk's most-quoted rule — "omit needless words" — governs information density, not word count. It says cut words that carry no meaning. It does not say "make it shorter."

In technical documentation, apply this test to every proposed cut within the content chosen for the reader (deciding what to include comes first):

> Does removing this lose a reason, constraint, or disambiguation that matters to the topic and prevents a likely misreading?

If yes, the words stay — even when keeping them makes the sentence longer. A clause that records why a default was chosen, names a precondition, or rules out a wrong reading carries information, not padding. Cutting it trades a moment of brevity for an hour of a reader's confusion. Keep the ones that matter, not every one you can think of: kept wholesale, they bury the signal in noise.

Cut without hesitation:

- Filler that restates the heading or the obvious ("This section describes...", "It is important to note that...").
- Hedges and intensifiers that add no fact ("basically", "simply", "very", "quite").
- Throat-clearing that delays the sentence's actual claim.

Keep, even at the cost of length, when it matters to the topic:

- The reason behind a decision or a default.
- A constraint, precondition, or limit.
- A disambiguation that prevents a likely misreading.

## Rules that pay off unconditionally in technical docs

These Strunk rules remove ambiguity rather than detail, so apply them with no length trade-off:

- **Active voice** — name the actor. "The scheduler retries the job," not "the job is retried."
- **Definite, specific, concrete language** — concrete nouns over abstractions. "Returns 404," not "fails."
- **One idea per sentence** — the reader verifies one claim at a time.
- **Parallel structure for parallel requirements** — express equivalent requirements in equivalent grammatical form, so the reader sees at a glance that they are equivalent.

## Separate distinct items into lists for scannability

A concision pass tends to fold distinct items — parameters, options, error codes, steps — into one dense paragraph. That honors brevity and defeats scanning: a reader hunting for one item must read the whole paragraph, where a list lets them jump straight to it. In technical docs the reader scans far more often than they read start to finish, so visual structure carries information the way words do.

Break enumerated items out of running prose:

- **Bulleted list** for an unordered set — options, constraints, error codes.
- **Numbered list** for an ordered sequence — steps, precedence, ranked choices.
- **Table** when every item shares the same attributes — field, type, default.

Keep the items parallel in grammatical form and each to one idea. Scannability is not a license to pad: apply "omit needless words" inside every bullet.

## Bottom line

In technical prose, brevity serves clarity; it does not outrank it — and neither outranks scannability. Cut empty words ruthlessly. Keep the reasons, constraints, and disambiguations that matter to the topic and prevent a likely misreading, not every one you can think of. Break distinct items into lists so the reader can scan. Lean on active voice, concrete nouns, one-idea sentences, and parallel structure to remove ambiguity rather than detail.
