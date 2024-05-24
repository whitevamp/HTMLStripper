# HTMLStripper
HTMLStripper, and exporter, to *.txt, *.doc, *.CSV, *.pdf, *.epub, *.html

```markdown
# HTML Stripper

This Python script recursively scans a directory for HTML files, strips out all HTML and JavaScript
content, and saves the cleaned content to new files in a specified output format. The script provides
a Tkinter-based graphical user interface (GUI) to select the input directory, output directory,
and output file format.

## Features

- Recursively scan a directory for HTML files
- Strip out HTML and JavaScript content
- Save cleaned content in various formats: `txt`, `doc`, `csv`, `pdf`, `epub`, `html`
- User-friendly GUI for selecting input and output directories and file format

## Requirements

- Python 3.x
- BeautifulSoup4
- python-docx
- pandas
- fpdf
- ebooklib
- tkinter

## Installation

1. Clone the repository or download the script.

   ```bash
   git clone https://github.com/your-username/html-stripper.git
   cd html-stripper
   ```

2. Install the required Python packages.

   ```bash
   pip install beautifulsoup4 python-docx pandas fpdf ebooklib
   ```

## Usage

1. Run the script.

   ```bash
   python HTMLStripper.py
   ```

2. Use the GUI to:
   - Select the input directory containing HTML files.
   - Select the output directory where cleaned files will be saved.
   - Choose the output file format from the dropdown list.

3. Click the "Start" button to begin processing.

## GUI Overview

- **Select Input Directory:** Opens a dialog to select the directory to scan for HTML files.
- **Select Output Directory:** Opens a dialog to select the directory to save the cleaned files.
- **Output Format:** Dropdown list to select the format of the output files (`txt`, `doc`, `csv`, `pdf`, `epub`, `html`).
- **Start Button:** Starts the processing of files based on the selected input directory, output directory, and file format.

## Example

If you have a directory structure like this:

```
/path/to/input_directory
    ├── file1.html
    ├── file2.html
    └── subdir
        └── file3.htm
```

And you select `/path/to/input_directory` as the input directory, `/path/to/output_directory` as the output directory, and `txt` as the output format, the script will process the HTML files and create the following structure in the output directory:

```
/path/to/output_directory
    ├── file1.txt
    ├── file2.txt
    └── subdir
        └── file3.txt
```

## License

This project is licensed under the GPL-3.0 license. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or suggestions, please open an issue or contact the repository owner.
