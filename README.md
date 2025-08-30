# Automated Sudoku Solver

## Overview
This project is an **Automated Sudoku Solver** built using **Python, OpenCV, OCR (Tesseract), and Backtracking algorithms** inside a Jupyter Notebook.  
It can:
- Extract Sudoku puzzles from images using **image processing**.
- Recognize digits with **OCR** and a CNN classifier.
- Solve puzzles efficiently using a **backtracking algorithm**.
- Display the solved Sudoku grid.

## Features
- Input Sudoku as an **image file**.
- Uses **OpenCV** for contour detection & grid extraction.
- Recognizes numbers with **Tesseract OCR**.
- Solves puzzles using **Backtracking**.
- Runs directly in a Jupyter Notebook (`.ipynb`).

## Tech Stack
- **Python 3.8+**
- **Jupyter Notebook**
- **OpenCV** – Image processing
- **Tesseract OCR** – Digit recognition
- **TensorFlow/Keras** – Digit classification
- **Backtracking Algorithm** – Puzzle solving

## Installation

1. **Clone the repository**
     
   git clone https://github.com/your-username/sudoku-solver.git
   cd sudoku-solver
 

2. **Create a virtual environment (optional but recommended)**

     
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
    

3. **Install required libraries**

     
   pip install opencv-python pytesseract tensorflow matplotlib numpy
    

4. **Install Jupyter Notebook**

     
   pip install notebook
    

5. **Install Tesseract OCR**

   * **Windows**: Download from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).
   * **Linux**:

       
     sudo apt-get install tesseract-ocr
      
   * **Mac (Homebrew)**:

       
     brew install tesseract
      

## Usage

1. Start Jupyter Notebook:

     
   jupyter notebook
    

2. Open the notebook file:

    
   sudoku_solver.ipynb
    

3. Run all cells in order:

   * Upload/point to a Sudoku image.
   * The notebook will extract the grid, recognize digits, and solve the puzzle.
   * The solved Sudoku will be displayed.

## Results

* \~99% digit recognition accuracy using CNN.
* Works across **Easy → Very Hard** Sudoku levels.
* Handles variations in image clarity and angle.

## Future Scope

* Real-time solving via webcam.
* Support for handwritten Sudoku puzzles.
* Web or mobile deployment.

## Authors

* Geshna B
* Neha R Menon
* Malavika S Prasad
* Dhruv AP
* Nandu Manoj

**Supervised by:** Dr. Kritesh Kumar Gupta, Assistant Professor, Department of AI, Amrita Vishwa Vidyapeetham
