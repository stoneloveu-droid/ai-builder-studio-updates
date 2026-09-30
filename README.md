# AI Builder Studio updates

Current release: **3.0.0-beta.7**, SketchUp desktop 2021+.

Two toolbar buttons: Dựng JSON and AI 3D (not integrated yet).

Beta 7 offers two output modes: Đúng khổ ván / Tự do. Materials and colors are always retained. One shared prompt guides silhouette preservation, geometry selection, empty spaces and assembly clearances. Solid geometry errors are grouped by item ID; radius failures explain the limit. Stock mode blocks overlapping unrotated panels; free mode displays an explicit warning and allows intentional intersections. Solid/rotated collisions are not fully verified.

Legacy parts/position JSON is converted to schema 3, retaining individual parts and relative positions. The supplied 92-part baluster example and shelf/slat collision have regression coverage. Legacy wood solids require free mode. No automatic redesign or silent trimming of geometry.

Updater retains Beta 6 GitHub API fallback for connection errors. Both routes require HTTPS and package size/SHA-256 validation.

Use Cập nhật → Kiểm tra bản mới → Cập nhật, save work and restart SketchUp. If the old installation cannot connect, install the RBZ with Extension Manager once. Settings and saved samples remain in their separate data folder.

Stable feed: https://raw.githubusercontent.com/stoneloveu-droid/ai-builder-studio-updates/main/latest.json

23 JavaScript tests pass; Ruby WASM geometry parity and mocked UI/updater checks pass. Direct SketchUp Windows acceptance testing is still required.
