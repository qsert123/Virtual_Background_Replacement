# Virtual_Background_Replacement
This project replaces the real-time video background using OpenCV. It detects the person and overlays a custom background, similar to Zoom or Teams.

## 📁 Files

- `virtual_background.ipynb`: The main Jupyter Notebook containing the code and explanation.
- `images/`: Folder with sample output screenshots showing background replacement.

## 🎯 Features

- Real-time background segmentation
- Background replacement using a static image or blur effect
- Adjustable threshold for segmentation accuracy
- Built with OpenCV

## 🛠️ Requirements

- Python 3.13.3
- OpenCV (`cv2`)
- cvzone
- NumPy
- import os
- queue
- tkinter

## 🚀 How to Use
- Clone the repository
- Run the Jupyter Notebook: virtual_background.ipynb
- Allow camera access if running locally
- Choose your background mode

## 🔒 Note
The camera must be connected and accessible for real-time execution. Static background images should be placed in the project folder or specified with a full path.


Install dependencies with:

```bash
pip install opencv-python numpy cvzone tkinter


