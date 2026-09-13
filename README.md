Project Overview: An Amazon Product Content-Based Recommendation System built using Python, PySpark, and Scikit-Learn.
Dataset: Evaluated 1,597 rows and 27 columns from an Amazon product and review dataset loaded via Databricks Volumes.
Model Implementation: Utilized TfidfVectorizer (with unigrams and bigrams up to 500 features) 
combined with cosine similarity to calculate product-to-product similarity metrics.
MLflow Integration: Tracked experiment parameters, vectorizer configurations, and average similarity score metrics using MLflow.
Feature Engineering: Combined product attributes—specifically name, brand, and categories—into a unified text corpus field (content) to capture semantic metadata overlap.
Environment & Storage: Hosted and executed the pipeline inside a Databricks workspace, utilizing Unity Catalog and DBFS storage volumes for scalable data access.
Model Artifact Management: Leveraged MLflow tracking servers to organize experiment logs, enabling version control and reproducibility for future iterations.
