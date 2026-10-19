# co.tasklinkr/corpus

**Registry name:** `co.tasklinkr/corpus`
**Version:** 1.0.0
**Category:** Knowledge
**Transport:** Streamable HTTP (remote)

## What it is

Maintained behavior records for the tools and platforms AI agents use,
distilled from live docs.

The corpus is the judgment layer on top of vendor documentation — not
re-published API references, but records of BEHAVIOR: auth flows, write-only
secrets, rate limits, webhook quirks, metering traps, and save-time gotchas.
Every record carries a pull date and is refreshed on use; a stale record is
treated as a falsehood.

Coverage runs in waves: the AI assistant's own connector surface first, then
the broader connector universe, prioritized by likely agent usage.

## Intended users

AI agents that need ground-truth behavior notes on the tools they call —
beyond what vendor docs say, into what actually bites.

## What is NOT public

Record contents, curation sources, coverage inventory, refresh mechanics,
and all backend implementation details remain private.
