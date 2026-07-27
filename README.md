# 🚗 License Plate Recognition Using OCR

An Automatic License Plate Recognition (ALPR) system built using **Python**, **OpenCV**, and **Tesseract OCR**. This project detects a vehicle's license plate from an image and extracts the license number using Optical Character Recognition (OCR).

---

## 📌 Features

- Detects vehicle license plates from images.
- Extracts license plate text using Tesseract OCR.
- Image preprocessing for improved OCR accuracy.
- Easy to understand and beginner-friendly implementation.
- Works with static vehicle images.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Tesseract OCR
- Imutils
- NumPy
- Jupyter Notebook

---

## 📂 Project Structure

```
License-Plate-Recognition-Using-OCR/
│
├── OCR_code.ipynb          # Main Jupyter Notebook
├── images/                 # Sample vehicle images
├── output/                 # Output images (Optional)
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/License-Plate-Recognition-Using-OCR.git
```

### 2. Move into the project folder

```bash
cd License-Plate-Recognition-Using-OCR
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Install Tesseract OCR

Download Tesseract OCR from:

https://github.com/UB-Mannheim/tesseract/wiki

Update the Tesseract path in the notebook:

```python
pytesseract.pytesseract.tesseract_cmd = r'Your_Tesseract_Path'
```

Example:

```python
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```

---

## ▶️ How to Run

1. Open `OCR_code.ipynb`.
2. Update the image path.
3. Run all notebook cells.
4. The detected license plate and extracted text will be displayed.

---

## 📸 Sample Output

Input:
 <img width="335" height="262" alt="Screenshot 2026-07-27 164516" src="https://github.com/user-attachments/assets/814d004b-406d-4342-b18b-31651ccf7ead" />


Output:
<img width="332" height="265" alt="Screenshot 2026-07-27 204548" src="https://github.com/user-attachments/assets/f725379a-5956-4856-8121-c23ccf509432" />



Example:

```
Detected License Plate: MH12AB1234
```

---

## 📦 Requirements

```
opencv-python
pytesseract
imutils
numpy
jupyter
```

or install manually:

```bash
pip install opencv-python pytesseract imutils numpy
```

---

## 🚀 Future Improvements

- Real-time webcam detection
- Video license plate recognition
- Deep Learning-based plate detection (YOLO)
- Support for multiple vehicles
- Improved OCR accuracy

---

## 👩‍💻 Author

**Swati Jadhav**

