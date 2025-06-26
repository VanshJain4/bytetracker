# 🎯 People Detection & Tracking using YOLOv8 + ByteTrack

This repository showcases an experimental pipeline I explored to understand the integration of **YOLOv8 object detection** and **ByteTrack multi-object tracking**. It was a foundational step before developing a more robust and production-ready system.

---

## 🚀 Overview

This project focuses on detecting and tracking people in videos using:

- **YOLOv8** (Ultralytics) — for real-time object detection
- **ByteTrack** — for associating detections across video frames to generate unique identities

---

## 📋 Project Highlights

- ✅ Detects only the **person** class from videos
- ✅ Draws bounding boxes with class names and confidence scores
- ✅ Saves detections in a ByteTrack-compatible format
- ✅ Tracks people across frames with unique IDs
- ✅ Exports annotated videos and tracking logs

---

## 📂 Outputs

- `output_people_detected.mp4` — video with YOLOv8 detection only  
- `output_tracked.mp4` — video with YOLO + ByteTrack tracking  
- `bytetrack_results.txt` — tracking results in MOT format  
- `yolo_dets/video.txt` — raw detection data for tracking input  

---

## 🔧 Environment

- Developed and tested in **Google Colab**
- Uses open-source models and tracking algorithms
- Includes setup for handling compatibility issues with NumPy and dependencies

---

## 📌 Note

This was an early-stage **exploratory attempt** to prototype people tracking from videos. The goal was to better understand the workings of object detection and tracking frameworks before moving on to a more advanced implementation.

---

## 🤝 Acknowledgements

- [Ultralytics](https://github.com/ultralytics/ultralytics) — YOLOv8
- [ByteTrack](https://github.com/ifzhang/ByteTrack) — Multi-object tracking

