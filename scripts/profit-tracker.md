# Profit Tracker

Script name: `profit-tracker`

Shows what hunting, crafting and burgling have earned.

```
.profit-tracker day
.profit-tracker week
.profit-tracker lifetime
.profit-tracker week rock trolls
```

The last words can name a creature or a hunting zone. The recording runs in the background while **Enable Profit Tracker** is on (Profit Tracker page).

## How to start it

Type `.profit-tracker` with the words shown above.

In Master Train, pick **Profit Tracker** as the activity and put the same words in its Arguments box.

## Settings

On the Configuration Studio page [Profit Tracker](/studio/profit-tracker.md):

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| <span id="setting-profit-tracker-enabled"></span>**Enable Profit Tracker** | Automatically run the protected background collector and record financial activity in the shared profile ledger. Yes or No. | Yes | Each character |
| <span id="setting-profit-tracker-runtime-heartbeat-seconds"></span>**Runtime Heartbeat Seconds** | How often active activity runtimes are durably checkpointed so a disconnect loses at most this much timing data. A number, at least 10, at most 300. | 60 | Each character |
| <span id="setting-profit-tracker-pouch-owners"></span>**Gem pouch owners** | Who owns each pouch color. When Jang sells a pouch, the money counts toward the owner of that color. Ground is the pouch a character fills while hunting, box is the one filled from picked boxes. Add a row for a new character or color. A color with no row is recorded under Jang as unassigned. A list. | {"color" =&gt; "black", "owner" =&gt; "Brachius", "pouch" =&gt; "ground"}, {"color" =&gt; "burlap", "owner" =&gt; "Brachius", "pouch" =&gt; "box"}, {"color" =&gt; "blue", "owner" =&gt; "Alaint", "pouch" =&gt; "ground"}, {"color" =&gt; "canvas", "owner" =&gt; "Alaint", "pouch" =&gt; "box"}, {"color" =&gt; "fuzzy", "owner" =&gt; "Tirax", "pouch" =&gt; "ground"}, {"color" =&gt; "dotted", "owner" =&gt; "Tirax", "pouch" =&gt; "box"}, {"color" =&gt; "green", "owner" =&gt; "Jang", "pouch" =&gt; "ground"}, {"color" =&gt; "oxhide", "owner" =&gt; "Jang", "pouch" =&gt; "box"}, {"color" =&gt; "indigo", "owner" =&gt; "Dehaka", "pouch" =&gt; "ground"}, {"color" =&gt; "paisley", "owner" =&gt; "Dehaka", "pouch" =&gt; "box"}, {"color" =&gt; "purple", "owner" =&gt; "Braxa", "pouch" =&gt; "ground"}, {"color" =&gt; "patchwork", "owner" =&gt; "Braxa", "pouch" =&gt; "box"} | Global, or each character |

