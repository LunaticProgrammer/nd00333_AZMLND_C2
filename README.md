# Operationalizing Machine Learning

## Project Overview

The project focuses on creating a workflow of a machine learning ecosystem and then operationalizing it to make the process of re-training, publishing endpoints and troubleshooting easier.

## Architectural Diagram

![Architecture](./images/arch.PNG "Architecture")

## Key Steps

1. Add Dataset

![Dataset Register](./images/dataset-snapshot.PNG "Dataset Registration")

2. Create a pipeline and a run with bank-marketing-dataset

![Machine Learning Pipeline with dataset](./images/dataset-with-aml.PNG "ML Pipeline")

3. After Completion of pipeline extract best model

![Model Extraction](./images/completed_run_best_model.PNG "Model Extraction")

4. Deploy best model and get endpoints along with enabling insights

![Model Deployment](./images/app_insights.PNG "Model Deployment")

5. Publish Pipeline,Get endpoints and submit another run

![Publishing Pipeline](./images/publish_pipeline.PNG "Publishing Pipeline")

6. Submitting run via published pipeline endpoint

![Submitting Run via published rest endpoint](./images/pipeline-submission.PNG "Submitting run")

7. Checking submitted runs on experiments

![Checking Runs](./images/scheduled-runs.PNG "Cheking runs")

8. Checking the completion in notebook

![Checking completion](./images/run-steps.PNG "checking completion")

9. Checking Pipeline Endpoints

![Checking Endpoints](./images/pipeline-endpoint.PNG "Pipeline Endpoints")

10. Creating Swagger doc to see api-endpoints and hit right away through it

![Swagger](./images/swagger.PNG "swagger")

11. Finally running tests,benchmarks and checking logs on deployed-model api

Endpoint Test

![Endpoint test](./images/endpoint.PNG "endpoint test")

Enabling logs

![Logs](./images/logs.PNG "Longs")

Running Benchmarks

![Benchmarks](./images/benchmark.PNG "benchmark")

## Screen Recording

[![Screen recording](https://i9.ytimg.com/vi/6SiwI0KuwJk/mq3.jpg?sqp=CNTJmoEG&rs=AOn4CLB_hHMs9LD1A2lXQW96TNmaR6Rr-A)](https://youtu.be/6SiwI0KuwJk)

## Standout Suggestions

1. Accuracy can be improved by solving the class-imbalance issue of the dataset used.
2. Number of cross-validations can be increased for better results.
3. Using more powerful tools like Deep-learning can definitely lead to better performance.
