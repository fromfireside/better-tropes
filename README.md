# Better Tropes

**A catalogue of 49 AI writing tells, each with a plain rewrite.** Free to copy, paste into a system prompt, or fork.

Language models have habits. They reach for `delve` and `leverage`, open on "In today's fast-paced world", close on a motivational line nobody asked for, and hedge every claim into mush. Better Tropes names 49 of those habits and shows the version a careful human writer would produce instead.

It is one Markdown file. Paste it into a system prompt, a `CLAUDE.md`, a Cursor rule, or an agent skill.

## Use it

```bash
curl -O https://raw.githubusercontent.com/fromfireside/better-tropes/main/better-tropes.md
```

Then drop [`better-tropes.md`](better-tropes.md) into your system prompt as-is. It works unmodified, but it works better tuned to your workflow — a technical blog post is not a social post is not a listicle.

## Why the entries look like this

Most "make it sound less like AI" files are full of editorial commentary: explanations of *why* a phrase is bad, arguments with the reader, meta-instructions about tone. That commentary competes with the rest of your prompt and degrades performance on the actual task.

This one strips it out. Every entry names a tell, explains it in a sentence, and shows the two lines side by side.

> ### Elevated Filler Verbs
>
> Verbs that sound important but carry no more meaning than a plain one: `delve`, `leverage`, `utilize`, `harness`, `foster`, `streamline`, `unlock`, `embark`, `spearhead`, `navigate`. Prefer the shortest verb that is true.
>
> - **✗** We leverage data to unlock growth and streamline collaboration.
> - **✓** We use data to grow and to help teams work together.

## What's in it

| Section | Entries | Covers |
|---|---|---|
| Word Choice | 8 | Filler verbs, magic adverbs, abstraction nouns, empty superlatives |
| Sentence Structure | 9 | Rhythm tics, the negation flip, symmetrical constructions |
| Paragraph Structure | 3 | Openers and transitions that announce rather than say |
| Tone | 11 | Relentless positivity, false vulnerability, grandiose stakes |
| Formatting | 5 | Em-dash overuse, heading inflation, fragment emphasis |
| Composition | 7 | Definition openers, scope inflation, invented sources |
| Whole-Piece Patterns | 6 | Dead metaphors, one-point dilution, the motivational closer |

**[→ Read the full catalogue](better-tropes.md)**

A rendered, searchable version lives at [fromfireside.com/tools/better-tropes](https://fromfireside.com/tools/better-tropes).

## Who made this

Better Tropes comes from [Fireside](https://fromfireside.com), which turns the work a company already does — merged pull requests, customer calls, meeting transcripts — into posts written in that company's own voice. Every tell in this file is one we had to catch by hand before it reached a customer's feed.

It began as a superset of [tropes.fyi](https://tropes.fyi), which taught us to expect better.

## Contributing

**This repository is a mirror.** The catalogue is maintained upstream and synced here on every change, so a pull request merged into this repo would be overwritten by the next sync.

Open one anyway — it is the easiest way to propose a specific wording, and it gets read. An accepted suggestion is applied upstream, ships back here on the next sync, and your PR is closed with a link to the commit that carried it. The change lands; it just enters through a different door, and you are credited here.

Issues are just as welcome, and are the better format for "this tell is missing" or "this rewrite is worse than the original" — neither needs a diff.

The bar for a new entry: it has to be a tell a careful human writer would not produce, and the rewrite has to be something a careful human writer *would*. Entries that swap one fashionable word for another do not earn their place.

## Licence

[CC BY 4.0](LICENSE) — copy it, paste it into a system prompt, ship it inside a product, sell what you make with it. Keep the attribution.
