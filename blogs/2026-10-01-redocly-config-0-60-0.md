---
title: "@redocly/config 0.60.0"
url: "https://redocly.com/docs/realm/changelog#%40redocly%2Fconfig%400.60.0"
date: "2026-10-01"
feed_url: "https://redocly.com/docs/changelog/feed.xml"
---
New release: @redocly/config@0.60.0 · Date: 2026-10-01 · 1 feature · 0 fixes Features: • Removed the `baseline` option from the `recheck` block of the `redocly.yaml` schema, so `check-config` and the `redocly recheck` command accept the same keys. **Note**: `recheck.baseline` is no longer accepted. Recheck finds the baseline file by its presence: put `.redocly.recheck-baseline.yaml` next to `redocly.yaml`.
