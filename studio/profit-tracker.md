# Profit Tracker

Configuration Studio page **Profit Tracker**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Whether income is recorded, and which gem pouch belongs to whom.

Scripts that read these settings: [Profit Tracker](/scripts/profit-tracker.md).

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Enable Profit Tracker** | Automatically run the protected background collector and record financial activity in the shared profile ledger. Yes or No. | Yes | Each character |
| **Runtime Heartbeat Seconds** | How often active activity runtimes are durably checkpointed so a disconnect loses at most this much timing data. A number, at least 10, at most 300. | 60 | Each character |
| **Gem pouch owners** | Who owns each pouch color. When Jang sells a pouch, the money counts toward the owner of that color. Ground is the pouch a character fills while hunting, box is the one filled from picked boxes. Add a row for a new character or color. A color with no row is recorded under Jang as unassigned. A list. | {"color" =&gt; "black", "owner" =&gt; "Brachius", "pouch" =&gt; "ground"}, {"color" =&gt; "burlap", "owner" =&gt; "Brachius", "pouch" =&gt; "box"}, {"color" =&gt; "blue", "owner" =&gt; "Alaint", "pouch" =&gt; "ground"}, {"color" =&gt; "canvas", "owner" =&gt; "Alaint", "pouch" =&gt; "box"}, {"color" =&gt; "fuzzy", "owner" =&gt; "Tirax", "pouch" =&gt; "ground"}, {"color" =&gt; "dotted", "owner" =&gt; "Tirax", "pouch" =&gt; "box"}, {"color" =&gt; "green", "owner" =&gt; "Jang", "pouch" =&gt; "ground"}, {"color" =&gt; "oxhide", "owner" =&gt; "Jang", "pouch" =&gt; "box"}, {"color" =&gt; "indigo", "owner" =&gt; "Dehaka", "pouch" =&gt; "ground"}, {"color" =&gt; "paisley", "owner" =&gt; "Dehaka", "pouch" =&gt; "box"}, {"color" =&gt; "purple", "owner" =&gt; "Braxa", "pouch" =&gt; "ground"}, {"color" =&gt; "patchwork", "owner" =&gt; "Braxa", "pouch" =&gt; "box"} | Global, or each character |

