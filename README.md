# PROJECT: BEYOND THE LEGACY

A Korean-language, responsive educational Mars exploration game. Open `index.html` in a modern browser; no build step or external JavaScript library is required.

## What is implemented

- A five-sol mission with choices that carry forward into later story beats and several endings.
- Simplified, explicitly game-only power, solar, life-support, oxygen, thermal, communications, water, science, data, and crew-trust systems. Sol-by-sol upkeep and cascading low-power effects make early decisions matter later.
- Fact-checked learning cards for InSight SEIS and HP³, Perseverance MOXIE and MEDA, and a clear research-stage classification for electrostatic dust removal. HP³'s deployment difficulty and MOXIE's status as a technology demonstration are not presented as mission successes beyond their actual records.
- NASA Images API image lookup for equipment, with a graceful text fallback and official source links when network access is unavailable.
- A glossary, three-question knowledge quiz, relationship feedback, and a final mission report.
- Mobile-responsive layout, keyboard focus styling, reduced-motion support, and a CSS Mars illustration that works without WebGL.

## Scientific and simulation notes

Game resource values, base operations, effects, and story events are educational abstractions, not actual NASA mission telemetry or engineering guidance. Each equipment entry links to NASA mission material; research-stage and hypothetical game systems are labeled separately. Images load from NASA's public Images API and therefore require an internet connection; the game itself remains playable when image loading fails.

## Smoke test checklist

1. Open `index.html` with network access disabled: the game should start, choices should work, and images should show their fallback.
2. Start a fresh mission and play through all five sols; check each choice for resource changes and confirm an ending is shown.
3. Replay with a different choice path and verify the narrative/log and ending can differ.
4. Check equipment cards and source links for SEIS, HP³, MOXIE, MEDA, and research-stage EDS.
5. Complete the glossary and all quiz questions; verify score and retry.
6. Use a narrow viewport and keyboard navigation; confirm controls remain usable and visible focus is present.

This is an educational community project, not an official NASA product.
