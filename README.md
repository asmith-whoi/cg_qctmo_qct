# CGSN CTDMO Automated QCT

Simple script to automate the QCT procedure and automatically generate the required
documentation and calibration CSV files.

## Requirements

* Windows 7 or later
* Python 3.X
* Python packages
	* py-serial
	* python-docx

## Usage

Install the required python packages using `pip install <package name>` if not already
completed.

Make sure the following files are located together in the same directory:

* 3305-00101-00000.docx Results form template
* cal_ctdmo.py 
* cg_ctdmo_qct.py
* ctdmo_inv.csv

Open a command terminal window and `cd` into the script directory. Enter
`python cg_ctdmo_qct.py` into the command line to start the script.

Alternatively, depending on your python installation, you may be able to double-click
the `python_cg_qct.py` file from Windows Explorer to start the program.

Follow the prompts as directed.

