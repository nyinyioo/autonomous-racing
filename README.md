# autonomous-racing 🚧

Autonomous driving stack for a 1/10-scale F1TENTH car (ROS 2, NVIDIA Jetson).

Note: C++ implementation of selected components, built with CMake, tested with GoogleTest, and CI on GitHub Actions. 

<br>

| Milestone | Description |
|---|---|
| 🤖 Object Detection | road sign detection, YOLOv8, PyTorch, TensorRT GPU acceleration |
| 📡 Camera–LiDAR Fusion | sensor fusion, depth–LiDAR ranging |
| 📷 Camera Perception | RealSense D435i, OpenCV track detection, lane following |
| 🏁 Gap Follow | follow the gap, disparity extender |
| 🧱 Wall Follow | wall following with PID control |
| 🛑 Safety | automatic emergency braking (AEB), time-to-collision (TTC) |