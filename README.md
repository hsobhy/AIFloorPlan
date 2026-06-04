# AIFloorPlan

**AIFloorPlan** is a Python-based system for detecting architectural elements from floor plan images using a YOLO object detection model. It preprocesses images, applies a trained YOLO model, and outputs labeled structural elements for analysis or further processing.
This project implements a multi-stage computer vision pipeline combining object detection, structural refinement, and OCR for floor plan understanding.

### Status
This is Version v0.2 (2026) of the AIFloorPlan system.   
The project will be updated with improved models, pipeline refinements, and expanded functionality.

---

## License & Commercial Use
This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. 

### Open Source Terms
You are free to use, modify, and distribute this software under the terms of the AGPL-3.0. **Important:** Any project or service (including cloud/web services) that uses this code must also be open-sourced under the same AGPL-3.0 license.

### Commercial Licensing
If you are a company or individual wishing to use this software in a commercial product, website, or service **without** the obligation to open-source your own proprietary code, you must purchase a **Commercial License**.

For licensing inquiries and pricing, please contact:
* **Name:** Haitham Sobhy
* **Email:** hsobhy at live dot com

---

## Project Overview

This project presents an AI-based Floor Plan understanding system that combines YOLO-based object detection, wall segmentation, and OCR-based text recognition.

The system is built using:
- YOLO for detecting structural components in floor plans
- Custom wall detection model for improving layout consistency
- EasyOCR for extracting textual information such as room labels

The final goal is to convert raw floor plan images into structured, machine-readable representations.

---

## Getting Started

### Requirements
```bash
pip install -r requirements.txt
```
---

## Code Structure

### AIFloorPlan-Yolo_v0.2.ipynb
Implements YOLO-based object detection for identifying floor plan components such as rooms, doors, and structural elements.

### AIFloorPlan-Wall_v0.2.ipynb
Focuses on wall detection and refinement to improve structural accuracy of detected layouts.

### AIFloorPlan-Easyocr_v0.1.ipynb
Uses EasyOCR to extract text labels from floor plan images (e.g., room names, annotations).

### /models
Contains trained YOLO models and custom weights used for inference and evaluation.

---

## Execution Order

Run notebooks in the following order:
1. AIFloorPlan-Yolo_v0.2.ipynb
2. AIFloorPlan-Wall_v0.2.ipynb
3. AIFloorPlan-Easyocr_v0.1.ipynb

## Models Folder
Contains trained YOLO weights and saved model checkpoints used for inference across different pipeline stages.

---

## Dataset and Models

This project uses a YOLO-based object detection model for floor plan analysis.

The YOLO model was trained using a floor plan dataset from Kaggle:
https://www.kaggle.com/datasets/asutoshprad/floor-plan-dataset

The object detection component is based on the YOLO framework:
https://github.com/ultralytics/ultralytics

OCR is implemented using EasyOCR:
https://github.com/JaidedAI/EasyOCR

---

## Contributors
The following people have contributed to the development of this project:

***Humber Polytechnic***
* **Hilary Bonnell** — Interior design team
* **Jordan Fang** — Interior design team
* **Haitham Sobhy** (@hsobhy) — AI Development team
* **Wai Yu Ho** (@Yukih20103) — AI Development team
* **Shiva Reddy Pinnapureddy** — AI Development team
* **Chengze Li** — AI Development team

---

### Contributor Agreement
By contributing to this repository, you agree that:
1. You grant the project owner a non-exclusive, perpetual, royalty-free license to use, modify, and redistribute your contribution.
2. The project owner reserves the right to license the project (including your contributions) under commercial terms to third parties.
3. Your name will remain in the Contributors list as credit for your work.

---

## 🚀 How to Cite
If you use this code in a project, research paper, or publication, please cite it as follows:

> AIFloorPlan v0.2 (2026).
> Humber Polytechnic AI & Interior Design Teams. [Source code] 
> GitHub repository: https://github.com/hsobhy/AIFloorPlan

