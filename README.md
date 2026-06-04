# AIFloorPlan

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

**AIFloorPlan** is a Python-based system for detecting architectural elements from floor plan images using a YOLO object detection model. It preprocesses images, applies a trained YOLO model, and outputs labeled structural elements for analysis or further processing.

## Features
- YOLO-based object detection for floor plan components  
- Pretrained model for room/class boundary recognition  
- Dataset integration and preprocessing tools  
- Deployment pipeline for inference and visualization  

## Getting Started

### Requirements
```bash
pip install -r requirements.txt

---

## Model and Dataset

This project uses a YOLO-based object detection model for floor plan analysis.

The dataset used for training is the Floor Plan Dataset available on Kaggle:
https://www.kaggle.com/datasets/asutoshprad/floor-plan-dataset

The model is based on YOLOv8 from Ultralytics:
https://github.com/ultralytics/ultralytics

Training scripts, preprocessing steps, and inference pipeline are included in this repository.

---

## Contributors
The following people have contributed to the development of this project:

***Humber Polytechnic***
* **Hilary Bonnell** — Interior design team
* **Jordan Fang** — Interior design team
* **Haitham Sobhy** (@hsobhy) — AI Development team
* **Wai Yu Ho** (@Yukih20103) — AI Development team
* **Shiva Reddy Pinnapureddy** — AI Development team

---

### Contributor Agreement
By contributing to this repository, you agree that:
1. You grant the project owner a non-exclusive, perpetual, royalty-free license to use, modify, and redistribute your contribution.
2. The project owner reserves the right to license the project (including your contributions) under commercial terms to third parties.
3. Your name will remain in the Contributors list as credit for your work.

---

## 🚀 How to Cite
If you use this code in a project, research paper, or publication, please cite it as follows:

> Sobhy, H., Ho, W. Y., & Pinnapureddy, S. R. (2026). AIFloorPlan [Source code]. GitHub. https://github.com/hsobhy/AIFloorPlan

