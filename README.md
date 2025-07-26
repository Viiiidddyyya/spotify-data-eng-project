# spotify-data-eng-project
We will retrieve data from the Spotify API,  transform it into desired format, and load it into AWS data store.
## [Spotfiy Data Pipeline End-To-End Python Data Engineering Project](https://github.com/darshilparmar/python-for-data-engineering/tree/main/6.%20End-To-End%20Data%20Pipeline%20Project)
Implement Complete Data Pipeline Data Engineering Project using Spotify 
* Integrating with Spotify API and extracting Data
* Deploying code on AWS Lambda for Data Extraction
* Adding trigger to run the extraction automatically 
* Writing transformation function
* Building automated trigger on transformation function 
* Store files on S3 properly
* Building Analytics Tables on data files using Glue and Athena

# Spotify Data Pipeline: Extract, Transform, and Analyze with AWS.

#### Spotify data pipeline: Extract, transform, and analyze using AWS, Lambda, Glue, Athena, and S3.

### OBJECTIVE:
#### This project aims to build a comprehensive data pipeline for extracting, transforming, and analyzing Spotify data using various AWS services. The pipeline will integrate with the Spotify API to fetch relevant data and store it in an organized manner on AWS S3. The extraction process will be automated by deploying code on AWS Lambda, which will run at scheduled intervals or trigger events.
#### Once the data is extracted, a transformation function will be implemented to clean and format the data for further analysis. This function will be designed to handle various data processing tasks, such as data normalization, aggregation, or filtering, based on specific requirements.
#### To ensure the pipeline's efficiency and reliability, an automated trigger will be built on top of the transformation function. This trigger will monitor for any changes or updates in the extracted data and execute the transformation function accordingly.
#### The transformed data will be stored back in AWS S3, maintaining proper file organization and structure. This will allow easy access and retrieval of the processed data for further analysis.
#### Furthermore, to enable seamless analytics, the project will involve creating analytics tables using AWS Glue and Athena. These services will assist in defining the data schema and enable querying and analysis of the transformed data efficiently.
#### By implementing this Spotify data pipeline on AWS, the project aims to provide a scalable, reliable, and automated solution for extracting, transforming, and analyzing Spotify data, unlocking valuable insights for various analytical purposes.

### Architecture :
![Architecture](https://github.com/On-car/spotify-end-to-end-data-engineering--project/blob/main/Project%20Archicture.png)

### Services Used:
**The project utilizes the following AWS services:**

1. Spotify API
2. AWS Lambda
3. AWS S3 (Simple Storage Service)
4. AWS Glue
5. Amazon Athena
