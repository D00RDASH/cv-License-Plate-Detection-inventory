# cv-License-Plate-Detection-inventory
# Team Member
Jeremy Okyere - W215244428@student.hccs.edu
# Project Tier
Tier 1: This project uses YOLOv8 for object detection, which is a well-established approach suitable for beginners. We're focusing on getting solid fundamentals right rather than implementing cutting-edge techniques. 
# 🎯 Problem Statement
Law enforcement officers spend hours manually reviewing footage to identify vehicles linked to crimes or terror-related activities.
# Solution Overview
I'm building an AI-based license-plate detection system capable of identifying and localizing plates from images and videos. The system will train and process images under one minute.
# 🔧 Technical Approach
CV Technique: Object Detection
Model: YOLOv8pt
# Dataset
Source: Kaggle
Size:
- Training: 304 images
- Validation: 44 images
- Test: 85 images
Link: https://www.kaggle.com/datasets/andrewmvd/car-plate-detection
# 🎯 Success Metrics
Primary Metric: mAP50 (mean Average Precision at 50% IoU)
Target: 90%+ detection accuracy
Secondary Metrics:
- Latency: <1 second per image (>10 FPS)
- False Positive rate: <5% error
