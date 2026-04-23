# Image Filtering Techniques

Implementations of spatial filtering techniques for image enhancement and edge detection. This project covers Laplacian sharpening, Laplacian of Gaussian (LoG) edge detection, the effect of kernel size on Gaussian smoothing, and a from-scratch bilateral filter implementation.

## Techniques

- **Laplacian Sharpening** : Enhance fine details using second-order derivatives
- **Laplacian of Gaussian (LoG)** : Combine Gaussian smoothing with Laplacian edge detection in a single filter
- **Gaussian Kernel Size vs Sigma** : Demonstrate why kernel size should depend on the standard deviation
- **Bilateral Filter (from scratch)** : Edge-preserving smoothing using spatial and range Gaussians, compared against scikit-image's built-in implementation

## Tech Stack

- Python
- NumPy
- Matplotlib
- scikit-image

## Results

All outputs are embedded in the notebook and render directly on GitHub : open `image_filtering.ipynb` to see the visualizations.
