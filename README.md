Disease Symptom Clustering using Unsupervised Learning

This project applies unsupervised machine learning to group diseases based on their symptom patterns. Using clustering algorithms like KMeans and dimensionality reduction via t-SNE, it helps uncover natural groupings of diseases with similar symptoms — a step toward better understanding and diagnosing disease correlations in healthcare data.

Project Structure
disease_clustering.ipynb – Main Jupyter notebook containing all steps

symptoms_dataset.csv – Input dataset of diseases and symptoms

requirements.txt – Python package dependencies

README.md – Project documentation (this file)

.gitignore – Git ignore rules

LICENSE – Project license (MIT)

Problem Statement
Modern healthcare systems collect large amounts of data on diseases and symptoms. However, the lack of structured symptom-disease grouping limits diagnostic support. The goal is to cluster diseases based on symptom occurrence patterns, allowing for visualization and analysis of disease similarity using unsupervised learning.

Proposed Solution
We clean and process a dataset of diseases and their symptoms, then apply unsupervised clustering algorithms to group diseases into clusters with similar symptom profiles. Visualization with t-SNE and bar plots makes the groupings interpretable and insightful.

Technologies Used
Python 3.x

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, nltk

Algorithms: KMeans Clustering, t-SNE (for dimensionality reduction)

Tools: JupyterLab on macOS (or any OS), GitHub for version control

How to Run the Project
Step 1: Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/DiseaseSymptomClustering.git
cd DiseaseSymptomClustering
Step 2: Create and activate a virtual environment
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
Step 3: Install required dependencies
nginx
Copy
Edit
pip install -r requirements.txt
Step 4: Start JupyterLab
nginx
Copy
Edit
jupyter lab
Then open disease_clustering.ipynb and run all cells step-by-step.

Output and Results
The notebook includes:

Cleaned and preprocessed symptom dataset

Clustering of diseases using KMeans

2D visualization of disease clusters using t-SNE

Bar plots for number of diseases per cluster

Heatmaps to show dominant symptom patterns

Interpretation of clusters and their clinical relevance

Sample Visualizations
t-SNE cluster scatter plot showing disease groupings

Bar chart: Count of diseases per cluster

Heatmap: Symptom intensity across clusters

Pie chart: Symptom category frequency distribution

(Refer to disease_clustering.ipynb to view all visuals.)

Future Scope
Enhance dataset with severity, frequency, and time-based symptoms

Use NLP to parse unstructured symptom descriptions

Build a web interface for doctors to input symptoms and visualize likely clusters

Integrate with medical diagnosis support tools

License
This project is licensed under the MIT License. See the LICENSE file for more information.

Acknowledgements
Guided by foundational knowledge from ML training program

Inspired by real-world medical clustering applications

Based on publicly available datasets and symptom corpora

Author
Asish Kumar Patra
Trainee @ Edunet Foundation Azure AI
GitHub: (https://github.com/ultron513)
LinkedIn: (https://linkedin.com/in/ashish-patra-513akp)
