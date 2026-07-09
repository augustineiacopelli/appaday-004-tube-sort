# Tube Sort Solver

Upload a screenshot of any Ball Sort-style puzzle and Claude vision parses
the tube layout automatically. Before analysis runs, an eyedropper step lets
you tap each distinct color directly on the screenshot — those sampled colors
are passed to the AI as the exact palette, eliminating misreads on similar
shades like pink vs magenta or red vs dark red.

Unknown hidden slots are marked with ? and treated as wildcards. Click any
cell to correct the AI's read, hit Solve, then step through the solution one
move at a time.

Settings (⚙ in the top bar) hold your Anthropic API key, tube count, and
distinct color count. The color count setting serves as a fallback constraint
when no eyedropper samples are provided.

Built with vanilla HTML, CSS, and JavaScript. No framework, no build step,
no backend. Screenshot analysis requires an Anthropic API key entered at
runtime — it is never stored or committed.

**Category:** A · AI-Powered Tools  
**Stack:** HTML · CSS · JS · Claude API (vision + claude-sonnet-4)  
**AppADay:** 004
