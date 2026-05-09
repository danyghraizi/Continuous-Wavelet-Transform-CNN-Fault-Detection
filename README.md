# Continuous-Wavelet-Transform-CNN-Fault-Detection
This repository is only a **simplified recreation** of the overall workflow at a conceptual level. The **original source code and experimental results remain confidential** and are not reproduced here.

This notebook sketches how **continuous wavelet transform (CWT) scalograms** can be built from vibration-like time series, how data might be exchanged between formats (CSV, NPZ, HDF5), and how a compact **2D CNN** could be used for binary classification. Example paths, timestamps, curves, and numbers are illustrative unless you substitute your own data.

**Setup:** Paths are placeholders. Set **`SCALOGRAM_DATA_ROOT`** or edit **`DATA_ROOT`** under **Configuration** for your machine.

**Dependencies:** TensorFlow 2.x, PyWavelets, scikit-learn, pandas, NumPy, scikit-image, matplotlib, h5py (installed in the setup cell where needed).
