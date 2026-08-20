# FeedNoodle

FeedNoodle is a spatial multi-feed browser for orchestrating many simultaneous information streams—especially AI conversations, web/RSS feeds, media, search results, workspace events and agent outputs—inside fluid, transformable spatial layouts.

## Product thesis

The feed is not a vertical list. The same normalized stream can be projected into multiple spatial forms without changing its underlying content model.

Initial canonical layouts:
- **Columns** — conventional parallel multi-feed baseline
- **Revolver / Wheel** — rotating multi-face feed object
- **Noodle** — long flowing content ribbons with parallel streams
- **Ring / Spiral / Cylinder** — dense continuous browsing modes
- **Sphere / Focus** — compact single-focus state
- **Unfold / Inside** — panels unfold into a room-scale or VR shell

## Core architecture

`source adapters -> normalized item model -> orchestration/ranking -> spatial layout engine -> interaction shell`

The browser shell should remain visually light and transparent; content and spatial relationships are the primary interface.

## First vertical slice

1. 4–8 simultaneous feeds.
2. One canonical normalized item schema.
3. Columns, Revolver and Noodle views.
4. Continuous morphing between views.
5. Search/filter/pin/focus.
6. Local persisted workspace state.
7. Placeholder adapters for AI chat, RSS and generic JSON streams.

Later phases may add RAG, agent orchestration, collaborative spaces, voice and VR.

## Provenance

This repository continues the FeedNoodle concept previously explored in legacy Aintropie/ISLAND/Drive material. Legacy repositories remain evidence/reference sources; this repository is the canonical active implementation.
