Bruce Homoya
CS4379G: Data Analysis & Visualization

This repository contains a complete data analysis workflow for CS4379G: Data Analysis & Visualization. It includes a Git-managed project structure featuring a Python Jupyter notebook that explores trends and distributions within the Netflix titles dataset.

How to Run the Notebook
To reproduce this analysis, follow these steps:

Clone the Repository: Run git clone [YOUR_REPO_LINK] and navigate into the Assignment_01 folder.

Install Dependencies: Ensure you have Python installed along with pandas, matplotlib, and seaborn. You can install them via pip: pip install pandas matplotlib seaborn.

Launch Jupyter: Open VS Code or a terminal and run jupyter notebook.

Execute: Open notebooks/analysis.ipynb and run all cells. Ensure netflix_titles.csv remains in the root directory, as the notebook uses a relative path (../netflix_titles.csv) to load the data.

Summary of Findings
Based on the analysis of the Netflix titles dataset, here are the key takeaways:


Content Growth: There was a significant surge in the volume of content added to Netflix starting around 2014, reaching its peak in 2019. This indicates a strategic shift toward rapid library expansion during that decade.


Target Audience: The distribution of ratings reveals that TV-MA is the most prevalent category on the platform, followed by TV-14. This suggests that Netflix’s content strategy is primarily focused on mature and teen audiences rather than young children.


Data Integrity: Using a custom cleaning function, the date_added column was successfully parsed to identify these trends, despite inconsistent formatting in the original dataset.