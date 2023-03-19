# Healthcare_Documents_Clustering_With_Pytesseract_OCR
This project aims to solve the problem of clustering large volumes of healthcare-related documents. The project uses OCR technology to extract text from PDFs, and then applies machine learning techniques to cluster similar documents together.

# Important Note
Please be aware that this project includes dummy data that was created by the author solely for testing & demonstration purposes. None of the information in these samples is associated with real individuals and may include fictitious details such as phone numbers and dates of birth.

# Features

- Support for PDF file format
- OCR technology for accurate text extraction
- KMeans clustering algorithm for document clustering
- Preprocessing steps for image optimization and noise reduction
- Exporting of clustering results as CSV file

# How it works

1. PDF documents are read using the PyPDF2 library
2. Documents are then transformed into images using the fitz library
3. The images are preprocessed to optimize for text extraction using OpenCV
4. Text is extracted from the preprocessed images using pytesseract
5. The extracted text is transformed using a TfidfVectorizer
6. The transformed text is clustered using the KMeans algorithm
7. The results of the clustering are exported as a CSV file

# Limitations

- The project may not perform well on documents with complex formatting or layouts
- The OCR technology used may not be able to accurately extract text from certain types of images or scans

# Installation

1. Clone the repository to your local machine
2. Install the required packages using pip
3. Install Tesseract-OCR by downloading it from here and add it to your PATH

# Usage

1. Open the Jupyter notebook in your local machine or in Google Colab
2. Update the necessary file paths in the notebook
3. Run the cells in order

# Package Requirements

- pandas
- json
- re
- fitz
- math
- sklearn
- collections
- PyPDF2
- cv2
- numpy
- multiprocessing
- skimage
- matplotlib
- pytesseract

# License

This project is licensed under the MIT License.
