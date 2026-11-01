# Automated Butterfly and Moth Classification Using Deep Learning: A Comparative Benchmark Analysis

**Student Name:** Lee Re Xuan  
**Student ID:** 24071969  
**Program:** Master of Data Science  
**Institution:** Faculty of Computer Science & Information Technology, Universiti Malaya  
**Academic Year:** 2026  

## Project Overview
This repository contains the codebase and documentation for my Master's Research Project (P2). The research establishes a rigorous, mathematically sound comparative benchmark for automated butterfly and moth classification across 100 distinct species. It evaluates a heavily optimized lightweight edge architecture (MobileNetV2) against an industry-standard heavy baseline (ResNet-50) to address the computational constraints and taxonomic limitations prevalent in current ecological computer vision frameworks.

## Repository Contents
* **`P2_MobileNetV2_Revise_2.ipynb`**: The Google Colab notebook containing the advanced optimization pipeline (100% unfreezing, Cosine Decay learning rate, AdamW weight decay, and Label Smoothing) and evaluation metrics for the MobileNetV2 architecture.
* **`P2_ResNet50_Benchmark_2.ipynb`**: The Google Colab notebook containing the two-stage transfer learning pipeline (classification head warm-up and deep fine-tuning) and evaluation metrics for the ResNet-50 baseline.
* **`Lee Re Xuan_24071969_P2_Report.pdf`**: The final comprehensive thesis detailing the methodology, training convergence, empirical classification results, and structural footprint analysis.

## Execution Requirements
The notebooks are designed to execute in a GPU-accelerated environment (e.g., Google Colab with an NVIDIA T4 GPU). To rerun the data ingestion pipeline, a valid Kaggle API key must be supplied in the first execution cell to securely download the 13,594-image dataset.
