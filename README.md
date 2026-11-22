# Arrumo Gemini Plugin

The default Gemini adapter for image generation.

## Icon and trademarks

`icon.svg` shows Google LLC's logo so creators recognise the service this plugin connects to. Gemini, Google and their logos are trademarks of Google LLC; the manifest's `iconNotice` says so wherever Arrumo shows the icon. The logo is not covered by this repository's license, and this plugin is not affiliated with or endorsed by Google LLC. The SVG is a square without rounded corners; Arrumo rounds it. If Google LLC asks, replace the logo with a generic symbol and remove `iconNotice`.

## Images

[English](docs/en/images.md) · [Español](docs/es/images.md) · [Português](docs/pt/images.md)

`image-generation.json` declares the Gemini `generateContent` endpoint with image output and an aspect ratio, the default model and the **Image model** setting that overrides it. See the [Gemini image generation guide](https://ai.google.dev/gemini-api/docs/image-generation).

## Package a release candidate

From this checkout, use the Arrumo Plugin SDK packager and record the SDK commit and the SHA-256 it prints.

```sh
python /path/to/plugin-sdk/tools/package_plugin.py . plugin.zip --include LICENSE --include README.md --include image-generation.json
```
