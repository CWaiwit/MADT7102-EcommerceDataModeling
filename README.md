# MADT7102-EcommerceDataModeling
Data Modeling Design and Data Pipeline Implementation - End-to-End

This project will demostrate data modeling design of e-commerce platform by capturing data that related to transaction between vendors and customers.
The PDF file will reveals business understanding, workflow, requirement, designing artifacts.

This demo tested on GCP-Environment; requires GCP 3 buckets, 3 BigQuery datasets.
Environment configuration on GCP:
    # GCP project - create with gcp
    GCP_PROJECT_ID = 'madt7102-termproject-ecommerce';

    # Cloud Storage: Bucket and Blob - create in GCP cloud storage
    GCP_STORAGE_BUCKET_RAW = 'madt7102-ecommerce-raw';
    GCP_STORAGE_BUCKET_STORAGE = 'madt7102-ecommerce-storage';
    GCP_STORAGE_BUCKET_ML_MODEL = 'madt7102-ecommerce-ml-model'

    # Big Query: Dataset ID - create in BigQuery
    GCP_BIGQRY_DATASET_REF_MASTER = 'madt7102-termproject-ecommerce.reference_master';
    GCP_BIGQRY_DATASET_FACT_DIM: = 'madt7102-termproject-ecommerce.fact_dimension';
    GCP_BIGQRY_DATASET_DATA_MART = 'madt7102-termproject-ecommerce.data_mart';
    
see more in python class: PipelineControl
