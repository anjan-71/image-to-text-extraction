# image-to-text-extraction

### Project Title: Text Extraction from Images using Tesseract OCR

### Introduction:
Optical Character Recognition (OCR) is a technology that enables the conversion of different types of documents, such as scanned paper documents, PDF files, or images captured by a digital camera, into editable and searchable data. Tesseract OCR is one of the most widely used OCR engines, capable of recognizing over 100 languages out-of-the-box. In this project, we aim to utilize Tesseract OCR to extract text from images.

### Objective:
The primary objective of this project is to demonstrate how to use Tesseract OCR in Python to extract text from images efficiently.

### Implementation:
We implemented the text extraction process using the following steps:

### Library Installation:
We utilized two Python libraries:

### pytesseract: A Python wrapper for Tesseract OCR engine.
PIL (Python Imaging Library): A library for opening, manipulating, and saving many different image file formats.
Setting Tesseract Path:
We specified the path to the Tesseract executable to ensure proper execution. This step is necessary if Tesseract is not in the system's PATH.

### Image Loading:
We loaded the image using the Image.open() function from the PIL library. The image file used for testing was named "Test 1.png" and "Test 2.png".

### Text Extraction:
We utilized the pytesseract.image_to_string() function to extract text from the loaded image. This function converts the image to text using Tesseract OCR.

### Printing Extracted Text:
The extracted text was printed to the console using the print() function.

### Completion Message:
Finally, a "finished" message was printed to indicate the completion of the text extraction process.

Results:
The project successfully extracted text from the input image "Test 1.png" and "Test 2.png" using Tesseract OCR. The extracted text was printed to the console, demonstrating the effectiveness of the OCR engine.

### Conclusion:
In conclusion, the project achieved its objective of extracting text from images using Tesseract OCR in Python. This functionality can be further integrated into various applications, such as document scanning, text recognition in images, and data extraction from images. Additionally, by leveraging the capabilities of Tesseract OCR, developers can automate text extraction tasks, leading to increased efficiency and productivity.
