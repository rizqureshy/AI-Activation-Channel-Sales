# Channel Sales — AI Activation Marathon

The standalone participant site for the Channel Partner Sales **AI Activation Marathon**
(soft launch Thu Jul 23 · Aug 3 – Sep 21).

Two pages plus a vendored `three.min.js` that powers the live WebGL
ink-in-water background on the main site — a real GPU fluid simulation of
salmon-red and powder-blue ink drifting on a black canvas, with a burst in
the week's accent color on every tab change. The main site is a refined
dark theme; the one-pager stays light for printing. Both degrade gracefully
without WebGL2:

- **`index.html`** — the full participant site: the four core weeks plus the
  capstone week (Rewire Your Thinking · Partner Intelligence · Partner Activation ·
  Partner Business Review · Course/Capstone Week), 22 activities with full briefs and
  the AI skill each one teaches, the Mon–Thu optional / Friday mandatory
  rhythm, the Partner Lifecycle checkpoints (Recruit · Onboard & Enable ·
  GTM & Execution), the Grand Final, the Equinix data rule, and key dates.
- **`one-pager.html`** — the print-friendly program summary.

**The Grand Final:** Week 4's Full Partner Business Review is every
participant's entry — the winning PBR is presented at the All Hands on
Mon Sep 21.

## Publish

GitHub Pages → Settings → Pages → deploy from the default branch, root.
Or copy `index.html` anywhere — it's fully self-contained.
