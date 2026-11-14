# Urdu-Orator-OCR-Dataset

### A Multi-Category Urdu Document Dataset for Optical Character Recognition (OCR)

**Urdu-Orator-OCR-Dataset** is a dataset project associated with **Orator-OCR**, a unified Urdu Optical Character Recognition (OCR) research project. It focuses on Urdu documents from different sources and writing conditions to support OCR research, text recognition, and document digitization.

The project covers four major Urdu document categories:

- Printed / PDF documents
- Handwritten documents
- Camera-captured documents
- Historical documents

## Project Overview

Urdu OCR presents challenges because of the cursive nature of the script, connected ligatures, overlapping strokes, diacritical marks, and variations in document quality.

The Orator-OCR project explored a unified approach to processing different types of Urdu documents through document-specific preprocessing, line segmentation, and OCR recognition.

This repository is intended to document the dataset categories, collection process, annotation workflow, and related research.

## Dataset Categories

### 1. Printed / PDF Dataset

A collection of Urdu text from printed books and PDF-based documents.

The thesis reports a collection of **3,603 pages** from **16 books**, representing **13 writers** and **5 publishers**.

### 2. Handwritten Dataset

A collection of handwritten Urdu documents contributed by different writers.

According to the thesis, this dataset contains **954 pages** from **477 writers** representing **74 institutions**.

The handwritten data preparation workflow included:

1. Collecting handwritten document images.
2. Obtaining initial text through Google OCR.
3. Aligning the extracted text line by line with the corresponding image.
4. Manually reviewing and correcting OCR errors.
5. Preparing the corrected text for the dataset.

The handwritten dataset includes the following processing stages:

- Original images
- Google OCR text
- Aligned text
- Aligned and annotated text

### 3. Camera-Captured Dataset

A collection of Urdu document pages photographed using different camera devices and viewing angles.

The thesis reports **1,415 page images** collected from **283 books**. The collection includes variations in illumination, focus, perspective, and camera quality.

### 4. Historical Dataset

A collection of historical Urdu document pages representing different levels of document aging and degradation.

The thesis reports **1,505 pages** from **22 books**. The pages include variations in color and condition, such as yellow, gray, yellow-gray, and brown-discolored pages.

## Data Preparation and Annotation

The project involved preparing Urdu document images and their corresponding text for OCR research.

The documented preparation workflow includes OCR text extraction, text-to-image alignment, and correction of recognition errors.

For the handwritten dataset, the alignment and correction stages were performed manually to improve correspondence between the document images and their text transcriptions.

## Preprocessing Methods

The Orator-OCR research explored document-specific preprocessing approaches:

- **Printed / PDF:** Grayscale conversion and Sauvola binarization.
- **Historical:** Denoising, background estimation, illumination normalization, stroke enhancement, and Wolf–Jolion binarization.
- **Camera-captured:** Perspective correction, document dewarping, and skew correction.
- **Handwritten:** Page preprocessing and histogram-based line segmentation.

## OCR Evaluation

The thesis describes evaluation using:

- Character Error Rate (CER)
- Ligature Error Rate (LER)

The OCR experiments compared multiple recognition approaches, including Google OCR, UTRNet, Qwen2-VL-2B-Instruct, and a CNN + RoBERTa + GPT-2 architecture.

Detailed evaluation results and dataset statistics will be documented separately.

## My Contribution

My work on this project included Urdu OCR dataset collection and preparation, particularly the handwritten dataset workflow.

This involved collecting document images, obtaining initial OCR text, aligning text with the corresponding image lines, and manually correcting the extracted text.

This repository is being organized to present the dataset work, annotation process, and supporting documentation in a clear and structured way.

## Repository Status

The repository is currently being organized.

Dataset files, sample data, documentation, and usage instructions will be added progressively after reviewing file organization, permissions, and data-sharing restrictions.

## Data Availability and Usage

Dataset availability will depend on the permissions and sharing rights associated with the collected documents and their transcriptions.

Please do not assume that the complete dataset is publicly available until the relevant files and permissions have been reviewed.

## Project Context

**Project:** Orator-OCR  
**Research Area:** Urdu Optical Character Recognition  
**Dataset Categories:** Printed / PDF, Handwritten, Camera-Captured, Historical  
**Primary Language:** Urdu

---

*This repository documents the dataset and annotation work associated with the Orator-OCR research project.*
