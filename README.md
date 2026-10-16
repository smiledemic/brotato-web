![Brotato Header](https://web.ankomstudios.com/brotatodlc-web/background.png)

<h1 align="center">Brotato: Web Port</h1>

<p align="center">
  <a href="https://github.com/smiledemic/brotatodlc-web">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository">
  </a>
  <a href="https://github.com/smiledemic/brotatodlc-web/stargazers">
    <img src="https://img.shields.io/github/stars/smiledemic/brotatodlc-web?style=for-the-badge&logo=github&color=yellow" alt="GitHub Stars">
  </a>
  <a href="https://github.com/smiledemic/brotatodlc-web/forks">
    <img src="https://img.shields.io/github/forks/smiledemic/brotatodlc-web?style=for-the-badge&logo=github&color=blue" alt="GitHub Forks">
  </a>
  <a href="https://github.com/smiledemic/brotatodlc-web/issues">
    <img src="https://img.shields.io/github/issues/smiledemic/brotatodlc-web?style=for-the-badge&logo=github&color=red" alt="GitHub Issues">
  </a>
</p>

<p align="center">
  A browser-playable port of <strong>Brotato</strong>, brought to completion by <a href="https://github.com/smiledemic">smiledemic</a>.
</p>

<p align="center">
  <a href="https://smiledemic.github.io/brotatodlc-web/externalBuild/">External Build</a> •
  <a href="https://smiledemic.github.io/brotatodlc-web/localBuild/">Local Build</a> •
  <a href="https://store.steampowered.com/app/1942280/Brotato/">Original Game</a>
</p>

## About Brotato

**Brotato** is a top-down arena shooter roguelite developed and published by Blobfish. You play as a potato stranded on an alien planet, fighting off waves of enemies while waiting to be rescued.

Build your character, collect materials, purchase upgrades, and survive increasingly challenging encounters.

### Features

- **Wave-based survival** — Fight off alien hordes in short, intense rounds.
- **Build customization** — Choose from a variety of characters, items, and weapons.
- **Automatic or manual aiming** — Adapt combat to your preferred playstyle.
- **Replayability** — Experiment with different character and item combinations.
- **Fast-paced gameplay** — Enjoy runs designed to be completed in under 30 minutes.

Learn more about the original game on [Steam](https://store.steampowered.com/app/1942280/Brotato/).

## Browser Builds

This project provides two browser builds, designed to make Brotato accessible through a web browser.

### External Build

A lightweight HTML entry point that loads the game engine and game assets from the project's externally hosted asset directory.

- Designed to keep the web page separate from the large game files.
- Loads the engine, game pack, and supporting assets remotely.
- Useful for deployments where the game assets are hosted separately from the HTML page.

### Local Build

A repository-based build that uses the game's files hosted alongside the main project page.

- Keeps the game entry point and its local assets together.
- Uses the repository's game pack and supporting engine files.
- Provides an alternative deployment arrangement to the External Build.

<a href="https://smiledemic.github.io/brotatodlc-web/localBuild/"><img src="https://img.shields.io/badge/▶_Play-Local_Build-0969da?style=for-the-badge" alt="Play Local Build"></a> <a href="https://smiledemic.github.io/brotatodlc-web/externalBuild/"><img src="https://img.shields.io/badge/▶_Play-External_Build-2ea44f?style=for-the-badge" alt="Play External Build"></a>

Both builds were completed by smiledemic. Their loading and hosting arrangements differ, but both are intended to deliver the browser-playable game.

## Development & Credits

This web-port project builds on the work and contributions of its developers and community.

| Contributor | Contribution |
|---|---|
| **Shayder** | Started the web-port project. |
| **[smiledemic](https://github.com/smiledemic)** | Finished both the External Build and Local Build, including their browser-loading and asset-hosting arrangements. |
| **Hazzawazza** | Special shout-out and appreciation for their involvement in the project's wider community. |

A huge thank-you to everyone who contributed to the project and helped bring it to completion.

## Project Structure

```text
brotatodlc-web/
├── externalBuild/
│   └── index.html
├── localBuild/
│   ├── index.html
│   ├── index.js
│   ├── index.wasm.part1
│   ├── index.wasm.part2
│   └── index.audio.worklet.js
├── index.html
├── index.js
├── index.pck
├── index.icon.png
├── background.png
└── README.md
```

*Note: The externally hosted assets used by the External Build are not necessarily stored inside the repository. The tree above illustrates the repository's build organization, not a complete listing of every deployed asset.*

## Hosting

The project is hosted through GitHub Pages, with supporting game assets served from the project's external asset host.

To deploy your own version:

1. Clone or fork this repository.
2. Ensure the required game files are available at the paths expected by each build.
3. Configure your hosting and asset URLs.
4. Enable GitHub Pages or use another compatible static host.
5. Test both builds to confirm that the engine, game pack, WASM files, and audio worklet load correctly.

Large game assets may need to be hosted separately depending on your hosting provider's file-size limits.

## Credits & Ownership

Brotato is the original game by **Blobfish**. This repository is a browser-port project, not the original game's official website.

All original game assets, trademarks, and intellectual property remain with their respective owners. Credits for the web-port work are listed above.

---

<p align="center">
  <strong>Brotato Browser Edition</strong><br>
  wasm.rip | ankomstudios | smiledemic | the unblocked initative
</p>