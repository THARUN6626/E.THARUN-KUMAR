# Real-Time Stampede Risk Detection through Motion Analytics

Timeline: July 2025 – November 2025

Overview

A production-oriented crowd monitoring system combining MobileNet-SSD for object detection, optical-flow motion analytics for spatio-temporal motion extraction, and a CNN–LSTM model for stampede risk prediction. Built and evaluated on large-scale video datasets; research accepted for publication (2025).

Repository

- https://github.com/THARUN6626/real-time-stampede-risk-detection

Key Features

- Real-time object detection & tracking (MobileNet-SSD)
- Optical flow to capture motion magnitude and direction
- CNN feature extractor + LSTM temporal model for risk scoring
- Lightweight pipeline tuned for CPU/GPU edge deployment

Installation & Run

1. Clone: `git clone https://github.com/THARUN6626/real-time-stampede-risk-detection`
2. Create env: `python -m venv venv && source venv/bin/activate`
3. Install: `pip install -r requirements.txt`
4. Run demo: `python run_inference.py --video sample.mp4`

Results & Paper

- Research paper accepted for a 2025 conference. Add PDF/slides to repo `docs/` when available.

Technologies

Python, TensorFlow, MobileNet-SSD, OpenCV, Optical Flow, CNN, LSTM, NumPy, Pandas
