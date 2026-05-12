# appaday-004-tube-sort
Snap a screenshot of any Ball Sort puzzle and let AI parse the tubes automatically. Fill in unknowns with ?, step through the BFS solution move by move, or enter tubes manually. One file, no build step, no backend.
# Tube Sort Solver

Upload a screenshot of any Ball Sort-style puzzle and Claude vision parses
the tube layout automatically. Unknown hidden slots are marked with `?` and
treated as wildcards by the solver. Click any cell to correct the AI's read,
hit Solve, then step through the solution one move at a time.

Built with vanilla HTML, CSS, and JavaScript. No framework, no build step,
no backend. Screenshot analysis requires an Anthropic API key entered at
runtime — it is never stored or committed.

**Category:** A · AI-Powered Tools  
**Stack:** HTML · CSS · JS · Claude API (vision + claude-sonnet-4)  
**AppADay:** 004

2026-05-11: Doesn't resolve all colors correctly in uploaded screenshot. Need to come back at some point to see if I can get this to handle the colors better on the uploads.
