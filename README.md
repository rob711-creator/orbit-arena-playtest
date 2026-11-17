# Orbit Arena playtest

Public browser playtest of Orbit Arena. The `dist` folder is the Poki playtest package with the audiovisual upgrade applied (gameplay rules and tuning unchanged).

The hosting workflow publishes only `dist`; it does not rebuild or alter the game.

Entrypoint SHA-256: `76ad353e09c0f19ee0046bb05fb2e17b7fdd6637f1f445a106f26cf56050f691`.

The current build keeps movement and firing available throughout the safe lesson, accepts quick fire taps, and uses a balanced default speed of 175%. Saved custom settings remain available.

Font licenses are included in `dist/licenses`.

## Audiovisual upgrade

- Deep-space environment (nebula, star field, ringed planet), engine trails, layered explosions with debris and shockwaves, projectile glow, bloom and a beat-reactive arena.
- New procedural score (120 BPM, 32 bars, layers that build with combat intensity) and rebuilt sound effects with reverb, stereo delay and positional panning. Still no audio files.
- Ship art converted from PNG to WebP: about 13 MB down to 0.5 MB.
- Effects scale down automatically on slow devices. Append `?q=0`, `?q=1` or `?q=2` to the URL to lock a quality tier.
