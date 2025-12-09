# Fashion-Image-Generation-using-GAN
# Fashion Image Generator - Setup & Usage Guide

## Preparation

### 1. Python Version

Ensure you are using **Python 3.10.10**.

### 2. Required Python Packages

Install the following packages for Python 3:

* OpenCV
* Flask
* numpy
* pandas
* sklearn
* torch
* torchvision
* torchaudio
* matplotlib
* seaborn
* PIL

You can install them using:

```bash
pip install opencv-python flask numpy pandas scikit-learn torch torchvision torchaudio matplotlib seaborn pillow
```

### 3. Dataset Setup

1. Download the **Fashion MNIST Dataset** (CSV format).
2. Rename the files:

   * `fashion-mnist_train.csv` → `train.csv`
   * `fashion-mnist_test.csv` → `test.csv`
3. Create a folder named `fashion-mnist` inside this project directory.
4. Place both CSV files inside the `fashion-mnist` folder.

---

## Running the Fashion Clothing Image Generator

1. Make sure all required packages listed above are installed.
2. Open your terminal and **navigate to the project folder**:

```bash
cd your-folder-name
```

3. Run the program:

```bash
python3 Fashion_Image_Generator.py
```

4. After running, your terminal should display:

```
Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

5. Open your browser and visit:

```
http://127.0.0.1:5000/
```

6. Follow the instructions on the webpage (Step 1, Step 2).
7. When done, press **CTRL + C** in the terminal to stop the server.

---

## Notes

* Ensure dataset files are correctly placed.
* Install dependencies before running the program.
* Use the localhost link to interact with the generator UI.

This README is ready to be added to your GitHub repository.
