---
title: "Dungeon Days: Making games"
date: 2026-07-22
tags:
  - Video-Games
  - Games
  - Arcade
slug: dungeon-days
description: A CRT-flavored roguelike I built solo, and the long road from motion designer to someone who can actually ship a game.
draft: false
---
### From screens I animated to screens I built

I've always been a visuals person.

Cut my teeth as a motion designer for WWE. Made 9-year-old me proud by landing at Nickelodeon, animating cartoons I grew up watching. Every project, no matter how different, came down to the same thing: what's happening on the screen.

Staying creative full-time takes fuel. Pinterest, Instagram, my favorite cartoons — they all helped. But video games hit different. Games weren't just inspiration. They were something to aspire to.

I always wanted to make one.

---

## The gap between wanting and doing

For years I put all my focus into learning the tools that made images and video. Code felt like a different language entirely — one I didn't know how to start speaking.

That changed a few years into Nickelodeon, buried in expressions with After Effects, scrolling Stack Overflow for answers. Somewhere in there, I made the leap into coding. Once that happened, "making a game" stopped feeling impossible.

Then came the AI boom.

Suddenly my computer — or some computer on the other end of a browser tab — could code too. I already knew the basics: what to look for, what I'd need to pull it off. The machine filled in the blanks.

The early days were a weird dance: prompt, copy, paste, google how to fix it, repeat. It wasn't that long ago. Feels like it's always been this way.

Somewhere in that loop, something shifted. I stopped being a motion designer who dabbled in code and became a creative technologist — where the art and the code aren't two separate skills anymore, they're one practice.

I started making my own games.

---

## They're not good. That's fine.

Each one has been rough. Each one has also been a little more advanced than the last.

Making the game _is_ the game, in a way. Every project teaches me something that gets me one step closer to maybe, someday, building the game I always wanted to play.

Right now I'm not trying to ship something polished. I'm making small arcade games for fun and sharing them as I go. Learn → build → post → document → share — same loop, new medium.

The latest one is **Dungeon Days**.

---

## What is Dungeon Days

> _They say the knight who clears the Lower Halls will have his name carved into the gates of the capital. But no one dares ask what happened to the last knight who believed that._

Dungeon Days is a retro CRT roguelike that runs entirely in the browser — no install, no build step, just open it and play. Clear each chamber, find the stairs, descend, repeat. Every day is a freshly generated dungeon. The only question is how many you can survive.

**How it plays:**

- WASD / arrow keys to move
- Space to shoot in the direction you're facing
- Clear every enemy in a chamber to reveal the stairs down
- `P` toggles the CRT shader, `M` toggles the minimap

**What's under the hood:**

- ✅ Procedurally generated dungeons — BSP room generation, so no two days look the same
- ✅ A power system — spend tokens dropped by enemies on upgrades between days: extra projectiles, piercing rounds, shields, lifesteal, a one-time revive, and more
- ✅ A curse ladder — the dungeon gets meaner over time. Every 5th day drops a temporary curse. Every 10th, the last curse becomes permanent and stacks on top of the others
- ✅ Shrines every 3rd day, where you pick a blessing or empower a power you already have
- ✅ Relics that unlock new powers into the pool
- ✅ A full WebGL CRT shader — chromatic aberration, bloom, scanlines, dithering — with a raw-canvas fallback, plus a tiny handmade 8-bit WebAudio sound synth

It's vanilla JavaScript. No framework, no bundler. One self-contained `index.html` file doing all the heavy lifting — canvas rendering, shader, game logic, the works.

---

## Why it matters more than the game itself

Old me would've looked at a scoreboard of zero forks and zero stars and called it a failure.

New me knows better. This isn't about numbers. It's R&D. It's proof that the gap between "I want to make games" and "I make games" isn't as wide as it used to feel.

I don't want to just publish a game. I want a sustainable creative pipeline where art, code, and play keep feeding each other — and Dungeon Days is one more rep in that direction.

---

## Try it

Dungeon Days is live now — drop into the dungeon and see how many days you last.

<iframe src="https://dungeondays.freshcake.wtf/" width="100%" height="600" style="border:2px solid #000;" allow="autoplay; fullscreen" loading="lazy"></iframe>

**[Play Dungeon Days →](https://dungeondays.freshcake.wtf/)**

Code's all up on [GitHub](https://github.com/freshcakewtf/DungeonDays) if you want to poke around under the hood.

If you enjoy it, there's a Ko-fi tip jar linked in the repo. Every bit helps keep the tiny experiments going.

Want more? This isn't the only tiny game I've thrown together — swing by the **[Fresh Cake Arcade](https://www.freshcake.wtf/src/arcade.html)** for the rest of them.

More dungeons, more tiny games, more learning in public. That's the plan for what's next.











