# Dataset Validation — MBDD2025

## Status
Initial metadata validation completed. Annotation-level validation is pending.

## Source
- Dataset: MBDD2025: A Deep Learning-Oriented Dataset for Diverse Building Defect Detection from UAV Images
- URL: https://zenodo.org/records/15622584
- Publication date: 2025-06-09
- License reported by Zenodo API: CC BY 4.0
- Archive: MBDD2025.zip
- Reported archive size: 2,533,687,033 bytes (~2.53 GB)

## Environment
- Google Colab
- NVIDIA Tesla T4 GPU detected
- Dataset inspection and training will use Colab to avoid consuming local disk space.

## Initial findings
The dataset is described as covering diverse structural types and defect categories.
The published annotation formats include Pascal VOC XML and YOLO labels.

## Open questions
1. What exact defect classes occur in the annotations?
2. Are structural/material labels explicitly available per image?
3. Are the XML and YOLO annotations consistent?
4. What train/validation/test split is appropriate?

## Current decision
1) Do not begin training until the annotation schema and target labels have been verified.
2) Do not infer or manufacture material labels from defect annotations.