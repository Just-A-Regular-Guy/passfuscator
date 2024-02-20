# passfuscator
Passfuscator reads a text file, masks each line by replacing all characters except the first two and the last two with "*", and writes the result to a CSV file. Lines with fewer than three characters are skipped.

# How to Use
Clone this repository to your local machine or download the script directly:

`git clone https://github.com/Just-A-Regular-Guy/passfuscator`

Ensure you have Python installed on your machine. You can download it from python.org.

Install the csv module if you haven't already. You can install it via pip:

`pip install csv`

Move to the script directory:

`cd passfuscator`

Run the script by executing the following command in your terminal:

`python passfuscator.py`

You will be prompted to enter the name of the input file. After the script finishes execution, it will generate an output file named `output.csv` in the same directory.

Open the `output.csv` file to view the masked content.

# Customization
You can customize the input and output filenames by modifying the input_file and output_file variables at the end of the script.

# Requirements
`Python 3.x`
`csv module`

# License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details: `https://github.com/Just-A-Regular-Guy/passfuscator/blob/main/LICENSE`
