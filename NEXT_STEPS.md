# Next Steps

## Completed
- New git repo created
- Git author confirmed as Koutian Wu <ktwu01@gmail.com>
- Research dossier created
- Milestone table v1 and v2 created
- Initial timeline / storymap JSON scaffold created
- First landing page prototype created
- SOTA design review added at `research/sota-design-review.md`
- Editorial content schema added:
  - `data/chapters.json`
  - `data/locations.json`
  - `data/validation.json`
  - `data/sources.json`
  - `data/artifacts.json`
- Landing page rebuilt into an editorial chronicle with:
  - premium hero + thesis framing
  - phase rail / quick navigation
  - narrative timeline chapters
  - synced MapLibre geography module
  - curated validation groups
  - denser reference timeline sourced from `data/timeline.json`
  - source archive
  - source-backed editorial artifact cards for the strongest chapters
  - archive timeline sourcing labels + source-origin filters
  - lightweight artifact/media taxonomy via `data/artifact-taxonomy.json`
  - chapter-specific map captions, camera presets, and active route emphasis
  - present-direction / why-now module via `data/present-direction.json`
  - chapter-to-archive crosslinks with supporting milestone clusters and archive return links

## Next implementation steps
1. Strengthen the source archive further by capturing more direct primary URLs for early academic/founding details.
2. Deepen the artifact system with real media slots for conference visuals, article snippets, and future scans only where source quality is strong enough.
3. Add chapter thumbnails or stronger visual cues to the geography nav so skimming feels more editorial than utility-only.
4. Add chapter-aware archive filtering so clicking a supporting cluster can temporarily scope the reference timeline to that chapter’s evidence set.
5. Consider migrating the static prototype into Astro once the content model stabilizes.
