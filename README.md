#YOLOv8 Object Detection: Humans & More 🚀

This repository showcases real-time object detection using YOLOv8 by Ultralytics. The model is capable of identifying humans and a wide range of objects from the COCO dataset in videos and images. Additionally, this project includes a comparative analysis of different YOLOv8 models to evaluate speed vs. accuracy.


**🌟 Features**
✅ Human Detection – Identify people in various environments (office, streets, low-light scenarios).
✅ Multi-Object Detection – Recognizes objects like cars, laptops, and more using COCO IDs.
✅ YOLOv8 Model Comparison – Benchmarking nano, small, medium, large, and extra-large YOLOv8 models.
✅ Video Processing – Detect objects in real-time across different videos.

**🔧 Installation**
Install dependencies with:

![image](https://github.com/user-attachments/assets/5ed2d32b-6e23-4810-87f9-1b58c6c00ddd)


**📊 Results**
- Here are sample videos demonstrating YOLOv8 in action:
   **1/🏃 People Walking**
📌 Video:
![image](https://github.com/user-attachments/assets/daba09a3-e0cc-48d3-80f0-297342764827)
🔹YOLOv8 detects humans in a daytime street scene. This showcases real-time pedestrian detection in motion.

🌙 People Walking at Night
📌 Video:- [📹 Watch: People Walking]([https://drive.google.com/file/d/YOUR_FILE_ID/view?usp=sharing](https://drive.google.com/file/d/1aIdP2E8xUoUg5sTSVRNlSnaL8__ogPRz/view?usp=sharing))

![image](https://github.com/user-attachments/assets/5f236f77-13fc-4218-afb8-b1b45bf34a62)

🔹YOLOv8 is tested in low-light conditions. The model effectively recognizes human figures despite dim lighting.

🏢 Office Environment Detection

📌 Video : https://github.com/user-attachments/assets/16b534c0-c956-4f26-8063-57ad4fbb8962

🔹Detecting people and objects( laptop ) in an indoor office setting. This highlights YOLOv8’s ability to recognize humans, laptops, chairs, and more in a workplace.

![image](https://github.com/user-attachments/assets/b7e280f7-3c30-49bf-8a6b-eee31fab7f78)
![image](https://github.com/user-attachments/assets/ac141cd1-408c-43ef-865e-f5b43b62fc49)


**Comparison: YOLOv8n vs YOLOv8s**
📌 Video: https://github.com/user-attachments/assets/af969a51-96f7-4e02-bba8-6f58fcb13864

🔹Side-by-side comparison of YOLOv8n (nano) and YOLOv8s (small) to visualize speed vs. accuracy trade-offs.
![image](https://github.com/user-attachments/assets/8738de52-8507-450b-aca6-e7c1b428ae5e)

🔹 Observations
🟢 YOLOv8n (Nano)
- Speed: Extremely fast (low-latency, real-time performance).
- Accuracy:  Misses some smaller or partially hidden objects.
- Use Case: Ideal for edge devices and real-time applications where speed matters more than accuracy.
🟢 YOLOv8s (Small)
- Speed: Still fast but slightly slower than YOLOv8n.
- Accuracy:  Better at detecting small objects and overlapping instances.
- Use Case: A balanced option for real-time object detection where both speed and accuracy are important.



**Comparison: YOLOv8m vs YOLOv8l vs YOLOv8x**
📌 Video: https://github.com/user-attachments/assets/09bf5bc6-c3f7-49df-b3db-03c8b1a21ff2
🔹  benchmark test comparing YOLOv8m (medium), YOLOv8l (large), and YOLOv8x (extra-large) to analyze the impact of model size on detection accuracy and processing speed.
🔹 Observations
🟢 YOLOv8m (Medium)
- Speed: 🏎 Faster than YOLOv8l and YOLOv8x but slower than YOLOv8s.
- Accuracy: ✅ Good balance, handles complex scenes better than YOLOv8s.
- Use Case: Suitable for medium-power GPUs where you need higher accuracy without extreme computational cost.
🟢 YOLOv8l (Large)
- Speed: Slower but still practical for powerful hardware.
- Accuracy: Excellent detection, significantly better than YOLOv8m.
- Use Case: Great for detailed object recognition, useful in surveillance, medical imaging, or autonomous vehicles.
🟢 YOLOv8x (Extra-Large)
- Speed: Slowest of all, requiring high-end GPUs.
- Accuracy: The most precise model, detecting even the smallest and hardest-to-see objects.
- Use Case: Best suited for applications where detection accuracy is critical (e.g., medical AI, security surveillance, autonomous driving).










