FROM python:3.6-slim
  
# Directories for model codes and secrets
RUN mkdir /app
RUN mkdir /app/secrets

# Watson studio and machine learning python client
RUN pip install watson_machine_learning_client minio

# Python functions with endpoints to Watson Machine Learning
COPY src/wml-deploy.py /app
