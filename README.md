# GenAI Model Fine-Tuning and Evaluation with AWS SageMaker

## Overview
This project focuses on deploying, evaluating, and fine-tuning a Generative AI model on AWS SageMaker.
The goal is to adapt a pre-trained foundation model to specialize in a selected domain — Financial, IT, or Healthcare — and evaluate its performance before and after fine-tuning.

✅ Project completed as part of the Udacity AWS Generative AI Scholarship Program.

## Project Structure
Model_Evaluation.ipynb
Initial deployment and evaluation of a pre-trained foundation model's text generation capabilities.

Model_FineTuning.ipynb
Fine-tuning the pre-trained model on a selected domain-specific dataset, followed by re-deployment and evaluation.

Project Documentation Report
Documentation summarizing domain selection, model evaluation, fine-tuning process, and insights.

Screenshots
Visual proof of notebook execution, deployment, and S3 bucket uploads.

### Key Technologies Used
- AWS SageMaker
- AWS S3
- Foundation Models (via SageMaker JumpStart)
- Python 3.10 (PyTorch Kernel)
- Generative AI Concepts
- Prompt Engineering and Fine-Tuning

## Project Workflow
Choose a Domain: Selected a domain (Financial, IT, or Healthcare) for specialized knowledge fine-tuning.
Model Deployment: Deployed a base model using SageMaker.
Baseline Evaluation: Analyzed the initial performance of the pre-trained model.
Fine-Tuning: Customized the model with domain-specific datasets.
Re-Deployment: Deployed the fine-tuned model.
Post-Fine-Tuning Evaluation: Compared and documented improvements in the model's text generation quality.
Cleanup: Deleted deployed endpoints to manage AWS budget constraints.

## How to Run the Project
Pre-requisites: AWS Account, SageMaker Notebook Instance, and necessary permissions for S3 and SageMaker.
Start a SageMaker notebook instance (Python 3.10 PyTorch or Tensorflow kernel).
Upload the .ipynb files into the instance.
Run the Model_Evaluation.ipynb to evaluate the base model.
Run the Model_FineTuning.ipynb to fine-tune and redeploy the model.
Review model outputs and save screenshots for documentation.

### Screenshots
Model Evaluation Results
Fine-Tuning Process Outputs
Fine-tuned Model Deployment Results
AWS S3 Storage Confirmation

## Highlights
Successfully deployed and evaluated a pre-trained Generative AI model.
Fine-tuned the model to enhance domain-specific knowledge and performance.
Demonstrated ability to integrate cloud services and manage AI model workflows.

### Acknowledgements
Special thanks to Udacity and AWS for providing the learning platform and resources through the AWS Generative AI Scholarship Program.

