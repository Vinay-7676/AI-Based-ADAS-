# AI-Based ADAS Prototype 🚗

## Project Overview
The AI-Based Advanced Driver Assistance System (ADAS) is a prototype designed to enhance road safety using Artificial Intelligence, Machine Learning, and Computer Vision techniques. The system processes video input to identify and detect objects on the road, helping demonstrate intelligent driver assistance capabilities.

## Objectives
- Develop an AI-based driver assistance prototype.
- Detect and identify objects from video input.
- Apply computer vision techniques for road-scene analysis.
- Demonstrate how AI can contribute to safer driving.

## Flow Chart

                 ┌───────────────┐
                 │     START     │
                 └───────┬───────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Input Driving    │
              │       Video        │
              └─────────┬───────────┘
                        │
                        ▼
              ┌─────────────────────┐
              │ Load Python         │
              │ Libraries           │
              └─────────┬───────────┘
                        │
                        ▼
              ┌─────────────────────┐
              │ Initialize AI       │
              │ Detection Model     │
              └─────────┬───────────┘
                        │
                        ▼
              ┌─────────────────────┐
              │ Read Video Frames   │
              └─────────┬───────────┘
                        │
                        ▼
              ┌─────────────────────┐
              │ Preprocess Frames   │
              └─────────┬───────────┘
                        │
                        ▼
              ┌─────────────────────┐
              │ AI-Based Object     │
              │ Detection           │
              └─────────┬───────────┘
                        │
                        ▼
               ┌──────────────────┐
               │ Objects Detected?│
               └──────┬─────┬─────┘
                    Yes     No
                     │       │
                     ▼       ▼
          ┌──────────────┐  ┌──────────────┐
          │ Identify and │  │ Continue     │
          │ Classify     │  │ Processing   │
          │ Objects      │  └──────┬───────┘
          └──────┬───────┘         │
                 │                │
                 ▼                │
          ┌──────────────┐        │
          │ Draw Bounding│        │
          │ Boxes & Labels│       │
          └──────┬───────┘        │
                 │                │
                 └───────┬────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Generate Processed  │
              │ Frame               │
              └─────────┬───────────┘
                        │
                        ▼
               ┌─────────────────┐
               │ More Frames?    │
               └──────┬─────┬────┘
                    Yes     No
                     │       │
                     │       ▼
                     │  ┌─────────────────┐
                     │  │ Generate Output │
                     │  │ Video           │
                     │  └────────┬────────┘
                     │           │
                     │           ▼
                     │  ┌─────────────────┐
                     │  │ Display and Save│
                     │  │ Results         │
                     │  └────────┬────────┘
                     │           │
                     │           ▼
                     │  ┌─────────────────┐
                     │  │      END        │
                     │  └─────────────────┘
                     │
                     └──────► Read Video
                              Frames

## Technologies Used
- Python
- Machine Learning
- Computer Vision
- OpenCV
- Google Colab

## Project Demo
The output video demonstrates the working of the proposed ADAS prototype.

## Future Scope
- Real-time object detection using a camera.
- Lane detection and lane departure warnings.
- Vehicle and pedestrian detection.
- Collision warning and driver assistance features.
- Integration with embedded automotive systems.

## Conclusion
This project demonstrates the potential of AI and computer vision in developing intelligent driver assistance systems and improving vehicle safety.

**Project Type:** Machine Learning / Intelligent Mobility
