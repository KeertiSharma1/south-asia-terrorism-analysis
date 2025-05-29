# South Asia Terrorism Analysis

---

## Project Overview

This project conducts an in-depth **Exploratory Data Analysis (EDA)** of terrorism incidents in the South Asia region, utilizing data from the Global Terrorism Database (GTD). The analysis aims to uncover key trends, geographical hotspots, common attack methods, target preferences, and the specific dynamics of major terrorist groups.

The insights gained can contribute to a better understanding of the terrorism landscape in South Asia, potentially aiding in research, policy-making, and security strategies.

## Key Objectives

* **Temporal Analysis:** Investigate how incidents and casualties have evolved over time.
* **Geographical Mapping:** Identify and visualize geographical hotspots of terrorist activity.
* **Attack & Target Profiling:** Determine the most frequent attack types and targeted entities, along with their associated casualty impacts.
* **Terrorist Group Dynamics:** Analyze the operational preferences (tactics and targets) and average lethality of prominent groups.
* **Statistical Validation:** Use hypothesis testing (e.g., Chi-Squared tests) to confirm the statistical significance of observed relationships.

## Data Source

The analysis uses data from the **Global Terrorism Database (GTD)**.
* **Dataset:** `globalterrorismdb_0718dist.csv` (or similar version)
* **Source:** [National Consortium for the Study of Terrorism and Responses to Terrorism (START)](https://www.start.umd.edu/data-tools/global-terrorism-database-gtd)

**Note:** Please ensure you have downloaded the GTD dataset and placed it in the project's root directory (or a `data/` folder if specified in the notebook) for the notebook to run successfully.

## Project Structure

The analysis is presented as a Jupyter Notebook, organized into the following sections:

1.  **Data Loading and Initial Inspection:** Handles dataset loading, initial checks, and data preparation.
2.  **Exploratory Data Analysis (EDA):** Focuses on visualizing and summarizing data to find patterns. This includes temporal trends, geographical distributions, and detailed analyses of attack types, target types, and terrorist group behaviors.
3.  **Statistical Analysis / Hypothesis Testing:** Employs formal tests (like Chi-Squared) to validate the statistical significance of observed relationships.
4.  **Key Findings and Overall Observations:** A concise summary of the most important insights from the entire analysis.
5.  **Conclusion & Next Steps:** Provides a concluding thought and outlines potential avenues for future research.

## How to Run the Notebook

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/KeertiSharma1/south-asia-terrorism-analysis
    cd south-asia-terrorism-analysis
    ```
    
2.  **Download the Data:** Obtain the `globalterrorismdb_0718dist.csv` dataset from https://www.kaggle.com/datasets/START-UMD/gtd.
3.  **Install Dependencies:** Ensure you have Python installed. Install the necessary libraries using `pip`:
    ```bash
    pip install pandas numpy matplotlib seaborn scipy
    ```
4.  **Open Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  **Navigate and Open:** In your web browser, navigate to and open the notebook file (e.g., `South_Asia_Terrorism_Analysis.ipynb`).
6.  **Run Cells:** Execute all the cells sequentially to replicate the full analysis.

## Technologies Used

* **Python 3.x**
* **Jupyter Notebook**
* **Pandas:** For efficient data manipulation.
* **NumPy:** For numerical operations.
* **Matplotlib:** For fundamental plotting.
* **Seaborn:** For advanced statistical visualizations.
* **SciPy:** For conducting statistical tests.