# Printed / PDF Urdu Dataset

## Overview

This dataset contains digitized printed Urdu book pages collected for the printed/PDF Optical Character Recognition (OCR) component of the Orator-OCR project.

The collection represents variation in Urdu typography, page layouts, publishing formats, and document quality.

## Dataset Collection

The dataset was compiled from:

- 16 digitized Urdu books
- 13 unique writers
- 5 different publishers
- Publication period: 1993–2018
- Publication cities: Islamabad, Lahore, and Peshawar

The source PDF documents were selected with a minimum resolution of 300 DPI.

## Dataset Statistics

| Attribute | Count / Details |
|---|---:|
| Total books | 16 |
| Total pages collected | 3,603 |
| Aligned pages | 2,500 |
| Aligned and corrected pages | 2,500 |
| Pages processed for OCR experiments | 1,500 |
| Unique writers | 13 |
| Unique publishers | 5 |
| Publication period | 1993–2018 |
| Publication cities | Islamabad, Lahore, Peshawar |

## Data Preparation

The project thesis describes the following preparation process:

1. Selection of digitized Urdu books from different writers and publishers.
2. Alignment of selected document pages with their corresponding text.
3. Correction of text to improve consistency and reduce OCR-related errors.
4. Preparation of aligned and corrected image-text pairs.
5. Processing of 1,500 pages for OCR experiments.

## Preprocessing

The printed/PDF pages were processed using:

- Grayscale conversion
- Sauvola binarization

These techniques were used to prepare scanned printed pages for subsequent text-line segmentation and OCR.

## Public Sample

This repository is intended to provide a representative sample rather than the complete dataset.

Approximately 50 sample image-text pairs will be shared for this category, subject to sharing permissions.

The complete dataset is maintained separately and is not included in this repository.

## Project Context

The Printed/PDF Urdu Dataset is one of four document categories in Orator-OCR:

- Printed/PDF documents
- Handwritten documents
- Historical documents
- Camera-captured documents

## Notes

The collection statistics are reported in the Orator-OCR project thesis. They describe the overall project dataset and do not represent the number of files publicly available in this repository.

Only material that is permitted for public distribution will be included in the sample release.
