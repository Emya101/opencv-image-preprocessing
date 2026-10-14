# OpenCV Image Preprocessing

A small Python notebook exploring **median**, **bilateral** and **Gaussian** filtering, histogram equalization, and **CLAHE**. Each processing stage is labeled to make it easy to compare outputs visually.

## Setup
```bash
pip install -r requirements.txt
jupyter notebook image_preprocessing.ipynb
```
Use `Run All` in Jupyter or Colab. The notebook saves `output/contrast_enhanced.png` locally; the `output/` folder is ignored by Git.

## Example input
`assets/noisy_image_sample.png` is a **synthetic** noisy graphic created for this public learning project. It is not the original photo used during experimentation, whose reuse rights were not established.

## What this shows
Practical use of OpenCV preprocessing filters, comparison of sequential transformations, visualizations with Matplotlib, and writing an image file.

## Limits
No OCR benchmark or numeric image-quality comparison has been performed; more contrast does not necessarily mean better data extraction.
