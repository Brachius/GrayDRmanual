# Memory diagnostics

Configuration Studio page **Memory diagnostics**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Memory measurements written to the log folder. Leave the first two on; turn the heavy trace on only for a measurement session.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Memory heap watch** | Write a per-minute memory ledger to the log directory: process totals, per-heap live vs committed bytes, window scrollback sizes, and queue depths. Costs one file line per minute; separates a real leak from allocator retention without a special measurement day. Yes or No. | Yes | Global |
| **Engine memory snapshots** | Append the .memory engine report (per-script Lua heaps, journal, game-data cache) to the memory ledger automatically each minute - no typing .memory in every window. Yes or No. | Yes | Global |
| **Deep allocation tracing (heavy)** | Record a call stack for every allocation in the process so a confirmed leak can be attributed to the exact code. WARNING: costs real CPU (~3x) - turn on only for a measurement session, then turn it off. Takes effect at the next GrayDR start; while on, the memory ledger includes the top unfreed call sites and scripts automatically get triple the engine time allowance so measurement overhead does not trip the runaway-script guard. Yes or No. | No | Global |

