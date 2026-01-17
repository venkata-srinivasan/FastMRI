# FastMRI: Accelerating MRI with Deep Learning

Exploring deep learning techniques to accelerate Magnetic Resonance Imaging (MRI) reconstruction, reducing scan times while maintaining diagnostic image quality.

## Overview

MRI scans are slow because they require collecting many measurements in k-space (frequency domain). By using deep learning to reconstruct high-quality images from undersampled k-space data, we can significantly reduce scan times - improving patient comfort and increasing scanner throughput.

This project explores neural network architectures for MRI reconstruction based on the [fastMRI dataset](https://fastmri.org/) from Facebook AI Research and NYU Langone Health.

## Approach

- **Problem**: Reconstruct high-quality MRI images from undersampled k-space measurements
- **Method**: Deep learning models trained on paired undersampled/fully-sampled MRI data
- **Goal**: Achieve 4x-8x acceleration while preserving diagnostic quality

## Tech Stack

- Python
- PyTorch
- Jupyter Notebooks
- NumPy, Matplotlib

## Dataset

This project uses the [fastMRI dataset](https://fastmri.org/), which contains:
- Knee MRI scans
- Brain MRI scans
- Raw k-space data and DICOM images

## References

- [fastMRI: An Open Dataset and Benchmarks for Accelerated MRI](https://arxiv.org/abs/1811.08839)
- [Facebook AI Research fastMRI](https://github.com/facebookresearch/fastMRI)

## License

This project is for educational and research purposes.

---

**Keywords**: Medical Imaging, Deep Learning, MRI, Healthcare AI, Computer Vision
