# Bib2JSON Converter

Bib2JSON converter is a simple Python script for transforming BibTeX files into JSON format. It allows you to maintain the structure and content of your bibliographic entries while converting them into a more versatile and machine-readable JSON format.

## Features

- Convert BibTeX files to JSON.
- Optional to retain the original BibTeX entries within the JSON output.
- Suitable for researchers, students, and project managers who need to work with reference data.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/brianrabern/bib2json.git
   ```

2. **Run the Converter:**

   To convert your BibTeX file to JSON, you can run the script from the command line. Use the following command:

   ```bash
   python bib2json.py input.bib output.json
   ```

   - `input.bib` should be replaced with the name of your input BibTeX file.
   - `output.json` should be replaced with the desired name for your output JSON file.

   Additionally, you can use the `--include_bibtex` flag to include the BibTeX field in the JSON output:

   ```bash
   python bib2json.py input.bib output.json --include_bibtex
   ```

   This flag is optional, and if provided, it will include the BibTeX field in the resulting JSON.

3. **Eat the JSON Data:**

   Your BibTeX data will now be available in JSON format, ready to be used in your research, applications, or projects.
