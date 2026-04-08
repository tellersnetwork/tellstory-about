---
title: "Content and Automation Update - 2026-04-08"
date: 2026-04-08
author: "TellStory Team"
---

**Summary**

This week focused on multimedia content enrichment and platform config hardening. tellstory received automated additions of illustration prompts and SSML for multiple stories (The Birth of Athena, The Girl with the Rose‑Red Slippers, Noah's Ark) and a targeted cleanup of lumberjack stories. tellstory.net updated Hugo data API configuration and fixed a JSON path expression; submodule syncs noted. tellstory-about added a contact section to about.md.

**Changes**

- Multimedia expansion: batch addition of illustration prompts + SSML scripts across several legacy and new stories — signals an illustration+audio rollout.
- Content cleanups: lumberjack stories were consolidated/cleaned, improving consistency and metadata quality.
- Automation: automation-bot drove most content enrichments (3 of 4 commits) — pipeline is active and scaling.
- Platform/config: hugo.toml data API configs added (dev/prod), plus a JSON path fix — reduces data-render risk.
- Repo ops: submodule updates observed in tellstory.net; verify that content submodule pointers and generated assets (images/SSML) are present and tested to avoid broken pages or missing media.

