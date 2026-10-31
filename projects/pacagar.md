# 🧴 Pacagar

**[pacagar.es](https://pacagar.es)** · Web · 🔒 Private code

> The bathroom bottles you read while you're there, now on your phone.

## What it does

- **3D bottles:** shampoo, shower gel, toothpaste… you spin the bottle to read the label on the back.
- **Ingredients in plain words:** every ingredient explained using its official cosmetic function (EU CosIng).
- **Barcode scanner:** point the camera at a product to open it.
- **Games:**
  - 🎯 bottle toss in 2D and 🥽 in **augmented reality**;
  - 🪳 cockroach hunting in AR;
  - 🚽 *Defend the throne*: the cockroaches go for your feet (easy / hard / hardcore);
  - 🎨 graffiti on your own floor and walls, in AR.

## Screenshots

<!--
<p>
  <img src="../assets/projects/pacagar/1.png" width="220" />
  <img src="../assets/projects/pacagar/2.png" width="220" />
  <img src="../assets/projects/pacagar/3.png" width="220" />
</p>
-->
*Coming soon.*

## How it's built

- **Backend:** read-only Python server (no accounts, no forms), standard library only.
- **Data:** built from the Open Beauty Facts and Open Products Facts dumps. A scheduled container rebuilds it every month and the app picks it up without restarting.
- **Front end:** Three.js for the 3D bottles, WebXR for augmented reality, BarcodeDetector for scanning, and custom physics tested with Node.
- **Ops:** Docker, Python and JavaScript tests, and a pentest on every deploy.
