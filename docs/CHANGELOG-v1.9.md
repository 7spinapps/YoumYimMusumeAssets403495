# Changelog

## V1.9 — October 19, 2026

### Racers and Scout

- Added YoumYim Assassin, Cleric, Joker, Swordmaster and Lightning Mage, with stable randomized base stats, the requested strategy grades and capitalized Pro/Con labels, textured rigs, portraits, procedural motion modes and English Linda name callouts.
- Added YoumYim Racer Vol.3: Assassin, Cleric, Joker, Swordmaster, Lightning Mage, Shielder and Heroine. Costs 300 Capy Coins per draw or 3,000 per ten. Featured rate remains 5% total; exchange remains 200 points.
- Applied banner03 artwork. Preserved original image ratios, enlarged the active card and added faded neighboring cards inside one shared scroll view.
- Fixed drag/snap ownership, first/last wrap-around, interrupted snaps and rapid-swipe navigation. Kept the swipe hint centered above the centered navigation row without obscuring the SSR rate box.
- Moved banner configuration into a shared catalog and deployed backward-compatible variable-length account exchange balances for future banners.

### Race presentation and sound

- Added Thai commentary by YoumYim Announcer using the Linda voice, English racer-name audio, varied event wording and winner praise, and blue-speaker/white-text captions on a dim background.
- Added independent saved BGM, SFX and Announcer toggles through SOUND SETTING. Announcements do not duck BGM; English name clips use faster pitch-preserving playback and narrator gain remains 2x.
- Added gate-start SFX with its silent lead trimmed. Finals intense music now starts from 0:30 when the phase changes.
- Added player-racer camera cycling in Champion's Meeting, horizontal Finals rewards with the earned prize highlighted, and lobby music retained after Finals.

### Creator and release packaging

- Racer Creator generates English name callouts automatically and validates them before rebuilding the Windows game and character content. Local synthesis tools/model weights are not shipped to players.
- Built Windows and WebGL with external character, BGM and SFX bundles enabled. Each new racer uses an individual bundle below 100 MiB.
- Bundle caches now use the game build version, avoiding reuse of an older release's downloaded audio/characters.
- Announcer audio/captions remain embedded, as previously agreed. Windows builds are not archived automatically.
- In-game changelog retains V1.8 and older history below this release.

External files must be committed/uploaded before players use these external-enabled builds. Builds do not publish or push the external repository automatically.
