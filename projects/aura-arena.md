# ⚡ Aura Arena

**[auraarena.app](https://auraarena.app)** · Web (PWA) + Android · 🔒 Private beta, private code

> The competitive aura league: who has more presence, style and *clutch*?

## What it does

- **Duels:** players face off 1 vs 1, through matchmaking by level or a direct link or QR code.
- **Live audience:** the crowd votes in real time and taps to give a player *hype*.
- **Progression:** ranks from *NPC* to *Aura Sovereign*, a skill tree, an in-game economy, badges and streaks.
- **Events radar:** local and global tournaments on a map.
- **Social:** chat with moderation, presence and voice.

## Screenshots

<!--
<p>
  <img src="../assets/projects/aura-arena/1.png" width="220" />
  <img src="../assets/projects/aura-arena/2.png" width="220" />
  <img src="../assets/projects/aura-arena/3.png" width="220" />
</p>
-->
*Coming soon.*

## How it's built

- **Client:** vanilla JavaScript split into single-purpose modules, available in several languages, installable as a PWA.
- **Real time:** WebSockets for matches and presence, and WebRTC for peer-to-peer video and voice.
- **Backend:** Node.js with a deliberately small stack (`ws`, `nodemailer`, `node:sqlite`). Data access goes through repositories, so the app can move to AWS without rewriting its logic.
- **Mobile:** packaged for Android with Capacitor, with AdMob.
- **Quality:** end-to-end test suites run before and after every change.
