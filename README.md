# Small Python Project Documentation

## Project Setup

To set up the project, follow these steps:

### Step 1: Create a Virtual Environment

1. Open your terminal or command prompt.
2. Create a virtual environment using the following command:
   ```bash
   python -m venv env
   ```
3. Activate the virtual environment:
   - On **Windows**:
     ```bash
     .\env\Scripts\activate
     ```
   - On **macOS/Linux**:
     ```bash
     source env/bin/activate
     ```

### Step 2: Install Required Packages

1. Make sure you are in the project directory where the `requirements.txt` file is located.
2. Install all dependencies from the `requirements.txt` file using the following command:
   ```bash
   pip install -r requirements.txt
   ```

---

## Package Descriptions

Below is an explanation of the packages used in this project and their roles:

### 1. **Boltons (v24.1.0)**
   - **Purpose**: Provides a set of utilities and helper functions that extend the functionality of the Python standard library.
   - **Usage in Project**: Used for common operations like managing data structures, iterators, and string manipulation.

### 2. **Face (v24.0.0)**
   - **Purpose**: Simplifies the creation of command-line interfaces (CLI).
   - **Usage in Project**: Used to design and handle the command-line interface for running the project efficiently.

### 3. **NumPy (v2.2.1)**
   - **Purpose**: A library for numerical computing in Python, providing support for arrays, matrices, and mathematical functions.
   - **Usage in Project**: Used for data manipulation, numerical computations, and handling image-related data arrays.

### 4. **OpenCV-Contrib-Python (v4.10.0.84)**
   - **Purpose**: An extended version of OpenCV with additional modules for computer vision tasks.
   - **Usage in Project**: Used for advanced image processing, including face detection, object recognition, and custom feature extraction.

### 5. **OpenCV-Python (v4.10.0.84)**
   - **Purpose**: A Python binding for OpenCV, a library for real-time computer vision and image processing.
   - **Usage in Project**: Used for core image processing tasks, such as reading, writing, and transforming images.

### 6. **Pillow (v11.0.0)**
   - **Purpose**: A Python Imaging Library (PIL) fork for handling image files.
   - **Usage in Project**: Used to read, write, and manipulate image files in various formats.

---
### NB: Add a folder called 'dataset' to store the datafile images

## Learning Experience and Conclusion

This project was an excellent opportunity to explore the integration of computer vision, image processing, and command-line interface design. Key takeaways include:

1. **Understanding Libraries**: Learned how to effectively use OpenCV for image processing tasks and leverage its contrib module for advanced features.
2. **Modular CLI Design**: Gained experience in designing intuitive command-line interfaces using the `face` package.
3. **Data Handling**: Improved proficiency in handling and manipulating image data with `NumPy` and `Pillow`.
4. **Code Optimization**: Developed efficient solutions by utilizing utility functions provided by the `boltons` library.

This project demonstrates the power of combining multiple libraries to build versatile Python applications. It also highlights the importance of understanding each library's unique features to use them effectively.

---
