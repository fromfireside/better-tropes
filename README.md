# Better Tropes

**A catalogue of AI writing tells, with a plain rewrite for each.** Free to copy, paste into a system prompt, or fork.

Most "make it sound less like AI" files are full of editorial commentary — explanations of *why* a phrase is bad, arguments with the reader, meta-instructions about tone. That commentary competes with the rest of your prompt and degrades performance on the actual task. This one strips it out. Every entry names a tell, explains it in a sentence, and shows the two lines side by side.

## Use it

Drop [`better-tropes.md`](better-tropes.md) into your system prompt as-is:

```bash
curl -O https://raw.githubusercontent.com/fromfireside/better-tropes/main/better-tropes.md
```

It works unmodified, but it works better tuned to your workflow — a technical blog post is not a social post is not a listicle.

## A sample entry

> ### Elevated Filler Verbs
>
> Verbs that sound important but carry no more meaning than a plain one: `delve`, `leverage`, `utilize`, `harness`, `foster`, `streamline`, `unlock`, `embark`, `spearhead`, `navigate`. Prefer the shortest verb that is true.
>
> - **✗** We leverage data to unlock growth and streamline collaboration.
> - **✓** We use data to grow and to help teams work together.

**[→ Read the full catalogue](better-tropes.md)** — 50 entries across word choice, sentence shape, structure, and formatting.

A rendered, searchable version lives at [fromfireside.com/tools/better-tropes](https://fromfireside.com/tools/better-tropes).

## Credit

Better Tropes began as a superset of [tropes.fyi](https://tropes.fyi), which taught us to expect better, and grew from operating [Fireside](https://fromfireside.com) — where every one of these tells had to be caught by hand before it reached a customer's feed.

## Contributing

**This repository is a mirror.** The catalogue is maintained upstream and synced here on every change, so a pull request merged into this repo would be overwritten by the next sync.

Open one anyway — it is the easiest way to propose a specific wording, and it gets read. An accepted suggestion is applied upstream, ships back here on the next sync, and your PR is closed with a link to the commit that carried it. The change lands; it just enters through a different door, and you are credited here.

Issues are just as welcome, and are the better format for "this tell is missing" or "this rewrite is worse than the original" — neither needs a diff.

The bar for a new entry: it has to be a tell a careful human writer would not produce, and the rewrite has to be something a careful human writer *would*. Entries that swap one fashionable word for another do not earn their place.

## Licence

[CC BY 4.0](LICENSE) — copy it, paste it into a system prompt, ship it inside a product, sell what you make with it. Keep the attribution.
