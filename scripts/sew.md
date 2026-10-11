# Tailoring

Script name: `sew`

Tailoring: sewing cloth and leather, knitting, and the armor enhancements (seal, reinforce, lighten). It buys thread, yarn and the other consumables when they run low, renews the private sewing room rental, trains crafting magic between steps when that is set on the Crafting page, and finishes the piece the way you asked.

```
.sew log sewing 2 "heavy gloves" wool gloves
.sew hold knitting 5 "socks" yarn socks
.sew stow leather 1 "leather helm" leather helm skip
.sew hold instructions silk hood
.sew seal gloves              (also: reinforce, lighten)
.sew resume gloves
```

The finish word comes first: `hold` keeps the piece in hand, `log` puts it in the work-order logbook, `stow` puts it away, `trash` throws it out. Then the kind (`sewing`, `leather` or `knitting`), the chapter, the recipe in quotes, the material, and the noun of the finished item. `skip` skips restocking. `instructions` works from instructions instead of a book (add `knit` for knitted pieces). `resume` carries on with a piece already started.

Pins and the other sewing tools come from your belt and crafting bag (Gear page). Pins are binned and rebought when they are down to four uses or fewer; pins that run out mid-piece are bought at the tool shop and the piece carries on.

## How to start it

Type `.sew` with the words shown above.

In Master Train, pick **Tailoring (Sew)** as the activity and put the same words in its Arguments box.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
