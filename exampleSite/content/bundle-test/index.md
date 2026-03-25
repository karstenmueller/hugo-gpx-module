---
title: "Page Bundle Test"
date: 2026-03-25
---

This page tests the new Page Bundle resolution. `track.gpx` is located in the same directory as this `index.md` file, not in `/static`.

{{< gpx-map file="track.gpx" height="400px" >}}

## Global Asset Test

This tests global assets. `gpx/global.gpx` is located in `assets/gpx/`, not in `/static`.

{{< gpx-map file="gpx/global.gpx" height="400px" >}}
