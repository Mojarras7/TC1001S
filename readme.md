# Image Filtering and OCR

This project demonstrates image filtering techniques and Optical Character Recognition (OCR) using Python. It allows users to select an image, apply filters, detect edges, and extract text from the image.

## Features

- Load an image using a file dialog.
- Convert the image to grayscale.
- Apply Gaussian blur for smoothing.
- Perform edge detection using the Canny algorithm.
- Extract text from the image using Tesseract OCR.
- Display the original, blurred, and edge-detected images side by side.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```
3. Install the required Python libraries:
    ```bash
    pip install opencv-python pytesseract matplotlib
    ```

4. Ensure Tesseract OCR is installed on your system:
    - On Ubuntu:
        ```bash
        sudo apt install tesseract-ocr
        ```
    - On macOS (using Homebrew):
        ```bash
        brew install tesseract
        ```
    - On Windows, download and install Tesseract from [Tesseract's official site](https://github.com/tesseract-ocr/tesseract).

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Actividad_1_Filtrado_imagen.ipynb
    ```
2. Run the cells step by step.
3. When prompted, select an image file using the file dialog.
4. View the processed images and detected text in the notebook output.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com).