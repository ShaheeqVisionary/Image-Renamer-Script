# Image Renamer Script

This Python script is designed to rename images in one folder to match the filenames of images in another folder. The script checks if both folders contain the same number of images and then renames the images in the first folder to have the same names as those in the second folder.

## Prerequisites

- Python 3.x
- `shutil` and `os` modules (included in the Python Standard Library)

## Usage

1. **Clone the repository** or copy the script to your local machine.

2. **Set the folder paths**:
   Modify the script to specify the paths to Folder A and Folder B.
   ```python
   folder_a_path = 'path/to/folder/A'
   folder_b_path = 'path/to/folder/B'
   ```

3. **Run the script**:
   Execute the script using Python.
   ```bash
   python image_renamer.py
   ```

4. **Output**:
   - The script will check if both folders exist and contain the same number of images.
   - It will then rename the images in Folder A to match the filenames in Folder B.
   - If the script encounters any issues (e.g., folders do not exist or the number of images doesn't match), it will print an appropriate error message and exit.

## Example

Suppose Folder A contains images named `image1.jpg`, `image2.jpg`, and `image3.jpg`, and Folder B contains images named `pic1.jpg`, `pic2.jpg`, and `pic3.jpg`. After running the script, the images in Folder A will be renamed to `pic1.jpg`, `pic2.jpg`, and `pic3.jpg`.

## Notes

- Ensure that both folders have the same number of images before running the script.
- The script will move (rename) the files in Folder A, so make sure to back up your data if necessary.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
