# GloBIAS 2026 · Group 5

Group 5's work for **Session 06 "Benchmarking"** of the GloBIAS 2026 workshop. *Group work for the
workshop; not an official GloBIAS account.*

**Can an AI agent run, and rerun, a bioimage analysis?** In October 2026 one Claude session ran ilastik's
MitoCheck cell-tracking example from scratch, hitting seven walls on the way. Four more sessions then
tried again. Two read that repository and reproduced it without help in 15–41 minutes; their results
matched except one step, ilastik 1.3.3post3 tracking, which renumbered two lineages and moved 113 pixels
between touching nuclei. Two sessions got only the group's question and the data. Neither ran the
tracking; both built a consensus experiment with simulated annotators instead, and concluded that
consensus is not sufficient to define ground truth. One used ilastik headless within a minute; the other
decided ilastik could not run and replaced it. Documentation turned the problem into a recipe, and every
session overstated something that a second look caught.

| repository | what it holds |
|---|---|
| [ilastik-agent-benchmark](https://github.com/globias-2026-group5/ilastik-agent-benchmark) | **Start here:** the five sessions compared, with figures |
| [ilastik-mitocheck-run](https://github.com/globias-2026-group5/ilastik-mitocheck-run) | The original run: every step, error and result, as a story |
| [workshop](https://github.com/globias-2026-group5/workshop) | The group's working space: Assignments I and II, the presentation, discussion issues |
| [shape-analysis-field-guide](https://github.com/globias-2026-group5/shape-analysis-field-guide) | A plain-language guide to the Shape Analysis 101 tutorial ([site](https://globias-2026-group5.github.io/shape-analysis-field-guide/)) |
