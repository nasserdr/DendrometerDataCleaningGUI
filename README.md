Here is your updated **README.md** text in clean Markdown, with emojis added and the TODO/roadmap section removed:

# dendroSense 🌲📊

DendroSense provides an intuitive graphical user interface and helper utilities for analysing dendrometer data. The package bundles common workflows—such as daily statistics, stem cycle metrics, and zero-growth phase detection—into a streamlined interface aimed at researchers who need to explore time-series measurements quickly. Under the hood, it implements the methods introduced in the original publication, helping analysts focus on interpreting measurements rather than wiring scripts together. 🌿📈

## Requirements 🧩

- **R 3.6.x** — best matches the environment in which the project was originally developed.  
- **Optional:** RStudio for an easy way to launch the GUI. 💻

## Installation 📦

Install the released version from CRAN:

```r
# install.packages("dendroSense")
````

Install the development version from GitHub:

```r
# install.packages("devtools")
# devtools::install_github("nasserdr/dendroSense")
```

## Getting started 🚀

Launch the graphical interface directly:

```r
library(dendroSense)
runGui()
```

Or open `gui/DendroSenseGUI.R` in your IDE and click **Run App** to start the Shiny interface.

## Example datasets 🗂️

The `data/` directory contains dendrometer recordings used for testing, demonstration, or reproducing examples from the accompanying publication. You can load them in the GUI or inspect them programmatically.

Available example files include:

* `Jumps_fixed_Base_1811_Dendro_531_Filtered.csv`
* `Jumps_fixed_Base_1814_Dendro_192_Filtered.csv`
* `Jumps_fixed_Base_1815_Dendro_552_Filtered.csv`
* `Jumps_fixed_Base_1816_Dendro_326_Filtered.csv`
* `Jumps_fixed_Base_1936_Dendro_594_Filtered.csv`

## Contributing 🤝

Contributions are welcome!
Feel free to open an issue for questions or suggested enhancements, or submit a pull request. Please update this README when adding or modifying features so that new users always have up-to-date guidance.

```

Just let me know!
```
