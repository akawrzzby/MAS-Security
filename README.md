# MAS-Security
Some papers on MAS Security

## Bookmarks

* [**Model Preparation**](#model-preparation)
  * [Data Preprocessing](#data-preprocessing)
  * [Model Training Tricks](#model-training-tricks)
  * [Model Quantization](#model-quantization)
* [**Deployment Tools**](#deployment-tools)
  * [Containerization (Docker)](#containerization-docker)
  * [Serverless Deployment](#serverless-deployment)
  * [Edge Deployment](#edge-deployment)
* [**Monitoring & Maintenance**](#monitoring--maintenance)
  * [Performance Monitoring](#performance-monitoring)
  * [Model Retraining](#model-retraining)
  * [Error Handling](#error-handling)

## Model Preparation

### Data Preprocessing

Effective data preprocessing ensures AI models receive clean, well-structured input. Below are tools and methods for streamlining this step:

| Tool/Method    | Description                                                  | Resource Link                              |
| -------------- | ------------------------------------------------------------ | ------------------------------------------ |
| SmartTrimmer   | Efficiently reduces redundant features while preserving key information. | [link](https://example.com/smarttrimmer)   |
| AutoNormalizer | Automatically applies normalization to multi-modal data (images, text, etc.). | [link](https://example.com/autonormalizer) |
| FederatedPrep  | Enables data preprocessing in federated learning setups with privacy guards. | [link](https://example.com/federatedprep)  |

### Model Quantization
Quantization reduces model size and accelerates inference by lowering parameter precision. Popular techniques:
| Technique            | Use Case                                                     | Tutorial Link                                   |
| -------------------- | ------------------------------------------------------------ | ----------------------------------------------- |
| Post-Training Quant  | Applies quantization after model training (easy to integrate). | [link](https://example.com/post-training-quant) |
| Quant-Aware Training | Trains models with quantization in mind (better accuracy for low precision). | [link](https://example.com/quant-aware-train)   |
| Dynamic Quantization | Adjusts precision during inference based on input.           | [link](https://example.com/dynamic-quant)       |

## Deployment Tools
### Containerization (Docker)
Containerization packages models with dependencies, ensuring consistency across environments. Popular Docker setups for AI:

| Image Name        | Use Case                                                  | Dockerfile Repository                          |
| ----------------- | --------------------------------------------------------- | ---------------------------------------------- |
| `torch-serve-ai`  | Serves PyTorch models via TorchServe.                     | [link](https://example.com/torch-serve-docker) |
| `tf-lite-runtime` | Runs TensorFlow Lite models (optimized for edge devices). | [link](https://example.com/tf-lite-docker)     |
| `fastapi-ml-api`  | Wraps ML models into RESTful APIs with FastAPI.           | [link](https://example.com/fastapi-ml-docker)  |
