# AI Builder Studio updates

Current release: **3.0.0-beta.6**, SketchUp desktop 2021+.

Beta 6 fixes the updater's single network route: connection failures on raw.githubusercontent.com trigger a fallback to the same repository and file revision via GitHub's contents API. HTTPS certificate checks, package size, SHA-256 and archive checks remain required. Custom feeds are not rerouted. If both routes fail, installation stops with a clear message.

If an older installation cannot reach the feed, install the Beta 6 RBZ manually through Extension Manager once, then restart SketchUp. User settings and saved samples remain in their separate data folder.

Beta 5 features retained: two toolbar commands (Dựng JSON and AI 3D), one shared prompt, preview controls for wood only/color/board stock. AI 3D is not integrated yet.

Stable feed: https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/main/latest.json

Packages are pinned by commit and verified with SHA-256. Tests use Ruby WASM and mocked SketchUp installation; direct SketchUp Windows acceptance testing remains necessary.
