# 🧼 Denoise an Image using Median Blur in Python with OpenCV

This project demonstrates how to add salt-and-pepper noise to an image and remove it using **Median Blur**, implemented in **Python** using **OpenCV**.

---

## 📸 Output Overview

The program:
1. Loads a colored image using OpenCV
2. Adds salt-and-pepper noise to the image
3. Applies **median blur** to denoise the image
4. Displays the **original**, **noisy**, and **denoised** images side-by-side using `matplotlib`

---

## 🛠 Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

Install required packages:
```bash
pip install opencv-python numpy matplotlib

Replace the image path in the code:
```bash
img = cv2.imread(r'C:\\path\\to\\your\\image.jpg')

Run the script:
```bash
python denoise_image.py
