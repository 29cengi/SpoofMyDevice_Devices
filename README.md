# SpoofMyDevice Presets

Device preset files for [SpoofMyDevice](https://github.com/BuSung-dev/SpoofMyDevice), props based from [Device Info HW Database](https://deviceinfohw.ru/devices/), then the rest is filled by Gemini AI. It is generated if not available or missing.
Device models are mostly global variants, with philippine region.


Each preset lives in the repository root as a single JSON file such as:

- `Google Pixel 8 Pro.json`
- `Samsung Galaxy S25 Ultra.json`
- `Samsung SM-X900.json`

## Format

```json
{
  "id": "pixel_8_pro",
  "brandLabel": "Google",
  "modelLabel": "Pixel 8 Pro",
  "summary": "Tensor G3 - Android 15",
  "profile": {
    "brand": "google",
    "manufacturer": "Google",
    "model": "Pixel 8 Pro"
  }
}
```

The app reads root-level `.json` files from this repository and turns them into selectable presets.

## AI Policy
This fork involves the use of AI to fill in the props, which may not be accurate, use with caution. You've been warned!

## Fork
This is a fork of BuSung-dev/SpoofMyDevice_Devices.
