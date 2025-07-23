# Weapon Detection using YOLOv5
This project implements a two-stage real-time weapon detection system using YOLOv5 models. It utilizes computer vision and deep learning techniques to identify weapons in video streams or camera feeds.

🔍 Overview
- The code leverages PyTorch and OpenCV to:

- Load YOLOv5 models (likely two versions: a lightweight and a larger one)

- Process video input (live or file-based)

- Detect and possibly classify weapons in real-time

Note: The notebook does not include a markdown introduction, so this summary is inferred from the code content.

🧠 Technologies Used
Python

PyTorch

OpenCV

YOLOv5 (likely YOLOv5n and YOLOv5l or similar variants)

🗂 Notebook Structure
Total Code Cells: 6

Total Lines of Code: 511

Sample Code Snippet
python
Copy
Edit
import torch
import cv2
import time

# Load models
📁 How to Use
Clone the repository or download the .ipynb file.

Ensure Python and dependencies like torch and opencv-python are installed.

Run the Jupyter Notebook in a compatible environment (e.g., Jupyter Lab or VS Code).

Adjust paths to models or video sources as needed.

✅ Requirements
Python 3.8+

torch

torchvision

opencv-python

matplotlib (optional, for visualization)

🚀 Future Improvements
Add markdown documentation within the notebook.

Include a requirements.txt or setup script.

Provide a sample video or image dataset.


