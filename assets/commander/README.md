# Commander Portrait Assets

Place 4 commander portrait PNG files in this directory with the following names:

## File Names (EXACT - case sensitive):

1. **commander-healthy.png** - Full health state (80-100% hull)
   - Commander appears calm, confident, battle-ready
   - Clean uniform, steady gaze
   - Use when ship is in good condition

2. **commander-damaged.png** - Moderate damage state (50-80% hull)
   - Commander shows concern, minor stress
   - Slight wear, more intense expression
   - Use when ship has taken moderate damage

3. **commander-critical.png** - Severe damage state (25-50% hull)
   - Commander appears wounded, stressed, alarmed
   - Visible damage/blood, worried expression
   - Use when ship is badly damaged

4. **commander-dead.png** - Critical/Death state (<25% hull or destroyed)
   - Commander incapacitated, eyes closed, or severely wounded
   - Final moments expression
   - Use when ship is nearly destroyed or dead

## Technical Specifications:

- **Format**: PNG with transparency
- **Recommended Size**: 256x256 pixels (will be scaled as needed)
- **Style**: 16-bit pixel art aesthetic
- **Framing**: Chest-up portrait, facing forward
- **Background**: Transparent (alpha channel)
- **Color Palette**: Military sci-fi (dark, muted colors)

## Health State Thresholds:

The portraits automatically switch based on hull health percentage:
- 80-100% → commander-healthy.png
- 50-80% → commander-damaged.png
- 25-50% → commander-critical.png
- 0-25% → commander-dead.png

These thresholds align with the power degradation system for consistent visual feedback.
