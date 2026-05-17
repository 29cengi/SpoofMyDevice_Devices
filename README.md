# SpoofMyDevice Devices

Device preset files for `SpoofMyDevice`, based on deviceinfohw database.

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
