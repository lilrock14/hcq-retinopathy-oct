# HCQ Retinopathy OCT Classifier

Binary deep learning classifier for detecting hydroxychloroquine-induced retinal toxicity from SD-OCT B-scan images. 

**Capstone Project — TC5035.10**  
Maestría en Inteligencia Artificial Aplicada  
Tecnológico de Monterrey

## Team 

- Natalia Nevarez Tinoco — A01566204
- Alejandro Caamaño Granados — A00843392
- Diana Jimena López Nájera — A01024913

## Clinical Sponsor 

Dr. Alejandro Rodríguez García, Hospital Zambrano Hellion, Monterrey.

## Project Overview

This project develops a binary classification model based on Optical 
Coherence Tomography (OCT) images to automatically detect macular 
toxicity caused by long-term use of hydroxychloroquine (HCQ), a drug 
commonly prescribed for autoimmune diseases such as lupus and 
rheumatoid arthritis.


## Milestones

### Milestone 1

- **Milestone 1 — Exploratory Data Analysis** (`Avance1_45Equipo.ipynb`)  
  Dataset audit, file format handling (PDF extraction), duplicate 
  detection, univariate and bivariate analysis, class imbalance 
  assessment, and identification of potential acquisition bias.


## Dataset

The clinical dataset was provided by Dr. Rodríguez García and is hosted 
in a private OneDrive folder shared with the team. **The data is not 
included in this repository for patient privacy reasons.**

The notebook automatically locates the dataset in Google Drive as long 
as the shared `Plaquenil` folder (containing subfolders `No`, `Si`, 
`Sospecha`) has been added to the user's Drive at any location.

## Running the Notebook

1. Open `Avance1_45Equipo.ipynb` in Google Colab.
2. Mount Google Drive when prompted.
3. Ensure the `Plaquenil` folder is accessible in your Drive.
4. Run all cells sequentially.

## Dependencies

All dependencies are installed within the notebook via `pip`:
- `pymupdf` (for PDF scan extraction)
- Standard scientific Python stack (numpy, pandas, matplotlib, seaborn, PIL)
