# Project Summary

## Overview
OralOptix is an AI-based system developed to automatically assess the quality of bitewing radiographic images used in dental diagnostics. The system classifies the uploaded bitewing image into one of three diagnostic quality categories:

- **0** = Non-diagnostic  
- **1** = Diagnostic with issues  
- **2** = Ideal for diagnosis  

In addition to diagnostic status classification, OralOptix predicts multiple quality-related attributes (errors), helping identify specific issues in the image.

## Motivation
The project addresses challenges in manual bitewing radiograph assessment, which can be time-consuming, inconsistent, and dependent on expertise. Poor-quality images may lead to retakes, delayed diagnosis, and unnecessary radiation exposure.

## Proposed Solution
When an image is uploaded to the OralOptix website, it undergoes preprocessing. A classification model evaluates the image and determines whether it is diagnostic, non-diagnostic, or diagnostic with issues. The system then outputs specific quality-related attributes (errors) and displays the analysis results on the website.

OralOptix is designed to support:
- Better clinical evaluation
- Improved workflow efficiency
- Reduced retakes
- Reduced patient radiation exposure

## Aim
To develop an AI system that automatically evaluates the diagnostic quality of bitewing radiographs and streamlines dental workflows, minimizing the risk of errors and improving diagnostic efficiency.

## Objectives
1. Gather a comprehensive dataset of bitewing X-ray images for the project.  
2. Develop a reliable AI model to distinguish between diagnostic, non-diagnostic, and diagnostic-with-issues bitewing radiographs.  
3. Identify and classify common radiographic errors (quality-related attributes).  
4. Develop a user-friendly website interface that clearly displays results for dental professionals.

## Scope
The scope of OralOptix focuses specifically on **bitewing intraoral radiographs**, which are essential for detecting interproximal caries and monitoring bone health.