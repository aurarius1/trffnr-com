---
date: "2025-11-02T12:00:00+01:00"
draft: true
title: "Project Update"
tags:
  - projects
  - software development
  - 3d printing
---

Wow, I’ve fallen behind on updating this blog. In the last year (and a month… sorry), a lot has happened. I’m still working on my master’s thesis and haven’t finished InventoryHero yet — more on that [here](#inventoryhero) — but in the meantime, I’ve taken on a few more projects, which I will quickly outline in the next paragraphs.

# 3D printing & Projects

I already presented a setup of my 3D printer when I bought the P1S. Since then I have made a few upgrades to my BentoBox (and therefore printer) that I would like to share in a detailed post.

Additionally, after watching [this YouTube video](https://www.youtube.com/watch?v=yqm4YfjJzO00) I wanted to restructure the way I organize my 3D printer and my room around these IKEA Metod cabinets (they look really nice, don’t they?). I will probably also share this once it's done, but only if it turns out good enough to annoy other people with it.

Currently, my setup is just a Kallax shelf. It works fine, but due to space constraints, the shelf is rather high, which makes maintenance and printer access a bit tricky.

# Development Projects

## Android App (Teaser)

I am currently thinking of implementing an Android app — my first one! I believe this app could be really beneficial for a lot of people. At the moment, I don’t want to share too much information, as it’s still in the early stages, but I can tease that it may involve 3D printing and some NFC tags. Don’t worry — this app will also be open source. So… do with that information what you will.

## Card Game ('Emma treiben')

Another project I want to finally tackle is the Austrian card game Emma Treiben (also known as 'Black Lady' in the UK, or 'Die schleichende Johanna' in other German-speaking regions). My friends and I really enjoy this game, and I promised long ago to implement an online version.

I plan to make both the game server and frontend open source — just like InventoryHero and the aforementioned Android app. Initially, the frontend will be written in Vue, but I’m planning a Flutter app for Android and iOS later. For the backend, I’ll use ASP.NET, which I’ve grown to enjoy through my work. If InventoryHero didn’t already exist, it probably would have been written in C# as well by now.

# InventoryHero

First and foremost, I really like how this app is progressing. I’ve learned a lot during development—mostly thanks to the phenomenal open-source projects I could draw inspiration from. I’m thinking about releasing a v0.0.1 by the end of the year, though I can’t promise anything since my development time is mostly limited to commuting on the train.

## Features in Progress

- **SMTP & Authentication:** Self-registration and password reset emails are being implemented.

- **Translation (ugh):** Still a work in progress (and likely always will be).

- **Docker Deployment:** I recently added a Dockerfile, which simplifies deployment, and now the frontend is served by FastAPI.

All of this development is happening on the “api-rewrite” branch. Admittedly, this is not the right branch for all of that, but hey, still my first project, still alone on it (or rather again alone). Migrating from Flask to FastAPI was definitely the right choice — it just feels smoother overall, even if I’m not a Python expert yet.

## Documentation

I’ve started the documentation using Vitepress and deployed it via Cloudflare Pages. This documentation has been extracted into a separate repository, which will be made public once there is real content to actually access.

## Inspiration & Licensing

Last but not least I want to mention that a lot of inspiration and guidance was drawn from the [Mealie project](https://github.com/mealie-recipes/mealie). Their code base is really well structured and is a standard I'd like to reach one day. Because of all this, I've decided to use the same license - AGPL-3.0.

# Conclusion

Probably the next update you'll read here will be about the organization using the IKEA Metod for my 3D printer. I will probably not be able to share pictures of the finalized setup yet (man ... those Voxtorp doors are expensive), we'll see.

More tinkering and debugging ahead — stay tuned!
