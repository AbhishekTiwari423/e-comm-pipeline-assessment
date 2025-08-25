This e-commerce pipeline has been designed to be generic with TDD approach. 
The codebase is divided into two modules :
  1. Jobs - This contain all the scripts for the actual data tranformation, cleansing and aggregation of result.
  2. Tests - This contain all the test scripts to validate the jobs script which are doing the actual work.

main script from the jobs module control the flow of the entire pipeline work. the flow of the pipeline is like main -> Reader -> data_quality_checks -> transformation -> aggregation.
Test scripts can be executed individually in databricks.

<img width="508" height="611" alt="image" src="https://github.com/user-attachments/assets/c381de0a-53c0-4ded-9fa6-0c7779ab1d23" />



