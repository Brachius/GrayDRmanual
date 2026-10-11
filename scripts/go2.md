# go2

Script name: `go2`

Walks you to a room. Type a room number, a map tag, or words from the room name:

- `go2 10028` walks to that room number (the numbers GrayDR shows, never Lich map numbers).
- `go2 bank` walks to the nearest room tagged bank. A plural like `thieves` is tried as `thief` too.
- `go2 town green` searches the room names. One match walks at once; several matches are listed nearest first and you type the number of the one you want. It says what it matched every time, so a wrong pick leaves a trace.

It works without the dot because it is listed under Bare commands on the Commands page. While walking, a way that is closed to this character (a gate that refuses, a crossing that is not there) is marked and another route is tried; it stops when no other route exists. `.k` stops a walk.

## How to start it

Type `.go2` in the game window.

## Settings

This script has no settings of its own. Shared pages such as [Character](/studio/character.md), [Magic](/studio/magic.md) and [Crafting](/studio/crafting.md) may still apply.
