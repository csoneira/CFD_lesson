# Signal Timing Extraction: Threshold vs Constant Fraction Discriminator (CFD)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

This notebook provides an educational demonstration of two key techniques used to extract timing information from detector signals:

- **Threshold crossing**: A basic method where the signal time is determined by when it exceeds a fixed amplitude level.
- **Constant Fraction Discriminator (CFD)**: A more robust method that reduces time walk by using a delayed and scaled version of the signal to find a consistent zero-crossing point.

## What This Notebook Shows

- How to simulate realistic Gaussian detector signals with varying amplitudes and delays.
- How threshold timing can lead to errors when signal amplitudes vary.
- How CFD improves timing precision, independent of signal amplitude.
- Statistical analysis comparing the two methods using Gaussian fits.
- Visualization with scatter plots, 2D density maps, and histograms.

## Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy

## Who Is This For?

This notebook is ideal for:

- Students and researchers in **nuclear physics**, **PET imaging**, or **particle detection**.
- Anyone interested in **pulse processing**, **signal timing**, and detector electronics.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
