## There is a collection of statistical analysis tutorials for ABV Module course

- **Day 1**: R basics and data cleaning: https://mohanb96.github.io/ABV_modul/D1_R_Intro.html
- **Day 2**: Significant testing and effect size: https://mohanb96.github.io/ABV_modul/D2_test.html
- **Day 3**: PCA analysis and Clustering: https://mohanb96.github.io/ABV_modul/D3_Demo.html
- **Day 4**: - One-way ANOVA and pair-wise significant testing: https://mohanb96.github.io/ABV_modul/D4_ANOVA_linear_model.html
             - General linear models: https://mohanb96.github.io/ABV_modul/D4_linear_model.html
- **Day 5**: Simple machine learning models: https://mohanb96.github.io/ABV_modul/D5_Tree_model.html
- **Day 7**: Multiple factors: Interaction effects and null models: https://mohanb96.github.io/ABV_modul/D7_Null_Models.html
- **Day 8**: Scientific writing

📊 Dataset: MultiFactor_data.csv

## Description:
This dataset summarizes results from a multi-factor global change experiment, where soil samples were exposed to various combinations of 12 global change factors (GCFs). It includes measures of soil ecosystem functions, chemical properties, and treatment composition (which stressors were applied).

Each row corresponds to one treatment combination, representing a unique set of factors acting on a soil microcosm.

## 🧾 Column Descriptions
| Column	| Description |
|---------|-------------|
|actv_ace |	Soil acetate esterase activity, an enzyme linked to the breakdown of organic compounds (indicator of microbial activity).|
|actv_cello |	Cellulase activity, measuring the capacity of soil microbes to decompose cellulose (plant material).|
|actv_gluco |	β-glucosidase activity, a key enzyme in carbon cycling (breaks down cellulose derivatives).|
|actv_phos |	Phosphatase activity, representing the rate of phosphorus mineralization in soil.|
|Decom |	Soil decomposition rate, overall measure of organic matter breakdown (a key soil ecosystem function).|
|PH	|Soil pH, indicating soil acidity or alkalinity.|
|WSA	|Water-stable aggregates, a measure of soil structural stability (related to erosion resistance and carbon storage).|
|dissim	|Factor dissimilarity index, quantifying how mechanistically different the applied global change factors are (higher = more diverse stressor types).|
|P, C, L, N, A, I, SU, FU, H, M, S, D|	Binary variables (1 = factor applied, 0 = absent), representing the 12 global change factors used in the experiment:
- P: Phosphorus addition
- C: Carbon addition
- L: Light (shading/illumination manipulation)
- N: Nitrogen addition
- A: Acidification
- I: Insecticide
- SU: Surfactant (pollutant)
- FU: Fungicide
- H: Heat (warming)
- M: Microplastic addition
- S: Salt (salinity)
- D: Drought|
|remark|	Type of treatment combination (e.g., single-factor, multi-factor).|
|Lv	|Number of factors applied in that treatment (from 0 to 8 in this dataset).|
