## Team
AISEHack Phase 2 | Theme 2 | IIT Delhi

## Problem
PM2.5 forecasting over India (140×124 grid), 10-hr input → 16-hr forecast

## Our Best Approach
- Model: EnhancedUNet (ResBlocks + SE attention + coordinate channels)
- 2-phase training: balanced loss → episode-heavy loss
- SWA ensemble: Phase2 weights + SWA weights
- Score: 0.8877

## Kaggle Notebook
[Link to best notebook]
