# Handwritten Urdu Dataset

## Overview

The Handwritten Urdu Dataset contains handwritten Urdu document images collected for the handwritten text recognition component of the Orator-OCR project.

The dataset represents variations in individual handwriting styles, letter shapes, word spacing, writing patterns, and document appearance. It is intended to support the development and evaluation of OCR systems for handwritten Urdu text.

## Dataset Collection

According to the Orator-OCR project thesis, the handwritten dataset consists of:

- 954 collected pages
- 477 unique writers
- Contributions from 74 institutions
- Contributors aged between 14 and 54 years

The collection represents a range of handwriting styles and writing patterns from different contributors.

## Dataset Characteristics

Handwritten Urdu presents several challenges for OCR systems, including:

- Variations in handwriting styles
- Differences in character shapes and joining patterns
- Irregular word and character spacing
- Overlapping or connected strokes
- Variations in writing size and slant
- Differences in page quality and writing clarity

## Dataset Structure

The original handwritten dataset preparation workflow includes the following stages:

| Folder | Description |
|---|---|
| `images/` | Original handwritten Urdu document images |
| `google_text/` | Initial text extracted using Google OCR |
| `aligned_text/` | Text manually aligned line by line with the corresponding images |
| `aligned_and_annotated_text/` | Manually reviewed, corrected, and annotated text |

## Data Collection and Annotation Workflow

The handwritten dataset was prepared through the following stages:

1. **Image Collection:** Collection of handwritten Urdu document images from different contributors.
2. **OCR Extraction:** Uploading images to Google OCR and saving the extracted text.
3. **Manual Alignment:** Aligning the extracted text line by line with the corresponding handwritten content.
4. **Manual Annotation and Correction:** Reviewing the aligned text, correcting OCR errors, and removing inaccurate text to produce the final annotations.

This workflow provides multiple text-processing stages, making it possible to compare raw OCR output with manually aligned and corrected annotations.

## OCR Challenges

Handwritten Urdu recognition is particularly challenging because of variations in writing styles, connected characters, diacritical marks, and irregular spacing.

The project thesis reports that UTRNet did not converge on the handwritten dataset during the reported experiments. This highlights the difficulty of handwritten Urdu recognition and the need for further model development.

## Public Sample

This repository is intended to contain a representative sample rather than the complete handwritten dataset.

Approximately 50 image-text pairs are intended for public release, subject to applicable sharing permissions and contributor privacy requirements.

Each sample may include:

- One handwritten Urdu document image
- Its corresponding Google OCR output
- Its manually aligned text
- Its corrected and annotated text

## Project Context

The Handwritten Urdu Dataset is one of four document categories in the Orator-OCR project:

- Printed/PDF documents
- Handwritten documents
- Historical documents
- Camera-captured documents

## Notes

The collection statistics and experimental observations described here are reported in the Orator-OCR project thesis. They describe the overall project dataset and do not necessarily represent the number of files included in this public repository.

Because the collection includes contributions from individuals, only material authorized for public distribution will be included. Personal identifying information and contributor details will not be published.
