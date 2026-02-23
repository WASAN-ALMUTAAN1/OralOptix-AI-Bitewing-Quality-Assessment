<p align="center">
  <img src="assets/looog.png" alt="OralOptix Banner" width="100%" />
</p>



<p align="center">
  <b>Intelligent Assessment of Intra-Oral Radiograph Quality</b><br/>
  AI-assisted quality assessment and reporting workflow for bitewing dental radiographs.
</p>

<p align="center">
  <img alt="Project Type" src="https://img.shields.io/badge/Project-Academic%20Graduation%20Project-0f172a">
  <img alt="Domain" src="https://img.shields.io/badge/Domain-Medical%20Imaging-1e3a8a">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-Bitewing%20Quality%20Assessment-2563eb">
  <img alt="Status" src="https://img.shields.io/badge/Status-Prototype%20%2F%20Research-0ea5e9">
  <img alt="License" src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey">
</p>

---

## Abstract

**OralOptix** is an academic AI project developed to support the **quality assessment of intra-oral dental radiographs**, with a primary focus on **bitewing images**. The project presents a prototype workflow that combines a structured user interface, AI-assisted analysis, and report-oriented output to support image quality review and reduce avoidable repeat imaging.

This repository is designed to document the project professionally for:
- academic review and graduation presentation,
- research and portfolio showcase,
- technical documentation and future extension.

---

## Clinical Motivation

In dental imaging workflows, radiograph quality directly affects diagnostic usability. Suboptimal image capture may lead to:
- non-diagnostic images,
- repeated radiation exposure,
- workflow delays,
- inconsistency in manual quality checking.

**OralOptix** addresses this by proposing an **AI-assisted quality assessment workflow** that helps classify image quality and generate structured feedback in a report-style interface.

---

## Important Notice

> **This repository contains prototype interfaces, academic materials, and demonstration outputs.**  
> **All patient names, IDs, and report fields shown in screenshots are demo/test content only (not real patient data).**

This repository is shared for **academic, educational, and portfolio purposes** only.

---

## Project Scope

The current repository documents the **academic/prototype version** of OralOptix and includes:
- project report,
- presentation materials,
- interface screenshots,
- documentation and governance notes,
- demo/prototype assets.

This public repository does **not** include the private training dataset or deployable production code.

---

## Target Users and Audience

### Primary Academic / Technical Audience
- Researchers in medical imaging AI
- Computer vision and deep learning students
- Graduation project reviewers and examiners
- Supervisors and academic committees

### Clinical / Domain Audience
- Dental clinicians (concept review / workflow understanding)
- Dental interns and students (educational demonstration)
- Healthcare technology stakeholders (prototype evaluation)

---

## System Overview

OralOptix is conceptually organized as a workflow-driven system for radiograph quality review:

### Workflow Summary
1. **Upload radiograph image** (bitewing)
2. **Select or add patient information**
3. **Enter technical imaging parameters**
4. **Run AI-assisted quality analysis**
5. **Generate structured report output**

### Main Functional Components
- **Authentication interface** (prototype UI)
- **Patient management module**
- **Image upload and technical settings form**
- **AI-assisted quality assessment dashboard**
- **Report-oriented output view (PDF-style)**

---

## Key Features

### 1) Multi-Step Clinical Workflow
A structured workflow guides users through the radiograph quality assessment process in a consistent sequence:
- patient selection,
- image upload,
- imaging settings entry,
- analysis and output generation.

### 2) Patient Management Interface (Prototype)
The prototype includes a patient management page supporting:
- patient list display,
- search and filtering,
- add/edit record actions,
- interface-level record organization.

### 3) AI-Assisted Report Output
The generated report-oriented output includes:
- patient metadata (demo),
- radiograph quality classification,
- imaging parameter summary,
- AI-assisted recommendations / corrective guidance.

### 4) Documentation-Ready Visual Workflow
The project includes polished UI screenshots and assets suitable for:
- thesis/project documentation,
- presentations,
- research demonstrations,
- portfolio use.

---

## Problem and Solution

<p align="center">
  <img src="assets/problem-solution-diagram.png" alt="Problem-Solution Diagram" width="80%" />
</p>

**Problem addressed:**  
Manual quality checking of dental radiographs can be inconsistent and time-consuming, and repeated imaging may increase unnecessary radiation exposure.

**OralOptix approach:**  
Provide an AI-assisted workflow to help classify radiograph quality and suggest corrective actions in a structured, report-oriented interface.

---

## AI / Research Context

OralOptix was developed as an AI-focused academic project in **medical imaging quality assessment**.  
The project investigates model-based assessment of bitewing radiograph quality and compares multiple deep learning architectures for classification performance.

### Research Orientation
- Medical imaging AI
- Dental radiograph quality assessment
- Deep learning model comparison
- Clinical workflow support (prototype-level)
- Explainable / structured reporting direction (future work)

---

## Model Performance Summary

The project evaluated multiple deep learning models for the classification task.

### Reported Performance (Project Results)

| Model | Accuracy | Precision | Recall | F1 Score |
|------|----------:|----------:|-------:|---------:|
| MobileNetV3 Small | 97.26% | 97.28% | 97.26% | 97.21% |
| **EfficientNetB0** | **98.63%** | **98.83%** | **98.63%** | **98.63%** |
| Vision Transformer (ViT) | 84.93% | 92.67% | 84.93% | 87.09% |
| EfficientNet + ViT Hybrid | 82.19% | 67.55% | 82.19% | 74.16% |
| MobileNetV3 + ViT Hybrid | 82.19% | 67.55% | 82.19% | 74.16% |
| Custom ViT-style | 89.04% | 93.07% | 89.04% | 90.09% |

### Key Observation
Among the evaluated models, **EfficientNetB0** achieved the strongest overall performance in this project’s experiments.

> Full experimental details, hyperparameters, and discussion are available in the report and presentation materials in this repository.

---

## Technical Stack and Tools

The OralOptix project (overall development and experimentation) involved tools and technologies commonly used across:
- AI model development,
- backend integration,
- frontend prototype interface,
- academic documentation and reporting.

### AI / Model Development
- **Python**
- **TensorFlow / Keras**
- **Deep Learning (CNN / ViT-based models)**
- **Google Colab** (training / experimentation)

### Backend / Integration (Project Prototype)
- **Flask** (AI backend integration workflow)

### Frontend / Interface (Prototype)
- **PHP** (multi-step interface / web pages)
- **HTML / CSS / JavaScript**
- **MySQL / phpMyAdmin** (project-side data organization)

### Documentation / Presentation
- **GitHub** (project documentation and portfolio)
- **PDF reports and slides**
- **Presentation assets / screenshots**

---

## Repository Structure

```bash
OralOptix-AI-Bitewing-Quality-Assessment/
│
├── assets/                 # UI screenshots, logo, poster, and visual assets
├── demo/                   # Demo materials / walkthrough references
├── docs/                   # Project documentation (summary, methodology, results, limitations)
├── paper/                  # Paper / manuscript folder (reserved for future academic version)
├── presentation/           # Presentation slides and presentation resources
├── report/                 # Final graduation project report PDF
├── data-governance/        # Privacy, ethics, and dataset governance notes
│
├── README.md               # Project overview and documentation
├── LICENSE                 # Project license (CC BY-NC 4.0)
└── CITATION.cff            # Citation metadata for academic referencing
