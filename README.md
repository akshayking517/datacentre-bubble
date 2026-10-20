# Datacentre Bubble

Interactive simulation: **AI Rack Power Allocation — Arithmetic Versus Moving Weights**

Shows where power goes during model inference: the actual arithmetic versus the cost of moving weights across wires (off-chip memory vs stationary on-chip weights). Highlights the impact on rack power, cooling requirements, and CapEx.

## View the simulation

- Repo: https://github.com/akshayking517/datacentre-bubble
- Direct file: https://github.com/akshayking517/datacentre-bubble/blob/main/index.html

To host it live with GitHub Pages:
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)` → Save

After a minute it will be available at:
https://akshayking517.github.io/datacentre-bubble/

## Instant preview (no Pages required)
https://htmlpreview.github.io/?https://github.com/akshayking517/datacentre-bubble/blob/main/index.html

## How it works
- Toggle between **Off-chip memory** (hauling weights) and **Stationary weights** (kept on-chip)
- Select model size (8B / 70B / 405B) and concurrent user streams (100–4,000)
- See total rack power, breakdown of math vs wire movement vs cooling, and whether air or liquid cooling is required
- Instant cost comparison ($12k air vs $115k liquid cooling)
