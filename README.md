# Deploying Mercury models with AWS Jumpstart

This repository contains Jupyter notebooks demonstrating how to deploy [Inception](https://www.inceptionlabs.ai/)'s Mercury family of diffusion large language models (dLLMs) using AWS SageMaker JumpStart.

## Models

- **Mercury**: A high-performance general-purpose language model
- **Mercury-Coder**: A specialized coding-focused language model

Both models are available on the AWS SageMaker Marketplace and optimized for `ml.p5.48xlarge` instances.

## Notebooks

- [`Mercury.ipynb`](Mercury.ipynb) - Deploy and run inference with Mercury
- [`Mercury Coder.ipynb`](Mercury%20Coder.ipynb) - Deploy and run inference with Mercury-Coder

## Prerequisites

- Amazon SageMaker Notebook Instance or SageMaker Studio
- IAM role with `AmazonSageMakerFullAccess` permissions
- Active subscription to the models via AWS Marketplace

## Quick Start

1. Subscribe to the desired model on AWS Marketplace:
   - [Mercury](https://aws.amazon.com/marketplace/pp/prodview-ycpatnhxuxgfa)
   - [Mercury-Coder](https://aws.amazon.com/marketplace/pp/prodview-qnkxatxcm4l7o)

2. Open the corresponding notebook in SageMaker
3. Follow the step-by-step deployment instructions

Each notebook includes complete deployment, inference, and cleanup examples.
