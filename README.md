This projects showcases the seamless integration of Apache Airflow and AWS services to process and analyze data.

Here’s how it all came together:
1️⃣ Data Extraction: Running Apache Airflow on an Amazon EC2 instance, I automated the extraction of real-time weather data from a public API.
2️⃣ Data Transformation: I used Python code to clean, structure, and prepare the data before uploading it to Amazon S3.
3️⃣ Data Cataloging: After loading the data into S3, I ran an AWS Glue Crawler to catalog the data and automatically detect its schema.
4️⃣ Analysis with Athena: Leveraging Amazon Athena, I queried and analyzed the data stored in S3, gaining valuable insights without managing servers.
5️⃣ Development Setup: As part of the project, I also learned how to connect my EC2 instance to VS Code on my laptop, enabling efficient development and debugging directly from my local machine.

This project demonstrated the power of orchestration, serverless architecture, and robust data services to streamline workflows and deliver insights efficiently.
