# opencv-image-processor
A Python-based image processing tool using OpenCV to perform basic image enhancements including grayscale conversion, resizing, and color space transformations.

## ✨ Features
* **Interactive Image Upload**: Seamlessly integrates with `google.colab.files` to allow users to process their own local images.
* **Color Space Conversion**: Automatically converts standard BGR image data to RGB for accurate visualization and generates a Grayscale version for analysis.
* **Spatial Transformation**: Implements precise image resizing to a standard 300x300 resolution, useful for preprocessing in machine learning pipelines.
* **Multi-View Visualization**: Uses Matplotlib to generate a side-by-side comparison of the Original, Grayscale, and Resized images.

## 🗺️ Navigation Flow
Follow these steps to navigate through the project:

1. **Environment Setup**: The first cell imports necessary dependencies (`cv2`, `matplotlib`, `numpy`).
2. **File Selection**: Execute the upload cell to trigger the file picker and select an image from your local drive.
3. **Automated Processing**:
    * The script reads the image and stores it as a NumPy array.
    * It converts the image to Grayscale using `COLOR_BGR2GRAY`.
    * It applies an interpolation-based resize to 300x300 pixels.
4. **Result Generation**: The final cell plots the three versions of the image in a 1x3 grid for immediate visual feedback.

## 🛠️ Requirements
To run this project, ensure you have the following installed:
- Python 3.x
- OpenCV (`opencv-python`)
- Matplotlib
- Numpy

## 🚀 How to Run
1. Upload the `Image_Enhacement_2_0.ipynb` file to your [Google Colab](https://colab.research.google.com/).
2. Run each cell sequentially (Shift + Enter).
3. View the output comparison at the bottom of the notebook.
