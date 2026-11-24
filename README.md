<p align="center">
  <img src="icon.svg" width="88" height="88" alt="">
</p>

<h1 align="center">Gemini for Arrumo AI Video Editor</h1>

<p align="center">Generate on-brand images and thumbnails with Gemini.</p>

<p align="center">
  <a href="LICENSE"><img alt="License: AGPL-3.0" src="https://img.shields.io/badge/license-AGPL--3.0-2337B4"></a>
  <img alt="Bundled with Arrumo" src="https://img.shields.io/badge/bundled%20with-Arrumo-2337B4">
  <a href="https://www.aidevs.pt/tools/arrumo/docs/plugins/gemini/images"><img alt="Docs in English, Spanish and Portuguese" src="https://img.shields.io/badge/docs-EN%20%C2%B7%20ES%20%C2%B7%20PT-111"></a>
</p>

This plugin ships with [Arrumo AI Video Editor](https://github.com/aidevs-pt/arrumo-video-editor), the free, open-source desktop app where an AI agent writes, designs, voices and cuts your videos and you approve every step. It comes installed with Arrumo; turn it on or off in **Settings › Plugins**.

## Guides

- **Images**: [English](https://www.aidevs.pt/tools/arrumo/docs/plugins/gemini/images) · [Español](https://www.aidevs.pt/es/tools/arrumo/docs/plugins/gemini/images) · [Português](https://www.aidevs.pt/pt/tools/arrumo/docs/plugins/gemini/images)

## How it works

`image-generation.json` declares the Gemini `generateContent` endpoint with image output and an aspect ratio, the default model and the **Image model** setting that overrides it. See the [Gemini image generation guide](https://ai.google.dev/gemini-api/docs/image-generation).

## Package a release candidate

From this checkout, use the Arrumo Plugin SDK packager and record the SDK commit and the SHA-256 it prints.

```sh
python /path/to/plugin-sdk/tools/package_plugin.py . plugin.zip --include LICENSE --include README.md --include image-generation.json
```

## Icon and trademarks

`icon.svg` shows Google LLC's logo so creators recognise the service this plugin connects to. Gemini, Google and their logos are trademarks of Google LLC; the manifest's `iconNotice` says so wherever Arrumo shows the icon. The logo is not covered by this repository's license, and this plugin is not affiliated with or endorsed by Google LLC. The SVG is a square without rounded corners; Arrumo rounds it. If Google LLC asks, replace the logo with a generic symbol and remove `iconNotice`.

## Contributing

Contributions are welcome: read [CONTRIBUTING.md](CONTRIBUTING.md) and our [Code of Conduct](CODE_OF_CONDUCT.md). Report security problems privately as described in [SECURITY.md](SECURITY.md).

## License

Copyright © 2026 DEVS.AI UNIPESSOAL LDA. Licensed under the [GNU Affero General Public License v3.0](LICENSE). Built by [DEVS AI](https://aidevs.pt), who make custom AI solutions for companies.
