# Arrumo Gemini Plugin

The default Gemini adapter for image generation.

Copyright © 2026 DEVS AI Unipessoal LDA. Licensed under the [GNU Affero General Public License v3.0](LICENSE).

For custom AI solutions for your company, visit [DEVS AI](https://aidevs.pt).

## Images

[English](docs/en/images.md) · [Español](docs/es/images.md) · [Português](docs/pt/images.md)

`image-generation.json` declares the Gemini `generateContent` endpoint with image output and an aspect ratio, the default model and the **Image model** setting that overrides it. See the [Gemini image generation guide](https://ai.google.dev/gemini-api/docs/image-generation).

## Package a release candidate

From this checkout, use the Arrumo Plugin SDK packager and record the SDK commit and the SHA-256 it prints.

```sh
python /path/to/plugin-sdk/tools/package_plugin.py . plugin.zip --include LICENSE --include README.md --include image-generation.json
```
