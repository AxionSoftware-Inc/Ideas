# Hypothesis Falsification Planner

## Thesis
Do not ask only "what experiment gives more data?" Ask "what is the cheapest experiment that can kill the wrong hypothesis?"

## Product
Given competing hypotheses or models, find measurements where their predictions diverge most strongly after accounting for uncertainty and experimental cost.

## Output
```text
Hypothesis A vs B
Best discriminating test:
- temperature: 412 K
- pressure: 2.3 bar
- observable: y(t=18 s)
Expected separation: 6.2 sigma
Estimated cost: $240
```

## Difference from generic experiment design
The primary objective is model discrimination and falsification, not only parameter precision.

## Value
Useful for science, engineering root-cause analysis, materials R&D and expensive laboratory programs.