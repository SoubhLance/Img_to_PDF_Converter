# Img_to_PDF_Converter


Img_to_PDF_Converter is a Python-based GUI utility for converting images to PDF format. This tool supports various image formats and allows users to easily select and convert multiple images into a single PDF document using a simple graphical user interface.

#Features
- Multi-format Support: Converts images of various formats (JPEG, PNG, etc.) to PDF.
- Batch Processing: Converts multiple images to a single PDF or individual PDFs.
- Simple Interface: User-friendly command-line interface for easy operation.
- Quality Control: Maintains the quality of the original images in the PDF output.

# Requirements
>Libraries:
- Pillow
- reportlab

#Overview
-Import Libraries: Import the necessary modules from the Python Imaging Library (PIL) and the standard library.
-Function Definition: Define a function convert_images_to_pdf that processes the images.
-Image Collection: Collect all images from the input directory and convert them to RGB format.
-Save as PDF: Save the collected images as a single PDF file.
-Command-line Interface: Provide a simple command-line interface for users to specify input and output paths.
