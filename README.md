# Recommender-Capstone-Project

Load the Data:
Ensure the transaction, customer and product category CSV files are in the specified directory.

Run the Code:
Execute the provided Jupyter notebook to preprocess the data and generate recommendations.

Output:
The system will output the top N product recommendations for a given user ID based on both collaborative and content-based filtering.

Example
To generate recommendations for user ID 270351, run the notebook and observe the output:

Collaborative Filtering Recommendations: ['Electronics', 'Footwear', 'Books', 'Bags', 'Clothing', 'Home and kitchen']
Content-Based Recommendations: ['Electronics', 'Books', 'Footwear', 'Clothing', 'Bags']
Evaluation Metrics


The system was evaluated using the following metrics:

Precision: 0.545
Recall: 1.0
F1-score: 0.694
Mean Average Precision (MAP): 0.060


Steps to Execute

Prepare the Data: Place the transaction, customer, and product category CSV files in the directory specified in the notebook.
Run the Jupyter Notebook: Open the Jupyter notebook and run all cells to preprocess the data, train the model, generate recommendations, and evaluate the model.
Review the Results: Examine the recommendations and evaluation metrics to understand the performance of the recommender system.


File Descriptions

recommender_system.ipynb: Jupyter notebook containing the code to preprocess the data, train the model, generate recommendations, and evaluate the system.
report.pdf: Comprehensive report detailing the project, including data preprocessing, recommendation techniques, evaluation metrics, and benefits.
README.md: This user guide explaining how to run the recommender system and interpret the results.
