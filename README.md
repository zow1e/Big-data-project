# Airline fare analysis

A team coursework repository exploring US airline data, with an individual analysis of fare-per-mile patterns across American, Delta, and United airlines. The available notebooks demonstrate reference-data joins, derived features, exploratory visualization, and dataset-merging steps.

## Technical skills

**Python · pandas · Seaborn · Matplotlib · Jupyter / Google Colab**

Verified notebook operations include CSV ingestion, filtering, carrier/holiday joins, grouping, fare-per-mile and route features, distribution plots, seasonal comparisons, and correlation heatmaps.

## Start with the evidence

- [zowie_EDA.ipynb](zowie_EDA.ipynb): fare analysis and visualization, including carrier and holiday reference joins.
- [zowie_appendixD.docx](zowie_appendixD.docx): individual report describing the analysis and transformations.
- [filter.ipynb](filter.ipynb): itinerary filtering.
- [Final_Merging.ipynb](Final_Merging.ipynb): merging review factors and other prepared datasets.
- Presentations and project reports provide broader team context. The original team description covered Spark-based work; the checked-in notebooks listed above demonstrate pandas analysis.

## Getting started

Open the notebooks in Jupyter or Google Colab. Install the imported analysis libraries if needed:

```sh
python -m pip install jupyter pandas seaborn matplotlib
jupyter notebook
```

Before executing `zowie_EDA.ipynb`, obtain the input CSVs referenced in its cells, including `small_dataset.csv`, `L_CARRIERS.csv`, and `US Holiday Dates (2004-2021).csv`, and update their paths. These files are not included in this checkout. Other notebooks reference additional datasets and machine-specific Windows/Drive paths that also need adjustment. The notebook code and stored discussion can be read without those inputs.

## Team and scope

The team is **Zowie, Siddarth, ZhangXiang, and Parik**. Zowie's named notebook and individual report support attribution of fare analysis, feature transformations, and visualization; the broader pipeline remains team work. Missing source datasets prevent an out-of-the-box rerun. No predictive-accuracy, scalability, or business-impact claim is made from the included files alone.
