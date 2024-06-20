# ML-flow-Basic-Practice

https://dagshub.com/ravivarmanr26/ML-flow-Basic-Practice.mlflow
5e6d5f4ffb9e3ba203e6374d219aacdea4815634
import dagshub
dagshub.init(repo_owner='ravivarmanr26', repo_name='ML-flow-Basic-Practice', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

export MLFLOW_TRACKING_URI=https://dagshub.com/ravivarmanr26/ML-flow-Basic-Practice.mlflow

export MLFLOW_TRACKING_USERNAME=ravivarmanr26

export MLFLOW_TRACKING_PASSWORD=5e6d5f4ffb9e3ba203e6374d219aacdea4815634
import mlflow
import dagshub

dagshub.init(repo_owner='ravivarmanr26', repo_name='ML-flow-Basic-Practice', mlflow=True)

with mlflow.start_run():
    mlflow.log_param("param1", 5)
    mlflow.log_metric("metric1", 0.5)
    mlflow.log_artifact("example.py")
