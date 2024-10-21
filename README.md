# Eye-Color-Change-and-Image-Filtering-Project

This repository contains a Python script that processes images to change eye colors and apply various filters. The script uses OpenCV, dlib, and Pillow to achieve these effects.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Features

- Detects facial landmarks using dlib.
- Changes eye colors by creating masks for the iris.
- Applies a series of image filters to enhance facial features.
- Saves processed images in a specified output directory.

## Requirements

To run the script, you need the following Python packages:

- `numpy`
- `opencv-python`
- `dlib`
- `Pillow`

You can install these packages using pip:

```bash
pip install numpy opencv-python dlib Pillow
```

Additionally, you will need the `shape_predictor_68_face_landmarks.dat` file, which is a pre-trained model for facial landmark detection. You can download it from [dlib's model files](http://dlib.net/files/).

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/shukdevtroy/Eye-Color-Change-and-Image-Filtering-Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Eye-Color-Change-and-Image-Filtering-Project
   ```

3. Make sure you have all the required packages installed.

4. Place the `shape_predictor_68_face_landmarks.dat` file in the project directory or adjust the path in the script accordingly.

## Usage

1. Prepare your images:
   - Organize your images in subfolders inside the `main_input_dir` directory. The script will process all images in these subfolders.

2. Set the `main_input_dir` and `output_dir` variables in the script to the appropriate paths.

3. Run the script:

   Using VS code

4. The processed images will be saved in the `output_dir` directory with the applied filters and color changes.

## File Structure

```
/your-repo-name
│
├── main_script.py                # The main script for processing images
├── shape_predictor_68_face_landmarks.dat  # Facial landmark model file
├── README.md                     # Documentation for the project
└── requirements.txt              # List of required packages
```

## License

This project is licensed under the MIT License. See the LICENSE file for more information. 

## Contact

For any questions or issues, please contact:

- **Email**: shukdevdatta@gmail.com
- **GitHub**: [Click to here to access the Github Profile](https://github.com/shukdevtroy)
- **WhatsApp**: [Click here to chat](https://wa.me/+8801719296601)

---

Feel free to modify the repository as needed and share your improvements! If you encounter any issues, please open an issue in the repository.
