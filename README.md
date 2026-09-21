## Justus Reichel

Data science at Aalto University. Finnish-German, Swedish-speaking.

I build tools I use every day, which is a harder constraint than it sounds —
they have to still work on an ordinary Tuesday, not just demo well.

### What I'm working on

**Strata** — an Obsidian plugin that turns a knowledge graph into layers instead
of one hairball. Nine edge types grouped by *who asserted the edge*, so a link I
wrote and a similarity a model proposed are never drawn as the same thing. The
semantic half embeds passages rather than whole notes and runs on a local model,
so there are no API keys and nothing leaves the machine. ~9,000 lines of
TypeScript, running daily over my own vault.

**A training and health store** — six years of Garmin, Apple Watch and Withings
data in Postgres, behind a PWA I open every morning: sleep, recovery, training
load, per-session detail. The interesting part is provenance. Two watches
disagree, so every value carries the device that produced it, and the app will
show you which readings it threw out and why. A number without its origin
attached is worse than no number, because you will trust it. On top of that it
aggregates the six years into training load, form and per-sport trends, which is
what makes it useful for Ironman training rather than a nicer dashboard.

**ThreadWeaver** — newsletter intelligence. Ingests what I subscribe to,
synthesises it into persistent threads rather than a daily dump, and turns those
into active recall. FastAPI, Postgres, Redis workers, deployed.

**MCP servers** — semantic retrieval over my own vaults, and a reader for Aalto
coursework.
