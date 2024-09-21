# ML Flow Experiments

https://dagshub.com/prince19998/mlflowexperiments.mlflow

dagshub upload prince19998/mlflowexperiments <local_file_path> <remote_file_path>

import dagshub
dagshub.init(repo_owner='prince19998', repo_name='mlflowexperiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)