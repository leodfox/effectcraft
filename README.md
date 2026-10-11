# Ardoise Motion (effectcraft fork)

Web motion-graphics and visual-effects editor of the Ardoise suite, based on EffectCraft by the ArtCraft Team
(MIT OR Apache-2.0). Branch `ardoise` starts from upstream tag v0.8.0 (https://github.com/storytold/effectcraft).

Changes in this fork: postMessage bridge for iframe embedding (apps/effectcraft-web/src/ardoise_bridge.rs),
Ardoise branding in the UI (the upstream name, wordmark and logos are not used; community links removed),
single web-only CI workflow (.github/workflows/web.yml).

Build the web bundle: `cargo xtask web` (needs the wasm32-unknown-unknown target and the wasm-bindgen CLI at the
version pinned in xtask/src/main.rs), or `packaging/web/package.sh` to also zip it.

Licences: see LICENSE-APACHE, LICENSE-MIT and NOTICE. The copyright notices of the original authors are kept.
