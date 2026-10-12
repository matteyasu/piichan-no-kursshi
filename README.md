# ぴーちゃんのきまぐれ暮らし

Buildless, mobile-friendly Japanese browser pet game. The user's reference photo appears in the profile and album. An original inline SVG character preserves charcoal fur, yellow-green eyes and a pink bow, with animated expressions and paws.

Features: petting by touch or pointer strokes, probabilistic paw trick, feeding, snacks, cleaning, naps, a 20-second feather minigame, daily missions in JST, coins, six room items, eight memories, level and bond, localStorage save, JSON import/export, opt-in Web Audio.

Data uses `piichan-life-v2` in browser localStorage; the earlier standalone prototype is not migrated. No server data or cross-device synchronization. Offline decay is capped at 12 hours and stats do not fall below 15. The cat does not die. Sleeping automatically ends after 90 seconds or on the next visit.

Verification: `node --test tests/*.test.cjs` and JS syntax checks. UI integration uses a simulated DOM; actual browser visual QA was unavailable in this environment.

Hosting output: `dist/`. Site identity: `.openai/hosting.json`.
