# SkyDelta 3D Flight Combat — Rebuild

**Neeljhor Alo Studio · Early access prototype**

This is a gameplay rebuild, not the previous 2D Canvas prototype. It uses Three.js/WebGL for a 3D scene, a procedural low-poly stealth-fighter model, river-delta terrain, vegetation, cloud banks, cockpit/chase camera, touch flight controls, throttle, moving hostile aircraft, cannon fire, missiles, damage, and respawning targets.

The fictional player aircraft designation is **ProAsian Type-96: Air Superiory**. It is an original fictional design, not an authentic Su-57 model or a military training simulator.

## Honest status

This is a **playable 3D prototype**, not ultra-photorealistic production art. The aircraft and world are procedural 3D assets. There are no scanned/artist-authored high-detail models, physically accurate flight dynamics, realistic weapon simulations, or production-grade terrain textures yet. The visuals will vary with phone GPU capability. The project intentionally uses local procedural assets after installation; the game itself does not need to fetch 3D assets from a remote server.

## Controls

- Start Flight to begin.
- Left touch pad: roll/turn and pitch.
- Right touch pad: look around.
- Throttle slider: adjust speed.
- GUN: hold to fire.
- FOX-2: launch a homing missile at the nearest hostile.
- CAM: switch cockpit and chase views.
- Pause button: suspend the sortie.

Keyboard testing: arrow keys fly, hold Space to fire, M launches a missile, C switches camera, Escape pauses.

## Build an Android APK using GitHub Actions

1. Upload the contents of this folder to the root of a GitHub repository, preserving `.github/workflows/android-apk.yml`.
2. Commit to the `main` branch.
3. Open **Actions → Build SkyDelta 3D Android APK**.
4. When the run succeeds, download the `SkyDelta-3D-Early-Access-APK` artifact. Extract it to obtain `app-debug.apk`.
5. Test the APK on the target phone. A successful build is not a substitute for gameplay testing.

GitHub Actions uses Java 21 and Node.js 22. The first build may take several minutes.
