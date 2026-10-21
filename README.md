# Signal Timing Extraction: Threshold vs Constant Fraction Discriminator (CFD)

[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-blue?logo=google-colab)](https://colab.research.google.com/github/csoneira/CFD_lesson/blob/main/CFD_notebook.ipynb)

Jupyter notebook comparing fixed-threshold timing with constant fraction discrimination (CFD) for synthetic Gaussian detector pulses.

The simulation varies pulse amplitude, width, and relative delay; measures the timing residual with both methods; applies a quadratic correction to the threshold result as a function of the amplitude ratio; and compares the resulting distributions.

## Requirements

- Python 3
- NumPy
- Matplotlib
- SciPy

Run `CFD_notebook.ipynb` locally or open it in Colab using the badge above.

## License

MIT. See [LICENSE.md](LICENSE.md).
