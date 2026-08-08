---
title: "Getting started with GODOT"
categories: GODOT
tags:
  - manual
excerpt: "First notes on picking up GODOT — and a quick reminder of how this Explorations section works."
---

This is the first entry under the **GODOT** topic. Every post with `categories: GODOT` in its front matter gets grouped under the same "GODOT" heading on the [Explorations](/explorations/) page, newest first — this file is also a working example of how to add more.

## How to add a new post

1. Create a new file in `_posts/`, named `YYYY-MM-DD-a-short-slug.md` (the date can be anything — it controls sort order, not necessarily the real writing date).
2. Give it front matter like this one:

   ```yaml
   ---
   title: "Your post title"
   categories: GODOT
   ---
   ```

3. Write the body in normal Markdown below the `---`.

That's it — no other file needs to change. Jekyll picks up everything in `_posts/` automatically.

## Starting a new topic

Just change `categories:` to a new word, e.g. `categories: Rust`. The first post with that category creates a brand-new "Rust" heading on the Explorations page — no page or nav edit required.

## A few optional front matter fields

- `excerpt: "..."` — a short teaser shown on the Explorations page (used above).
- `tags: [tag1, tag2]` — separate from categories, shown on the post itself and grouped on `/tags/` (not currently linked in the nav, but the page exists).
- `date: 2026-08-08` — set explicitly instead of relying on the filename if you want a specific display date.

## Where it ends up

The URL is built automatically from the category and the filename's slug (the part after the date): this post is at `/godot/how-to-add-a-post/`. A post in a new "Rust" category would land under `/rust/...`.

Delete this post whenever you don't need it as a reference anymore — it's just a working example.