# Medlr_assignment

This project comprises four components aimed at various text recognition tasks. Here's an overview of each component:

## Basic Text Extraction from Image

This component is designed to extract text from images using basic image processing and OCR methods. It can be used for tasks such as extracting text from documents, signs, labels, and more. Input to the code is a black-n-white .png image and the output is text in that image.

## Number Plate Text Recognition

This component focuses on recognizing text from vehicle number plates. It employs OpenCV and optical character recognition (OCR) algorithms to extract and interpret text from images containing vehicle number plates and overlays the text in number plate just above the number plate in the image.

## PDF Text Extraction

This component specializes in extracting text from PDF documents. It utilizes PDF parsing libraries and text extraction techniques to retrieve text content from PDF files, making it useful for processing textual data embedded within PDF documents. It first converts each page of the pdf in .jpeg form and then extracts the text and appends it into a text file which ultimately is the output.

## Handwritten Character Recognition

This component deals with recognizing handwritten characters. It employs machine learning models along with deep learning libraries.
Each component serves a specific text recognition need and can be utilized independently or collectively based on the requirements of the task at hand. Additionally, these components can be integrated into larger systems or workflows for automating text-related tasks and processes.

The link to the dataset used for model training can be downloaded here:
dataset link: https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format
