# Calligraphy 3D — from brush and paper to digital form

Photograph a piece of calligraphy you've written and turn it into a 3D object you can turn, inspect and export.

**Forms:** xuan (rice) paper · floating strokes · carved stone tablet · gilded palace plaque (匾額)

**Features**
- Auto-clean: removes shadows and uneven light, separates ink from paper, detects rubbings (white writing on black)
- Remove stray marks by clicking them, or with a brush eraser
- Adjust raised height, edge softness, ink strength and colour
- Export a high-res PNG (transparent, dark or light background) or a looping 360° GIF

Everything runs in the browser — photos never leave your device.

## Run it in a Codespace
1. On this repo, click **Code → Codespaces → Create codespace on main**.
2. Wait for it to start. A local server starts on port 8080 and opens in a new browser tab.
   If it doesn't open, go to the **Ports** tab and click the globe icon next to port 8080.

## Run it locally
```bash
python3 -m http.server 8080
```
then open <http://localhost:8080>.

> The "describe any form" box (Claude-designed custom forms) only appears when the page is opened inside Claude; everything else works anywhere.
