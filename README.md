# DataPipeline-for-YouTube-Ad-Recommendations

Project Summary: AWS-Based Serverless Data Pipeline for YouTube Analytics

This project builds a scalable, serverless data pipeline on AWS to analyze YouTube video statistics and gain key insights into viewer engagement, content performance, and audience behavior. By leveraging a suite of AWS services—including Amazon S3, AWS Lambda, AWS Glue, Athena, and visualization tools like Amazon QuickSight and Tableau—the pipeline efficiently ingests, transforms, and analyzes data from trending YouTube videos across multiple regions.

Key aspects include:

Data Ingestion & Transformation:
YouTube data is ingested via AWS CLI into S3, then processed using Lambda and Glue Studio to prepare it for analysis in Athena.

Insight Generation:
The system extracts metrics such as views, likes, tags, sentiment, and audience demographics. These insights enable content creators and marketers to tailor their strategies effectively.

Ad Recommendation Model:
The pipeline also serves as a recommender system, suggesting the most appropriate ad categories for videos based on regional viewership trends.

Dataset Composition:
The project utilizes CSV files containing video details (e.g., title, channel, views, likes, comments) and JSON files mapping category information for regions like the US, GB, IN, JP, and more, allowing for comparative regional analysis.

Overall, the project demonstrates how modern data engineering techniques and cloud-based solutions can transform raw, diverse datasets into actionable insights and strategic recommendations for the rapidly evolving digital advertising landscape.
