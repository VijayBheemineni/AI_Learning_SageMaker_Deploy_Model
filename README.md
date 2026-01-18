# AI_Learning_SageMaker_Deploy_Model

This repository focuses on deploying a trained machine learning model using AWS SageMaker. As part of my AI learning journey, I explore how a trained XGBoost model can be hosted as a SageMaker endpoint and used to make real-time predictions on new data.

The goal of this repo is to understand the model deployment workflow, including creating endpoints, sending inference requests, and managing deployed models in SageMaker. This work helps bridge the gap between model training and real-world usage.

## AWS SageMaker Inference Options

SageMaker offers different ways to run inference depending on cost, scale, and response time needs.

- **Real-time inference**  
  Used when the application needs instant predictions with low latency.

- **Batch transform**  
  Used to run predictions on large datasets at once without keeping an endpoint running.

- **Serverless inference**  
  Automatically scales up and down and is useful for low or unpredictable traffic.

- **Asynchronous inference**  
  Used for long-running predictions where results can be returned later.

---
