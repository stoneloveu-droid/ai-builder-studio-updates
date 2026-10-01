# AI Builder Studio

Current release: **3.0.0-beta.8** · SketchUp desktop 2021+.

- Door components use the Canh tag; raw geometry stays Untagged.
- Edge setback is per edge: 1 mm produces 2 mm between adjacent fronts in newly compiled plans.
- Dedicated toolbar resize command for a selected AI Builder root; undo supported. Independent nested-module resizing is not supported.
- Cabinet slat lining with backing, plus standalone slat assemblies. Interior shelves/dividers stop at the slat face. Stock limits remain enforced.
- ASCII English component codes.
- Background update checks on opening JSON, a once-per-version notification per dialog, and no feed URL in the UI. Installation still requires the Update button and a SketchUp restart.

Existing SketchUp plans retain their formulas. Rebuild from JSON to adopt new door-gap rules. Old loose slats are not automatically converted into assemblies. Copy the new prompt for slats/door roles.

Update inside the plugin or install the RBZ through Extension Manager, then restart SketchUp. Settings and saved samples are kept separately.

Feed: https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/main/latest.json

27 builder tests pass, with Ruby WASM parity and mocked tagging/UI/updater tests. Direct SketchUp Windows acceptance testing is still required.
