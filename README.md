# Face Recognition Using Eigenfaces

This project implements a face recognition system using the **Eigenfaces algorithm**, developed as part of a Linear Algebra course. The project applies key mathematical concepts such as **eigenvectors** and **eigenvalues** to solve the real-world problem of facial identification and verification.

## 📌 Features

- Implements face recognition using the **Eigenfaces** method
- Uses **Principal Component Analysis (PCA)** for dimensionality reduction
- Applies core **linear algebra** principles for feature extraction and matching
- Built with **Python** and **OpenCV** for image processing and facial detection
- Achieves a high recognition rate through extensive testing
- Collaborative development and refinement of algorithm accuracy

## 🧠 Algorithm Overview

1. Convert input face images into grayscale and resize them for consistency.
2. Flatten images and construct a dataset matrix.
3. Apply PCA to extract principal components (eigenfaces).
4. Project all face images into the eigenface space.
5. For a new input image, project it into the same space and compare with existing projections using Euclidean distance.

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **NumPy**
- **Matplotlib** (for visualizations)

## 📂 Project Structure

Face_Recog/ │ ├── dataset/ # Folder containing face image datasets ├── Face_Recog.ipynb # Main Jupyter Notebook for training and testing ├── utils/ # Utility functions (e.g., preprocessing, PCA) └── README.md # Project documentation


## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/face-recognition-eigenfaces.git
   cd face-recognition-eigenfaces

2. Imstall dependencies
   pip install opencv-python numpy matplotlib

3. Run the notebook: Open Face_Recog.ipynb in Jupyter Notebook or VS Code and run the cells step-by-step.

## 👤 Author

Purab Shingvi
