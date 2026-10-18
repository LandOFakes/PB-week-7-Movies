# PBrownWeek7 | Precious’s Movie Night

**Precious Brown · IS 362 · Week 7: Data Aggregation**

This purple-themed notebook loads a movie-ratings CSV and calculates original, per-reviewer min-max normalized, and per-reviewer standardized ratings, including user and movie averages and a written conclusion.

## Data disclosure
All five reviewers and their ratings are fictional, using the assignment’s permission to use imaginary friends. The six movies are 2025 releases. Empty CSV cells mean not seen, not zero.

## Run
1. Keep the notebook and CSV in the same folder.
2. Install dependencies with `python -m pip install -r requirements.txt`.
3. Open Jupyter with `jupyter notebook` and select `PBrownWeek7.ipynb`.
4. Restart the kernel and run all cells in order.

In Colab, upload both the notebook and CSV. Purple inline styles may render differently on GitHub. Saved outputs are included.

## Files
- `PBrownWeek7.docx`: Required Word report with results, explanations, conclusion, and full code appendix.
- `PBrownWeek7.ipynb`: Code, Markdown, outputs, and conclusion.
- `PBrownWeek7Ratings.csv`: Source observations; integer ratings from 1 through 5.
- `requirements.txt`: Packages needed to run the notebook.

## Methods
Normalization uses each user’s observed minimum and maximum. Standardization uses each user’s mean and population standard deviation (`ddof=0`). Missing values are excluded from averages and preserved in transformations. Zero ranges or standard deviations produce undefined transformed rows rather than invented preferences.

## Source
[Box Office Mojo: 2025 worldwide releases](https://www.boxofficemojo.com/year/world/2025/) supports movie selection only; ratings are synthetic. Accessed October 18, 2026.


