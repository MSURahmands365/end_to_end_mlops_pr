# end_to_end_mlops_pr
this is my first complete MLops project 
to create projects 
`cookiecutter -c v1 https://github.com/drivendata/cookiecutter-data-science ` 

`https://dagshub.com/MSURahmands365/end_to_end_mlops_pr.mlflow`

import dagshub
dagshub.init(repo_owner='MSURahmands365', repo_name='end_to_end_mlops_pr', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)