# Multi-Media Processing — Coursework Notebooks

A collection of Python / Jupyter notebooks from university coursework exploring digital signal processing and image processing techniques with real-world datasets.

## Topics Covered

| Topic | Folder | Description |
|-------|--------|-------------|
| **Wiener filter** | `winer/` | Denoising a noisy audio signal using the Wiener filter (`quize.ipynb`) |
| **Median filter** | `midian/` | Removing salt-and-pepper noise from images with a median filter |
| **Local Binary Pattern (LBP)** | `locll_binary_pattern/` | Texture analysis using Local Binary Patterns |
| **Color conversion** | `from 8 to hsv/` | Converting 8-bit images to HSV color space |
| **Color depth** | `from 8 to 24 blue/` | Working with 8-bit vs 24-bit color channels |
| **Contrast & brightness** | `conatarst and brightness/` | Image enhancement via contrast and brightness adjustments |
| **Run-Length Encoding** | `rle/` | Lossless image compression with RLE |
| **OpenCV basics** | `show image with cv2/` | Image loading and display with OpenCV |
| **Sound assessment** | `assessment_file/` | Medium-filter + noisy audio samples used across exercises |

## Stock Price Prediction

`predictor.ipynb` steps outside image/signal processing: a **linear regression model** (scikit-learn) trained on `stock_data.csv` to forecast stock prices, including a backtesting configuration with initial capital and transaction costs.

## Technologies

- Python 3
- NumPy, Pandas
- Matplotlib
- scikit-learn
- OpenCV
- librosa / soundfile
- Jupyter Notebook