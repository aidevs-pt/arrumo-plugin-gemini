# Arrumo Gemini Plugin

The default Gemini adapter for image generation.

## Icon and trademarks

`icon.svg` is a generic symbol drawn for Arrumo (a picture frame, for image generation), covered by this repository's
license. It is not the provider's logo: the provider has not published permission for its
logo to appear in another app's interface, so the plugin does not use it. The name is used
only to say which service the plugin connects to; this plugin is not affiliated with or
endorsed by the provider.

## Images

[English](docs/en/images.md) · [Español](docs/es/images.md) · [Português](docs/pt/images.md)

`image-generation.json` declares the Gemini `generateContent` endpoint with image output and an aspect ratio, the default model and the **Image model** setting that overrides it. See the [Gemini image generation guide](https://ai.google.dev/gemini-api/docs/image-generation).

## Package a release candidate

From this checkout, use the Arrumo Plugin SDK packager and record the SDK commit and the SHA-256 it prints.

```sh
python /path/to/plugin-sdk/tools/package_plugin.py . plugin.zip --include LICENSE --include README.md --include image-generation.json
```
