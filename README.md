# license-plate-detection
This project is a License Plate Recognition (LPR) system that utilizes the power of OpenCV and PyTesseract to extract and recognize license plate numbers from an image of a car. The system first preprocesses the image by converting it to grayscale, applying morphological operations, blurring, and adaptive thresholding to enhance the license plate's visibility and remove any noise.

Once the image is preprocessed, the system then extracts the license plate contours based on their position and size. These contours are then grouped together to form a single license plate. The grouped contours are then rotated and cropped to obtain a clear and straight license plate image.

The license plate image is then passed through PyTesseract, an OCR (Optical Character Recognition) engine, to recognize and extract the license plate number. The system then prints the longest recognized license plate number as the output.

This project is an excellent resource for anyone looking to learn about image processing, computer vision, and OCR techniques. It can be used for various applications, such as traffic monitoring, parking management, and security surveillance.
