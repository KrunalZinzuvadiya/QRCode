
# QR Code and Barcode Scanner using OpenCV

This project is an implementation of a QR code and barcode scanner using OpenCV in Python. It can detect and decode QR codes and barcodes from images or real-time video streams.

## Features

- Detect and decode QR codes and barcodes from images.
- Real-time QR code and barcode scanning using a webcam.
- Supports various barcode formats.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/qr-barcode-scanner.git
    cd qr-barcode-scanner
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Scanning from an image

1. Place your image in the `images` directory.
2. Run the script with the image path as an argument:
    ```bash
    python scan_image.py --image images/your-image.jpg
    ```

### Real-time scanning using a webcam

1. Simply run the script:
    ```bash
    python scan_realtime.py
    ```

## Project Structure

- `scan_image.py`: Script to scan QR codes and barcodes from images.
- `scan_realtime.py`: Script to scan QR codes and barcodes in real-time using a webcam.
- `requirements.txt`: List of dependencies required to run the project.
- `images/`: Directory to store images for scanning.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Pyzbar

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or issues, please open an issue on GitHub or contact the project maintainer.
