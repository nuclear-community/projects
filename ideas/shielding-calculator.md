# 💡 Idea: Shielding calculator

**A dose-and-shielding calculator with worked steps** — inverse-square law, half-value/tenth-value layers for common materials, decay-and-distance scenarios; every answer shows its arithmetic, not just a number.

- **For whom:** [module 05](https://github.com/nuclear-community/nuclear-101/tree/main/modules/05-radiation-detection-protection) students checking shielding homework; early-career HP techs
- **Core features (v0.1):** inverse-square, HVL/TVL attenuation with build-up toggled off (clearly stated), dose-rate from activity using common gammas; SI + legacy units with clean conversion
- **Guardrail:** strictly educational — textbook formulas with stated assumptions, never a worksite tool; label it clearly
- **Tech:** static web app or small CLI; a unit-test suite is essential (this is also a good first-testing-project)
- **Skill range:** beginner-friendly math logic + careful documentation
- **Stretch:** a gamma library per isotope (Cs-137, Co-60, Ir-192…) with dose constants
