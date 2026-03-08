# opencv-image-processor
A Python-based image processing tool using OpenCV to perform basic image enhancements including grayscale conversion, resizing, and color space transformations.

## 🚀 Features
* **Image Upload**: Integrated with Google Colab for easy local file processing.
* **Color Space Transformation**: Converts standard BGR images to RGB (for plotting) and Grayscale.
* **Spatial Transformation**: Includes image resizing to specific dimensions (300x300).
* **Visual Comparison**: Side-by-side visualization of original, grayscale, and resized images using Matplotlib.

## 🛠️ Requirements
To run this project, you need the following Python libraries:
* `opencv-python` (cv2)
* `matplotlib`
* `numpy`

## 📖 How to Use
1. Open the `Image_Enhacement_2_0.ipynb` notebook in Google Colab or a local Jupyter environment.
2. Run the initial cells to import dependencies.
3. Use the upload widget to select an image from your computer.
4. The script will automatically process the image and display the results.

## 📸 Results
The script outputs a 1x3 visualization panel:
1. **Original Image**: The source image in full color.
2. **Grayscale**: The luminance-only version of the image.
3. **Resized**: The image scaled to a 300x300 resolution.

## ⚖️ License
This project is open-source and available under the MIT License.
