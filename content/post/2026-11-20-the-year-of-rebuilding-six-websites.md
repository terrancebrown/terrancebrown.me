---
title: "The Year of Rebuilding Six Websites"
date: 2026-11-20T12:00:00+02:00
draft: false
description: "After a long stretch of silence, a year spent pulling six neglected websites back from the brink."
summary: "After a long stretch of silence, a year spent pulling six neglected websites back from the brink."
tags: [meta, websites, rebuilding]
---

For most of this year, my websites were embassies with no ambassador. The lights were on — Cloudflare kept serving whatever was last deployed — but nothing inside moved. No posts, no updates, no maintenance. A blog that hasn't posted in a year starts to feel less like a blog and more like a museum exhibit of a person who used to write things.

This is the post where I take stock of the year I spent fixing that.

## Six is a lot

Six sites sounds absurd when I write it down. Nobody needs six personal websites. But each one earned its keep by being *about* something specific, and that turned out to be the thing that made rebuilding them possible. A site with a narrow purpose is easy to maintain; a site that could be about anything is infinitely procrastinatable.

The rundown: a personal hub that is mostly lists of what I am currently playing, watching and drinking. A site for stationery and games, where I say what I honestly think about pens and Controllers. A tech notebook, which is really a series of letters to my future self about configs I will forget by March. A long-form essays site. A private match tracker for a Friday night FIFA group. And this one — the meanderer, the catch-all for anything that doesn't fit the other five.

The rule that finally made the constellation manageable was routing: every idea gets exactly one home, decided by what the piece *does*, not by wherever my whims land that evening. Tech fix? Straight to the notebook, no prose flourishes. Review of a pen? Stationery site. Something that happened to me and won't leave me alone? Here. If it fits two places, I make myself choose before writing a word. Before the rule, half-finished drafts wandered between repos like ghosts looking for a house. Now they know where they live.

## What broke, and why

The silence wasn't just neglect. Some of it was structural, which is the more forgivable kind.

The Hugo sites use git submodules for their themes, which means a fresh checkout of any of them comes up hollow until you remember to pull the theme in too. Fine once you know. But somewhere along the way I had also overridden bits of the themes locally — copied a layout or two into my own repo to tweak something — and forgotten. Those copies sat there quietly freezing against every theme update, like a handbrake left on. When a rebuild produced odd output months later, the cause and the symptom were separated by half a year. The lesson I wrote down for future me: overrides are loans against future maintenance, and the interest compounds silently.

One site came back from the dead with no body at all. The old essays site traced back to a Blogger blog whose content is long gone — so it relaunches as a blank page, which is oddly liberating. Nothing to migrate, nothing to preserve, no guilt about broken links. The first post sets the tone, and that is a nicer problem than an archive.

The newest member of the family isn't even a website in the classical sense: a little worker-and-database app that tracks 2v2 FIFA matches between friends, gated so that only the six of us who care about the results can see them. It exists purely because keeping score in a group chat produced arguments. Infrastructure in service of friendship banter is, I think, a legitimate use of computing.

## Why hand-built, still

The obvious question is why not put everything on one platform and never think about it again. Honest answer: I did think about it, more than once, usually at 23:00 with a broken build in front of me.

But the maintenance, unpleasant as it sometimes is, is part of the point. Owning the pipeline — plain files, git, a push that deploys — means the sites are mine in a way that a profile on someone else's platform can never quite be. Nobody can redesign my homepage out from under me. Nobody can turn off my archive or change my fonts. The price is that when Hugo releases an update, I am the entire IT department, and sometimes the IT department does not show up for eleven months.

There is also a quieter reason. Small, hand-maintained things are legible. I can hold all six sites in my head. On a good day I can even explain how they work. That is not true of most of the software in my life, and there is something worth preserving about the small systems you fully understand.

## Starting again

So this is where the year lands: themes updated, pipelines fixed, ghosts routed to the right houses, and this site — the oldest, driftest of them — finally getting a post.

I am deliberately not promising a schedule. Promises of cadence are how blogs die: the author vows weekly posts, misses a week, and lets the guilt metastasise into three years of silence. Better to say only this: the machinery works now, the drafts have destinations, and when something earns a post, it has somewhere to go.

That is more than the embassy could say a year ago.
