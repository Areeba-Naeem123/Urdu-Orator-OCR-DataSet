# Camera-Captured Urdu Dataset

## Overview

This dataset contains camera-captured Urdu document images collected for the camera-based Optical Character Recognition (OCR) component of the Orator-OCR project.

The collection represents real-world document capture conditions, including variations in camera devices, viewing angles, image orientation, lighting, and document appearance. It is intended to support the development and evaluation of OCR systems for Urdu documents captured using cameras.

## Dataset Collection

According to the Orator-OCR project thesis, the camera-captured dataset consists of:

- 1,415 collected pages
- 283 books
- 253 unique writers
- 144 publishers

The pages were captured using different devices and viewing angles to introduce variation in document appearance and image quality.

## Dataset Structure

The camera-captured dataset is organized into the following stages:

| Folder | Description |
|---|---|
| `images/` | Original camera-captured Urdu document images |
| `google_ocr/` | Raw text extracted using Google OCR |
| `aligned_text/` | Text manually aligned with the corresponding document images |
| `corrected_text/` | Manually reviewed and corrected text annotations |

## Data Annotation Workflow

The dataset preparation process consists of the following stages:

1. **Image Collection:** Urdu document pages were captured using different camera devices and viewing angles.
2. **OCR Extraction:** Google OCR was used to generate initial text from the captured images.
3. **Text Alignment:** Extracted text was manually aligned with the corresponding document content.
4. **Text Correction:** OCR errors were reviewed and corrected to produce the final annotated text.

This workflow provides multiple annotation stages, allowing comparison between raw OCR output, aligned text, and corrected annotations.

## Image Preprocessing

The project thesis describes camera-image preprocessing techniques including:

- Perspective transformation
- Document dewarping
- Skew correction

These techniques help address geometric distortions introduced during camera-based document capture.

## Public Sample

This repository contains a representative sample of the camera-captured dataset rather than the complete collection.

Approximately 50 image-text examples are intended for public release, subject to applicable sharing permissions.

Each sample may include:

- One camera-captured document image
- Its corresponding Google OCR output
- Its aligned text
- Its corrected text annotation

## Project Context

The Camera-Captured Urdu Dataset is one of four document categories in the Orator-OCR project:

- Printed/PDF documents
- Handwritten documents
- Historical documents
- Camera-captured documents

## Notes

The collection statistics are reported in the Orator-OCR project thesis and describe the overall project dataset, not necessarily the number of files included in this public repository.

Only material authorized for public distribution will be included in the sample release.
