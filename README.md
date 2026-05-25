This program do basic operation to an image such as blur,grayscale,edges,original

# OpenCV Image Processing Basics

This script performs basic image processing operations using OpenCV in Python. It loads an image and simultaneously displays the original version alongside grayscale, blurred, and edge-detected outputs.

---

## Instructions & Requirements

### 1. Python Installation
You need to install the latest version of Python. Download it from the official Python website:
https://www.python.org

During installation on Windows, make sure to check the box that says "Add Python to PATH" so you can run Python commands from your command prompt.

### 2. Install Required Libraries
This script requires the OpenCV and NumPy libraries. Open your Python IDE terminal, command prompt, or powershell and run:

```cmd
pip install opencv-python numpy

```

If you get an error saying "pip is not recognized", you can fix that easily by typing:

```cmd
python -m pip install opencv-python numpy

```

---

## Setup & Execution

1. Download the `main.py` script from this repository.
2. Place the image you want to process in the exact same folder as your script and rename it to `image.png` (or update the filename inside the `cv2.imread()` line in the code).

### Ways to Run / Execute the Script

#### Method 1: From the CLI (Command Prompt / PowerShell / Python IDE Terminal)

1. Open your command prompt, powershell, or IDE terminal.
2. Navigate to the folder where you saved the script using the `cd` command:
```cmd
cd path/to/your/folder

```


3. Run the script by typing:
```cmd
python main.py

```



#### Method 2: From Python IDLE

1. Open the file in Python IDLE.
2. Click on the "Run" tab in the top menu.
3. Select "Run Module" (or simply press F5 on your keyboard).

---

## How It Works

Once running, the script applies the following modifications and opens four separate windows:

* **Original:** The source color image.
* **Grayscale:** Converts the image from BGR color to single-channel gray.
* **Blur:** Applies a Gaussian blur filter to smooth out details.
* **Edges:** Uses Canny edge detection to highlight structural boundaries.

To close all display windows and exit the program, simply click on any image window and press any key on your keyboard.

```

```
