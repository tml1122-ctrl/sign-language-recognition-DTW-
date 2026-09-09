# Sign Language Recognition

A prototype system for sign language recognition using MediaPipe,
hand landmark features, Dynamic Time Warping (DTW), and Gemini API.

## Pipeline

Video
→ MediaPipe Hand Landmark Extraction
→ 94D Feature Representation
→ DTW Sequence Matching
→ Symptom Recognition
→ Gemini-based Guidance

## Features

- MediaPipe hand landmark extraction
- 47D feature representation per hand
- 94D dual-hand representation
- DTW-based temporal sequence matching
- DTW alignment visualization
- Skeleton visualization
- Gemini API integration
- Gradio demo interface

## Status

Prototype / research project.

## Limitations

The current system uses a limited vocabulary and
database-dependent DTW matching. Continuous sign language,
sentence segmentation, and cross-user generalization remain
open challenges.