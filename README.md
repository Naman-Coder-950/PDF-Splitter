# Mini-Project-13

# PDF-Splitter

## Requirements

- Python 3.x
- `PyPDF2` library

## Usage

1. **Clone the Repository**
2. **Set the paths**
   - Enter the path to your input PDF file.
   - Enter the output directory where you want the split PDF files to be saved.
3. **Run the Script**

   ```bash
   python3 pdf_splitter.py
   ```
 
   The script will prompt you to:
   - Enter the page number where you want to split the PDF.

## Script Explanation

### split_pdf Function

This function takes three arguments:
- `input_pdf`: The path to the input PDF file.
- `output_dir`: The directory where the split PDF files will be saved.
- `split_page`: The page number where the PDF will be split.

The function performs the following steps:
1. Checks if the output directory exists and creates it if it doesn't.
2. Reads the input PDF file.
3. Splits the PDF into two parts based on the specified page number.
4. Saves the two parts as `part1.pdf` and `part2.pdf` in the specified output directory.


