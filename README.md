# Tweet Classification with Sentiment Analysis
#Complete Python Code
## Project Overview
This project classifies tweets into:
1. **First-Level Categories**:
   - **Corona-Related** or **Non-Corona-Related**.
2. **Second-Level Categories**:
   - Emotional (e.g., fear, sadness, hope) or Non-Emotional.

Additionally, the project performs **Sentiment Analysis** to identify whether tweets are:
- Positive
- Negative
- Neutral

## Features
- Multi-level classification using **Random Forest Classifiers**.
- Sentiment analysis using **TextBlob**.
- Results saved to CSV for further analysis.
- Visualizations of classification and sentiment distributions.

## Files in This Project
1. `project_notebook.ipynb`: The main Jupyter notebook with all the code.
2. `project_script.py`: Python script version of the notebook.
3. `Hackathon_Round_1.xlsx`: Input dataset used for the project.
4. `classification_results.csv`: Results of the classification (predictions).
5. `README.md`: This file.
6. (Optional) Images like confusion matrix or sentiment distribution charts.

## How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib textblob
