# Linear probing GPT-2 small for next-token-is-noun

Can a linear probe on GPT-2 small's residual stream predict whether the *next* token will be a noun? Sweep across layers to see where this information is most readable.

## Layout
- `notebooks/` — exploratory work
- `src/` — reusable code (data prep, probe training, eval)
- `data/` — cached activations and labelled datasets

