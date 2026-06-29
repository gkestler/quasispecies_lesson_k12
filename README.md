# Quasispecies Simulation (`Quasispecies.ipynb`)

This interactive Python notebook simulates molecular evolution, Eigen's Paradox, and fitness landscapes using Google Colab[cite: 1].

## 🛠️ How to Use
* **Run cells:** Press `Shift + Enter` or click the **Play ▶️** button[cite: 1]. 
* **Engine Boot:** You **must** run the first code cell ("Master Engine") to initialize variables and functions before starting labs[cite: 1].
* **Modify:** Click inside code cells to adjust parameters like `MUTATION_RATE` or `alpha`, then rerun the cell[cite: 1].

## 🧬 Lab Modules
* **Module 1 (The Error Threshold):** Move the mutation rate across a single fitness peak to find the point where natural selection fails and a population drifts permanently into random genetic noise[cite: 1].
* **Module 2 (Survival of the Flattest):** Race an ultra-fit but sharp peak (**Lineage A**) against a lower but broad plateau (**Lineage B**)[cite: 1]. High mutation rates counter-intuitively cause the flat lineage to outcompete and drive the fittest lineage to extinction[cite: 1].

## 📊 Core Parameters
* `MUTATION_RATE`: Probability of random genetic shifts per site, per generation[cite: 1].
* `alpha` ($\alpha$): Peak decay rate (higher values create sharp needles; lower values create flat hills)[cite: 1].
* `GENERATE_ANIMATION`: Set to `False` to skip the rendering pipeline and instantly get final summary plots[cite: 1].
