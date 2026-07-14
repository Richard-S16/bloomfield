# 🌼 Bloomfield

A generative botanical garden that grows itself. Single HTML file — no deps, no build step.

## Run
Double-click `index.html` (opens in any modern browser).

## How to play
- **Click** anywhere to plant a seed.
- **Drag** across the ground to broadcast a meadow of seeds.
- Plants **grow** from an L-system grammar driven by a genome (~12 traits: branching angle, leaf size/shape, flower hue/sat, petal count, sway, growth rate, …).
- Mature flowers **drop seeds** that drift on the wind, land, and sprout children with **mutated** genomes — your garden evolves over time.
- **Wind** & **Growth** sliders tune the whole field.

## Share a garden
- **Copy DNA** → copies the first plant's genome as a `bloom1:…` string.
- **Paste DNA** → grows one plant from a friend's string (its offspring will mutate from there).
- **Save PNG** → exports the current frame.

## Tips
- Cap is ~30 plants (for perf). Hit **Clear** to start a wilder lineage.
- Low wind + high growth = fast, tranquil shapes. High wind = dancing field.
- Each plant's genome is unique; mutations keep things surprising.