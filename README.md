"# House-price-prediction-using-mlops" 


#zenml experiment-tracker register mlflow_price1_tracker --flavor=mlflow
#zenml model-deployer register mlflow_price1 --flavor=mlflow
#zenml stack register local-mlflow-price-stack -a default -o default -d mlflow_price1 -e mlflow_tracker --set