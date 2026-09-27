# Cosine Similarity Case Study

Calculating and visualizing cosine similarity for numeric data and comparing text documents with count vectors and TF-IDF.

## Run

Use Python 3.12. From this project folder:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Open `Cosine_Similarity_Case_Study.ipynb` and select Restart Kernel and Run All Cells. Keep the dataset at `data/distance_dataset.csv`.

## Contents and results

- Numeric similarity for 2,000 points in the YZ and XYZ spaces.
- 2D and 3D plots correctly labeled as cosine distance (1 minus similarity).
- Original business-name example: TF-IDF similarity 0.2606.
- Custom sentence exercise: count-vector similarity 0.4444; TF-IDF similarity 0.2883; distance 0.7117.
- Discussion of record matching, lexical overlap, feature scaling, and limitations.

The template's obsolete get_feature_names calls are updated to get_feature_names_out. The incorrect positional argument to cosine_similarity is removed. ClusterID is excluded from numeric feature vectors.

All 14 code cells executed sequentially in a fresh Python process, with formula and similarity-matrix checks passing. Both plots were inspected. Outputs are saved; local Jupyter execution was not tested. The supplied CSV is unchanged.

## Submission

Suggested repository: `cosine-similarity-case-study`.

Upload the extracted notebook, data folder, README, and requirements to a public GitHub repository. Review the notebook and submit its GitHub page URL, checking access while signed out. No GitHub upload was performed.

Assignment and dataset supplied by Springboard. Completed with AI assistance.
