# 💡 Idea: Decay chain visualizer

**Interactive decay chains in the browser** — pick a parent nuclide (U-238, Th-232, U-235, or any nuclide), and watch the chain unfold: daughters, decay modes, half-lives, and branch ratios, laid out as a navigable diagram.

- **For whom:** anyone in [module 01](https://github.com/nuclear-community/nuclear-101/tree/main/modules/01-nuclear-physics-foundations) — decay chains are much easier to *see* than to read
- **Core features (v0.1):** the three natural series pre-loaded; click a node to see half-life, decay mode, and branch ratios; export as image
- **Data:** half-lives and decay modes from NuDat/ENSDF (a small bundled JSON snapshot is fine for v0.1; live API later)
- **Tech:** any browser stack — vanilla JS or a light framework; layout of the graph is the fun part
- **Skill range:** beginner-friendly (UI + data) with an intermediate data-prep task
- **Stretch:** animate a population of atoms decaying over time (exponential law made visceral)
