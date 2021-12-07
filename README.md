# PDF
## Solving the problem of accessing free pdf

The Portable Document Format, or PDF, is a file format that can be used to present and exchange documents reliably across operating systems. While the PDF was originally invented by Adobe, it is now an open standard that is maintained by the International Organization for Standardization (ISO).

# AGENDA
1. extract text from a PDF file.
2. Rotate pages of a PDF file.
3. Extract document information from a PDF file.
4. Split pages from a PDF file.
5. Merge pages of a PDF file.
6. Encrypt PDF files.
7. Add a watermark to a PDF file.

# Some Common Libraries for PDFs in Python
There are many libraries available freely for working with PDFs:

1. PDFMiner: It is an open-source tool for extracting text from PDF. It is used for performing analysis on the data. It can also be used as a PDF transformer or PDF parser.

2. PDFQuery: It is a lightweight python wrapper around PDFMiner, Ixml, and PyQuery. It is a fast, user-friendly PDF scraping library.

3. Tabula.py: It is a python wrapper for tabula.java. It converts PDF files into Pandas’ data frame and further all data manipulation operations can be performed on the data frame.

4. Xpdf: It allows conversion of PDFs into text.

5. pdflib: It is an extension of the poppler library with python bindings present in it.

6. Slate: It is a Python package based on the PDFMiner and used for extraction of text from PDF.

7. PyPDF2: It is a python library used for performing major tasks on PDF files such as extracting the document-specific information, merging the PDF files, splitting the pages of a PDF file, adding watermarks to a file, encrypting and decrypting the PDF files, etc. We will use the PyPDF2 library in this tutorial. It is a pure python library so it can run on any platform without any platform-related dependencies on any external libraries.

# Getting Started with PyMuPDF Library
## Installing the required packages
You copy the following commands in the command prompt and run: </br>
`pip install fitz
pip install PyMuPDF`






