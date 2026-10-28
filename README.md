# Repair the Robot

An interactive, step-by-step robot repair prototype built from the robot parts and lab background in this repo.

Open `index.html` in a browser (or serve the folder, e.g. `python3 -m http.server`) to play.

**Sequence:** Open ACCESS panel → Connect wire → Battery → Screw → Memory card → Close panel → Power on → SYSTEM ONLINE

- Each step unlocks only after the previous one is finished; only the current target glows.
- Drag-and-drop uses Pointer Events, so it works with mouse, touch and pen.
- Wrong drops send the part back to the Parts Bin.
