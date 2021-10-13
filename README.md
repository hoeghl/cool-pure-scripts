# cool-pure-scripts

## api.py
Small script to download all research output UUIDs, titles and secondary sources from Pure into a spreadsheet. 

Usage: 

1. Install Python 3 and pip.
2. Install requirements in working folder: `pip install -r requirements.txt`.
3. Run `python3 api.py --help` for instructions.
4. Output file will be saved in working folder with a .xlsx extension supplied in the `--outputfile` option.

Example:
`python3 api.py https://test.pure.elsevier.com not-real-api-key --outputfile test.xlsx --apiversion 521`.
