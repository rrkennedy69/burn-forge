# Burn Forge

**Live app: https://rrkennedy69.github.io/burn-forge/**

Burn Forge is a touch-first web app for creating and editing LightBurn project files (`.lbrn2`, and older `.lbrn`) on iPad and iPhone Safari. It runs entirely in the browser, works offline once installed (Share → Add to Home Screen), and keeps a "My files" library on the device.

* Opens existing projects and saves them back **without touching anything it doesn't understand**: untouched XML is written back byte-for-byte; only shapes/settings you actually edit are rewritten.
* Draw rectangles, ellipses, lines/polylines, text; import SVG; move/resize/rotate, align, group, duplicate, numeric mm entry, snap.
* Layers use LightBurn's standard colors; edit mode (Line / Fill / Offset Fill / Fill+Line / Image), speed, power, passes, interval, output and visibility.
* Exports `.lbrn2` (iOS share sheet or download) and SVG.

It does **not** control a laser. Not affiliated with or endorsed by LightBurn Software. This branch contains the built static site only.
