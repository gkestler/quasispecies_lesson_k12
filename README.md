# Quasispecies Simulation (`Quasispecies.ipynb`)

This interactive Python notebook simulates molecular evolution, Eigen's Paradox, and fitness landscapes using Google Colab.

## 🧬 Lab Modules
* **Module 1 (The Error Threshold):** Move the mutation rate across a single fitness peak to find the point where natural selection fails and a population drifts permanently into random genetic noise.
* **Module 2 (Survival of the Flattest):** Race an ultra-fit but sharp peak (**Lineage A**) against a lower but broad plateau (**Lineage B**). High mutation rates counter-intuitively cause the flat lineage to outcompete and drive the fittest lineage to extinction.

## 📊 Core Parameters
* `MUTATION_RATE`: Probability of random genetic shifts per site, per generation.
* `alpha` ($\alpha$): Peak decay rate (higher values create sharp needles; lower values create flat hills).
* `GENERATE_ANIMATION`: Set to `False` to skip the rendering pipeline and instantly get final summary plots.
