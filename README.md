# Biopol Chain Reaction

Biopol Chain Reaction is a lightweight browser game about guiding a polymer chain through a hazardous reaction floor and outlasting every competing chain.

## What it includes

- Local multiplayer trail-survival gameplay
- Support for up to six human chains plus six extra CPU chains
- Configurable CPU-controlled opponents for solo play or larger matches
- Multiple arena layouts
- Responsive HUD with touch steering for player one
- Custom Biopol-themed presentation and artwork

## How to run it

Open [index.html](./index.html) directly in a browser.

If you prefer serving it locally:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Controls

- `Space` pauses or resumes the current reaction
- `R` restarts the current round
- Chain 1 uses `WASD`
- Chain 2 uses the arrow keys
- Chain 3 uses `IJKL`
- Chain 4 uses `TFGH`
- Chain 5 uses `8 4 2 6`
- Chain 6 uses numpad `8 4 2 6`
