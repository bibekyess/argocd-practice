# Define base image
FROM python:3.11.3-slim

# Install MLFlow
RUN pip install mlflow[extras]==2.6.0
RUN pip install psycopg2.binary==2.9.7

# Expose MLFlow default port
EXPOSE 5000

# Run MLFLow server
ENTRYPOINT ["mlflow", "server"]