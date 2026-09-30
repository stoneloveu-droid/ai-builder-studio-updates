# AI Builder Studio updates

Current release: **3.0.0-beta.5** (SketchUp desktop 2021+).

Two toolbar commands: **Dựng JSON** and **AI 3D**. AI 3D is a placeholder, not an integrated generation service yet.

The JSON workspace uses one shared prompt. Output controls in preview: wood only, color, and board stock. Changes rebuild the preview; invalid plans cannot be placed. Original JSON and output settings are retained when saving samples.

Update from the plugin: Cập nhật → Kiểm tra bản mới → Cập nhật. Save work and restart SketchUp after installation.

Stable feed: https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/main/latest.json

Packages are stored in this repository and manifests pin the exact package commit with byte count and SHA-256. No automatic installation. This is a beta: geometry, Ruby/JS parity and mocked UI/updater checks pass; direct SketchUp Windows acceptance testing is still needed.
