# -Ultralytics_YOLO

**YOLO** (You Only Look Once) is a popular real-time object detection algorithm used in Computer Vision.

Unlike traditional approaches that detect objects in multiple stages, YOLO analyzes an image in a single forward pass through a deep learning model. This makes it fast and suitable for real-time applications.

**For example**, YOLO can identify:

Person
Car
Motorcycle
Dog
Mobile phone
Helmet
Fire
Face
Custom objects

YOLO projects are used when we need to detect and locate objects in images or videos quickly and accurately.

**YOLO Framework**

Modern YOLO projects commonly use implementations such as:

YOLOv5
YOLOv8
YOLO11 / newer Ultralytics variants, depending on project requirements

**The framework performs:**

Object Classification
+
Bounding Box Prediction
+
Confidence Prediction

**Typical YOLO Project Architecture**

A complete YOLO project generally follows this architecture:
                    ┌─────────────────┐
                    │  Input Data     │
                    │ Image / Video   │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │ Data Processing │
                    │ OpenCV / NumPy  │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   YOLO Model    │
                    │ Object Detection│
                    └────────┬────────┘
                             │
                             ▼
                 ┌─────────────────────┐
                 │ Prediction Results  │
                 │ Class + Confidence  │
                 │ Bounding Box        │
                 └──────────┬──────────┘
                            │
                            ▼
                ┌──────────────────────┐
                │ Application Layer    │
                │ Streamlit / FastAPI  │
                └──────────────────────┘

**Important Concepts to Explain in an Interview**

If you build a YOLO project, you should be able to explain these concepts:

Object Detection

Identifying what object is present and where it is located.

Bounding Box

A rectangle around the detected object.

Confidence Score

Probability that the prediction is correct.
