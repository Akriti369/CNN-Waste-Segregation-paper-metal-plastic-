♻️ Waste Classification of Plastic, Paper and Metal Using CNN Fine Tuning
Deep Learning Engine using EfficientNetB0 with CNN Fine Tuning — 97% Accuracy

Python 3.10+ TensorFlow 2.12 Flask EfficientNetB0

🌟 Project Overview
This project presents a state-of-the-art waste classification system that identifies Metal, Paper, and Plastic waste using CNN Fine Tuning with the EfficientNetB0 architecture, achieving an impressive 97% validation accuracy.

✨ Highlights
Premium Dark-Mode UI: A modern, glassmorphism-inspired web interface built with Flask and Vanilla CSS/JS.
EfficientNetB0 Power: High-accuracy classification with low computational overhead, optimized for cloud deployment.
Real-Time Analysis: Instant results with confidence scoring and recycling tips.
Production-Ready: Fully configured for deployment on Render.com with memory-optimized startup logic.
🚀 Experience the UI
The new web interface features:

🎯 Drag & Drop image uploads.
📊 Animated Confidence Bars showing the top 3 predictions.
💡 Smart Recycling Tips based on the identified material.
📱 Fully Responsive design for mobile and desktop presentation.
🛠️ Technical Implementation
Model Architecture
The engine utilizes EfficientNetB0, which uses a compound scaling method to balance network depth and width.

Training Strategy: Two-phase approach (Frozen Feature Extraction + Fine-Tuning).
Optimization: Adam optimizer with ReduceLROnPlateau and EarlyStopping callbacks.
Accuracy: ~96% on the verified dataset.
Deployment Stack
Backend: Flask (Python)
Production Server: Gunicorn (Optimized with 1 worker/4 threads for Render Free Tier)
Environment: tensorflow-cpu to fit within 512MB RAM limits.
