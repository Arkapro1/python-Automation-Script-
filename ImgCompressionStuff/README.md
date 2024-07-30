## Description

This repository contains a powerful and easy-to-use Python script for compressing image files, retrieving image details, and removing folders with specific substrings in their names. The script is designed to handle multiple tasks with simple user inputs.

## Features

- **Image Compression**: Compress images in a specified folder and save them to a new folder.
- **Image Details**: Retrieve and display details of a specified image file.
- **Folder Removal**: Remove all folders containing a specific substring in their names.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- PIL (Pillow)
- OS and shutil modules (pre-installed with Python)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/powerful-easy-file-compression.git
    cd powerful-easy-file-compression
    ```

2. **Install required packages**:
    ```bash
    pip install opencv-python pillow
    ```

## Usage

### 1. Image Compression

This script compresses all images in a specified folder and saves the compressed images to a new folder.

#### Run the Script

```bash
python compress_images.py
```

Enter the names of the folders as prompted.

### 2. Image Details

This script retrieves and displays details of a specified image file.

#### Run the Script

```bash
python get_image_details.py
```

Enter the path to the image file as prompted.

### 3. Folder Removal

This script removes all folders containing a specific substring in their names within the current directory.

#### Run the Script

```bash
python remove_folders_with_substring.py
```

Enter the substring to match in folder names as prompted.

## Contribution

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
</response>
