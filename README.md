# Repair the Robot

An interactive, step-by-step robot repair prototype built from the robot parts and lab background in this repo.

Open `index.html` in a browser (or serve the folder, e.g. `python3 -m http.server`) to play.

**Sequence:** Open ACCESS panel → Connect wire → Get battery from the shelf → Open the tool drawer and use the screwdriver on the screw → Get memory card from the shelf → Close panel → Power on → SYSTEM ONLINE

- Each step unlocks only after the previous one is finished; only the current target glows.
- While the robot is open, the lab dims and the robot's head screen shows the SYSTEM CHECK repair checklist.
- Drag-and-drop uses Pointer Events, so it works with mouse, touch and pen.
- Wrong drops send the part back to where it came from.
- Sound effects are synthesised with the Web Audio API (no audio files).
