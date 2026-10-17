# ChestAI Radiology

AI-powered Chest X-ray analysis Android app for **educational and research purposes only**.

> ⚠️ **Medical Disclaimer:** This app is NOT a medical device and must NOT be used for clinical diagnosis or treatment decisions. Outputs are for learning and research. Always rely on a qualified radiologist/physician.

## Overview
ChestAI lets students and researchers load a chest radiograph and view an AI-generated analysis of common findings (e.g., consolidation, effusion, pneumothorax, cardiomegaly), helping build image-interpretation skills.

## Features
- Import chest X-ray images (gallery / camera)
- On-device AI inference (TensorFlow Lite)
- Probability scores per finding
- Educational notes for each finding
- Works offline

## Tech Stack
- Android (Kotlin)
- TensorFlow Lite
- Material Design

## Getting Started
1. Clone the repo:
   `git clone https://github.com/hemazoo/chestai-radiology.git`
2. Open in Android Studio (latest stable).
3. Sync Gradle, then run on a device or emulator (Android 8.0+).

## Project Status
🚧 In development.

## Data & Privacy
No real patient data is included in this repository. Use only de-identified, publicly available datasets and follow the dataset license terms.

## Limitations
- Model performance has not been clinically validated.
- Results may be inaccurate, especially on images unlike the training data.

## License
MIT License

## Author
Hema — Radiology student, graduation research project.
