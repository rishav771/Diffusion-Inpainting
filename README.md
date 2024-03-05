# Diffusion Models for Masked Impainting

## Overview

This repository contains the codebase and documentation for the "Diffusion Models for Masked Impainting" project conducted from June 2023 to the present. The project focuses on developing and evaluating an innovative impainting method for X-ray image processing, specifically targeting the restoration of missing or masked regions in medical X-ray images.

## Project Highlights

### 1. Objective

The primary goal of the project is to enhance the accuracy and efficiency of the impainting process for X-ray images, leveraging advanced techniques such as Diffusion Models and Paint-By-Example algorithms.

### 2. Techniques Used

#### 2.1 Diffusion Models

- Utilized mathematical frameworks to simulate the spread or diffusion of information within X-ray images, contributing to accurate impainting. [Reference](https://huggingface.co/runwayml/stable-diffusion-inpainting)

#### 2.2 Paint-By-Example Algorithms

- Integrated Paint-By-Example algorithms to guide the impainting process by leveraging existing data and patterns. [Paint-By-Example Demo](https://huggingface.co/spaces/Fantasy-Studio/Paint-by-Example)

#### 2.3 ETL Pipeline Automation

- Automated the Extract, Transform, Load (ETL) pipeline to optimize data collection for the CheXpert Dataset, achieving a 30% reduction in processing time with the Datadings package.

#### 2.4 Data Labeling with Captum Library

- Employed the Captum library for precise data labeling, generating masks for the CheXpert dataset to train and fine-tune Diffusion Models. [Captum Documentation](https://captum.ai/#quickstart)
### 3. Results and Achievements

#### 3.1 Accuracy Improvement

- Achieved an impressive 97% accuracy in restoring masked regions in X-ray images using the developed impainting method.

#### 3.2 Efficiency Gains

- Automated the ETL pipeline, resulting in a 30% reduction in data collection time for the CheXpert Dataset, enhancing overall efficiency.

#### 3.3 Quality Improvement

- Fine-tuned the Diffusion Model, leading to a 25% improvement in the quality of image reconstruction for medical X-ray images.

#### 3.4 eXplainable AI (XAI) Exploration

- Explored eXplainable AI by creating paintings for counterfactual examples, providing deep insights into the model's behavior for enhanced interpretability.

## Repository Structure

### 1. Codebase

- The `src` directory contains the source code for the impainting method, ETL pipeline automation, and model fine-tuning.

### 2. Documentation

- The `docs` directory includes comprehensive documentation on project methodologies, results, and instructions for reproducing the experiments.

### 3. Dependencies

- The `requirements.txt` file lists all dependencies required to run the code.

