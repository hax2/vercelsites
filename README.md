# WCS reviewer evidence sites

Static Vercel deployment containing four reviewer-facing Word Coverage Score
evidence pages:

- `/url1-correlation/` — WCS correlation with TTR and MTLD.
- `/url2-topk80/` — focused top-k sweep through 80.
- `/url3-all-samplers/` — top-k, top-p, and min-p with 95% confidence intervals.
- `/url4-token-strata/` — WCS stratified by target-word token count.

The repository root provides an index linking all four pages. No build command
or server-side runtime is required; Vercel serves the committed static files.
