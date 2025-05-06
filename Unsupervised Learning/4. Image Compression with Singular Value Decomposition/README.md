# Image Compression using SVD

This folder demonstrates how Singular Value Decomposition (SVD) can be used to compress grayscale and color images while preserving visual quality. SVD is a linear algebra technique that reduces the storage size of an image by keeping only the most significant singular values.

## Contents

- `image_compression.ipynb` — Jupyter Notebook containing all code, visualizations, and analysis.
- `matrix_visual.jpeg` and `svd_eq.jpg` - Diagrams.
- `dog.jpg` - Example image used for SVD image compression.

## Image Compression Overview

SVD decomposes an image matrix into three parts: `U`, `S`, and `V^T`. By retaining only the top `k` singular values and their corresponding vectors, we can approximate the original image with fewer data points.

### Grayscale Compression
- Grayscale images require fewer singular values (`k`) to retain high quality.
- A 300×300 grayscale image has an original size of 90,000 pixels.
- With `k = 150`, the compressed version closely resembles the original but at the same storage cost (~90,000).

### Color Compression
- Color images are stored in 3 channels: Red, Green, and Blue.
- Each channel is compressed separately using SVD.
- Because of the three channels, the storage cost grows 3× faster.
- The original image size in RGB was 5,025,402 pixels.
- High-quality approximation requires much higher `k` compared to grayscale.

## Visualizations

- Side-by-side comparison of original and compressed images for multiple `k` values (10, 50, 100, 150).
- Plots showing storage cost vs. `k` to determine at what point compression becomes less efficient than storing the full image.

## Key Takeaways

- SVD is highly effective for image compression, especially in grayscale.
- Color images require more singular values to maintain clarity, increasing storage demands.
- There is a trade-off between compression ratio and visual fidelity.
- Visualization of compression results helps choose an optimal `k`.

## How to Run

1. Clone this repo
2. Install dependencies:
    ```bash
   pip install numpy matplotlib pillow
3. Open `image_compression.ipynb` and run all cells.
