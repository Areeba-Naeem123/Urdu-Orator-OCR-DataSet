# Historical Urdu Dataset

## Overview

The Historical Urdu Dataset contains images of historical Urdu documents collected for the historical document recognition component of the Orator-OCR project.

The dataset represents challenges commonly found in old and degraded documents, including faded text, discolored paper, uneven backgrounds, and variations in document quality.

It is intended to support the development and evaluation of OCR systems capable of recognizing Urdu text from historical document images.

## Dataset Collection

According to the Orator-OCR project thesis, the historical dataset consists of:

- 1,505 collected pages
- 22 historical books
- Documents with different paper conditions and levels of discoloration

The collection includes historical pages with the following appearances:

- Yellow pages
- Gray pages
- Yellow-gray pages
- Brown-discolored pages

These variations help represent the visual challenges encountered when processing historical Urdu documents.

## Dataset Characteristics

Historical Urdu documents can present several challenges for OCR systems:

- Faded or degraded text
- Discolored and aged paper
- Uneven background illumination
- Low contrast between text and background
- Noise and scanning artifacts
- Variations in ink and document appearance

## Data Preparation and Annotation

The historical dataset preparation process described in the project thesis includes:

1. **Image Collection:** Collection of historical Urdu document pages.
2. **OCR Extraction:** Generation of initial text using Google OCR.
3. **Text Alignment:** Alignment of extracted text with the corresponding document content.
4. **Text Correction:** Review and correction of OCR-generated text to improve annotation quality.

The aligned and corrected text provides reference annotations for OCR development and evaluation.

## Image Preprocessing

The project thesis describes the following preprocessing techniques for historical document images:

- Image denoising
- Background estimation
- Illumination normalization
- Stroke enhancement
- Wolf–Jolion binarization

These techniques help improve document readability and prepare degraded historical pages for OCR processing.

## Public Sample

This repository is intended to contain a representative sample of the historical Urdu dataset rather than the complete collection.

Approximately 50 image-text pairs are intended for public release, subject to applicable sharing permissions.

Each sample may include:

- One historical Urdu document image
- Its corresponding OCR-generated text
- Its aligned text
- Its corrected text annotation

## Project Context

The Historical Urdu Dataset is one of four document categories in the Orator-OCR project:

- Printed/PDF documents
- Handwritten documents
- Camera-captured documents
- Historical documents

## Notes

The collection statistics and preprocessing methods described here are reported in the Orator-OCR project thesis. They describe the overall project dataset and do not necessarily represent the number of files included in this public repository.

Only documents and annotations authorized for public distribution will be included in the sample release.
