---
layout: docs
title: Migrating to v6
description: Track and review changes to the Bootstrap source files, documentation, and components to help you migrate from v5 to v6.
group: migration
aliases: "/migration/"
toc: true
---

## Guided migration

### Helpers
- **Ratios:** Remove the parent wrapper element and apply the new `.ratio-*` utility directly to the element you want to modify. [More info.](#helpers-1)

## Changelog

### Helpers

- <span class="badge text-danger-emphasis bg-danger-subtle">Breaking</span> **Ratio helpers have been replaced by the [aspect ratio utility](/docs/5.3/utilities/aspect-ratio/).**
  - Custom ratios via CSS variable are no longer supported, but you can still use the `$aspect-ratios` Sass map to customize the available ratios.
  - The `.ratio-*` utilities no longer apply to a parent wrapper—instead, place them directly on the element you want to modify.
