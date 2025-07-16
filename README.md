# PDF-Splitter
# Requirements
1. Python 3.x
2. PyPDF2 library

# Usage
1. Clone the Repository

2. Set the paths
  2.1. Enter the path to your input PDF file.
  2.2. Enter the output directory where you want the split PDF files to be saved.
3.Run the Script
  python3 pdf_splitter.py
The script will prompt you to:
  Enter the page number where you want to split the PDF.

# Script Explanation
# split_pdf Function
This function takes three arguments:

1. input_pdf: The path to the input PDF file.
2. output_dir: The directory where the split PDF files will be saved.
3. split_page: The page number where the PDF will be split.

The function performs the following steps:

1. Checks if the output directory exists and creates it if it doesn't.
2. Reads the input PDF file.
3. Splits the PDF into two parts based on the specified page number or more according to our requirement.
4. Saves the two parts as part1.pdf and part2.pdf in the specified output directory.
