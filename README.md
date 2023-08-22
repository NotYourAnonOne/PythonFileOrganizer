# File Organizer

This is a simple Python script to organize files in a given directory based on their file extensions and creation dates.

## Getting Started

To use this script, follow the instructions below:

### Prerequisites

Make sure you have Python installed on your system.

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/NotYourAnonOne/PythonFileOrganizer.git
   ```

2. Change to the directory where the script is located:
   ```
   cd src
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Usage

1. Open the `file_organizer.py` file.

2. Modify the `source_dir` variable with the path to the directory where your files are located. Make sure to use forward slashes (`/`) and provide the full path.

3. Modify the `destination_dir` variable with the path to the directory where you want your organized files to be placed. Make sure to use forward slashes (`/`) and provide the full path.

4. Save the changes.

5. Run the script:
   ```
   python file_organizer.py
   ```

6. The script will iterate through the files in the source directory, create separate directories for each file extension in the destination directory, and move the files to their respective directories based on their creation dates.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Python](https://www.python.org/) - Programming language used
- [shutil](https://docs.python.org/3/library/shutil.html) - Library used for file operations
- [datetime](https://docs.python.org/3/library/datetime.html) - Library used for handling dates and times
