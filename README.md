# Face Average

This project focuses on creating an average face of the Presidents of the United States using computer vision techniques.

## Overview

The core idea of this repository is to process facial images of US presidents and compute their average face. This is achieved through facial landmark detection and image processing strategies.

## Features

- Uses **shape predictor 68 face landmarks** for accurate facial feature detection.
- Aligns and averages multiple faces to create a composite "average" face.
- All code and analysis are provided in Jupyter Notebook format for easy exploration and reproducibility.

## Requirements

- Python 3.x
- Jupyter Notebook
- OpenCV
- dlib (for 68-point shape predictor)
- numpy
- matplotlib

You can install the required Python packages with:

```bash
pip install numpy opencv-python dlib matplotlib
```

> **Note:** You will also need the `shape_predictor_68_face_landmarks.dat` file for dlib.
> Download it from [dlib model files](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and extract it into your project directory.

## Usage

1. Collect or download the facial images of the US presidents you'd like to include.
2. Place the images in the appropriate directory (see notebook instructions).
3. Open the Jupyter Notebook(s) and execute the cells step-by-step.
4. The notebook will detect facial landmarks, align faces, and compute the average face.

## Methodology

- Detect facial landmarks using dlib's 68-point shape predictor.
- Align faces based on the landmarks to a common reference.
- Average the pixel values across all aligned faces to generate the composite face.

## Repository Structure

- `notebooks/` - Jupyter Notebooks containing the code and results.
- `images/` - Directory containing input face images.
- `output/` - Directory for saving the average face result.

## Acknowledgements

- [dlib library](http://dlib.net/)
- [shape_predictor_68_face_landmarks](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)
- OpenCV

## License

This project is licensed under the MIT License.

---
*Created by [Shashankkusu](https://github.com/Shashankkusu)*
