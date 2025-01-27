# Deep Learning from Scratch

This folder contains study materials for the **Convolutional Neural Networks (CNN)** phase of the RATEL AI Study Group. 

## 🛠️ Environment Setup

Follow these steps to set up your environment for the study:

### 1. Install Python and VSCode
- **Python:**
  
   - Download and install Python from the official site: [Python Downloads](https://www.python.org/downloads/)
   - *Recommended Version:* Python 3.8 or higher.
- **VSCode (Visual Studio Code):**
  
   - Download and install VSCode: [VSCode Downloads](https://code.visualstudio.com/)

### 2. Install Python Extension for VSCode
- Open VSCode.
- Go to **Extensions** (Ctrl+Shift+X).
- Search for **Python** and install the extension.

### 3. Install Git
- Download and install Git: [Git Downloads](https://git-scm.com/downloads)

### 4. Clone the Repository
1. Visit the repository for *Deep Learning from Scratch*: [GitHub Repository](https://github.com/kchcoo/WegraLee-deep-learning-from-scratch)
2. Copy the HTTPS URL:  
   `https://github.com/kchcoo/WegraLee-deep-learning-from-scratch.git`
3. Open VSCode, press **F1**, and type or select **Git: Clone**.
4. Paste the copied URL and press **Enter**.
5. Choose a location for cloning (e.g., Desktop).
6. The folder and files from the GitHub repository will be cloned to your system.

### 5. Library Installation

Open a terminal (Ctrl+') and install the required libraries:
```bash
pip install numpy
pip install matplotlib
```

## Hands-on Example: `hungry.py` (ch01)

You can run the example code provided in the book using the following methods:

### Method 1: Using the Run Button
- Open `hungry.py` in VSCode.
- Click the Run button (▶️) in the top-right corner.

### Method 2: Using the Terminal (Highly Recommended)
1. Open the terminal in VSCode.
2. Navigate to the ch01 folder:
```bash
cd ch01
```
3. Run the script:
```bash
python hungry.py
```
4. To return to the parent folder:
```bash
cd ..
```

### 💡 **Tips for Terminal Navigation**
- Use the **Tab** key to autocomplete file paths or commands.
- Press **Tab** multiple times to view available options.

### 📝 Testing Your Own Code
- Create a new Python file in the current folder.
- Ensure the file name does not conflict with existing files.
- Write and run your code following the methods above.

## 🛠️ Common Errors and Solutions

### 1. Chapter 1: `img_show.py`
- Issue: File path errors when loading images.
- Solution:
  - In the dataset folder, right-click the target file and select Copy Path.
  - Paste the path inside single quotes (`' '`) and add an `r` prefix to handle escape characters:

    ```python
    img_path = r'path_to_image'
    ```

### 2. Chapter 3: Errors in step_function.py
- Issue: Using deprecated NumPy data types.
- Solution:
   - Replace `np.int` with `int`:
     
     ```python
     y = int(x > 0)
     ```

---

📌 If you encounter any additional issues, feel free to ask for help. Happy Coding! 🚀
